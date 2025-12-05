# 🕌 Site Web des Horaires de Prière - Version Améliorée HD

Site web moderne affichant les horaires de prière pour Montréal (Canada) et Tunis (Tunisie) avec **animations HD**, **notifications intelligentes** et **lecture automatique de l'adhan**.

## ✨ NOUVELLES FONCTIONNALITÉS

### 🔔 Système de Notifications Intelligent
- **Notifications du navigateur** : Recevez des alertes à l'heure exacte de chaque prière
- **Adhan automatique** : L'appel à la prière (adhan1.mp3) se joue automatiquement
- **Contrôle individuel** : Activez/désactivez les notifications pour chaque prière séparément
- **Contrôle du volume** : Ajustez le volume de l'adhan selon vos préférences
- **Notifications visuelles** : Alertes élégantes qui apparaissent sur la page
- **Sauvegarde automatique** : Vos préférences sont mémorisées

### 🎨 Animations HD Améliorées
- **Dégradés animés** : Fond d'écran avec gradient dynamique fluide
- **Particules flottantes** : Effets visuels subtils et élégants
- **Transitions douces** : Animations professionnelles sur tous les éléments
- **Effets de brillance** : Animations de lumière sur la prière actuelle
- **Pulse dynamique** : Effets de pulsation sur les prières en cours
- **Hover effects** : Interactions visuelles au survol de la souris

### 📱 Design Responsive HD
- Interface optimisée pour tous les appareils
- Animations fluides même sur mobile
- Graphiques haute définition
- Transitions optimisées pour les performances

## 📋 Fonctionnalités Complètes

- ✅ Affichage des 5 prières quotidiennes (Fajr, Dhuhr, Asr, Maghrib, Isha)
- ✅ Mise à jour automatique toutes les minutes
- ✅ Mise en évidence de la prière actuelle
- ✅ Affichage du temps restant avant la prochaine prière
- ✅ Support de 25+ villes dans le monde
- ✅ Interface bilingue (Français/العربية)
- ✅ Compte à rebours pour Ramadan
- ✅ Lecteur du Coran (Hafs)
- ✅ Tasbih électronique
- ✅ Direction de la Qibla
- ✅ **NOUVEAU** : Notifications de prière avec adhan
- ✅ Design moderne et responsive
- ✅ Gratuit et hébergé sur GitHub Pages

## 🚀 Comment déployer sur GitHub Pages (GRATUIT)

### Étape 1: Créer un compte GitHub
1. Allez sur [github.com](https://github.com)
2. Cliquez sur "Sign up" et créez un compte gratuit

### Étape 2: Créer un nouveau dépôt (repository)
1. Connectez-vous à votre compte GitHub
2. Cliquez sur le bouton "+" en haut à droite
3. Sélectionnez "New repository"
4. Nommez votre dépôt (par exemple: `horaires-priere`)
5. Cochez "Public"
6. Cliquez sur "Create repository"

### Étape 3: Ajouter les fichiers
1. Sur la page de votre nouveau dépôt, cliquez sur "uploading an existing file"
2. Glissez-déposez ou sélectionnez TOUS ces fichiers:
   - `index.html`
   - `style.css`
   - `script.js`
   - `adhan1.mp3` (fichier audio de l'adhan)
   - `ramadan.mp4` (vidéo Ramadan)
   - `ramadan.gif` (GIF Ramadan)
   - `fajr-bg.jpg` (image de fond Fajr)
   - `dhuhr-bg.jpg` (image de fond Dhuhr)
   - `asr-bg.jpg` (image de fond Asr)
   - `maghrib-bg.jpg` (image de fond Maghrib)
   - `isha-bg.jpg` (image de fond Isha)
3. Cliquez sur "Commit changes"

### Étape 4: Activer GitHub Pages
1. Dans votre dépôt, cliquez sur "Settings" (en haut)
2. Dans le menu de gauche, cliquez sur "Pages"
3. Sous "Source", sélectionnez "main" branch
4. Cliquez sur "Save"
5. Attendez 1-2 minutes

### Étape 5: Accéder à votre site
Votre site sera accessible à l'adresse:
```
https://votre-nom-utilisateur.github.io/horaires-priere/
```

(Remplacez `votre-nom-utilisateur` par votre nom d'utilisateur GitHub et `horaires-priere` par le nom de votre dépôt)

## 🔔 Comment Utiliser les Notifications

### Configuration des Notifications

1. **Ouvrir le panneau de notifications**
   - Cliquez sur le bouton "🔔 Notifications" dans le header

2. **Autoriser les notifications du navigateur**
   - Cliquez sur le bouton vert "Autoriser les notifications du navigateur"
   - Acceptez la demande de permission dans votre navigateur

3. **Activer les prières souhaitées**
   - Utilisez les toggles pour activer/désactiver chaque prière individuellement
   - Les toggles verts indiquent que la notification est active

4. **Ajuster le volume de l'adhan**
   - Utilisez le curseur pour régler le volume (0-100%)
   - Le volume est sauvegardé automatiquement

5. **Tester le système**
   - Cliquez sur "🔊 Tester l'Adhan" pour vérifier que tout fonctionne

### Fonctionnement Automatique

Une fois configuré, le système :
- ✅ Vérifie l'heure toutes les 30 secondes
- ✅ Envoie une notification 1 minute avant l'heure de prière
- ✅ Joue l'adhan automatiquement
- ✅ Affiche une notification visuelle sur la page
- ✅ Ne notifie qu'une seule fois par prière par jour

### Notes Importantes

⚠️ **Permissions requises** : 
- Autorisez les notifications dans votre navigateur
- Sur mobile, vérifiez aussi les paramètres de votre téléphone

🔊 **Audio** :
- L'adhan se joue uniquement si les notifications sont actives
- Le volume est ajustable individuellement
- Compatible avec tous les navigateurs modernes

💾 **Sauvegarde** :
- Vos paramètres sont sauvegardés localement
- Ils persistent même après fermeture du navigateur
- Pas besoin de reconfigurer à chaque visite

## 🎨 Personnalisation

### Changer les villes
Le site supporte 25+ villes par défaut. Les villes sont définies dans `script.js` :

```javascript
const citiesDatabase = {
    'montreal-ca': { ... },
    'tunis-tn': { ... },
    // Ajoutez vos villes ici
};
```

### Remplacer l'adhan
Pour utiliser votre propre fichier adhan :
1. Renommez votre fichier audio en `adhan1.mp3`
2. Remplacez le fichier existant
3. Format supporté : MP3

### Changer les images de fond
Remplacez les fichiers suivants par vos propres images :
- `fajr-bg.jpg` - Fond pour Fajr (aube)
- `dhuhr-bg.jpg` - Fond pour Dhuhr (midi)
- `asr-bg.jpg` - Fond pour Asr (après-midi)
- `maghrib-bg.jpg` - Fond pour Maghrib (coucher du soleil)
- `isha-bg.jpg` - Fond pour Isha (nuit)

### Modifier les couleurs et animations
Les styles sont dans `style.css`. Vous pouvez personnaliser :

```css
/* Gradient de fond principal */
body {
    background: linear-gradient(135deg, #1e3c72 0%, #2a5298 35%, #764ba2 65%, #667eea 100%);
}

/* Couleurs des notifications */
.notification-enable-btn {
    background: linear-gradient(135deg, #22c55e 0%, #16a34a 100%);
}
```

## 🔧 Méthodes de calcul disponibles

- `0` - Shia Ithna-Ashari
- `1` - University of Islamic Sciences, Karachi
- `2` - Islamic Society of North America (ISNA)
- `3` - Muslim World League (MWL)
- `4` - Umm al-Qura, Makkah
- `5` - Egyptian General Authority of Survey
- `7` - Institute of Geophysics, University of Tehran

## 🔄 Mise à jour automatique

Le site se met à jour automatiquement:
- ✅ Toutes les minutes: mise à jour des horaires
- ✅ Toutes les 30 secondes: vérification des notifications
- ✅ Toutes les 10 secondes: mise à jour de la prière actuelle

## 📱 Responsive Design

Le site s'adapte automatiquement à tous les appareils:
- 💻 Ordinateurs (1920x1080 et plus)
- 📱 Téléphones (iPhone, Android)
- 📱 Tablettes (iPad, etc.)
- 🖥️ Écrans ultra-larges (4K)

## 🌐 API utilisée

Ce site utilise l'API gratuite [Aladhan](https://aladhan.com/prayer-times-api) pour obtenir les horaires de prière.

## 🎯 Technologies Utilisées

- **HTML5** : Structure sémantique moderne
- **CSS3** : Animations et transitions avancées
- **JavaScript ES6+** : Logique et interactions
- **Notifications API** : Notifications du navigateur
- **LocalStorage API** : Sauvegarde des préférences
- **Audio API** : Lecture de l'adhan

## 🔒 Sécurité et Confidentialité

- ✅ Aucune donnée n'est envoyée à des serveurs tiers
- ✅ Toutes les préférences sont stockées localement
- ✅ Pas de cookies ou trackers
- ✅ Code source ouvert et transparent
- ✅ Connexion sécurisée (HTTPS sur GitHub Pages)

## 📄 Licence

Libre d'utilisation et de modification pour des fins personnelles et communautaires.

## 💡 Support et Contribution

Pour toute question ou suggestion:
1. Créer une "Issue" sur GitHub
2. Consulter la documentation de l'API Aladhan
3. Modifier le code selon vos besoins

## 🆕 Journal des Modifications

### Version 2.0 (Nouvelle)
- ✨ Ajout du système de notifications avec adhan
- 🎨 Animations HD améliorées
- 🌈 Nouveaux effets visuels (particules, gradients animés)
- 📱 Amélioration du responsive design
- 🔊 Contrôle du volume de l'adhan
- 💾 Sauvegarde automatique des préférences
- 🎯 Notifications visuelles élégantes

### Version 1.0 (Originale)
- 📍 Support de 25+ villes
- 🌍 Interface bilingue
- 📖 Lecteur du Coran
- 📿 Tasbih électronique
- 🧭 Direction Qibla

---

**Note:** Assurez-vous d'avoir une connexion internet pour que le site fonctionne, car il récupère les horaires en temps réel depuis l'API. Les notifications fonctionnent même hors ligne une fois les horaires chargés.

## 🎉 Remerciements

Merci d'utiliser ce site pour rester connecté avec vos prières quotidiennes. Qu'Allah accepte nos prières et nos efforts. Ameen.

---

**Développé avec ❤️ pour la communauté musulmane**

بارك الله فيكم (Qu'Allah vous bénisse)
