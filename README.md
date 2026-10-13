# Aidonoo

Aidonoo est une plateforme de services entre particuliers pensée pour faciliter l’entraide locale en Belgique. Les particuliers peuvent trouver de l’aide près de chez eux et les prestataires présenter leurs services.

## Fonctionnalités de la maquette

- Interface responsive en français
- Navigation et recherche de services par catégorie
- Mise en avant de prestataires avec badges, notes et avis
- Carrousel continu de professions populaires
- Espace de présentation pour les futurs prestataires
- Écran de connexion en cours de conception

## Technologies

- React 19 et TypeScript
- Mantine UI
- Tabler Icons
- Vite
- Clean Architecture

## Démarrer le projet

Prérequis : Node.js et npm.

```bash
npm install
npm run dev
```

Pour générer la version de production :

```bash
npm run build
npm run preview
```

## Organisation du code

```text
src/
├── domain/          # Modèles et contrats métier
├── application/     # Cas d’usage
├── infrastructure/  # Dépôts et données de démonstration
└── presentation/    # Pages et composants React
```

## État du projet

Aidonoo est en phase de prototypage. Les profils et services affichés utilisent des données de démonstration. L’authentification réelle et la connexion à Supabase ne sont pas encore intégrées.
