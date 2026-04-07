# Installation de DaVinci Resolve 20 sur Ubuntu 24

Ce guide explique comment installer DaVinci Resolve 20 sur Ubuntu 24, en contournant les problèmes rencontrés lors de l'installation classique.

---

## Prérequis

- Ubuntu 24 (64-bit)
- NVIDIA GPU ou AMD GPU avec pilotes à jour
- sudo / droits administrateur
- `curl` et `wget` installés

---
 
## Étapes d'installation

### 1. Installer les packages nécessaire 
```bash
sudo apt install libfuse2 libapr1 libaprutil1 libasound2t64 libglib2.0-0 libxcb-composite0 libxcb-cursor0 libxcb-icccm4 libxcb-image0 libxcb-keysyms1 libxcb-render-util0  libxcb-xinerama0 libxcb-xinput0
```
### Dezipper le fichier davinci resolve 20

```bash 
cd ~/Téléchargements
unzip DaVinci_Resolve_Studio_20.x.y_Linux.zip 
```

### Changer placez-vous dans le dossier dezipper changer la permission du fichier 
```bash
cd DaVinci_Resolve_20.x.y_Linux
chmod +x DaVinci_Resolve_20.3.2_Linux.run
```
### Installer lancer l'installation de davinci resolve 
```bash
sudo SKIP_PACKAGE_CHECK=1 ./DaVinci_Resolve_20.3.2_Linux.run
```

## Installtion du script de lancement 

Si vous avez git, donc pas la peine de le reinstaller 

```bash 
sudo apt install git
```
### Télechargement du script 

Pour ce faire, clonner le Télechargement du script  dans votre /home (cd /home)

```bash 
sudo git clone https://gist.github.com/f11099a970b22e99f5e13468bd65afff.git
```