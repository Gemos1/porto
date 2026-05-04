# 🌈 Site de Vacances - Instructions

## 📁 Fichiers inclus
- `index.html` - Page d'accueil avec les 2 boutons
- `girl.html` - Page pour votre amie
- `boy.html` - Page pour vous

## ✏️ À personnaliser

### 1. **Textes à modifier**

#### Dans `index.html` :
- Ligne 62 : `<h1 class="intro-text">Did we catch your eye? 👀</h1>`
- Ligne 63 : `<p class="subtitle">Choose wisely...</p>`
- Lignes 66-67 : Textes des boutons

#### Dans `girl.html` :
- Ligne 112 : `<h1>Hey there! 💕</h1>`
- Lignes 113-116 : Le texte de bio
- Ligne 119 : `https://instagram.com/USERNAME_AMIE` ← **REMPLACER par le vrai Instagram**

#### Dans `boy.html` :
- Ligne 112 : `<h1>Hey there! 💙</h1>`
- Lignes 113-116 : Le texte de bio
- Ligne 119 : `https://instagram.com/VOTRE_USERNAME` ← **REMPLACER par le vrai Instagram**

### 2. **Photos à ajouter**

#### Pour `girl.html` :
1. Renommez la photo de votre amie en `photo-amie.jpg`
2. Placez-la dans le même dossier que les fichiers HTML
3. Ligne 110 : Supprimez la div avec `placeholder-photo`
4. À la place, ajoutez : `<img src="photo-amie.jpg" alt="Her photo" class="profile-photo">`

#### Pour `boy.html` :
1. Renommez votre photo en `photo-vous.jpg`
2. Placez-la dans le même dossier
3. Ligne 110 : Supprimez la div avec `placeholder-photo`
4. À la place, ajoutez : `<img src="photo-vous.jpg" alt="His photo" class="profile-photo">`

**Format recommandé pour les photos :**
- Format : JPG ou PNG
- Poids : Moins de 500 Ko (compressez si nécessaire)
- Orientation : Portrait ou carré (la photo sera automatiquement rognée en rond)

---

## 🚀 Mettre en ligne (GitHub Pages)

### Étape 1 : Créer un compte GitHub
1. Allez sur [github.com](https://github.com)
2. Créez un compte gratuit

### Étape 2 : Créer un nouveau repository
1. Cliquez sur le bouton **"New"** (vert)
2. Nom du repository : `vacation-site` (ou ce que vous voulez)
3. Cochez **"Public"**
4. Cliquez sur **"Create repository"**

### Étape 3 : Upload vos fichiers
1. Cliquez sur **"uploading an existing file"**
2. Glissez-déposez tous vos fichiers (index.html, girl.html, boy.html, + vos 2 photos)
3. Cliquez sur **"Commit changes"**

### Étape 4 : Activer GitHub Pages
1. Dans votre repository, allez dans **Settings** (onglet en haut)
2. Dans le menu de gauche, cliquez sur **Pages**
3. Sous "Source", sélectionnez **"main"** branch
4. Cliquez sur **Save**
5. Attendez 2-3 minutes

### Étape 5 : Récupérer votre URL
Votre site sera disponible à : `https://VOTRE-USERNAME.github.io/vacation-site/`

---

## 📱 Générer le QR Code

Une fois votre site en ligne :
1. Allez sur [qr-code-generator.com](https://www.qr-code-generator.com) ou [qr.io](https://www.qr.io)
2. Collez votre URL GitHub Pages
3. Téléchargez le QR code en PNG
4. Imprimez-le ou partagez-le !

---

## 💡 Astuces

- **Tester en local** : Double-cliquez sur `index.html` pour voir le site dans votre navigateur
- **Modifier après mise en ligne** : Retournez sur GitHub, cliquez sur le fichier, puis sur l'icône crayon pour éditer
- **Changer les couleurs** : Modifiez les valeurs dans les `background: linear-gradient(...)` 

Amusez-vous bien en vacances ! 🌴✨
