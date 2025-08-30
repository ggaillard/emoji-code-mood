# 🎭 Emoji Code Humeur

*Un brise-glace moderne pour vos cours de programmation*

👉 **Accéder à l'application :** [https://ggaillard.github.io/emoji-code-mood/](https://ggaillard.github.io/emoji-code-mood/)
[![Licence](https://img.shields.io/badge/Licence-GNU_GPL_v3-blue)](LICENSE)

---

## ✨ L'idée

Transformez votre ritual de début de cours ! Au lieu du classique "Comment ça va ?", vos étudiants partagent leur humeur avec une ligne de code personnalisée et leurs préférences tech.

Interface moderne style **réseaux sociaux** qui s'adapte automatiquement selon le nombre de participants.

## 🌟 Comment ça marche

1. **L'étudiant** choisit un emoji qui représente son humeur
2. **Il sélectionne** son langage de programmation préféré  
3. **Il choisit** sa préférence tech (gaming, musique, IA, sport...)
4. **Il peut ajouter** un commentaire personnel
5. **Tout apparaît** instantanément pour toute la classe dans un feed social

**Résultat :** Une ambiance détendue et une classe connectée ! 🚀

## 📱 Interface 

```
┌─────────────────────────────────┐
│ 🅜 Marie 🐍 🚀            2min  │
│ Python | Jeux vidéo             │  
│ humeur = "🚀" // projet    📋   │
└─────────────────────────────────┘
```


```python  
humeur = "🚀" # prêt à décoller cette année !
```

```java
String mood = "🤔"; // en mode réflexion intense
```

## 🎯 Idéal pour

- **Première semaine** de cours (faire connaissance)
- **Début de séance** (prendre la température)
- **Après les vacances** (transition en douceur) 
- **Avant un gros projet** (voir le niveau de motivation)

Aucune installation nécessaire, ça fonctionne directement dans votre navigateur.

## 💻 Créer votre propre version

### Option simple (5 minutes)
1. Cliquez sur le bouton **Fork** en haut de cette page
2. Dans votre nouveau repository : **Settings** → **Pages** → **Source: Branch main**
3. Votre version sera disponible à `https://votre-nom.github.io/emoji-code-mood`

### Option collaborative (temps réel)
Pour que tous vos étudiants voient les réponses en temps réel :

#### 🚀 **Déploiement automatique avec GitHub Actions (Recommandé)**
1. **Forkez** ce repository
2. **Configurez vos secrets GitHub** :
   - Allez dans `Settings` → `Secrets and variables` → `Actions`
   - Ajoutez `SUPABASE_URL` avec votre URL Supabase
   - Ajoutez `SUPABASE_ANON_KEY` avec votre clé anonyme
3. **Poussez votre code** - Le déploiement se fait automatiquement !
4. **Votre app est déployée** sur GitHub Pages avec Supabase configuré

#### 📖 **Guide détaillé** : 
- [Configuration GitHub Actions](docs/github-actions-setup.md) - Déploiement automatique
- [Configuration Supabase](docs/supabase-setup.md) - Base de données

> ⚡ **Configuration automatique et sécurisée** :
> Les paramètres Supabase sont injectés automatiquement via GitHub Actions. 
> Aucune configuration manuelle n'est nécessaire côté client.

## 🎨 Personnaliser

Vous pouvez facilement adapter l'outil à votre contexte :
- Modifier les couleurs aux couleurs de votre école
- Ajouter votre logo
- Personnaliser les suggestions de commentaires
- Ajuster les langages proposés

## 📊 Ce que ça vous apporte

- **Ambiance détendue** dès les premières minutes
- **Connexion** immédiate avec vos étudiants
- **Données utiles** pour adapter votre pédagogie
- **Introduction naturelle** aux concepts de programmation

## 🛠️ Fonctionnalités
=======
## 🎯 Fonctionnalités Clés
>>>>>>> 57e3340f1ac7654842fa49c482a8fa317a6ae8dc

### Pour vos étudiants
- **Interface sociale moderne** avec avatars colorés
- **70+ emojis** organisés par catégories (énergie, fatigue, cool...)
- **12 langages** de programmation supportés
- **32 préférences tech** (Gaming, IA, Musique, Sport, Netflix...)
- **Auto-actualisation** invisible en arrière-plan
- **Copie de code** en un clic
- **Compatible** mobile/tablette/ordinateur

### Pour vous, enseignant
- **Feed temps réel** style Instagram/Twitter
- **Affichage adaptatif** selon le nombre de participants
- **Badges langages** avec icônes (⚡ JS, 🐍 Python, ☕ Java...)
- **Panneau de contrôle caché** (Ctrl+Shift+A)
- **Export CSV/JSON** pour analyse
- **Aucune installation** requise

### Préférences Disponibles
- 🎮 **Gaming & Fun** : Jeux vidéo, Streaming, YouTube, Twitch
- 🎨 **Design** : Graphisme, Photoshop, Montage vidéo, UI/UX  
- 🎵 **Musique** : Écoute, Spotify, Production, Podcasts
- 🤖 **Tech & IA** : Intelligence Artificielle, ChatGPT, Robotique
- 📱 **Mobile** : Apps mobiles, TikTok, Instagram, Snapchat
- 🏃 **Sport** : Fitness, Course, Vélo, Activités physiques
- 🎬 **Divertissement** : Netflix, Séries, Cinéma, Disney+
- 📚 **Apprentissage** : Lecture, Cours en ligne, Langues
- 🍔 **Lifestyle** : Cuisine, Voyage, Shopping, Nature

## 🚀 Installation Rapide

### Option 1: Fork Simple (2 minutes)
1. **Fork** ce repository
2. **Settings** → **Pages** → **Source: GitHub Actions**
3. Votre version : `https://votre-nom.github.io/emoji-code-mood`

### Option 2: Mode Collaboratif Temps Réel
Pour la synchronisation entre tous vos étudiants :

1. **Créez un compte** [Supabase](https://supabase.com) (gratuit)
2. **Nouveau projet** + récupérez URL et clé API
3. **Repository Settings** → **Secrets** → Ajoutez :
   - `SUPABASE_URL` : `https://xxx.supabase.co`
   - `SUPABASE_ANON_KEY` : `eyJhbGciO...`
4. **Workflow automatique** injecte les clés de façon sécurisée
5. **Guide complet** : [docs/supabase-setup.md](docs/supabase-setup.md)

## 🎓 Panneau Enseignant

**Accès secret :** `Ctrl + Shift + A`

- 🗑️ **Effacer tout** - Reset rapide entre les classes
- 📄 **Export CSV** - Analyse des données avec Excel
- 💾 **Export JSON** - Données complètes avec métadonnées
- 📊 **Stats temps réel** - Nombre de participants, tendances

*Panneau totalement caché des étudiants pour éviter les distractions.*

## 💡 Idées d'utilisation

- **🎒 Rentrée scolaire** : Apprendre à connaître sa nouvelle classe
- **☕ Lundi matin** : Prendre la température après le weekend  
- **📝 Avant un contrôle** : Gérer le stress et motiver
- **🚀 Nouveau projet** : Mesurer l'enthousiasme de l'équipe
- **🎯 Formation d'équipes** : Regrouper par affinités tech
- **📈 Suivi pédagogique** : Identifier les tendances d'humeur

## 🛠️ Technologies

- **Frontend** : HTML5, CSS3, JavaScript ES6+
- **Temps réel** : Supabase (PostgreSQL + WebSockets)
- **Déploiement** : GitHub Actions + Pages
- **Sécurité** : Secrets GitHub, Row Level Security
- **Design** : CSS Grid, Flexbox, animations CSS

## 📊 Exemples de Code Générés

```javascript
let humeur = "🚀"; // prêt pour les projets
```

```python  
humeur = "☕"  # besoin de caféine pour démarrer
```

```java
String humeur = "🤯"; // cerveau en surchauffe
```

```rust
let humeur = "😎"; // maître de l'univers aujourd'hui
```

## 🔒 Sécurité & Confidentialité

- **Clés API** injectées automatiquement via GitHub Secrets
- **Jamais de données** sensibles dans le code source
- **Base de données** avec Row Level Security
- **HTTPS** obligatoire pour toutes les connexions
- **Données** automatiquement supprimées après 30 jours

## 📈 Analytics Intégrées

L'export JSON inclut :
- **Distribution des emojis** avec pourcentages
- **Langages populaires** par classe
- **Préférences tech** tendances
- **Évolution temporelle** de l'humeur
- **Métadonnées** de session complètes

## 🤝 Contribution

Des idées d'amélioration ? Un nouveau langage à ajouter ? Un emoji manquant ?

- 🐛 **[Signaler un bug](../../issues)**
- 💡 **[Proposer une fonctionnalité](../../issues)**  
- 🔧 **[Contribuer au code](CONTRIBUTING.md)**
- 🌍 **[Aider à traduire](docs/translation.md)**



