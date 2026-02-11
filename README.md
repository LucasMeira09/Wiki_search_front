# WikiSearch Frontend

Un mini moteur de recherche pour Wikipedia avec une interface moderne construite en React + TypeScript.

##  Technologies

- **React 18** - Bibliothèque d’interface
- **TypeScript** - Typage statique
- **Vite** - Outil de build et serveur de développement
- **Tailwind CSS** - Framework CSS
- **PostCSS** - Traitement CSS

##  Pré-requis

- **Node.js** 18+ 
- **npm** ou **yarn**

##  Installation

1. **Clonez le dépôt :**
```bash
git clone https://github.com/SEU_USUARIO/wiksearch-frontend.git
cd wiksearch-frontend
```

## Installez les dépendances :
```
npm install
```

## Configurez les variables d’environnement :
```
cp .env.example .env
```

## Modifiez le .env avec l’URL de votre API :
```
VITE_API_URL=http://localhost:3000
```

## Démarrez le serveur de développement :
```
npm run dev
```

## Ouvrez dans le navigateur :
```
http://localhost:5173
```

# Scripts Disponibles
```
npm run dev - Démarre le serveur de développement

npm run build - Génère le build de production

npm run preview - Visualise le build de production
```

## Build de Production
npm run build
Les fichiers optimisés seront générés dans le dossier dist/.
```
 Structure du Projet
src/
  ├── App.tsx          # Composant principal
  ├── main.tsx         # Point d’entrée
  └── index.css        # Styles globaux
public/              # Fichiers statiques
 Fonctionnalités
 Recherche en temps réel sur Wikipedia
```

 - Résumé automatique des résultats

 - Interface responsive et moderne

 - Liens directs vers les articles de Wikipedia

Développé par : @PolyannaMeira
