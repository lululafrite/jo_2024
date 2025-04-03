# 🐍 Gestion de projets Python — Installation et environnement

![Python](https://img.shields.io/badge/Python-3.11.9-blue.svg)
![PowerShell](https://img.shields.io/badge/Shell-PowerShell-blue)
![OS](https://img.shields.io/badge/OS-Windows%2011-lightgrey)
![Status](https://img.shields.io/badge/Status-En%20cours-brightgreen)

---

## 📚 SOMMAIRE

🛠️ [INSTALLER PYTHON](#installer-python)  
💻 [COMMANDES DU TERMINAL A CONNAITRE](#commandes-du-terminal-a-connaitre)

---

## 🛠️ INSTALLER PYTHON

Téléchargez l’installateur depuis le site officiel :  
🔗 https://www.python.org/downloads/windows/

> 📝 Il est **fortement recommandé d’organiser proprement vos installations de Python**, surtout si vous utilisez plusieurs versions.

---

### 📁 Avant l'installation

1. Créez un dossier nommé `Python` dans :  
   📂 `C:\Program Files (x86)\`

2. Dans ce dossier, créez un **sous-dossier portant le nom exact de la version** que vous souhaitez installer.  
   Par exemple :

   - Python **3.9.1** → 📂 `C:\Program Files (x86)\Python\Python391\`  
   - Python **3.11.9** → 📂 `C:\Program Files (x86)\Python\Python3119\`

> 🧠 Toutes vos versions de Python doivent être installées dans ce dossier commun pour rester organisées :  
📂 `C:\Program Files (x86)\Python\`

---

### ⚙️ Pendant l'installation

- 🔥 Choisissez **l’installation personnalisée**  
- 🔥 Indiquez le **chemin du dossier créé**, exemple :  
  `C:\Program Files (x86)\Python\Python3119\`  
- 🔥 Cochez **"Ajouter Python au PATH"**

---

## 💻 COMMANDES DU TERMINAL A CONNAITRE

> 💡 L’objectif est de créer un environnement virtuel Python propre pour chaque projet.

1. **Ouvrez PowerShell**  
   (via le menu Démarrer ou intégré à VS Code).

2. **Naviguez jusqu’à votre projet** :
   ```powershell
   cd "C:\wamp64\www\monProjet\"

3. **Créez l’environnement virtuel Python** :
   ```powershell
   python -m venv nomEnvironnement