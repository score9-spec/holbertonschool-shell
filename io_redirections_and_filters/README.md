# Shell - IO Redirections and Filters 🚀

Ce repository contient une collection de scripts shell qui démontrent l'utilisation des **redirections I/O** et des **filtres** en Bash.

## 📋 Table des matières

### Scripts de base (Hello World & Affichage)
- [0-hello_world](#0-hello_world) - Affiche "Hello, World"
- [1-confused_smiley](#1-confused_smiley) - Affiche un smiley confus
- [2-hellofile](#2-hellofile) - Affiche le contenu de /etc/passwd

### Manipulation de fichiers
- [3-twofiles](#3-twofiles) - Affiche le contenu de /etc/passwd et /etc/hosts
- [4-lastlines](#4-lastlines) - Affiche les 10 dernières lignes de /etc/passwd
- [5-firstlines](#5-firstlines) - Affiche les 10 premières lignes de /etc/passwd
- [6-third_line](#6-third_line) - Affiche uniquement la troisième ligne
- [7-file](#7-file) - Créer un fichier avec caractères spéciaux

### État du système
- [8-cwd_state](#8-cwd_state) - Sauvegarde l'état du répertoire courant
- [9-duplicate_last_line](#9-duplicate_last_line) - Duplique la dernière ligne

### Filtres et recherches
- [10-no_more_js](#10-no_more_js) - Supprime les fichiers .js
- [11-directories](#11-directories) - Compte les répertoires
- [12-newest_files](#12-newest_files) - Affiche les fichiers les plus récents
- [13-unique](#13-unique) - Affiche les mots uniques

### Recherche de texte
- [14-findthatword](#14-findthatword) - Trouve des lignes contenant "root"
- [15-countthatword](#15-countthatword) - Compte les lignes contenant "bin"
- [16-whatsnext](#16-whatsnext) - Affiche les lignes après "root"
- [17-hidethisword](#17-hidethisword) - Affiche les lignes ne contenant pas "bin"

### Manipulation de caractères
- [18-letteronly](#18-letteronly) - Affiche uniquement les lettres
- [19-AZ](#19-AZ) - Remplace A par Z et c par e
- [20-hiago](#20-hiago) - Supprime les lettres C et c

### Transformations avancées
- [21-reverse](#21-reverse) - Inverse l'input
- [22-users_and_homes](#22-users_and_homes) - Affiche utilisateurs et répertoires home
- [23-empty_casks](#23-empty_casks) - Trouve les fichiers et répertoires vides
- [24-gifs](#24-gifs) - Liste les fichiers .gif triés

### Challenges avancés
- [25-acrostic](#25-acrostic) - Décode un acrostiche
- [26-the_biggest_fan](#26-the_biggest_fan) - Analyse des logs web (TOP 11 hosts)

---

## 🔧 Utilisation

### Prérequis
- **OS:** Ubuntu/Linux
- **Shell:** Bash
- **Permissions:** Scripts exécutables (`chmod +x script_name`)

### Exécution
```bash
# Exemple avec hello_world
./0-hello_world

# Exemple avec analyse de logs
./26-the_biggest_fan < logfile.tsv
