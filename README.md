# GoIT JavaScript - Homework #2.

---

## Задача 1. Генератор slug

Напиши функцію `slugify(title)`, яка приймає заголовок статті, параметр `title`
і повертає `slug`, створений із цього рядка.

Значенням параметра `title` будуть рядки, слова яких розділені лише пробілами.
Усі символи `slug` повинні бути в нижньому регістрі. Усі слова `slug` повинні
бути розділені тире. Візьми код нижче і встав після оголошення своєї функції для
перевірки коректності її роботи. У консоль будуть виведені результати її роботи.

```js
console.log(slugify('Arrays for beginners')); // "arrays-for-beginners"
console.log(slugify('English for developer')); // "english-for-developer"
console.log(slugify('Ten secrets of JavaScript')); //"ten-secrets-of-javascript"
console.log(slugify('How to become a JUNIOR')); //"how-to-become-a-junior"
``;
```

Задача 2. Композиція масивів

Виконуй це завдання у файлі task-2.js

Напиши функцію під назвою makeArray, яка приймає три параметри: firstArray
(масив), secondArray (масив) і maxLength (число). Функція повинна створювати
новий масив, який містить усі елементи з firstArray, а потім усі елементи з
secondArray.

Якщо кількість елементів у новому масиві перевищує maxLength, функція повинна
повернути копію масиву з довжиною maxLength елементів. В іншому випадку функція
повинна повернути весь новий масив.

Візьми код нижче і встав після оголошення своєї функції для перевірки
коректності її роботи. У консоль будуть виведені результати її роботи.

console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)); // ["Mango",
"Poly", "Ajax"] console.log(makeArray(["Mango", "Poly", "Houston"], ["Ajax",
"Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]
console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); //
["Mango", "Ajax", "Chelsea"] console.log(makeArray(["Earth", "Jupiter"],
["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); //
["Earth", "Jupiter", "Neptune", "Uranus"] console.log(makeArray(["Earth",
"Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []
