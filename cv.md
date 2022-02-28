# Pavel Mochalov

### Junior Frontend Developer

---

### Contacts:

**e-mail:** 010mochalovpa@gmail.com<br> **Phone:** +79278828280<br> **Telegram:** @mochalovpa<br>

---

### About:

In recent years, I have worked in a different specialty. There is no experience in this field.<br> Beginner frontend developer.<br> In 2022, I plan to change the field of activity and engage in front-end development.<br> I am fluent in HTML, CSS, JS. I quickly learn new things. Feel free to use the documentation and reference information.<br> I continue to learn, get acquainted with different tools, as well as use and learn new ones.<br>

---

### Skills and Proficiency:

- HTML (semantic elements, forms, code validity)
- CSS (adaptive layout, entry level preprocessors, flexbox, grid, BEM methodology)
- JS (basic concepts, DOM, ES6, function Expression, function Declaration, arrow functions, variable scopes)
- TypeScript (basic concepts)
- Angular (basic concepts, RxJS, Angular Reactive Forms, Angular Material)
- NPM
- NodeJS (ExpressJs, mongoose)
- Bootstrap5, Materialize
- Git
- CI/CD (running a simple yaml script on GitHub Actions and GitLab CI/CD)
- Docker (deploying a simple docker image with an angular app)
- Rest API

---

### Code example:

**Count the number of Duplicates:** _Write a function that will return the count of distinct case-insensitive alphabetic characters and numeric digits that occur more than once in the input string. The input string can be assumed to contain only alphabets (both uppercase and lowercase) and numeric digits._

```javascript
function duplicateCount(text) {
  result = 0;
  usedChar = [];
  text = text.toLowerCase();
  for (let i = 0; i <= text.length; i++) {
    for (let j = i + 1; j <= text.length; j++) {
      if (text[i] == text[j] && !usedChar.includes(text[j])) {
        usedChar.push(text[j]);
        result++;
        continue;
      }
    }
  }
  return result;
}
```

---

### Languages:

- English \- A1 Begginer
- Russian \- Native
