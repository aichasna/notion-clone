# Application web de gestion et d’édition de documents

Cette application web est une plateforme moderne de gestion et d’édition collaborative de documents, fortement inspirée de Notion.
Elle permet aux utilisateurs de créer, modifier et partager des documents en temps réel au sein d’une interface fluide, épurée et hautement interactive.

Conçue avec une architecture full-stack moderne, l’application repose sur Next.js, React, Prisma et PostgreSQL, offrant à la fois performance, fiabilité et évolutivité.
Chaque utilisateur dispose d’un espace de travail sécurisé, accessible après authentification via Clerk, où il peut gérer ses documents, les organiser et restaurer les fichiers supprimés grâce à un système de corbeille intégré.

L’interface utilisateur a été développée avec Tailwind CSS et shadcn/ui, garantissant un design cohérent, minimaliste et responsive, adapté à tous les formats d’écran.


## Technologies utilisées
- **Next.js** – Framework React côté serveur pour des performances optimales.  
- **React** – Construction d’interfaces utilisateur dynamiques et réactives.  
- **Tailwind CSS** – Stylisation rapide et design moderne.  
- **Prisma ORM** – Gestion des données et du schéma de base de données.  
- **PostgreSQL** – Base de données relationnelle performante et scalable.  
- **Clerk** – Authentification et gestion des utilisateurs.  
- **TypeScript** – Typage statique pour un code plus fiable et maintenable.  


## Fonctionnalités principales
- Création et édition de documents avec une interface riche et intuitive.  
- Collaboration en temps réel entre plusieurs utilisateurs.  
- Authentification et gestion des comptes utilisateurs avec Clerk.  
- Organisation hiérarchique des fichiers (dossiers, sous-dossiers, corbeille).  
- Système de corbeille avec récupération de documents supprimés.  
- Publication en ligne et partage via des liens publics.  
- Persistance des données dans PostgreSQL via Prisma.  
- Interface adaptative (responsive design) compatible mobile et bureau.  


## Architecture du projet
- **Front-end :** Next.js + React + Tailwind CSS  
- **Back-end :** API Next.js (routes `app/api`) avec Prisma  
- **Base de données :** PostgreSQL (hébergée sur Supabase)  
- **Authentification :** Clerk  
