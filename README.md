# PsychoMotion — Bibliothèque d'Exercices en Psychomotricité

Une application web interactive pour organiser, consulter et partager vos exercices de psychomotricité avec vos patients.

## ✨ Fonctionnalités

- **Bibliothèque complète** — Tous vos exercices organisés par fonction cognitive et type d'activité
- **Recherche instantanée** — Trouvez un exercice par nom, fonction, matériel ou mot-clé
- **Filtres combinés** — Par fonction ciblée (mémoire, attention, coordination…) et type d'activité (jeu, fiche, relaxation…)
- **Fiches détaillées** — Description, déroulement étape par étape, variantes et adaptations
- **QR Code** — Générez un QR code pour chaque exercice et partagez-le avec vos patients
- **Impression** — Imprimez une fiche individuelle ou toute la bibliothèque en fiches formatées
- **Ajout d'exercices** — Créez et enregistrez vos propres exercices facilement
- **Stockage local** — Toutes les données restent dans votre navigateur (localStorage)

## 🚀 Hébergement sur GitHub Pages

### Méthode rapide

1. Créez un nouveau repository sur GitHub (ex: `psychomotion`)
2. Uploadez le fichier `index.html` à la racine du repository
3. Allez dans **Settings** → **Pages**
4. Sous **Source**, sélectionnez la branche `main` et le dossier `/ (root)`
5. Cliquez **Save**
6. Votre site sera accessible à `https://votre-nom.github.io/psychomotion/`

### Méthode Git (terminal)

```bash
git init
git add .
git commit -m "Initial commit - PsychoMotion"
git branch -M main
git remote add origin https://github.com/VOTRE_NOM/psychomotion.git
git push -u origin main
```

Puis activez GitHub Pages dans les Settings du repository.

## 📱 Partage avec les patients

Chaque exercice dispose d'un bouton **QR Code** qui génère un code scannable. Le QR code pointe vers votre site avec l'exercice pré-ouvert. Imprimez le QR code et collez-le sur vos supports !

## 🖨️ Impression

- **Un exercice** : Ouvrez la fiche → cliquez "Imprimer"
- **Tous les exercices** : Cliquez l'icône imprimante dans l'en-tête
- Les fiches imprimées sont formatées professionnellement avec mise en page optimisée

## 📂 Structure

```
psychomotion/
└── index.html    ← Tout est dans ce fichier unique (HTML + CSS + JS)
```

Aucune dépendance externe hormis Google Fonts et la librairie QRCode.js (chargée via CDN).

## 🔒 Confidentialité

Toutes les données sont stockées localement dans votre navigateur. Rien n'est envoyé à un serveur externe.
