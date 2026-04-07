# Installation de DaVinci Resolve 20 sur Ubuntu 24

Ce guide explique comment installer DaVinci Resolve 20 sur Ubuntu 24, en contournant les problèmes rencontrés lors de l'installation classique.

---

## Prérequis

- Ubuntu 24 (64-bit)
- NVIDIA GPU ou AMD GPU avec pilotes à jour
- sudo / droits administrateur
- `curl` et `wget` installés

---
s
## Étapes d'installation

### 1. Installer les 
```bash
sudo apt install libfuse2 libapr1 libaprutil1 libasound2t64 libglib2.0-0 libxcb-composite0 libxcb-cursor0 libxcb-icccm4 libxcb-image0 libxcb-keysyms1 libxcb-render-util0  libxcb-xinerama0 libxcb-xinput0
cd ~/Téléchargements
unzip DaVinci_Resolve_Studio_20.x.y_Linux.zip 
```
