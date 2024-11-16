# Network Frame Analyzer & Visualizer 🌐

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=java&logoColor=white)](https://openjfx.io/)
[![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)](https://maven.apache.org/)

## 📋 Description

Application permettant l'analyse et la visualisation de trames réseaux. Le projet combine un analyseur Java pour le traitement des données et une interface de visualisation construite avec JavaFX.

## 🏗️ Architecture

### Analyseur (Backend)

#### Composants Principaux
* `Converter`
  - Entrée : fichiers traces (.txt)
  - Sortie : tableau de trames
  - Fonction : conversion des données brutes

* `Analyzer`
  - Traitement des trames
  - Subdivision des octets
  - Analyse détaillée
  - Conversion en format lisible

### Visualiseur (Frontend)

#### Modèle MVC
* `Info` (DTO)
  - Stockage des données analysées
  - Interface entre l'analyseur et le visualiseur

* `Controllers/`
  - `MainController` : contrôleur principal
  - Gestion de la logique applicative
  - Coordination des vues

* `Views/`
  - Interface utilisateur
  - Affichage des données
  - Interaction utilisateur

## 🛠️ Technologies

- **Backend**: Java
- **Frontend**: JavaFX
- **Build Tool**: Maven
- **Architecture**: MVC Pattern

## 📦 Installation

```bash
# Cloner le projet
git clone [URL_DU_REPO]

# Installer les dépendances
mvn install

# Lancer l'application
mvn javafx:run
```

## 📚 Documentation

Pour plus de détails sur l'utilisation et l'architecture :
- [Guide d'utilisation](docs/user-guide.md)
- [Documentation technique](docs/technical-docs.md)
- [API Reference](docs/api-reference.md)

## 🤝 Contribution

Les contributions sont les bienvenues ! Voir [CONTRIBUTING.md](CONTRIBUTING.md) pour les détails.

## 📝 Licence

Ce projet est sous licence [MIT](LICENSE)
