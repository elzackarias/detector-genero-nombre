# Gender detection from name

### Install
`npm i ```detector-genero-nombre

### Example
```js
const { getGender } = require('dector-genero-nombre');

const genderEN = getGender('Andrea', 'en');
const genderIT = getGender('Andrea', 'it');
const genderES = getGender('Andrea', 'es');
const genderFR = getGender('Andrea', 'fr');
const genderDE = getGender('Andrea', 'de');
const genderTR = getGender('Radife', 'tr');
const gender = getGender('Jennifer');
console.log(genderEN); // female
console.log(genderIT); // male
console.log(genderES); // male
console.log(genderFR); // male
console.log(genderDE); // female
console.log(genderTR); // female
console.log(gender); // female

### Supported languages
`en`, `it`, `es`, `fr`, `de`, `tr`

### Run tests
```npm test```
### Run lint
```npm run lint```
