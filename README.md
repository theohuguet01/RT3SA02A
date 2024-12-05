# SAE 3.02 - Developper des applications communicantes APP; Projet en autonomie

## Description du projet
Ce projet consiste  dvelopper une application de gestion des absences base sur une architecture client-serveur en utilisant les sockets. Le serveur sera crit en langage C et devra communiquer efficacement avec plusieurs clients. Lapplication permettra de grer et de suivre les absences dans un contexte prcis dfini par le projet.

## Objectifs principaux
- **Cration dun serveur robuste :** capable de traiter les demandes de plusieurs clients de manire concurrente.
- **Dveloppement des clients :** permettant de communiquer avec le serveur pour effectuer les oprations lies  la gestion des absences.
- **Mise en place dune communication via sockets :** garantissant une transmission fiable et efficace des donnes.

## Livrables
1. **Code source du serveur**
   - Fichiers source en langage C.
   - Scripts ou outils pour la compilation et lexcution du serveur.

2. **Code source des clients**
   - Fichiers source pour chacun des clients.
   - Scripts ou outils pour leur compilation et leur excution.

3. **Documentation technique**
   - Un rapport dtaill reprenant les tapes de conception et de dveloppement.
   - Explications comparables au dernier chapitre du polycopi fourni en cours.

## Technologies utilises
- **Langage principal :** C
- **Protocoles de communication :** TCP/IP via sockets

## Structure du projet
- `src/` : Contient les fichiers source du serveur et des clients.
- `docs/` : Rapport et documentation complmentaire.
- `build/` : Scripts de compilation et binaires gnrs.

## Installation et excution
### Compilation
1. Naviguez dans le rpertoire `src/`.
2. Compilez le serveur :
   ```bash
   gcc -o server server.c
   ```
3. Compilez les clients :
   ```bash
   gcc -o client client.c
   ```

### Excution
1. Lancez le serveur :
   ```bash
   ./server
   ```
2. Lancez les clients dans des terminaux spars :
   ```bash
   ./client
   ```

## Rgles de collaboration
- Assurez-vous de documenter le code avec des commentaires clairs.
- Effectuez des tests unitaires pour verifier la robustesse du serveur et des clients.
- Utilisez un systme de gestion de version comme Git pour suivre les modifications.


