<div align="center">
  <h1 style="color: #2c3e50; margin-bottom: 0;">Assane KANE</h1>
  <h3 style="color: #7f8c8d; margin-top: 0;">Étudiant en Master 1 Informatique – Génie Logiciel à l’Université de Lille</h3>
  
  <p>
    <a href="https://www.linkedin.com/in/assane-kane-10bb19267/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://logibuilder.github.io/assane.kane/">
      <img src="https://img.shields.io/badge/Portfolio-Visiter-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio" />
    </a>
    <a href="mailto:kaneassane81@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
      <a href="https://drive.google.com/file/d/1d2eev6XXp_epj4a-yBdBJMFNIie9DCyx/view?usp=sharing">
    <img src="https://img.shields.io/badge/📄_CV_PDF-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white">
  </a>
  </p>

  <p style="border: 2px solid #2980b9; padding: 15px; border-radius: 10px; background-color: #f0f8ff; color: #2c3e50;">
    <strong>🚀 RECHERCHE D'OPPORTUNITÉS</strong><br/>
    Curieux, proactif et passionné par le développement logiciel, je suis à la recherche d’un <strong>stage en développement logiciel à partir d’avril 2026</strong> et une <strong>alternance en septembre 2026</strong>.
  </p>
</div>

<br/>

<h2 style="color: #2980b9; border-bottom: 2px solid #2980b9; padding-bottom: 5px;">💼 EXPÉRIENCES PROFESSIONNELLES & PROJETS ACADÉMIQUES</h2>

### 🔹 Stage Développement Web – IRIT, Université Toulouse 2
*📅 05/2025 - 08/2025*
* Prétraitement de données RDF et génération d’embeddings en Python.
* Exploration du web sémantique et rédaction de documentation technique.
* **Participation au Symposium BigData** : Veille technologique sur les problématiques de traitement de données massives.
    * **Logistique & Accueil** : Gestion des flux de participants et accueil des chercheurs.
    * **Support opérationnel** : Assistance technique lors des sessions de présentation de travaux de recherche.
    * **Veille scientifique** : Participation aux conférences sur les thématiques du traitement de données massives.

### 🔹 Tisséo Mobile – Application Android de transport [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/Tisseo)
*📅 11/2025 - 01/2026 | Université de Lille*
* Conception et développement d'une application Android pour le réseau de transport Tisséo (Toulouse Métropole).
* Mise en œuvre d'une **Clean Architecture** avec le pattern **MVVM**.
* Gestion d'états réactifs avec **Kotlin Coroutines** et **Flow**.
* **Fonctionnalités :** recherche avec autocomplétion, cartographie (OSMDroid), favoris hors ligne.
* Système d'exportation de données (Favoris) en format JSON.
<br><em><strong>Stack technique :</strong> Kotlin, Jetpack Compose (Material 3), Retrofit, Room, Moshi.</em>

### 🔹 Serveur FTP conforme RFC 959 – Projet systèmes répartis [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/ftp_server)
*📅 01/2026 – 02/2026 | Université de Lille*
* Conception et implémentation d’un serveur FTP multi-threadé en Java conforme à la norme **RFC 959**.
* Gestion des connexions concurrentes via **ServerSocket** et pool de threads (**ExecutorService**).
* Implémentation du **mode passif (PASV)** avec une séparation stricte entre les canaux de contrôle et de données.
* Sécurisation des accès par **Root Jail** (prévention des attaques par traversée de répertoires).
* Architecture extensible basée sur le **Command Pattern** pour le traitement des requêtes.
* **Qualité :** Mise en place d'une suite de tests unitaires et d'intégration avec **JUnit 5** et **Mockito**.
* **Fonctionnalités clés :** USER, PASS, PWD, CWD, CDUP, LIST, NLST, RETR, STOR, DELE, MKD, RMD, RNFR/RNTO, SIZE, MDTM.
<br><em><strong>Stack technique :</strong> Java 21, Socket, Java NIO, Maven, JUnit 5, Mockito.</em>

### 🔹 Client FTP – conforme RFC 959 – Projet systèmes répartis [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/ftpclient)
*📅 01/2025 – 03/2025 | Université de Lille*
* Développement d'un client FTP en ligne de commande avec **exploration récursive** d'arborescence et export de structure.
* Implémentation d'algorithmes de parcours : **DFS** (profondeur) et **BFS** (largeur avec Queue).
* Architecture basée sur les design patterns **Façade** (abstraction réseau) et **Composite** (hiérarchie de fichiers).
* Mise en place d'un mécanisme de **tolérance aux pannes** : reconnexion automatique et restauration d'état (3 tentatives).
* Intégration de l'export JSON via **Gson** avec construction récursive de l'arbre.
* **Fonctionnalités :** Mode passif (PASV) avec parsing regex, filtrage de dossiers, profondeur d'exploration paramétrable.
<br><em><strong>Stack technique :</strong> Java 21, Sockets TCP/IP, Gson, Maven, UML.</em>

### 🔹 League of Stones – Jeu de cartes stratégique en ligne [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/LeaguesOfStones)
*📅 03/2025 – 04/2025*
* Développement d'une application de jeu de cartes complexe avec **Next.js**, incluant le rendu côté serveur (SSR) et un routage dynamique.
* Architecture modulaire composée de plus de **40 composants réutilisables** stylisés avec **CSS Modules**.
* Implémentation d'un système de **Gameplay complet** : gestion du plateau (board), de la main, des phases de combat et des points de vie.
* Mise en place d'un **Matchmaking** performant utilisant le polling serveur (setInterval) pour la synchronisation des joueurs.
* Gestion d'états complexes via les **React Hooks** et persistance des sessions utilisateur avec **SessionStorage**.
* Sécurisation de l'application par **Authentification JWT** et intégration d'une gestion centralisée des erreurs API.
<br><em><strong>Stack technique :</strong> Next.js, React, JavaScript, CSS Modules, JWT, MongoDB.</em>

### 🔹 Chef de projet académique – Université Toulouse 2
*📅 01/2025 - 03/2025*
* Encadrement d’une équipe projet sur l’application de gestion d’emplois du temps.
* Organisation des réunions, répartition des tâches et support technique aux membres.

<br/>

<h2 style="color: #2980b9; border-bottom: 2px solid #2980b9; padding-bottom: 5px;">🎓 FORMATION & PÉDAGOGIE</h2>

### 🎓 Master 1 Informatique – Génie Logiciel | Université de Lille
*📅 2025 – présent*
Formation d'excellence en ingénierie logicielle, adossée aux laboratoires de recherche **CRIStAL** et **Inria Lille**.
* **Spécialisation :** Conception logicielle avancée, méthodes Agiles, systèmes répartis, DevOps.
* **Compétences clés :** Maîtrise du cycle de vie logiciel, qualité logicielle, architecture et sécurité.
* **Innovation (Module RIC) :** Participation à des séminaires de recherche et projets innovants en lien avec les laboratoires.

### 📜 Licence MIASHS (Mathématiques & Informatique) | Université Toulouse 2 – Jean Jaurès
*📅 2022 – 2025*
Cursus pluridisciplinaire alliant informatique fondamentale et mathématiques appliquées.
* **Socle technique :** Algorithmique complexe, structures de données, bases de données (SQL) et architecture système.
* **Approche projet :** Réalisation de projets concrets intégrant modélisation, développement web et gestion de données.

### 👨‍🏫 Tutoring en Informatique – Université de Lille
*📅 Depuis 09/2025*
* Accompagnement d’étudiants de Licence 1 en Python, algorithmes et développement web.
* Préparation des séances de tutorat, suivi pédagogique et soutien à la réussite académique.

<br/>

<h2 style="color: #2980b9; border-bottom: 2px solid #2980b9; padding-bottom: 5px;">🛠️ COMPÉTENCES TECHNIQUES</h2>

**Langages**
<br>
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/sql-%23CC2927.svg?style=for-the-badge&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

**Frameworks & Outils**
<br>
![Spring Boot](https://img.shields.io/badge/spring%20boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-%237F52FF.svg?style=for-the-badge&logo=android&logoColor=white)
![JUnit](https://img.shields.io/badge/junit-%2325A162.svg?style=for-the-badge&logo=junit5&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

**Bases de Données**
<br>
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**Conception & Architecture**
<br>
UML, Clean Architecture, MVVM, Design Patterns (Command, Façade, Composite), Ecore (modélisation).

<br/>

<h2 style="color: #2980b9; border-bottom: 2px solid #2980b9; padding-bottom: 5px;">📁 PROJETS PERSONNELS</h2>

### 📌 TaskBoard [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/taskboard/)
*📅 05/2025 – présent*
* Application web de gestion de tâches inspirée de Trello.
* Tâches organisées en colonnes avec glisser-déposer.
* Authentification multi-rôles (admin/utilisateur) et suivi par statut.
* **Technologies :** React.js, Spring Boot, MariaDB, Bootstrap 5.

### 🎳 Bowling Game [![GitHub](https://img.shields.io/badge/-Code-black?logo=github)](https://github.com/Logibuilder/BowlingGame)
*📅 11/2024 – 12/2024*
* Jeu de simulation de bowling développé en Java (interface console).
* La logique interne gère les scores et les règles du bowling pour offrir une expérience interactive dans le terminal.

---
