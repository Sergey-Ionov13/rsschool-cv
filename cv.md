## Sergey Ionov
***
## Contacts:
* Phone: +375 (29) 263-53-69
* Email: ipionov13@gmail.com
* Discord: Serge_I (@Sergey-Ionov13)
* GitHub: [Sergey-Ionov13](https://github.com/Sergey-Ionov13)
* CodePen: [Sergey13](https://codepen.io/Sergey13/pens/public)
***
## About me:
I am 38 years old and work as an engineer in the construction industry. My next goal is to get my first job as a front-end developer so I can concentrate fully on development in this area. My hallmarks are: perseverance, meticulousness and accuracy.
***
## Skills:
* HTML
* CSS
* Bootstrap
* JavaScript Basics
* Git
***
## Code example:
Large Factorials from CODEWARS: write a function that takes an integer n and returns the value of n!.
```
function factorial(n){
  if (n === 1) return '1';
  let arr = [];

  for (let i = n; i > 1; i--) {
    arr.push(String(i).split('').reverse());
  }

  let resArr = arr.reduce( (result, current) => {
    return multiplication(result, current);
  });

  return resArr.reverse().join('');

  function multiplication(x, y) {
    let result = x;
    let n = Number(y.reverse().join(''))
    for (let i = 1; i < n; i++) {
      result = addition(result, x);
    }
    return result;
  }

  function addition(a, b) {
    let intermed = 0;
    let resultArr = [];
    for (let i = 0; i < a.length; i++) {
      let res = i < b.length ? Number(a[i]) + Number(b[i]) + intermed : Number(a[i]) + intermed;
      intermed = Math.floor(res/10);
      res = res % 10;
      resultArr.push(String(res));
    }
    if(intermed === 1) resultArr.push(intermed);
    return resultArr;
  }
}
```
***
## Experience:
Nothing yet…
***
## Education
* HTML Academy
* FreeCodeCamp
* learn.javascript.ru
* MDN (developer.mozilla)
* YouTube course "React JS - путь самурая 1.0"
## English
A1