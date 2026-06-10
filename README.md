# ✂️ Séparateur de PDF Ultra-Rapide (Client-Side)

Un outil web moderne, léger et ultra-rapide permettant de découper et d'extraire les pages de fichiers PDF. L'ensemble du traitement est effectué **directement dans le navigateur de l'utilisateur**, garantissant une confidentialité absolue et une vitesse d'exécution instantanée.

## 🌟 Fonctionnalités

- **Mode "Toutes les pages"** : Découpe l'intégralité du PDF et génère un fichier `.zip` contenant chaque page convertie en un document PDF individuel.
- **Mode "Plage personnalisée"** : Permet d'extraire un groupe spécifique de pages (ex: `1-3, 5`) dans un unique nouveau fichier PDF.
- **100% Sécurisé & Privé** : Les fichiers ne sont jamais téléchargés sur un serveur. Tout est traité localement via la RAM du navigateur.
- **Interface Fluide (Drag & Drop)** : Glissez-déposez simplement votre fichier pour commencer le traitement.
- **Design Responsive** : Interface moderne et épurée conçue avec Tailwind CSS, adaptée aux mobiles, tablettes et ordinateurs.

## 🛠️ Technologies utilisées

- **HTML5 & JavaScript (ES6+)** : Logique globale et manipulation de fichiers.
- **[pdf-lib](https://pdf-lib.js.org/)** : Bibliothèque principale pour charger, copier et générer les documents PDF.
- **[JSZip](https://stuk.github.io/jszip/)** : Pour la compression des pages individuelles en archive ZIP.
- **[Tailwind CSS](https://tailwindcss.com/)** : Pour un stylisage rapide, moderne et responsive (via CDN).

## 🚀 Installation et Utilisation Locale

Ce projet ne nécessite **aucun serveur**, **aucun Node.js**, ni **aucune installation complexe**.

1. **Téléchargez** le code source ou clonez le dépôt :
   ```bash
   git clone [https://github.com/votre-utilisateur/nom-du-projet.git](https://github.com/votre-utilisateur/nom-du-projet.git)
