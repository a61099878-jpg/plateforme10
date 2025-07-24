# Guide des Logos pour les Conventions de Stage

## 📂 Où placer vos logos

**Dossier de destination :** `/public/`

Placez vos deux logos dans le dossier public avec ces noms exacts :
- `um5.png` (Logo UM5)
- `ensamrabat.png` (Logo ENSAM Rabat)

## 🔧 Si vous voulez changer les noms des fichiers images

Si vous souhaitez utiliser des noms différents pour vos logos, modifiez ces fichiers :

### 1. Convention d'Initiation
**Fichier :** `src/templates/convention_initiation.html`
**Lignes à modifier :**
```html
<img src="/um5.png" alt="Logo UM5" class="logo">
<img src="/ensamrabat.png" alt="Logo ENSAM Rabat" class="logo">
```

### 2. Convention de Fin d'Année  
**Fichier :** `src/templates/convention_fin_annee.html`
**Lignes à modifier :**
```html
<img src="/um5.png" alt="Logo UM5" class="logo">
<img src="/ensamrabat.png" alt="Logo ENSAM Rabat" class="logo">
```

### 3. Convention de Fin d'Études
**Fichier :** `src/templates/convention_fin_etudes.html`  
**Lignes à modifier :**
```html
<img src="/um5.png" alt="Logo UM5" class="logo">
<img src="/ensamrabat.png" alt="Logo ENSAM Rabat" class="logo">
```

## 🎨 Couleurs par type de stage

### Stage d'Initiation (Vert)
- Couleur principale : `#2e7d32`
- Arrière-plan logos : `linear-gradient(135deg, #e8f5e8, #f1f8e9)`
- Informations étudiant : couleur `#1976d2`

### Stage de Fin d'Année (Bleu) 
- Couleur principale : `#1976d2`
- Arrière-plan logos : `linear-gradient(135deg, #e3f2fd, #f0f7ff)`
- Informations étudiant : couleur `#2e7d32`

### Stage de Fin d'Études (Violet)
- Couleur principale : `#7b1fa2`
- Arrière-plan logos : `linear-gradient(135deg, #f3e5f5, #faf2ff)`  
- Informations étudiant : couleur `#d81b60`

## 📋 Modifications apportées selon vos spécifications

### Article 1 adapté par type :
- **Stage d'Initiation :** "Stage d'Initiation" du 01 Juillet au 31 Août 2025
- **Stage de fin d'année :** "Stage de fin d'année" du 01 Juillet au 31 Août 2025  
- **Stage de fin d'étude :** "Stage de fin d'étude" du 01 janvier au 30 juin 2025

### Structure conforme au PDF :
✅ Logos en haut avec arrière-plan coloré  
✅ Titre "CONVENTION DE STAGE EN ENTREPRISE"  
✅ Articles numérotés 1-8  
✅ Tableau des partenaires (Article 2)  
✅ Signatures à la fin  
✅ Fiche d'évaluation sur page 2  
✅ Critères d'évaluation avec cases à cocher  
✅ Footer avec informations ENSAM

## 💡 Pour tester
1. Placez vos logos dans `/public/um5.png` et `/public/ensamrabat.png`
2. Redémarrez l'application 
3. Générez une convention pour vérifier l'affichage

Le système utilisera automatiquement le bon template selon le type de stage sélectionné !