# 30 jours de recettes

Application Android (Kotlin + Jetpack Compose) du TP « 30 jours » : une fiche par jour, soit 30 recettes, affichées dans une `LazyColumn`.

## Contenu
- Chaque fiche contient le numéro du jour, le titre de la recette, une image et la description (visible en touchant la fiche).
- Animations : `animateContentSize` (déploiement de la fiche) et `animateColorAsState` (changement de couleur).
- Material Design 3 : palette terracotta/crème en thème clair et sombre, police Poppins (licence OFL), formes arrondies.

## Ouvrir le projet
1. Ouvrir Android Studio, puis `File > Open` et choisir le dossier `TrenteJours`.
2. Attendre la synchronisation Gradle (connexion internet nécessaire la première fois).
3. Lancer l'application sur un émulateur ou un téléphone (`Run > Run 'app'`).

## Structure
- `app/src/main/java/com/example/trentejours/MainActivity.kt` : interface (Scaffold, LazyColumn, fiches)
- `app/src/main/java/com/example/trentejours/model/Tip.kt` : les 30 recettes
- `app/src/main/java/com/example/trentejours/ui/theme/Theme.kt` : couleurs, typographie, formes
- `app/src/main/res/values/strings.xml` : titres et descriptions
- `app/src/main/res/drawable/` : images des recettes (images générées pour ce projet, remplaçables par des photos personnelles en gardant les mêmes noms)
- `app/src/main/res/font/` : Poppins Regular et Bold
