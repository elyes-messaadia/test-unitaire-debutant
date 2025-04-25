
# 🧪 Job-03 – Toujours des Calculs et des Tests

---

## 🎯 Objectifs du projet

- Écrire des tests unitaires en **PHP avec PHPUnit**
- Écrire des tests unitaires en **JavaScript avec Jest**
- Tester : addition, soustraction, multiplication, division
- Gérer les erreurs : division par zéro, expression invalide, chaîne vide
- Documenter le projet avec des **captures d’écran**
- Versionner et structurer le projet proprement

---

## 🗂 Fichiers fournis

- `Calculator_PHP.php` : interface PHP fonctionnelle
- `Calculator_JS.html` : interface JS fonctionnelle
- `calculator.php` : classe PHP `Calculator`
- `calculator.js` : fonction JS `calculate()`
- `calculator.css` : feuille de style

---

## 🧪 À tester dans les fichiers de test

### 🔹 PHP (`tests/CalculatorTest.php`)

- ✅ L’addition : `2+3`
- ✅ La soustraction : `10-4`
- ✅ La multiplication : `3*4`
- ✅ La division : `8/2`
- ❌ Division par zéro ➜ doit lever une erreur
- ❌ Expression invalide : `"2+bad"` ➜ doit lever une erreur
- ❌ Chaîne vide : `""` ➜ doit lever une erreur

### 🔹 JS (`tests/calculator.test.js`)

- ✅ `2+3`
- ✅ `10-4`
- ✅ `3*4`
- ✅ `8/2`
- ✅ `2+3*4` ➜ 14 (priorités)
- ✅ `(2+3)*4` ➜ 20 (parenthèses)
- ❌ `"2+bad"` ➜ erreur
- ❌ `""` ➜ erreur

---

## 📸 Captures d’écran à intégrer

| Étape | Description | Nom de l’image |
|-------|-------------|----------------|
| 1 | Structure du projet | `arborescence.png` |
| 2 | Code `calculator.php` | `calculator-php.png` |
| 3 | Code `calculator.js` | `calculator-js.png` |
| 4 | Tests PHP écrits | `test-php.png` |
| 5 | Résultat tests PHP OK | `test-php-success.png` |
| 6 | Tests JS écrits | `test-js.png` |
| 7 | Résultat tests JS OK | `test-js-success.png` |
| 8 | Résultats erreurs volontairement provoquées | `test-failures.png` |

---

## 📝 Bonnes pratiques de versionning

- Dossiers : `src/`, `tests/`, `images/`, `interfaces/`
- Commits clairs :
  - `ajout de la classe Calculator`
  - `écriture des tests PHP`
  - `écriture des tests JS`
  - `ajout des interfaces`
  - `ajout des captures`
  - `finalisation du README`

---

## 📚 Ressources utiles

- [PHPUnit – Documentation](https://phpunit.de/documentation.html)
- [Jest – Guide de démarrage](https://jestjs.io/docs/getting-started)
- [PHP Officiel](https://www.php.net/manual/fr/)
- [Node.js](https://nodejs.org/fr/docs/)
- [eval() JS – MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/eval)
- [Expressions régulières – MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide/Regular_expressions)
- [Formulaires HTML – MDN](https://developer.mozilla.org/fr/docs/Web/HTML/Element/form)
- [DOM / Clavier – MDN](https://developer.mozilla.org/fr/docs/Web/API/KeyboardEvent)
- [querySelector – MDN](https://developer.mozilla.org/fr/docs/Web/API/Document/querySelector)

---