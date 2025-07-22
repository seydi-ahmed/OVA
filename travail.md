# 🧩 Répartition du travail des développeurs Full Stack

## 👩🏽‍💻 1. Oumy Laye Kane – Responsable Frontend mobile (React Native - Expo)
1) Objectif: Construire l'interface mobile côté utilisateur.

2) Tâches principales:
- Mettre en place le projet React Native avec Expo
- Intégrer l'onboarding multilingue (français, langues locales)
- Développer les écrans:
    - Accueil / Dashboard personnalisé
    - Parcours éducatifs (vidéos, audio, quiz)
    - Progression (badges, niveau, % complétion)
    - Défis citoyens (vue locale + soumission)
- Gérer le mode offline-first (via expo-file-system ou async-storage)
- Connecter les APIs backend
- Travailler avec le designer (Khady Lo) pour respecter les maquettes

## 👨🏽‍💻 2. Elimane Gning – Responsable Backend (Node.js + Express + Auth)
1) Objectif: Créer les APIs REST + logique serveur.

2) Tâches principales:
- Initialiser serveur Node.js + Express
- Modéliser les schémas MongoDB (via Mongoose):
    - Utilisateur, parcours, défis, badges, progression
- Créer les routes API:
    - Authentification (Firebase Auth + middleware)
    - CRUD Parcours, Quiz, Défis, Progressions
    - Téléchargement des contenus (audio, vidéo)
- Mettre en place la pagination, filtres, etc.
- Gérer les permissions utilisateurs
- Déploiement sur Render ou Railway

## 👨🏽‍💻 3. Mouhamed Diouf – Responsable CMS + Intégration IA + Système de contenu
1) Objectif: Gérer le contenu dynamique (Strapi) + IA assistant.

2) Tâches principales:
- Installer et configurer Strapi (admin multilingue + API REST)
- Structurer les types de contenu:
    - Récits audio, quiz, vidéos, défis, témoignages
- Créer l'espace d'administration pour les partenaires ONG / mentors
- Intégrer GPT API (ou fallback simple local)
    - Assistant IA qui accompagne les jeunes dans leur progression
- Liaison CMS ↔ Backend Express
- Gérer la modération de contenu, publication, versionnage