# Basile TELLIER — Étudiant en Informatique et Cybersécurité

Étudiant diplômé d'une Licence Informatique à l'Université de Caen et auditeur en Master 1 Sécurité Informatique, Cybersécurité et Cybermenaces .

Ayant suivi avec le module CYRCE le mooc de l'ANSSI, j'ai participé au CTF Orion 2026 organisé par le COMCYBER
(182ème/2000), je développe activement mes compétences en sécurité offensive
et défensive via TryHackMe, Root-Me et différents  projets, et j'ai conçu un système client-serveur
intégrant TLS, hachage et multithreading en Python.

**GitHub :** https://github.com/Garagorn/

---

## Compétences

- **Langages :** Java, C, PHP, SQL, Python, HTML/CSS, Haskell, JavaScript, Vagrant, Ansible 
- **Virtualisation** : VirtualBox
- **Conteneurisation** : Docker, Docker compose
- **Développement logiciel :** Programmation orientée objet, structures de données, algorithmique
- **Web :** React, PHP, API, applications CRUD/MVCR
- **Algorithmique & Graphes :** Tris, BFS/DFS, Prim, Kruskal, FM³, Floyd-Warshall, Bellman-Ford, Dijkstra
- **Systèmes & Réseaux :** Bash, programmation système, notions réseaux
- **Cybersécurité :** Cryptographie (Diffie-Hellman ECC), sécurité des systèmes (bases), OSINT, collecte de preuves
- **Outils :** Git, GitHub, LaTeX, Trello, Overleaf

---

## Formation

**Master 1 Cybersécurité HTT** - Conservatoire National des Arts et Métiers (2026- )
Enseignements clés : Intelligence artificielle, Conception et Urbanisation de services réseaux, Gestion de données à large échelle, Sécurité des réseaux, Systèmes et applications répartis pour le cloud.

**Licence Informatique** — Université de Caen (2023–2026)

Enseignements clés :
- Réseaux (LAN/WAN, routage OSPF/BGP, VPN WireGuard/MPLS, firewall)
- Cryptologie & Sécurité des systèmes
- Programmation système (C, Shell, Git)
- Théorie des langages & Compilation
- Bases de données (SQL, MongoDB)

---

## Certifications
- **AI Security** - TryHackMe(En cours)
- **SOC Level 1** — TryHackMe (Octobre, 2026)
    Certification couvrant les enjeux et outils d'un SOC : prise en main de Splunk, Snort, Wireshark
  et Networkminer, détection et analyse d'incidents, surveillance Web, Windows et Linux.
  Approche pratique à travers des labs et challenges progressifs.
- **Cybersecurity101** — TryHackMe (28 Avril 2026)
    Fondamentaux Linux, Windows/AD, réseaux, cryptographie, sécurité
  offensive & défensive, OWASP Top 10
- **Cyberprotecteur tout-terrain** — CYRCE ANSSI/SensCyber (2026)
  Sécurité des postes, nomadisme, gestion des risques
- **Gardien des données** — CYRCE ANSSI/SensCyber (2025)
  Gestion sécurisée des données
- **Cyberveilleur** — CYRCE ANSSI/SensCyber (2025)
  Acculturation à la sécurité numérique

---

## Pratique technique et challenges

### CTF Orion 2026 — Opération Bellatrix (COMCYBER)
CTF orienté OSINT et investigation numérique, 182ème/2000.

- Jour 1 : identification du premier diffuseur d'une campagne de
  désinformation via sources ouvertes
- Jour 2 : collecte et croisement de preuves techniques pour remonter
  à l'origine de la campagne
- Jour 3 : localisation d'un individu ("Lynx") par techniques OSINT

Lien : https://www.defense.gouv.fr/air/actualites/orion-jeunesse-2026-loperation-bellatrix-met-au-defi-jeunes

### Root-Me
Pratique régulière de challenges web et techniques pour progresser sur
l'exploitation de vulnérabilités et la sécurité applicative. <br>


### TryHackMe — Cybersecurity101
Formation structurée en cours couvrant Linux, réseaux, Active Directory,
cryptographie et outils de sécurité offensive/défensive. <br>
Profil : https://tryhackme.com/p/Eragonn

---

## Projets Personnels

### Validateur de mot de passe — Architecture client-serveur (Python)
Extension d'un validateur local vers une architecture client-serveur TCP
intégrant TLS, hachage sécurisé, gestion de logs et multithreading.
Lien : https://github.com/Garagorn/VerificateurMotDePasse_Client_Serveur

### Validateur de mot de passe — Version locale (Python)
Outil d'analyse de robustesse des mots de passe avec règles de complexité,
stockage et hachage sécurisé.
Lien : https://github.com/Garagorn/Validateur-MDP

### Mise en place d'un lab homelab d'attaque et SOC (En cours)
Laboratoire de test sur **VirtualBox** créer avec **Vagrant** et provisionné avec **Ansible** de machines virtulles :
0. Fondations du lab
0.1 Vagrant basique
0.2 Ansible basique
0.3 Playbook
0.4 Ansible pour provisionner Vagrant
1. Mise en place du réseau de base
1.1 Plan d'addressage
1.2 Routage
1.3 Configuration des routeurs avec Ansible
2. Machine cible et journalisation
2.1 Mise en place de la machine cible
2.2 Déploiement DVWA / Juice shop en conteneurs
2.3 Installation de Wazuh
2.4 Installation des agents Wazuh sur machine cible et routeur
2.5 Remontée des logs
3. Attaque et détection
3.1
4. Durcissement
4.1
5. IDS
5.1
6. DMZ et bastion
7. VLAN


---

## Projets Académiques

### Diffie-Hellman sur Courbes Elliptiques
Démonstrateur pédagogique de l'échange de clés sécurisé basé sur la cryptographie ECC.
Le projet illustre l'arithmétique modulaire sur courbes elliptiques et visualise chaque
étape du protocole. <br>
Lien : https://github.com/Garagorn/Demonstrator-DH

### Calculatrice Scientifique — ANTLR4
Calculatrice scientifique compilable par une machine à pile virtuelle, réalisée avec ANTLR4.
Le projet couvre la conception de la grammaire, la génération du lexer/parser et l'émission
d'un bytecode interprétable. <br>
Lien : https://github.com/Garagorn/LangageCompilation

### Analyse des Algorithmes de Tri
Chaîne de traitement permettant d'évaluer et de comparer différents algorithmes de tri sur
des jeux de données variés. Implémentée en Java, Bash et Python, elle produit des mesures
de performance exploitables pour comparer les approches. <br>
Lien : https://github.com/Garagorn/AnalyseAlgoSorting

### Arbres Couvrants Minimaux — Prim & Kruskal
Démonstrateur pédagogique autour de l'implémentation et comparaison des algorithmes de Prim
et Kruskal sur des graphes pondérés. Visualisation des étapes de construction et analyse
comparative des performances. <br>
Lien : https://github.com/Garagorn/Demonstrator-MST

---

## Autres projets académiques

- **Jeu de Blackjack (contre IA)** — modélisation de stratégies adverses et gestion d'état de jeu. <br>
  Lien : https://github.com/Garagorn/Projet_Blackjack
- **Todo List — React** — gestion de tâches, gestion d'état et composants fonctionnels. <br>
  Lien : https://github.com/Garagorn/TodoList
- **Site Web PHP + SQL (Animaux & API)** — application CRUD avec API REST et schéma relationnel .<br>
  Lien : https://github.com/Garagorn/Web-Animals 
- **CRUD Musique — PHP / SQL** — gestion de titres musicaux avec authentification, architecture MVC. <br>
  Lien : https://github.com/Garagorn/Web-Music
- **Analyseur de "Livre Dont Vous Êtes le Héros"** — transformation en graphe de décisions, visualisation FM3. <br>
  Lien : https://github.com/Garagorn/FM3-LDVELH

---

## Objectifs 2026

- **Docker** 
- **Ansible / Terraform / Vagrant **
Se former avec TryHackMe pour apprendre et comprendre :
- **SOC Level 1** de TryHackMe -
- Ecrit régulier de Write-Up de salle THM
- **CTF continus** — via l'association Caen Hack You entre autre
- 404 CTF

## Objectifs 2027
- **Ansible / Terraform / Vagrant ** plus développée
- <br> Se former avec TryHackMe pour apprendre et comprendre :-
- Ecrit régulier de Write-Up de salle THM
- **Rootme** - Pratique appliquée des concepts et notions vu avec THM / Cours
- **SOC Level 2** de TryHackMe -
- **AI Security** de TryHackMe - <br>
- **CTF continus** — via l'association Caen Hack You entre autre
- 404 CTF

---

## Contact

**GitHub :** https://github.com/Garagorn/ <br>
**E-mail :** contact.able899@passmail.net <br>
**LinkedIn :** BASILE TELLIER
