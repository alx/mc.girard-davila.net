---
title: "Pinecone (lanceur Minecraft)"
subtitle: "Installer, jouer en solo hors-ligne, et rejoindre le serveur"
---

**PineconeMC** est un lanceur Minecraft **gratuit**, fork de **Prism Launcher** (ex-ElyPrismLauncher). Il gère les **comptes hors-ligne** et **Ely.by** (aucun compte Microsoft requis) — parfait pour notre serveur, qui est en **mode hors-ligne**.

> Téléchargement officiel : **[pineconemc.com/download](https://pineconemc.com/download)** (ou [pineconemc.org](https://pineconemc.org/download)). Ne téléchargez que depuis ces sites.

## 1. Installation

1. Téléchargez la version **portable** (recommandée) pour votre système : **Windows 10+**, **Linux** ou **macOS**.
2. Décompressez l'archive où vous voulez, puis lancez l'exécutable — aucune installation.
3. Au premier lancement, laissez Pinecone télécharger **Java** automatiquement (sinon, indiquez un Java 21+ dans *Réglages → Java*).

## 2. Créer un compte hors-ligne

1. En haut à droite : **Comptes** → **Ajouter un compte hors-ligne**.
2. Choisissez un **pseudo** (sans espaces) — ce sera votre nom en jeu.
3. *(Optionnel)* Ajoutez un compte **Ely.by** pour afficher un skin.
4. Cochez le compte pour l'activer.

## 3. Lancer Minecraft

1. **Ajouter une instance** → choisissez une version. Notre serveur est **Paper 26.2** ; les versions plus anciennes fonctionnent aussi grâce à **ViaVersion/ViaBackwards**.
2. Nommez l'instance (ex. « Rétro ») et validez.
3. Sélectionnez l'instance puis **Jouer**. Le premier lancement télécharge la version et les ressources (cela peut prendre quelques minutes).

## 4. Jouer en solo hors-ligne

- Dans le jeu : **Solo** → **Créer un nouveau monde** → jouez.
- **Aucune connexion internet ni compte Microsoft** n'est nécessaire. Vos mondes restent en local (le bouton dossier de l'instance ouvre le répertoire).

## 5. Rejoindre notre serveur

1. Dans le jeu : **Multijoueur** → **Ajouter un serveur**.
2. Renseignez :
   - **Nom :** `New World`
   - **Adresse :** `192.168.1.109:25565`
3. Le serveur apparaît aussi dans l'onglet **LAN** (grâce à LANBroadcaster).
4. Le serveur est en **mode hors-ligne** : votre compte hors-ligne fonctionne directement.
5. En jeu : `/lobby` pour revenir au hub, puis empruntez un **portail** vers les mini-jeux (BedWars, OneBlock, Parkour, Créatif).

> 🔒 Adresse publique (`mc.girard-davila.net`) : **à venir**. Le serveur est pour l'instant accessible uniquement sur le **réseau local**.

## Dépannage

- **Le téléchargement de la version reste bloqué** : votre FAI peut bloquer les serveurs ; essayez un VPN.
- **« This app can't run on your PC »** : mauvaise architecture (ARM64 vs x64) — reprenez le bon fichier.
- **Écran noir / pas de son au lancement** : vérifiez Java (*Réglages → Java*) et la RAM allouée.
- **Le serveur n'apparaît pas** : êtes-vous bien sur le même réseau `192.168.1.x` ? Sinon, ajoutez-le manuellement (étape 5).
