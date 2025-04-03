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

1. Créez un dossier nommé Python dans :  
   📂 C:\Program Files (x86)\

2. Dans ce dossier, créez un **sous-dossier portant le nom exact de la version** que vous souhaitez installer.  
   Par exemple :

   - Python **3.9.1** → 📂 C:\Program Files (x86)\Python\Python391\
   - Python **3.11.9** → 📂 C:\Program Files (x86)\Python\Python3119\

> 🧠 Toutes vos versions de Python doivent être installées dans ce dossier commun pour rester organisées :  
📂 C:\Program Files (x86)\Python\

---

### ⚙️ Pendant l'installation

- 🔥 Choisissez **l’installation personnalisée**
- 🔥 Indiquez le **chemin du dossier créé**, exemple :  
  C:\Program Files (x86)\Python\Python3119\
- 🔥 Cochez **"Ajouter Python au PATH"**

---

## 💻 COMMANDES DU TERMINAL A CONNAITRE

> 💡 L’objectif est de créer un environnement virtuel Python propre pour chaque projet.

1. **Ouvrez PowerShell**  
   (via le menu Démarrer ou intégré à VS Code).

---

2. **Naviguez jusqu’à votre projet** :
   
powershell
   cd "C:\wamp64\www\monProjet\"

A partir de là, tu ajoutes :
Créez l’environnement virtuel Python :

✅ Si vous avez une seule version de Python installée :
powershell
python -m venv nomEnvironnement

✅ Si vous avez plusieurs versions installées :
   
powershell
   "C:\Program Files (x86)\Python\Python3119\python.exe" -m venv nomEnvironnement

📝 Cela créera un dossier nomEnvironnement contenant votre environnement virtuel isolé.

Activez l’environnement :
powershell
.\nomEnvironnement\Scripts\activate

👉 L’invite du terminal doit ressembler à :
   
powershell
(nomEnvironnement) PS C:\wamp64\www\monProjet>

Vérifiez la version de Python utilisée dans l’environnement :
powershell
python --version

Exemple de résultat :
   
powershell
Python 3.11.9

✅ Résultat attendu
🎉 Votre environnement virtuel est maintenant prêt à être utilisé pour développer votre projet Python dans un espace propre et isolé.

🧾 À propos
📁 Ce document est un mémo personnel de configuration, mais il peut être utilisé par d'autres développeurs souhaitant structurer proprement leurs projets Python sous Windows.

🖋️ Auteur
Rédigé avec soin par Ludo,
🧠 Développeur en reconversion passionné par l’organisation, la clarté et la rigueur technique. 