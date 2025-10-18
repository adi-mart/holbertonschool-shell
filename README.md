# Holberton School - Shell Project

Ce dépôt regroupe une série de scripts Bash réalisés dans le cadre du cursus Holberton School. Il vise à explorer et maîtriser les commandes fondamentales du shell Unix/Linux, la gestion des variables, les redirections, les permissions et bien plus.

## Arborescence du projet

```text
holbertonschool-shell/
├── basics/
│   ├── 0-current_working_directory
│   ├── 1-listit
│   ├── 2-bring_me_home
│   ├── 3-listfiles
│   ├── 4-listmorefiles
│   ├── 5-listfilesdigitonly
│   ├── 6-firstdirectory
│   ├── 7-movethatfile
│   ├── 8-firstdelete
│   ├── 9-firstdirdeletion
│   ├── 10-back
│   ├── 11-lists
│   ├── 12-file_type
│   ├── 13-symbolic_link
│   ├── 14-copy_html
│   ├── 15-lets_move
│   ├── 16-clean_emacs
│   ├── 17-tree
│   └── README.md
├── init_files_variables_and_expansions/
│   ├── 0-alias
│   ├── 1-hello_you
│   ├── 2-path
│   ├── 3-paths
│   ├── 4-global_variables
│   ├── 5-local_variables
│   ├── 6-create_local_variable
│   ├── 7-create_global_variable
│   ├── 8-true_knowledge
│   ├── 9-divide_and_rule
│   ├── 10-love_exponent_breath
│   ├── 11-binary_to_decimal
│   ├── 12-combinations
│   ├── 13-print_float
│   ├── 14-decimal_to_hexadecimal
│   └── README.md
├── io_redirections_and_filters/
│   ├── 0-hello_world
│   ├── 1-confused_smiley
│   ├── 2-hellofile
│   ├── 3-twofiles
│   ├── 4-lastlines
│   ├── 5-firstlines
│   ├── 6-third_line
│   ├── 7-file
│   ├── 8-cwd_state
│   ├── 9-duplicate_last_line
│   ├── 10-no_more_js
│   ├── 11-directories
│   ├── 12-newest_files
│   ├── 13-unique
│   ├── 14-findthatword
│   ├── 15-countthatword
│   ├── 16-whatsnext
│   ├── 16-whatsnext.save
│   ├── 17-hidethisword
│   ├── 18-letteronly
│   ├── 19-AZ
│   ├── 20-hiago
│   ├── 21-reverse
│   ├── 22-users_and_homes
│   ├── iacta
│   ├── ls_cwd_content
│   └── README.md
├── permissions/
│   ├── 0-iam_betty
│   ├── 1-who_am_i
│   ├── 2-groups
│   ├── 3-new_owner
│   ├── 4-empty
│   ├── 5-execute
│   ├── 6-multiple_permissions
│   ├── 7-everybody
│   ├── 8-James_Bond
│   ├── 9-John_Doe
│   ├── 10-mirror_permissions
│   ├── 11-directories_permissions
│   ├── 12-directory_permissions
│   ├── 13-change_group
│   ├── 14-change_owner_and_group
│   ├── 15-symbolic_link_permissions
│   ├── 16-if_only
│   ├── hello
│   ├── .3-new_owner.swp
│   └── README.md
└── README.md
```


## Détail des dossiers

---

### basics/
**Scripts pour apprendre les commandes de base du shell : navigation, gestion de fichiers et dossiers, liens, etc.**

| Script                      | Fonction principale                                                        |
|-----------------------------|-----------------------------------------------------------------------------|
| 0-current_working_directory | Affiche le répertoire courant (`pwd`)                                       |
| 1-listit                    | Liste le contenu du répertoire courant (`ls`)                               |
| 2-bring_me_home             | Va dans le répertoire personnel (`cd ~`)                                    |
| 3-listfiles                 | Liste les fichiers avec détails (`ls -l`)                                   |
| 4-listmorefiles             | Liste tous les fichiers, y compris cachés (`ls -la`)                        |
| 5-listfilesdigitonly        | Liste fichiers avec détails numériques (`ls -lna`)                          |
| 6-firstdirectory            | Crée un dossier `/tmp/my_first_directory`                                   |
| 7-movethatfile              | Déplace `/tmp/betty` dans `/tmp/my_first_directory`                         |
| 8-firstdelete               | Supprime `/tmp/my_first_directory/betty`                                    |
| 9-firstdirdeletion          | Supprime `/tmp/my_first_directory`                                          |
| 10-back                     | Revient au dossier précédent (`cd -`)                                       |
| 11-lists                    | Liste le contenu de plusieurs dossiers (`ls -la . .. /boot`)                |
| 12-file_type                | Affiche le type d'un fichier (`file`)                                       |
| 13-symbolic_link            | Crée un lien symbolique vers `/bin/ls`                                      |
| 14-copy_html                | Copie les fichiers `.html` modifiés dans le dossier parent                  |
| 15-lets_move                | Déplace les fichiers/dossiers majuscules vers `/tmp/u`                      |
| 16-clean_emacs              | Supprime les fichiers de sauvegarde Emacs (`rm *~`)                         |
| 17-tree                     | Crée une arborescence de dossiers `welcome/to/school`                       |

---

### init_files_variables_and_expansions/
**Scripts pour manipuler les variables, alias, expansions arithmétiques et fichiers d'init du shell.**

| Script                   | Fonction principale                                                          |
|--------------------------|------------------------------------------------------------------------------|
| 0-alias                  | Crée un alias personnalisé                                                   |
| 1-hello_you              | Affiche un message de bienvenue avec le nom de l'utilisateur                 |
| 2-path                   | Ajoute `/action` à la variable PATH                                          |
| 3-paths                  | Compte le nombre de chemins dans PATH                                        |
| 4-global_variables       | Affiche toutes les variables d'environnement (`printenv`)                     |
| 5-local_variables        | Affiche toutes les variables locales et d'environnement (`set`)               |
| 6-create_local_variable  | Crée une variable locale nommée BEST                                         |
| 7-create_global_variable | Crée une variable d'environnement nommée BEST                                |
| 8-true_knowledge         | Affiche la somme de 128 et de TRUEKNOWLEDGE                                  |
| 9-divide_and_rule        | Affiche le résultat de POWER / DIVIDE                                        |
| 10-love_exponent_breath  | Affiche la puissance de BREATH à la LOVE                                     |
| 11-binary_to_decimal     | Convertit une variable binaire en décimal                                    |
| 12-combinations          | Affiche toutes les combinaisons de deux lettres minuscules sauf "oo"         |
| 13-print_float           | Affiche une variable NUM au format flottant à deux décimales                 |
| 14-decimal_to_hexadecimal| Convertit une variable décimale en hexadécimal                               |

---

### io_redirections_and_filters/
**Scripts pour pratiquer les redirections d'entrée/sortie et les filtres classiques du shell.**

| Script                | Fonction principale                                                            |
|-----------------------|--------------------------------------------------------------------------------|
| 0-hello_world         | Affiche "Hello, World"                                                         |
| 1-confused_smiley     | Affiche un smiley confus                                                        |
| 2-hellofile           | Affiche le contenu de `/etc/passwd`                                             |
| 3-twofiles            | Affiche le contenu de deux fichiers                                             |
| 4-lastlines           | Affiche les 10 dernières lignes d'un fichier                                    |
| 5-firstlines          | Affiche les 10 premières lignes d'un fichier                                    |
| 6-third_line          | Affiche la 3ème ligne d'un fichier                                              |
| 7-file                | Ajoute une ligne dans un fichier au nom complexe                                |
| 8-cwd_state           | Sauvegarde le contenu du dossier courant dans un fichier                        |
| 9-duplicate_last_line | Duplique la dernière ligne d'un fichier                                         |
| 10-no_more_js         | Supprime tous les fichiers `.js` du dossier courant et sous-dossiers            |
| 11-directories        | Compte le nombre de dossiers dans le répertoire courant                         |
| 12-newest_files       | Affiche les 10 fichiers les plus récents                                        |
| 13-unique             | Affiche les lignes uniques d'une entrée triée                                   |
| 14-findthatword       | Recherche le mot "root" dans `/etc/passwd`                                     |
| 15-countthatword      | Compte le nombre d'occurrences du mot "bin" dans `/etc/passwd`                 |
| 16-whatsnext          | Affiche 3 lignes après la première occurrence de "root" dans `/etc/passwd`     |
| 17-hidethisword       | Affiche les lignes ne contenant pas "bin" dans `/etc/passwd`                   |
| 18-letteronly         | Affiche les lignes commençant par une lettre dans un fichier de config          |
| 19-AZ                 | Remplace certains caractères par d'autres                                       |
| 20-hiago              | Supprime les caractères 'c' et 'C' de l'entrée                                  |
| 21-reverse            | Inverse chaque ligne de l'entrée                                                |
| 22-users_and_homes    | Affiche les utilisateurs et leur dossier personnel                              |

---

### permissions/
**Scripts pour comprendre et manipuler les permissions, propriétaires et groupes de fichiers/dossiers.**

| Script                      | Fonction principale                                                        |
|-----------------------------|-----------------------------------------------------------------------------|
| 0-iam_betty                 | Se connecter en tant qu'utilisateur betty                                   |
| 1-who_am_i                  | Affiche le nom de l'utilisateur courant                                     |
| 2-groups                    | Affiche les groupes de l'utilisateur courant                                |
| 3-new_owner                 | Change le propriétaire du fichier `hello` pour betty                        |
| 4-empty                     | Crée un fichier vide nommé `hello`                                          |
| 5-execute                   | Donne le droit d'exécution à l'utilisateur sur `hello`                      |
| 6-multiple_permissions      | Définit les permissions 754 sur `hello`                                     |
| 7-everybody                 | Donne le droit d'exécution à tous sur `hello`                               |
| 8-James_Bond                | Définit les permissions 007 sur `hello`                                     |
| 9-John_Doe                  | Définit les permissions 753 sur `hello`                                     |
| 10-mirror_permissions       | Copie les permissions d'un fichier à un autre                               |
| 11-directories_permissions  | Donne le droit d'exécution à tous sur tous les dossiers                     |
| 12-directory_permissions    | Crée un dossier avec des permissions spécifiques                            |
| 13-change_group             | Change le groupe du fichier `hello`                                         |
| 14-change_owner_and_group   | Change le propriétaire et le groupe de tous les fichiers                    |
| 15-symbolic_link_permissions| Change le propriétaire/groupe d'un lien symbolique                          |
| 16-if_only                  | Change le propriétaire si l'ancien est guillaume                            |

## Utilisation

Chaque script est exécutable et peut être lancé directement depuis le terminal :

```bash
./nom_du_script
```

Pensez à donner les droits d'exécution si besoin :

```bash
chmod +x nom_du_script
```

## Objectifs pédagogiques

- Comprendre le fonctionnement du shell Unix/Linux
- Automatiser des tâches système
- Manipuler les fichiers, variables, permissions et flux de données
- Développer de bonnes pratiques en scripting Bash

## Auteur

Projet réalisé dans le cadre du cursus Holberton School.
