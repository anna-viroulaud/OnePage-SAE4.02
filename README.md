# Spear Fisher - XR Game Project Website

Site web statique pour le projet SAE4.02 - Jeu de pêche en réalité étendue (XR)

## Structure du Site

Le site est composé de **4 pages principales** :

### 1. GAME (index.html)
Page principale présentant la version commune développée en trinôme pendant les 3 premières semaines :
- **Hero Section** : Image de fond immersive avec titre
- **Game Presentation** : Description détaillée du gameplay et des contrôles
- **Features** : 6 fonctionnalités clés du jeu
- **Code Examples** : Exemples de code C# avec système de scoring et feedback haptique
- **Screenshots** : Galerie de captures d'écran
- **Team Versions** : Liens vers les 3 versions individuelles
- **Download** : Liens GitHub, builds et ressources

### 2. ADDEM (addem.html)
Version individuelle développée par Addem pendant les semaines 4-5 :
- Présentation des améliorations personnelles
- Liste des fonctionnalités ajoutées
- Vidéo de démonstration
- Screenshots de la version
- Exemples de code
- Défis techniques rencontrés et solutions
- Liens de téléchargement et GitHub

### 3. CELENA (celena.html)
Version individuelle développée par Celena pendant les semaines 4-5 :
- Présentation des améliorations personnelles
- Liste des fonctionnalités ajoutées
- Vidéo de démonstration
- Screenshots de la version
- Exemples de code
- Défis techniques rencontrés et solutions
- Liens de téléchargement et GitHub

### 4. ANNA (anna.html)
Version individuelle développée par Anna pendant les semaines 4-5 :
- Présentation des améliorations personnelles
- Liste des fonctionnalités ajoutées
- Vidéo de démonstration
- Screenshots de la version
- Exemples de code
- Défis techniques rencontrés et solutions
- Liens de téléchargement et GitHub

## Navigation

La barre de navigation en haut de chaque page permet de naviguer entre les 4 pages :
- **GAME** - Version commune (index.html)
- **ADDEM** - Version d'Addem
- **CELENA** - Version de Celena
- **ANNA** - Version d'Anna

## Fichiers du Projet

```
OnePage-SAE4.02/
├── index.html          # Page GAME - Version commune
├── addem.html          # Version individuelle Addem
├── celena.html         # Version individuelle Celena
├── anna.html           # Version individuelle Anna
├── style.css           # Styles CSS pour toutes les pages
├── README.md           # Ce fichier
└── asset/
    ├── logo.png        # Logo Spear Fisher
    └── backgound.png   # Image de fond underwater
```

## À Compléter

### 1. Page GAME (index.html)
- ✅ Structure de base créée
- ⏳ Ajouter votre vidéo de gameplay de la version commune
- ⏳ Remplacer les placeholders de screenshots par vos vraies captures
- ⏳ Mettre à jour les exemples de code avec votre code réel
- ⏳ Ajouter les liens GitHub (version commune)
- ⏳ Ajouter le lien de téléchargement du build
- ⏳ Lister toutes les ressources web consultées

### 2. Pages Individuelles (addem.html, celena.html, anna.html)
Pour chaque page :
- ⏳ Remplacer "Feature 1/2/3/4" par vos vraies fonctionnalités développées
- ⏳ Ajouter votre vidéo de démonstration
- ⏳ Ajouter vos screenshots (4 recommandés)
- ⏳ Remplacer les exemples de code génériques par vos vrais extraits
- ⏳ Décrire les défis techniques rencontrés et vos solutions
- ⏳ Ajouter votre lien GitHub individuel
- ⏳ Ajouter votre lien de téléchargement

### 3. Médias
**Format recommandé :**
- Vidéos : MP4, WebM (max 50MB pour le web)
- Images : PNG pour screenshots, JPG pour photos
- Résolution : 1920x1080 recommandée

**Intégration vidéo :**
```html
<video controls width="100%" style="border-radius: 10px;">
    <source src="asset/gameplay-video.mp4" type="video/mp4">
    Your browser does not support video.
</video>
```

**Intégration images :**
```html
<img src="asset/screenshot1.png" alt="Description" style="width: 100%; border-radius: 10px;">
```

### 4. Liens à Mettre à Jour
Recherchez tous les `href="#"` et remplacez-les :
- GitHub repositories (version commune + 3 versions individuelles)
- Liens de téléchargement des builds
- Ressources web consultées (tutoriels, documentation, etc.)

## Hébergement

### Option 1 : GitHub Pages (Recommandé) ⭐
1. Créez un repository GitHub public
2. Uploadez tous les fichiers (gardez la structure)
3. Allez dans **Settings** > **Pages**
4. Source : **Deploy from a branch** > **main** > **/ (root)**
5. Cliquez sur **Save**
6. Votre site sera disponible à : `https://username.github.io/repository-name`

### Option 2 : Netlify
1. Créez un compte sur [netlify.com](https://netlify.com)
2. Glissez-déposez votre dossier dans Netlify Drop
3. Votre site est en ligne instantanément !

### Option 3 : Vercel
1. Créez un compte sur [vercel.com](https://vercel.com)
2. Importez votre repository GitHub
3. Deploy automatique à chaque push

## Personnalisation

### Couleurs
Les couleurs principales sont dans [style.css](style.css) :
- **Cyan primaire** : `#4dd0e1`
- **Cyan clair** : `#69e0f0`
- **Fond foncé** : `#0a1e2e`
- **Fond alternatif** : `#0d2538`

Pour changer le thème, remplacez ces valeurs dans le CSS.

### Polices
Actuellement utilise Arial. Pour changer :
```css
body {
    font-family: 'Votre Police', sans-serif;
}
```

## Support Technique

### Structure du Code
- **HTML** : Structure sémantique avec sections clairement définies
- **CSS** : Design responsive avec breakpoints à 992px, 768px, 480px
- **Navigation** : Smooth scroll et états actifs automatiques

### Compatibilité
- ✅ Chrome, Firefox, Safari, Edge (versions récentes)
- ✅ Responsive : Desktop, Tablet, Mobile
- ✅ Pas de JavaScript requis (site statique pur)

## Checklist Avant Publication

- [ ] Toutes les vidéos sont ajoutées
- [ ] Tous les screenshots sont en place
- [ ] Les exemples de code sont à jour
- [ ] Tous les liens GitHub sont fonctionnels
- [ ] Les liens de téléchargement fonctionnent
- [ ] Les ressources web sont listées
- [ ] Le site est testé sur mobile
- [ ] Le site est testé sur différents navigateurs
- [ ] Les noms des membres sont corrects
- [ ] Le copyright est à jour

---

**Projet SAE4.02 - 2026**  
**Spear Fisher - XR Fishing Game**
