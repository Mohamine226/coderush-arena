
# ⚡ CodeRush Arena

> **Plateforme de duels de différents domaines informatique**
>
> Deux développeurs, un même problème, le plus rapide gagne.

---

## 🎯 Vision

CodeRush Arena permet à deux développeurs de s'affronter en temps réel sur un même problème informatique selon le cadre choisi. Le premier à produire une solution correcte remporte le duel et gagne des points de classement.

**Pourquoi ce projet ?**
- Apprendre mieux le domaine de l'informatique par la pratique
- Maîtriser une stack full-stack moderne
- Travailler en équipe (11 étudiants)
- Avoir un projet concret pour son CV

---

## 🛠️ Stack Technique

| Partie | Technologies |
|--------|-------------|
| **Frontend** | React, Vite, Tailwind CSS, Monaco Editor |
| **Backend** | Node.js, Express, Socket.IO |
| **Base de données** | MongoDB Atlas |
| **Cache** | Redis (Upstash) |
| **Sandbox** | Judge0 API |
| **Déploiement** | Render (backend), Vercel (frontend) |

---

## 📁 Structure du Projet

```
coderush-arena/
├── 📁 frontend/          # Application React (UI + Éditeur)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── 📁 backend/           # API Node.js / Express
│   ├── src/
│   ├── routes/           # Endpoints API
│   ├── models/           # Schémas MongoDB
│   └── server.js
│
├── 📁 docs/              # Documentation du projet
│   ├── dossier-projet.md
│   ├── api-spec.md
│   └── planning.md
│
├── 📁 problems/          # Énoncés des problèmes algorithmiques
│   └── problem-001.md
│
└── README.md             # Ce fichier
```

---

## 👥 Équipes

| Équipe | Membres | Responsabilités |
|--------|---------|-----------------|
| **🎨 UI** | 2 pers. | Design, pages, navigation, Tailwind |
| **🖥️ Éditeur / Duel** | 2 pers. | Monaco Editor, timer, interface de duel |
| **⚙️ Backend / Auth** | 2 pers. | API REST, authentification JWT, MongoDB |
| **⚡ Temps réel** | 2 pers. | Socket.IO, matchmaking, synchronisation |
| **🧪 Sandbox / Problèmes** | 2 pers. | Judge0 API, énoncés, validation des solutions |
| **📋 Chef de projet & QA** | 1 pers. | Planning, coordination, tests, déploiement |

---

## 📅 Planning (10 semaines)

| Semaine | Objectif | Livrable |
|---------|----------|----------|
| **S1** | Setup | Environnements prêts, repo structuré |
| **S2** | Auth | Inscription, connexion, JWT fonctionnels |
| **S3** | Éditeur | Monaco Editor intégré dans React |
| **S4** | Problèmes | 5 problèmes créés, Judge0 connecté |
| **S5** | Matchmaking | File d'attente 1v1, appariement des joueurs |
| **S6** | Duel | Duel complet : code, soumission, résultat |
| **S7** | Validation | Tests, corrections de bugs |
| **S8** | Classement | Système de points, leaderboard |
| **S9** | Polish | Design final, animations, optimisations |
| **S10** | Démo | Présentation finale, déploiement |

---

## 🚀 Comment contribuer

### 1. Cloner le repo

```bash
git clone https://github.com/[TON-ORG]/coderush-arena.git
cd coderush-arena
```

### 2. Créer une branche pour ta fonctionnalité

```bash
git checkout -b feature/nom-de-la-fonction
```

**Règle d'or :** Ne jamais coder directement sur `main` !

### 3. Faire un commit régulier

```bash
git add .
git commit -m "feat: ajout de la page de connexion"
git push origin feature/nom-de-la-fonction
```

### 4. Créer une Pull Request

Sur GitHub → Pull Requests → New Pull Request → Demande une revue à un membre de ton équipe.

---

## 📝 Conventions de code

| Type de commit | Préfixe | Exemple |
|----------------|---------|---------|
| Nouvelle fonctionnalité | `feat:` | `feat: ajout du matchmaking` |
| Correction de bug | `fix:` | `fix: timer non synchronisé` |
| Documentation | `docs:` | `docs: mise à jour du README` |
| Refactoring | `refactor:` | `refactor: simplification du auth` |

---

## 💰 Coût du projet

Tout est **gratuit** grâce aux plans gratuits :

| Service | Plan | Coût |
|---------|------|------|
| MongoDB Atlas | M0 Shared | 0€ |
| Judge0 API | Free tier | 0€ |
| Redis Upstash | Free tier | 0€ |
| Render | Free tier | 0€ |
| Vercel | Hobby | 0€ |
| GitHub | Free | 0€ |

---

## 🔗 Liens utiles

| Ressource | Lien |
|-----------|------|
| Documentation React | https://react.dev |
| Documentation Express | https://expressjs.com |
| Documentation Socket.IO | https://socket.io/docs/v4 |
| Documentation Tailwind | https://tailwindcss.com/docs |
| API Judge0 | https://rapidapi.com/judge0-official/api/judge0-ce |
| MongoDB Atlas | https://www.mongodb.com/atlas |

---

## ✅ Checklist avant de coder

- [ ] Node.js installé (`node -v` fonctionne)
- [ ] Git installé (`git --version` fonctionne)
- [ ] VS Code installé avec les extensions
- [ ] Compte GitHub créé et ajouté au repo
- [ ] Compte MongoDB Atlas créé
- [ ] Compte Render créé
- [ ] Compte Vercel créé
- [ ] Discord installé et serveur rejoint

---

## 📞 Contact

- **Discord** : [Lien du serveur à ajouter]
- **Trello** : [Lien du tableau à ajouter]

---

*Projet académique — Équipe de 11 étudiants — 2026*
