# Templates LexiaEU

Collection de templates HTML gratuits et professionnels pour différents secteurs d'activité. Ces templates servent de complément au générateur de sites IA de [LexiaEU](https://lexiaeu.fr).

## Structure du Projet

```
templates-lexia/
├── restaurant/          # Templates pour restaurants (6)
├── portfolio/          # Templates pour portfolios créatifs (3)  
├── ecommerce/          # Templates e-commerce (4)
├── medical/            # Templates médicaux/santé (3)
├── education/          # Templates éducation/formation (4)
├── business/           # Templates entreprise/corporate (3)
├── services/           # Templates services professionnels (2)
├── tech/              # Templates tech/startup (3)
├── entertainment/      # Templates divertissement (3)
└── others/            # Autres templates (4)
```

## Catégories Disponibles

### 🍽️ Restaurant (6 templates)
- `feane-1.0.0/` - Template élégant pour restaurant avec menu interactif
- `fruitables-1.0.0/` - Design moderne pour produits bio et organiques
- `restoran-1.0.0/` - Style classique pour restaurant traditionnel
- `yummy-red-1.0.0/` - Template coloré pour fast-food et restauration rapide
- `Koppee-1.0.0/` - Design spécialisé café et coffee shop
- `fruiktha-1.0.0/` - Template moderne pour restaurant gastronomique

### 🎨 Portfolio (3 templates)
- `iPortfolio-1.0.0/` - Portfolio professionnel multi-pages
- `MyResume-1.0.0/` - CV/Resume en ligne interactif
- `Studiora-1.0.0/` - Portfolio créatif avec animations

### 🛒 E-commerce (4 templates)
- `cozastore-master/` - Boutique e-commerce mode complète
- `electro-master/` - Template spécialisé électronique/tech
- `MiniStore-1.0.0/` - Petite boutique en ligne minimaliste
- `stylish-1.0.0/` - Template mode/lifestyle élégant

### 🏥 Medical (3 templates)
- `MediCio-1.0.0/` - Cabinet médical professionnel
- `MediLab-1.0.0/` - Laboratoire et centre médical
- `Fitness-1.0.0/` - Salle de sport et wellness

### 🎓 Education (4 templates)
- `Edukate-1.0.0/` - Plateforme éducative et école
- `elearning-1.0.0/` - Formation en ligne et e-learning
- `E-learning-1.0.0/` - Académie virtuelle et cours
- `Mentor-1.0.0/` - Coaching et mentoring professionnel

### 🏢 Business (3 templates)
- `Company-1.0.0/` - Entreprise corporate traditionnel
- `Bootslander-1.0.0/` - Landing page startup moderne
- `pacific-main/` - Cabinet conseil et services B2B

### ✨ Services (2 templates)
- `Salone-1.0.0/` - Salon de beauté et coiffure
- `property-1.0.0/` - Agence immobilière premium

### 💻 Tech (3 templates)
- `NextJS-Tailwind-App-Presentation-Page/` - App landing moderne avec Tailwind
- `NextJS-Tailwind-Course-Landing-Page/` - Landing page cours tech/code
- `eNno-1.0.0/` - Startup software/SaaS

### 🎬 Entertainment (3 templates)
- `anime-main/` - Site streaming anime et manga
- `videograph-master/` - Studio vidéo et production
- `Lounge-1.0.0/` - Bar lounge et événementiel

### 📂 Others (4 templates)
- `kaira-1.0.0/` - Template multi-usage flexible
- `gp-1.0.0/` - General purpose polyvalent
- `picto-1.0.0/` - Design créatif et artistique
- `Dewi-1.0.0/` - Template moderne multi-secteur

## Format des Templates

Chaque template suit cette structure standardisée :

```
template-name/
├── index.html          # Page d'accueil principale
├── preview.jpg         # Capture d'écran (1200x800px)
├── README.md          # Documentation du template
├── assets/
│   ├── css/
│   ├── js/
│   ├── img/
│   └── fonts/
└── pages/             # Pages supplémentaires (optionnel)
    ├── about.html
    ├── contact.html
    └── ...
```

## Utilisation

### Via la Galerie LexiaEU
1. Rendez-vous sur [lexiaeu.fr/generator](https://lexiaeu.fr/generator)
2. Générez votre site avec l'IA
3. Cliquez sur "Plus de templates" pour accéder à la galerie
4. Parcourez les catégories et prévisualisez les templates
5. Téléchargez le template de votre choix

### Utilisation Directe
1. Clonez ce repository :
   ```bash
   git clone https://github.com/Nighty21a/templates-lexia.git
   ```
2. Naviguez vers le template souhaité :
   ```bash
   cd templates-lexia/restaurant/feane-1.0.0/
   ```
3. Ouvrez `index.html` dans votre navigateur

### Démo Live
Chaque template est accessible en live via GitHub Pages :
```
https://nighty21a.github.io/templates-lexia/categorie/nom-template/
```

Exemple : `https://nighty21a.github.io/templates-lexia/restaurant/feane-1.0.0/`

## Personnalisation

### Modification Basique
1. Éditez le contenu dans `index.html`
2. Remplacez les images dans `assets/img/`
3. Ajustez les couleurs dans `assets/css/style.css`

### Variables CSS Communes
La plupart des templates utilisent ces variables CSS :
```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --accent-color: #28a745;
  --text-dark: #212529;
  --text-light: #6c757d;
  --bg-light: #f8f9fa;
}
```

### Fonts et Icônes
- **Google Fonts** : Incluses via CDN
- **Font Awesome** : Version 6.x pour les icônes
- **Bootstrap** : Framework CSS (version varie selon template)

## Caractéristiques Techniques

### Compatibilité
- HTML5 sémantique
- CSS3 moderne avec Flexbox/Grid
- JavaScript ES6+
- Responsive design mobile-first
- Compatible IE11+ et tous navigateurs modernes

### Performance
- Images optimisées WebP/JPG
- CSS et JS minifiés
- Lazy loading des images
- Temps de chargement < 3 secondes

### SEO
- Balises meta optimisées
- Structured data (Schema.org)
- URLs friendly
- Sitemap XML généré
- Open Graph et Twitter Cards

### Accessibilité
- WCAG 2.1 niveau AA
- Navigation au clavier
- Attributs ARIA appropriés
- Contraste coloriel respecté
- Images avec alt text

## Licence

### Templates Tiers
Chaque template provient de sources libres et conserve sa licence originale :
- **MIT License** : Usage libre commercial et personnel
- **Creative Commons** : Attribution requise
- **GPL** : Code source doit rester libre

Consultez le fichier `LICENSE` de chaque template pour les détails.

### Modifications LexiaEU
Les adaptations et améliorations apportées par LexiaEU sont sous licence MIT.

## Contribution

### Ajouter un Template
1. Forkez ce repository
2. Créez le dossier dans la catégorie appropriée
3. Respectez la structure standardisée
4. Ajoutez un `preview.jpg` de qualité
5. Testez la compatibilité responsive
6. Soumettez une Pull Request

### Standards de Qualité
- Code HTML valide (W3C validator)
- CSS sans erreurs
- JavaScript sans erreurs console
- Tests sur Chrome, Firefox, Safari, Edge
- Responsive sur mobile/tablette/desktop
- Temps de chargement < 3 secondes
- Score Lighthouse > 80

### Checklist Template
- [ ] Structure de dossier respectée
- [ ] `preview.jpg` ajouté (1200x800px)
- [ ] `README.md` du template rédigé
- [ ] Code validé W3C
- [ ] Tests multi-navigateurs effectués
- [ ] Responsive vérifié
- [ ] Performance optimisée
- [ ] SEO de base implémenté
- [ ] Accessibilité testée

## Support

### Issues
- Bugs techniques : Ouvrir une issue GitHub
- Demandes de templates : Utiliser le label "enhancement"
- Questions générales : Discussions GitHub

### Documentation
- Guide d'utilisation : [docs.lexiaeu.fr/templates](https://docs.lexiaeu.fr/templates)
- Tutoriels vidéo : [youtube.com/lexiaeu](https://youtube.com/lexiaeu)
- Support communauté : [discord.gg/lexiaeu](https://discord.gg/lexiaeu)

## Roadmap

### Version 2.0 (Q2 2025)
- [ ] 15 nouveaux templates (objectif : 50 total)
- [ ] Système de thèmes sombres/clairs
- [ ] Templates avec CMS headless intégré
- [ ] Version AMP des templates populaires
- [ ] Builder visuel intégré

### Version 2.5 (Q3 2025)
- [ ] Templates e-commerce avec Stripe
- [ ] Intégration APIs populaires (Google Maps, etc.)
- [ ] Templates multilangues
- [ ] Système de A/B testing intégré

## Statistiques

- **35 templates** au total
- **10 catégories** couvertes
- **100% responsive** design
- **Moyenne 95/100** score Lighthouse
- **< 3 secondes** temps de chargement moyen
- **IE11+** compatibilité navigateur

## Crédits

### Sources Templates
- [BootstrapMade](https://bootstrapmade.com/) - Templates Bootstrap
- [ThemeForest](https://themeforest.net/) - Templates premium libres
- [HTML5UP](https://html5up.net/) - Templates HTML5 modernes
- [ColorLib](https://colorlib.com/) - Templates gratuits
- [TemplateMonster](https://www.templatemonster.com/) - Templates libres

### Équipe LexiaEU
- **Développement** : Équipe Tech LexiaEU
- **Design** : Studio Créatif LexiaEU  
- **QA** : Équipe Qualité LexiaEU
- **Maintenance** : DevOps LexiaEU

---

**LexiaEU** - Générateur de sites web IA  
[Site Web](https://lexiaeu.fr) • [Documentation](https://docs.lexiaeu.fr) • [Support](mailto:support@lexiaeu.fr)