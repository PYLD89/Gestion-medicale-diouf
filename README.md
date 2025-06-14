# 💊 Application de Gestion Médicale - Diouf Consulting

Cette application est une Progressive Web App (PWA) simple, conçue en HTML/CSS/JS pur avec IndexedDB pour stocker les données des patients en local (offline-ready).

## 🚀 Fonctionnalités principales

- Ajouter un patient
- Voir la liste des patients
- Historique médical stocké
- Mode hors ligne (offline)
- Installation sur mobile/PC (PWA)

## 📁 Structure du projet

```
/
├── index.html                # Fichier principal HTML
├── manifest.json             # Fichier manifest PWA
├── service-worker.js         # Fichier pour gestion offline
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
```

## 🛠️ Déploiement en ligne

1. Créez un nouveau dépôt GitHub
2. Ajoutez ce fichier comme `README.md`
3. Déposez tous les fichiers listés ci-dessus (y compris `icons/`)
4. Activez GitHub Pages (Settings > Pages > Branch: `main`, `/root`)
5. Attendez l’URL de publication (`https://<votre-utilisateur>.github.io/<nom-du-depot>/`)

## 🧪 Test local

1. Clonez ou extrayez le dossier sur votre PC
2. Ouvrez `index.html` dans un navigateur compatible (Chrome, Edge, Firefox)
3. Acceptez l'installation si proposée (mobile)

## 📲 Installation mobile

- Sur Android/Chrome : Cliquez sur le menu ⋮ > “Ajouter à l'écran d'accueil”
- Sur iOS/Safari : Appuyez sur ⬆️ > “Sur l’écran d’accueil”

## 🔒 Données stockées

Toutes les données sont stockées en local via IndexedDB. Cette app est 100% offline et ne communique pas avec un serveur distant.

---

© Diouf Consulting – 2025
