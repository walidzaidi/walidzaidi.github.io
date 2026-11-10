# Portfolio Web — Walid ZAIDI 🚀

> Application web interactive & portfolio personnel pour **Walid ZAIDI**, Développeur Full Stack & Intégrateur Senior (17+ ans d'expérience).

---

## 📋 Table des matières

- [À propos](#-à-propos)
- [Fonctionnalités](#-fonctionnalités)
- [Stack Technique](#-stack-technique)
- [Prérequis](#-prérequis)
- [Installation et Démarrage](#-installation-et-démarrage)
- [Scripts Disponibles](#-scripts-disponibles)
- [Structure du Projet](#-structure-du-projet)
- [Contact](#-contact)
- [Licence](#-licence)

---

## 👨‍💻 À propos

Ce projet héberge le portfolio en ligne de **Walid ZAIDI**. Le site présente :
- Un profil complet avec un style API/Terminal (`whoami`, routes HTTP `GET`/`POST`/`PUT`).
- Le parcours professionnel chronologique (17 ans d'expérience).
- La stack technique détaillée (Laravel, Vue.js, Node.js, MySQL high-load, etc.).
- La formation académique et les langues.
- Un formulaire de contact direct et le téléchargement du CV en format PDF.

---

## ✨ Fonctionnalités

- **Interface interactive & moderne :** Mode clair/sombre, animations fluides, design responsive & Mobile-First.
- **Visualisation des expériences :** Présentation sous forme d'endpoints API (`/affitech/full-stack-dev`, `/siroko-travel/tech-lead`, etc.).
- **Filtrage des projets & compétences :** Navigation par catégories techniques.
- **Formulaire de contact :** Envoi direct de messages via API / Webhook.
- **Génération / Téléchargement du CV PDF.**

---

## 🛠 Stack Technique

### Application
- **Front-end :** [Vue.js 3](https://vuejs.org/) (Composition API), [TypeScript](https://www.typescriptlang.org/), HTML5, CSS3 / Sass
- **Build Tool :** [Vite](https://vitejs.dev/)
- **Back-end & API :** Node.js / PHP (Laravel)
- **Base de données :** MySQL (Forte volumétrie)
- **DevOps :** Docker, Git / GitHub

---

## ⚙️ Prérequis

Avant de commencer, assurez-vous de disposer de :
- **Node.js** `>= 18.x`
- **npm** `>= 9.x` (ou **pnpm** / **yarn**)

---

## 🚀 Installation et Démarrage

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/walid-zaidi/walid-zaidi-cv.git
   cd walid-zaidi-cv
   ```

2. **Installer les dépendances :**
   ```bash
   npm install
   ```

3. **Configurer les variables d'environnement :**
   Créer un fichier `.env` à la racine à partir de `.env.example` :
   ```bash
   cp .env.example .env
   ```

4. **Lancer le serveur de développement :**
   ```bash
   npm run dev
   ```
   L'application sera accessible sur `http://localhost:5173`.

---

## 📜 Scripts Disponibles

| Commande | Description |
| :--- | :--- |
| `npm run dev` | Démarrer le serveur de développement avec HMR |
| `npm run build` | Compiler et optimiser le projet pour la production |
| `npm run preview` | Prévisualiser le build de production en local |
| `npm run lint` | Exécuter le linter ESLint et corriger les erreurs de style |

---

## 🗂 Structure du Projet

```text
walid-zaidi-cv/
├── public/              # Fichiers statiques (favicon, CV PDF, images)
├── src/
│   ├── assets/          # Styles Sass/CSS, icônes, logos
│   ├── components/      # Composants UI (Header, ExperienceCard, ContactForm, etc.)
│   ├── data/            # Données structurées (expériences, compétences, projets)
│   ├── views/           # Vue principale (HomeView, ProjectsView)
│   ├── App.vue          # Composant racine
│   └── main.ts          # Point d'entrée TypeScript
├── .env.example         # Exemple de configuration environnement
├── package.json         # Dépendances et scripts
└── vite.config.ts       # Configuration de Vite
```

---

## 📞 Contact

**Walid ZAIDI** — Développeur Full Stack & Intégrateur Senior  
📍 Tunis, Tunisie  
✉️ **Email :** [zaidi.walid@gmail.com](mailto:zaidi.walid@gmail.com)  
📞 **Téléphone :** +216 50 65 61 49  
🔗 **LinkedIn :** [linkedin.com/in/walid-zaidi-dev](https://linkedin.com/in/walid-zaidi-dev)  

---

## 📄 Licence

Ce projet est sous licence [MIT](LICENSE).