# PE_Compétition_informatique

Ce dépôt regroupe l'ensemble des ressources produites dans le cadre du Projet d'Étude de l'École Centrale de Lyon, dédié à l'entraînement à la programmation compétitive, à l'algorithmique avancée et à la préparation aux concours internationaux (SWERC, Prologin, etc.).

## 1. Installation et Configuration de l'environnement

Pour être performant en compétition et lors des phases d'entraînement, l'automatisation de la récupération des énoncés et des cas de tests est indispensable. L'environnement de travail recommandé repose sur Visual Studio Code.

### Prérequis
* Visual Studio Code
* Compilateur C++ (GCC/MinGW)
* Environnement Python (pour l'affichage et l'exécution des Jupyter Notebooks)

### Extensions nécessaires
1. Dans VS Code, installez l'extension **C++ Programming Helper (cph)**.
2. Sur votre navigateur web, installez l'extension **Competitive Companion**.

### Configuration du flux de travail
Le couplage de ces deux outils permet un gain de temps majeur lors de la résolution de problèmes :
1. Ouvrez un problème sur une plateforme d'évaluation en ligne (Codeforces, CSES, etc.).
2. Cliquez sur l'icône de l'extension Competitive Companion dans votre navigateur ou le raccourci ctrl + maj + u
3. L'extension CPH dans VS Code intercepte automatiquement les données, crée un fichier source et importe les cas de tests d'exemple fournis dans l'énoncé.
4. Une fois votre solution codée, un simple clic sur "Run All" dans l'interface de CPH permet de compiler et d'exécuter votre code contre tous les tests locaux instantanément.

### Configuration du Template C++
Afin d'éviter de réécrire les inclusions et les optimisations d'entrées/sorties pour chaque nouveau problème, il convient de configurer CPH pour qu'il utilise un template par défaut. 

Dans VS Code, accédez aux paramètres de l'extension CPH et liez le code suivant comme fichier de démarrage :

```cpp
#include "bits/stdc++.h"

using namespace std;
using ll = long long;

const ll MOD = 1e9 + 7;

void solve() {
    
}

int main() {
    ios::sync_with_stdio(0);
    cin.tie(0);
    
    // int t; cin >> t; while(t--) solve();
    solve(); 
    
    return 0;
}
