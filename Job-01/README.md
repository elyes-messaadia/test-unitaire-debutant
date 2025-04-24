
# 🧪 Job-01 – Premiers Tests Unitaires avec Jest

Bienvenue dans ce projet d’initiation aux **tests unitaires avec Jest** en JavaScript.  
Tu vas apprendre à écrire une fonction, la tester avec Jest, corriger les erreurs, et documenter tout ça comme un pro.

---

## 🎯 Objectifs

- Créer une fonction simple en JavaScript
- Écrire un test unitaire avec Jest
- Corriger une erreur de test
- Documenter chaque étape avec des captures d’écran
- Versionner le projet proprement sur GitHub

---

## 🚀 Étapes du projet

### 1. Initialiser le projet Node.js

```bash
npm init -y
```

📸 ![Initialisation npm](./images/init-npm.png)

---

### 2. Installer Jest

```bash
npm install --save-dev jest
```

📸 ![Installation de Jest](./images/install-jest.png)

---

### 3. Configurer Jest dans package.json

Ajoute ce script dans la section `"scripts"` :

```json
"scripts": {
  "test": "jest"
}
```

📸 ![Configuration de Jest](./images/config-jest.png)

---

### 4. Créer la fonction `addition`

**Fichier : `math.js`**

```js
function addition(a, b) {
  return a + b;
}
module.exports = addition;
```

📸 ![Code de la fonction addition](./images/math-js.png)

---

### 5. Écrire un test unitaire

**Fichier : `math.test.js`**

```js
const addition = require('./math');

test('addition de 2 + 3 doit retourner 5', () => {
  expect(addition(2, 3)).toBe(5);
});
```

📸 ![Code du test Jest](./images/test-code.png)

---

### 6. Lancer le test avec succès ✅

```bash
npm test
```

📸 ![Test réussi](./images/test-passed.png)

---

### 7. Provoquer une erreur volontairement ❌

Modifie temporairement `addition` pour retourner `a - b`, puis relance le test.

📸 ![Test échoué](./images/test-fail.png)

---

### 8. Corriger l’erreur et revérifier ✅

Remets `a + b`, puis relance `npm test`.

📸 ![Test corrigé et réussi](./images/test-fixed.png)

---

### 9. Vue d’ensemble du projet

📸 ![Arborescence du projet](./images/arborescence.png)

---

## 💬 Bonnes pratiques Git utilisées

- ✅ Commits fréquents et clairs :
  - `initialisation du projet`
  - `ajout de la fonction addition`
  - `création du test`
  - `erreur provoquée`
  - `correction et test validé`
  - `ajout des images et finalisation du README`

---

## 📚 Ressources utiles

- [Documentation Jest](https://jestjs.io/docs/getting-started)
- [Node.js](https://nodejs.org/)
- [MDN – JavaScript](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [Guide Markdown](https://www.markdownguide.org/basic-syntax/)

---

