# 🧮 Calculatrice React - Interactive & Précise

Une calculatrice moderne et fonctionnelle développée avec React.js, offrant des fonctionnalités avancées comme les opérations de base, les pourcentages et les fonctions trigonométriques en radians.

🔗 [Accéder au site](https://kevgenga.github.io/test-calculatrice-react/)  

## 🚀 Technologies utilisées

- **React.js** : Bibliothèque JavaScript pour la création d'interfaces dynamiques.  
- **Styled-components** : Pour un stylisme personnalisé et réactif.  
- **Math.js** : Bibliothèque permettant d'effectuer des calculs avancés en JavaScript.  

## 📋 Description

Cette calculatrice offre une interface intuitive avec :  

✅ **Les opérations mathématiques classiques** (+, -, ×, ÷)  
✅ **Le calcul des pourcentages** (ex: `10% de 1700` renvoie `170`)  
✅ **Les augmentations et réductions en pourcentage** (ex: `200 +% 10` donne `220`)  
✅ **Les fonctions trigonométriques** (sin, cos, tan) avec conversion en radians  
✅ **Une interface fluide et esthétique**, optimisée avec Styled-components  

## 📝 Formules de calcul

### 📏 Opérations mathématiques classiques
✅ **Addition** : `a + b`  
✅ **Soustraction** : `a - b`  
✅ **Multiplication** : `a × b`  
✅ **Division** : `a ÷ b`  

### 🎯 Calcul des pourcentages
✅ **Obtenir X% d’un nombre**  
> **Exemple** : `10% 100 = 10`  
> **Formule** : `(X ÷ 100) × Y`  
> **Explication** : `10 ÷ 100 × 100 = 10`  

✅ **Augmentation d’un nombre de X%**  
> **Exemple** : `200 +% 10 = 220`  
> **Formule** : `Y × (1 + X ÷ 100)`  
> **Explication** : `200 × (1 + 10 ÷ 100) = 220`  

✅ **Réduction d’un nombre de X%**  
> **Exemple** : `200 -% 10 = 180`  
> **Formule** : `Y × (1 - X ÷ 100)`  
> **Explication** : `200 × (1 - 10 ÷ 100) = 180`  

### 📐 Fonctions trigonométriques en radians
✅ **sin(X)** ➝ `Math.sin(X)`  
✅ **cos(X)** ➝ `Math.cos(X)`  
✅ **tan(X)** ➝ `Math.tan(X)`  

📌 **Conversion degrés → radians** : `X degrés × π / 180`  
> **Exemple** : `sin(30°) = sin(30 × π / 180) ≈ 0.5`  

### 📌 Autres fonctionnalités avancées
✅ **Carré d’un nombre** : `X² = X × X`  
✅ **Racine carrée** : `√X = Math.sqrt(X)`  
✅ **Inverse d’un nombre** : `1 ÷ X`  
✅ **Factorielle** : `X! = X × (X-1) × (X-2) ... × 1`  
✅ **Puissance** : `X^Y = Math.pow(X, Y)`  
