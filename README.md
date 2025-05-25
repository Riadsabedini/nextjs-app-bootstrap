# Dating App

Une application de rencontre moderne construite avec Next.js et Tailwind CSS.

## Déploiement sur Vercel

1. Créez un compte sur [Vercel](https://vercel.com) si vous n'en avez pas déjà un.

2. Installez Vercel CLI globalement :
   ```bash
   npm i -g vercel
   ```

3. Connectez-vous à votre compte Vercel :
   ```bash
   vercel login
   ```

4. Dans le dossier du projet, déployez avec :
   ```bash
   vercel
   ```

5. Pour les déploiements suivants :
   ```bash
   vercel --prod
   ```

## Développement local

1. Clonez le repository :
   ```bash
   git clone <votre-repo-url>
   cd dating-app
   ```

2. Installez les dépendances :
   ```bash
   npm install
   ```

3. Démarrez le serveur de développement :
   ```bash
   npm run dev
   ```

4. Ouvrez [http://localhost:8000](http://localhost:8000) dans votre navigateur.

## Fonctionnalités

- 👤 Authentification utilisateur
- 💑 Swipe pour matcher
- 💬 Messagerie en temps réel
- 📝 Gestion de profil
- 🎨 Interface moderne et responsive

## Technologies utilisées

- Next.js 15
- React 19
- Tailwind CSS
- TypeScript
- ShadcN UI Components

## Structure du projet

```
dating-app/
├── src/
│   ├── app/              # Pages de l'application
│   ├── components/       # Composants réutilisables
│   └── lib/             # Utilitaires et configurations
├── public/              # Assets statiques
└── package.json         # Dépendances et scripts
```

## Déploiement sur d'autres plateformes

### Hébergement traditionnel

1. Construisez l'application :
   ```bash
   npm run build
   ```

2. Le dossier `.next` contient l'application construite.

3. Démarrez le serveur en production :
   ```bash
   npm start
   ```

### Docker (optionnel)

1. Construisez l'image :
   ```bash
   docker build -t dating-app .
   ```

2. Lancez le conteneur :
   ```bash
   docker run -p 3000:3000 dating-app
   ```

## Support

Pour toute question ou problème :
1. Ouvrez une issue sur GitHub
2. Consultez la documentation de [Next.js](https://nextjs.org/docs)
3. Consultez la documentation de [Vercel](https://vercel.com/docs)
