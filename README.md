# 🌍 TD2 - Decentralized Tic-Tac-Toe

Bienvenue dans **TD2 - Decentralized Tic-Tac-Toe**, un projet visant à explorer les technologies **P2P et Web3** à travers un site web entièrement hébergé sur **IPFS**.

---

## 🎮 Aperçu du Projet

Ce projet est un simple jeu de **Tic-Tac-Toe**, conçu avec **HTML, CSS et JavaScript**, et déployé sur IPFS via **Pinata** et **GitHub Actions**.

🚀 **Accédez au site ici** :  
👉 [Jouer à Tic-Tac-Toe](https://ipfs.io/ipfs/QmeJaufp9seXCpHMFwxX53P3oRQW8Ny1DduCXAxebEwxv7)

---

## 📂 Structure du Projet

```
TD2_Decentralization/
│── src/
│   ├── index.html       # Fichier principal du jeu Tic-Tac-Toe
│── LICENSE              # Licence du projet
│── README.md            # Ce fichier
│── .github/
│   └── workflows/
│       └── deploy.yml   # Automatisation du déploiement via GitHub Actions
```

---

## 🔧 Installation & Déploiement

### 🛠 Prérequis

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [IPFS Desktop](https://docs.ipfs.tech/install/ipfs-desktop/)
- [Pinata](https://www.pinata.cloud/)
- Un compte **GitHub** avec **Actions activées**

### 📥 Cloner le projet

```bash
git clone git@github.com:CryptoL1nx/TD2_Decentralization.git
cd TD2_Decentralization
```

### 🚀 Déploiement Manuel sur IPFS
1. Assurez-vous que **IPFS** est installé et en cours d'exécution.
2. Ajoutez les fichiers à IPFS :
   ```bash
   ipfs add -r src/
   ```
3. Copiez le **CID généré** et ouvrez l'URL :
   ```
   https://ipfs.io/ipfs/QmeJaufp9seXCpHMFwxX53P3oRQW8Ny1DduCXAxebEwxv7
   ```

---

## 🤖 Automatisation avec GitHub Actions

Ce projet utilise **GitHub Actions** pour uploader les fichiers sur **Pinata** automatiquement à chaque modification.

### 📌 **Configuration**
1. Créez un compte sur **[Pinata](https://www.pinata.cloud/)**.
2. Générez une **API Key** et ajoutez-la à **GitHub Secrets** :
   - `PINATA_API_KEY`
   - `PINATA_API_SECRET`
3. Chaque push sur `main` déclenche **`.github/workflows/deploy.yml`**, qui déploie le site.

---

## 🚀 Technologies Utilisées
✅ **IPFS** - Stockage décentralisé  
✅ **Pinata** - Hébergement IPFS  
✅ **GitHub Actions** - CI/CD pour IPFS  
✅ **HTML, CSS, JavaScript** - Interface du jeu  
✅ **P2P & Web3** - Technologie de déploiement  

---

## 📜 Licence
Ce projet est sous licence **MIT**. Vous êtes libre de le réutiliser et de le modifier.

---

## ✨ Contributeurs
👤 **CryptoL1nx**  
💬 Contact : [GitHub](https://github.com/CryptoL1nx)

---

🎉 **Merci d'avoir exploré le Web3 avec ce projet !** 🚀

