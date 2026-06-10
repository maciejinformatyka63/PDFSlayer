# 🛠️ Boîte à Outils PDF Ultra-Rapide (Client-Side)

Un outil web moderne, léger et ultra-rapide permettant de **découper**, **extraire** et **fusionner** des fichiers PDF. L'ensemble du traitement est effectué **directement dans le navigateur de l'utilisateur**, garantissant une confidentialité absolue et une vitesse d'exécution instantanée sans aucun transfert de données vers un serveur tiers.

## 🌟 Fonctionnalités

### ✂️ Séparation de PDF
- **Mode "Toutes les pages"** : Découpe l'intégralité du PDF et génère une archive `.zip` contenant chaque page convertie en un document PDF individuel.
- **Mode "Plage personnalisée"** : Permet d'extraire un groupe spécifique de pages (ex: `1-3, 5`) dans un unique nouveau fichier PDF.

### 🧲 Fusion de PDF (Nouveau)
- **Assemblage Multi-fichiers** : Glissez-déposez plusieurs fichiers PDF simultanément pour les combiner en un seul et unique document final en un seul clic.

### 🔒 Sécurité & Expérience Utilisateur
- **100% Sécurisé & Privé** : Les fichiers ne quittent jamais votre ordinateur. Tout est traité localement via la RAM du navigateur.
- **Interface Intelligente (Drag & Drop)** : Glissez-déposez vos fichiers pour commencer. L'application détecte automatiquement si vous souhaitez séparer (1 fichier) ou fusionner (plusieurs fichiers) et adapte l'interface en conséquence.
- **Design Responsive** : Interface moderne et épurée conçue avec Tailwind CSS v4, parfaitement adaptée aux mobiles, tablettes et ordinateurs.

## 🛠️ Technologies utilisées

- **HTML5 & JavaScript (ES6+)** : Logique globale, gestion des événements de drag & drop et manipulation des flux de fichiers.
- **[pdf-lib](https://pdf-lib.js.org/)** : Bibliothèque principale pour charger, copier, fusionner et générer les documents PDF.
- **[JSZip](https://stuk.github.io/jszip/)** : Pour la compression des pages individuelles en archive ZIP lors de la séparation totale.
- **[Tailwind CSS v4](https://tailwindcss.com/)** : Pour un stylisage ultra-moderne, rapide et responsive (via CDN natif).

## 🚀 Installation et Utilisation Locale

Ce projet est entièrement autonome. Il ne nécessite **aucun serveur**, **aucun Node.js**, ni **aucune installation complexe**.

1. **Téléchargez** le code source ou clonez le dépôt :
   ```bash
   git clone [https://github.com/votre-utilisateur/nom-du-projet.git](https://github.com/votre-utilisateur/nom-du-projet.git)
