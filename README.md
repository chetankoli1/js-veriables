```js
let name = "chetan";
```

```js
let Rank = "sagar";
```

```js
let jay = 1;
```

```js
let r = 34;
```

```js
let add = 3 + 4;
```

```js
4 > 1;
```

```js
let mName = null;
```

```js
let a = "abc" / 3;
```

```js
x = "xyz" * 2;
```

```js
/**
 * Returns a letter grade.
 * "A": 90-100%
 * "B": 80-89%
 * "C": 70-79%
 * "D": 60-69%
 * "F": 0-59%
 * @param {number} score
 * @param {number} total maximum possible score
 * @return {string} the score represented as a letter grade
 */

 function checkResult(score) {
      if (score >= 90 && score <= 100) {
            return 'A';
          } else if (score >= 80 && score < 90) {
            return 'B';
          } else if (score >= 70 && score < 80) {
            return 'C';
          } else if (score >= 60 && score < 70) {
            return 'D';
          } else if (score <= 59 && score >= 0) {
            return 'F';
          } else {
            return 'wrong score';
          }
}

checkResult(98)

```
```js
const dogAge = (age) => {
 let n = age * 7;
console.log("Your doggie is " + n +" years old in dog years!")
}

dogAge(3)
```