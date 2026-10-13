# Aidonoo

<p align="center">
  <strong>La plateforme de services entre particuliers, près de chez vous.</strong><br />
  Trouvez un coup de main ou proposez vos services en Belgique.
</p>

## Aperçu

<p align="center">
  <img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/Accueil.png" alt="Page d’accueil Aidonoo" width="100%" />
</p>

<details>
  <summary>Voir les autres captures</summary>
  <br />
  <p><img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/Hero.png" alt="Hero Aidonoo" width="100%" /></p>
  <p><img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/Hero2.png" alt="Services et prestataires Aidonoo" width="100%" /></p>
  <p><img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/End.png" alt="Fin de la page d’accueil Aidonoo" width="100%" /></p>
  <p><img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/Footer.png" alt="Pied de page Aidonoo" width="100%" /></p>
  <p><img src="https://raw.githubusercontent.com/evdk25-wq/Aidonoo/main/Password.png" alt="Écran de connexion Aidonoo" width="100%" /></p>
</details>

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
