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
   
## 🚀 Déploiement et Utilisation

### 🌍 Utilisation en ligne (Recommandé)
L'application est configurée pour être déployée instantanément sur **GitHub Pages**. 
👉 **[Cliquez ici pour accéder à l'application en direct](https://votre-utilisateur.github.io/nom-du-projet/)** *(Remplacez par votre lien réel)*

---

### 🛠️ Déploiement sur votre propre compte GitHub

Puisque le projet est composé uniquement de fichiers statiques (HTML/JS), son déploiement sur GitHub Pages ne prend que quelques secondes :

1. **Créez un dépôt** sur GitHub et poussez-y votre code (le fichier `index.html` doit être à la racine).
2. Rendez-vous dans les **Settings** (Paramètres) de votre dépôt GitHub.
3. Dans le menu de gauche, cliquez sur **Pages**.
4. Dans la section **Build and deployment** :
   - Source : Sélectionnez `Deploy from a branch`.
   - Branch : Choisissez `main` (ou `master`) et le dossier `/ (root)`.
5. Cliquez sur **Save**. 

Votre application sera en ligne à l'adresse `https://votre-nom-d-utilisateur.github.io/votre-nom-de-depot/` en moins d'une minute !

---

### 💻 Utilisation Locale (Alternative)
Si vous préférez l'exécuter hors ligne :
1. Clonez le dépôt :
   ```bash
   git clone [https://github.com/votre-utilisateur/nom-du-projet.git](https://github.com/votre-utilisateur/nom-du-projet.git)
