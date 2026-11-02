<div align="center">

# Michel Darryl TAMO FOTSO

### Développeur Full Stack · Java / Spring Boot · Angular · DevOps

Étudiant en Master 2 Architecture et Développement Logiciel — **3iL Ingénieurs, Limoges**

<br>

![Statut](https://img.shields.io/badge/Recherche_un_stage_de_6_mois-d%C3%A8s_d%C3%A9but_mars_2027-16A34A?style=for-the-badge)

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--michel--fotso.vercel.app-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-michel-fotso.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-darryl--fotso-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darryl-fotso)
[![Email](https://img.shields.io/badge/Email-tamofotso90@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tamofotso90@gmail.com)

</div>

<br>

## À propos

Je conçois des applications complètes, **web et mobiles**, de l'analyse du besoin jusqu'à la mise en production. Chaque projet suit la même démarche :

1. **Modélisation** de l'application en UML avec **StarUML** (cas d'utilisation, classes, séquences) avant d'écrire du code
2. **Développement** d'une API REST sécurisée et de clients web et mobiles
3. **Qualité** : tests, analyse statique (SonarQube) et *quality gates* intégrées aux pipelines
4. **Livraison automatisée** avec des pipelines **CI/CD GitHub Actions** et des conteneurs Docker

**Actuellement**
- Master 2 à 3iL Ingénieurs (Limoges, France)
- À la recherche d'un stage de 6 mois en développement **Full Stack Java / Angular**, à partir de début mars 2027
- Je monte en compétence sur le cloud (AWS) et l'infrastructure as code (Terraform, Ansible)

<br>

## Stack technique

| | |
|---|---|
| **Backend** | ![Backend](https://skillicons.dev/icons?i=java,spring,php,laravel) |
| **Frontend** | ![Frontend](https://skillicons.dev/icons?i=angular,react,nextjs,ts,js,tailwind,bootstrap) |
| **Mobile** | ![Mobile](https://skillicons.dev/icons?i=flutter,dart) |
| **Bases de données** | ![BDD](https://skillicons.dev/icons?i=mysql,postgres) |
| **DevOps & Cloud** | ![DevOps](https://skillicons.dev/icons?i=docker,githubactions,aws,terraform,ansible,linux) |
| **Outils** | ![Outils](https://skillicons.dev/icons?i=git,github,jira,postman,figma,idea,vscode) |

**Qualité & sécurité** : SonarQube, JUnit, Mockito, Spring Security (JWT, RBAC, BCrypt), Swagger / OpenAPI  
**Temps réel & messagerie** : RabbitMQ, WebSockets, OneSignal  
**Modélisation** : UML avec **StarUML**, Merise  
**Méthodes** : Agile, Scrum, Kanban · **Documentation** : Confluence

<br>

## Projets

> Pour chaque projet : modélisation UML réalisée avec **StarUML** et pipeline **CI/CD GitHub Actions**.

<br>

### CarrefourConnect — annuaire numérique des commerces

Annuaire interactif des commerces d'une zone géographique. L'utilisateur trouve les commerces près de lui grâce à une **cartographie interactive** et une **recherche de proximité**, depuis le web ou son mobile.

| | |
|:--|:--|
| **Backend** | Spring Boot **3.4** · API REST |
| **Frontend web** | Angular **21** · cartographie Leaflet |
| **Mobile** | Flutter |
| **Base de données** | PostgreSQL + extension **PostGIS** (requêtes géospatiales) |
| **Modélisation** | UML avec StarUML |
| **Qualité** | SonarQube |
| **CI/CD** | GitHub Actions |

**Points clés**
- Recherche de commerces par proximité grâce aux fonctions géospatiales de PostGIS
- Carte interactive Leaflet pour visualiser et explorer les commerces
- Une seule API consommée par l'application web et l'application mobile
- Analyse de la qualité du code avec SonarQube, intégrée au pipeline GitHub Actions

![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.4-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-21-DD0031?style=flat-square&logo=angular&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![StarUML](https://img.shields.io/badge/UML-StarUML-F59E0B?style=flat-square)

[![Voir le code](https://img.shields.io/badge/Voir_le_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fotso12/CarrefourConnect)

<br>

### Collecte-épargne-app — gestion de collecte et d'épargne

Application **multiplateforme** de gestion de collecte et d'épargne d'argent, avec **notifications en temps réel** pour tenir les utilisateurs informés de chaque opération.

| | |
|:--|:--|
| **Backend** | **Java 21** · Spring Boot **3.5** · API REST |
| **Frontend web** | Angular **21** |
| **Mobile** | Flutter |
| **Base de données** | MySQL |
| **Messagerie** | RabbitMQ (traitement asynchrone) |
| **Temps réel** | WebSockets · notifications push OneSignal |
| **Modélisation** | UML avec StarUML |
| **CI/CD** | GitHub Actions |

**Points clés**
- Une application, deux clients : web (Angular) et mobile (Flutter)
- Architecture orientée événements avec RabbitMQ pour découpler les traitements
- Mises à jour instantanées côté client grâce aux WebSockets
- Notifications push sur mobile avec OneSignal

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-21-DD0031?style=flat-square&logo=angular&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![OneSignal](https://img.shields.io/badge/OneSignal-E54B4D?style=flat-square&logo=onesignal&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![StarUML](https://img.shields.io/badge/UML-StarUML-F59E0B?style=flat-square)

[![Voir le code](https://img.shields.io/badge/Voir_le_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fotso12/collecte-epargne-app)

<br>

### Agricam-IaC — infrastructure cloud as code

Provisionnement et automatisation d'une **infrastructure cloud sécurisée**, avec une étude de migration vers un **modèle hybride** (cloud public + serveurs VPS).

| | |
|:--|:--|
| **Provisionnement** | Terraform |
| **Configuration des serveurs** | Ansible |
| **Cloud** | AWS |
| **Hébergement complémentaire** | VPS (approche hybride) |
| **Environnement de travail** | WSL |
| **Modélisation** | UML avec StarUML (schémas d'architecture) |
| **CI/CD** | GitHub Actions |

**Points clés**
- Infrastructure entièrement décrite en code : reproductible, versionnée avec Git, relue comme du code applicatif
- Séparation claire entre le provisionnement (Terraform) et la configuration (Ansible)
- Étude comparative cloud / VPS pour évaluer une migration vers un modèle hybride

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![StarUML](https://img.shields.io/badge/UML-StarUML-F59E0B?style=flat-square)

[![Voir le code](https://img.shields.io/badge/Voir_le_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fotso12/agricam-iac)

<br>

### MonBois.eu — site vitrine d'exportation de bois

Site vitrine d'une entreprise de **négoce et d'exportation de bois nobles et de construction** vers l'Union Européenne et l'Amérique du Nord.

| | |
|:--|:--|
| **Framework** | Next.js **15** · React **19** |
| **Langage** | TypeScript |
| **Styles** | Tailwind CSS (thème personnalisé tons bois et forêt) |
| **Icônes** | Lucide React |
| **Hébergement** | Vercel |
| **Modélisation** | UML avec StarUML |
| **CI/CD** | GitHub Actions (déploiement automatique sur Vercel) |

**Fonctionnalités**
- **Bilingue FR / EN** avec bascule instantanée de la langue dans la barre de navigation
- **Multi-devises EUR / USD** pour l'affichage des tarifs indicatifs
- **Recherche et filtres** par essence, provenance ou usage, et par catégorie (feuillus, résineux, tropicaux, construction)
- **Catalogue** de cartes illustrées avec fenêtre de détails techniques : densité, dureté, origine, certification FSC, usages
- **Section « À propos »** : histoire, certifications écologiques, séchage KD (Kiln Dried), logistique internationale
- **Formulaire de demande de devis** avec choix du bois et de la région de livraison

**Déploiement**
- Pipeline GitHub Actions configuré avec les secrets Vercel pour déployer à chaque mise à jour
- Documentation de migration vers Ionos ou Hostinger (export statique ou hébergement Node.js)

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![StarUML](https://img.shields.io/badge/UML-StarUML-F59E0B?style=flat-square)

[![Voir le code](https://img.shields.io/badge/Voir_le_code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fotso12/MonBois.eu)
[![Site en ligne](https://img.shields.io/badge/Site_en_ligne-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://mon-bois-eu.vercel.app)

<br>

## Expériences

### Stagiaire développeur backend Java / Spring Boot
**Dooke Corporation, Douala (Cameroun)** · 04/2026 – 09/2026
- Analyse fonctionnelle des modules ERP (RH, parc matériel) et modélisation des données via les entités JPA
- Développement d'une trentaine d'endpoints REST (Spring Boot, architecture N-tiers), conteneurisation Docker, automatisation CI/CD avec GitHub Actions
- Sécurisation RBAC avec Spring Security, JWT et BCrypt
- Qualité logicielle : tests JUnit / Mockito, quality gates SonarQube
- Validation des API avec Postman, administration de PostgreSQL, documentation Swagger / OpenAPI, spécifications sur Confluence
- Méthodologie Agile Scrum : daily meetings, brainstorming technique, pair programming

`Java 25` `Spring Boot 4` `PostgreSQL` `Spring Security` `JWT` `Docker` `SonarQube` `GitHub Actions` `Swagger`

### Stagiaire développeur Full Stack
**Dooke Corporation, Douala (Cameroun)** · 05/2025 – 08/2025
- Audit de l'existant et modélisation UML de l'architecture cible pour la migration des plateformes d'entreprise
- Maquettes UI/UX sous Figma et bibliothèque de composants React réutilisables (boutons, navbar, footer)
- Développement front-end des plateformes migrées et d'un site optimisé (Next.js, Tailwind CSS, TypeScript)
- Sécurisation des formulaires (validation client / serveur, anti-spam) et déploiement automatisé avec GitHub Actions
- Méthodologie Kanban, documentation sur Confluence

`Next.js` `React` `TypeScript` `Tailwind CSS` `Figma` `GitHub Actions`

### Stagiaire développeur Full Stack
**YTech, Douala (Cameroun)** · 06/2024 – 08/2024
- Analyse des besoins et conception de la base de données (Merise : MCD, MLD) pour un outil web de SAV (service après-vente)
- Backend Laravel / MySQL en architecture MVC : Eloquent ORM, migrations, routes, contrôleurs
- Interfaces dynamiques et responsives avec Blade, Bootstrap et JavaScript
- Authentification par profils utilisateurs via les middlewares Laravel, tableaux de bord de suivi
- Versionnement avec Git (commits, branches)

`PHP 8.3` `Laravel 11` `Bootstrap 5.3` `MySQL` `Git`

<br>

## Formation

- **Master 2 Expert en Architecture et Développement Logiciel** — 3iL Ingénieurs, Limoges *(2026 – 2027, en cours)*
- **Master 1 Expert en Architecture et Développement Logiciel** — Institut Universitaire de la Côte, Douala *(2025 – 2026)*
- **Bachelor en Conception de Systèmes d'Information, Développement Logiciel et Web** — Institut Universitaire de la Côte, Douala *(2024 – 2025)*

<br>

## Certifications

| Certification | Attestation |
|:--|:--:|
| Introduction to Cloud | [Consulter](https://ag3il-my.sharepoint.com/:b:/g/personal/tamofom_3il_fr/IQCUAmNxcyQVSK8lBUHzs-CpAU3fglligkEh9kgU4yPZs2E?e=K2Y022) |
| Job Roles in the Cloud | [Consulter](https://ag3il-my.sharepoint.com/:b:/g/personal/tamofom_3il_fr/IQBvKzeHUjLXR7UDE4CRaHKhARAWE0zvzMjaCMcO1nUmA1Y?e=vrcWR3) |
| AWS Technical Essentials | [Consulter](https://ag3il-my.sharepoint.com/:b:/g/personal/tamofom_3il_fr/IQCdVLL36m_QQpSA17NrR79iAZ5NPSY8cmuv0G2gwRVGmP4?e=eYWuVR) |
| Getting Started with DevOps | [Consulter](https://ag3il-my.sharepoint.com/:b:/g/personal/tamofom_3il_fr/IQDNmGm6U2kiT6W-2AwphYzYAfnQ2GHfLsalMvs4XHZjF2w?e=ToORQu) |
| Foundations of Prompt Engineering | [Consulter](https://ag3il-my.sharepoint.com/:b:/g/personal/tamofom_3il_fr/IQCh3uSRce19RL2oUu9LB0hCATzAhe5ktHK04JqNJHHUxlc?e=j1jfXJ) |

<br>

## Langues

**Français** : langue maternelle · **Anglais** : intermédiaire

<br>

<div align="center">

### Travaillons ensemble

Un stage, un projet, une question technique ? Écrivez-moi.

[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-michel-fotso.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darryl-fotso)
[![Email](https://img.shields.io/badge/Me_contacter-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tamofotso90@gmail.com)

</div>
