# ElectroMobile Website

Site web professionnel pour la mobilité électrique.

## 🚀 Déploiement sur Vercel

### Méthode 1 : Via l'interface Vercel (Recommandé)

1. Allez sur [vercel.com](https://vercel.com)
2. Cliquez sur "Add New" → "Project"
3. Importez votre dossier ou déposez les fichiers
4. Vercel détectera automatiquement la configuration
5. Cliquez sur "Deploy"

### Méthode 2 : Via Git

1. Créez un repo GitHub avec ces fichiers
2. Sur Vercel, connectez votre repo GitHub
3. Vercel déploiera automatiquement à chaque push

### Méthode 3 : Via CLI Vercel

```bash
npm i -g vercel
cd vercel-project
vercel
```

## 📁 Structure du projet

```
vercel-project/
├── public/
│   └── index.html       # Votre site web
├── vercel.json          # Configuration Vercel
├── package.json         # Informations du projet
└── README.md           # Ce fichier
```

## ⚙️ Configuration

Le fichier `vercel.json` configure :
- URLs propres (sans .html)
- Routing automatique
- Optimisation des performances

## 🔧 Développement local

Pour tester en local :

```bash
cd vercel-project
npx serve public
```

Puis ouvrez http://localhost:3000

## 📝 Notes importantes

- Le fichier principal doit s'appeler `index.html` dans le dossier `public/`
- Vercel sert automatiquement les fichiers du dossier `public/`
- Aucune dépendance à installer, c'est un site statique HTML pur
- Le site est 100% responsive et fonctionne sur tous les appareils

## 🎨 Personnalisation

Vous pouvez modifier :
- Les couleurs dans les variables CSS (`:root`)
- Les textes et contenus
- Les images (ajoutez-les dans `public/images/`)
- Les coordonnées de contact

## 📱 Pages disponibles

- Accueil
- Réparation & Maintenance
- Location
- Conversion Électrique
- Vente

## 🆘 Résolution de problèmes

**Erreur 404 sur Vercel :**
- Vérifiez que `index.html` est bien dans le dossier `public/`
- Assurez-vous que `vercel.json` est à la racine du projet

**Le site ne s'affiche pas correctement :**
- Videz le cache du navigateur (Ctrl+Shift+R)
- Vérifiez la console du navigateur pour les erreurs

**Problème de déploiement :**
- Vérifiez que tous les fichiers sont bien uploadés
- Consultez les logs de déploiement sur Vercel

## 📞 Support

Pour toute question, contactez votre développeur.

---

Fait avec ❤️ pour une mobilité électrique durable
