
# 🎭 Emoji Code Humeur

## Public ciblé

Étudiants en BTS SIO, NSI, BUT Informatique, ou toute formation en développement applicatif.

*Un brise-glace sympathique pour vos cours de programmation*

👉 **[Voir l'application](https://ggaillard.github.io/emoji-code-mood/)** | � **[Tableau de bord](https://ggaillard.github.io/emoji-code-mood/dashboard.html)** | 📚 **[Formation](docs/formation/)** | ⚙️ **[Installation](docs/setup/)** | 📖 **[Documentation](docs/)**

---

## ✨ Qu'est-ce que c'est ?

**Emoji Code Mood** transforme le traditionnel "Comment ça va ?" en activité interactive. Vos étudiants partagent leur humeur avec une ligne de code et leurs préférences tech dans une interface simple et moderne.

### 🎯 **L'idée**

```python
# Au lieu de ça...
prof: "Comment ça va aujourd'hui ?"
étudiants: "Ça va..." 😶

# Vous obtenez ça ! 
marie = {"mood": "🚀", "lang": "Python", "pref": "Gaming"}
jules = {"mood": "🤔", "lang": "Java", "pref": "Musique"} 
```

**Résultat :** Une classe plus détendue et des informations utiles pour adapter votre cours.

---

## 🎥 Aperçu de l'Interface

### **Pour vos étudiants :**
```
┌─────────────────────────────────────┐
│ 🎭 Emoji Code Mood                 │
│ Exprime ton humeur avec du code !   │
├─────────────────────────────────────┤
│ 🅜 Marie 🐍 🎮          2min       │
│ Python | Gaming                     │  
│ humeur = "🚀" // projet excitant!   │
├─────────────────────────────────────┤
│ 🅹 Jules ☕ 🎵          5min       │
│ Java | Musique                      │
│ String mood = "🤔"; // réflexion    │
└─────────────────────────────────────┘
```

### **Pour vous, enseignant :**
- **Feed temps réel** style Instagram/Twitter
- **Panneau de contrôle** discret (triple-clic)
- **Export des données** CSV/JSON pour analyse
- **Interface responsive** mobile/tablette/desktop

---

## 🚀 Installation Simple

### **Option 1 : Version basique (2 minutes)**
1. Cliquez sur **Fork** 
2. **Settings** → **Pages** → **Source: GitHub Actions**
3. Votre version : `https://votre-nom.github.io/emoji-code-mood`

### **Option 2 : Version collaborative (15 minutes)**
Pour que tous vos étudiants voient les réponses en temps réel :

1. **Créez un compte** [Supabase](https://supabase.com) gratuit
2. **Nouveau projet** + copiez URL et clé API
3. **Dans GitHub :** Settings → Secrets → Ajoutez vos clés Supabase
4. **Push votre code** → Déploiement automatique

**📖 Guide pas à pas :** [Configuration complète](docs/setup/)

---

## 🎓 Formation Pratique (4 heures)

**Public :** Enseignants en programmation, formateurs

### **Programme :**
- **Prise en main** (45min) : Fork, configuration, premier déploiement
- **Interface** (60min) : HTML5, CSS moderne, design responsive  
- **JavaScript** (60min) : ES6+, événements, programmation asynchrone
- **Base de données** (60min) : Supabase, SQL, temps réel
- **Personnalisation** (45min) : Votre version unique

### **Ce que vous repartez avec :**
- Application web fonctionnelle en ligne
- Code source sur votre GitHub
- Compétences techniques modernes
- Outil prêt pour vos cours

**📊 Supports :** [Slides interactifs](https://ggaillard.github.io/emoji-code-mood/docs/formation/Slide-Presentation.html) | [Guides détaillés](docs/formation/)

---

## 💻 Technologies

- **Frontend :** HTML5, CSS3, JavaScript moderne
- **Backend :** Supabase (base de données PostgreSQL cloud)
- **Déploiement :** GitHub Actions + GitHub Pages
- **Temps réel :** WebSocket natif

---

## 🎯 Utilisation

### **Quand l'utiliser :**
- Première semaine de cours (faire connaissance)
- Début de séance (prendre la température)  
- Après les vacances (reprise en douceur)
- Avant un projet important (évaluer la motivation)

### **Ce que ça vous apporte :**
- Ambiance détendue dès les premières minutes
- Informations sur l'état d'esprit de la classe
- Introduction naturelle aux concepts de programmation
- Données pour adapter votre pédagogie

---

## 🛠️ Fonctionnalités

### **Pour vos étudiants :**
- Interface simple et intuitive
- 70+ emojis d'humeur
- 12 langages de programmation
- 32 préférences tech (Gaming, IA, Musique, Sport...)
- Génération automatique de code
- Compatible mobile et ordinateur

### **Pour vous :**
- Vue temps réel de toute la classe
- Panneau de contrôle discret (triple-clic)
- Export des données (CSV/JSON)
- Pas d'installation nécessaire
- Configuration simple

---

## 📁 Structure du Projet

```
emoji-code-mood/
├── index.html              # Tableau de bord (navigation)
├── index.html              # Application temps réel principale (point d'entrée)
├── app.html                # Copie conservée / version alternative (transition)
├── dashboard.html          # Ancien tableau de bord de navigation
├── main.js                 # Logique applicative  
├── styles.css              # Styles de l'application (feed, formulaires...)
├── css/
│   ├── common.css          # Variables, reset, utilitaires partagés
│   └── dashboard.css       # Styles spécifiques au tableau de bord
├── supabaseClient.js       # Client base de données
├── private-config.js       # Configuration (générée automatiquement)
│
├── docs/                   # Documentation
│   ├── setup/             # Guides d'installation
│   ├── formation/         # Formation complète
│   └── concepts/          # Documentation technique
│
├── .github/workflows/     # Automatisation GitHub
└── test.html              # Page de test
```

### 🧩 Organisation CSS
- `styles.css` : styles historiques de l'application principale (interface temps réel)
- `css/common.css` : variables, reset léger, helpers accessibilité & utilitaires
- `css/dashboard.css` : mise en page et composants du tableau de bord (cartes, grille, animations)

Objectif : séparation claire entre la logique visuelle de navigation (dashboard) et l'application interactive.

---

## 🎨 Personnalisation

Vous pouvez adapter l'outil à votre contexte :
- Couleurs aux couleurs de votre école
- Langages de programmation proposés  
- Préférences tech disponibles
- Messages d'accueil personnalisés

```css
/* Exemple de personnalisation */
:root {
  --primary-color: #your-school-color;
  --secondary-color: #your-accent-color;
}
```

---

## 🤝 Contribution

Envie d'améliorer l'outil ? Vous êtes les bienvenus !

1. **Fork** le projet  
2. **Créez** votre branche (`git checkout -b ma-fonctionnalité`)
3. **Commitez** (`git commit -m 'Ajout: ma super fonctionnalité'`)
4. **Poussez** (`git push origin ma-fonctionnalité`)
5. **Ouvrez** une Pull Request

**Besoin d'aide ?** [Issues GitHub](issues) • [Discussions](discussions)

---


## 📄 Licence

Ce projet est sous licence GNU General Public License v3.0
- Utilisation libre pour l'éducation
- Modifications autorisées  
- Code source ouvert


---


**🎭 Emoji Code Mood - Pour des cours plus sympas !**

*Fait avec ❤️ pour les enseignants*






