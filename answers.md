# Answers

## 🧱 Exercises A

**A1:**

```js
let weight;
```

**A2:** `undefined`

**A3:**

```js
let name = "Gabriel";
let age = 22;
let weight = 75.9;
let isSubscribed = true;
```

**A4:** `object`

**A4.1:**

```js
let student = {
  name: "Gabriel",
  age: 22,
  weight: 75.9,
  isSubscribed: true,
};
```

**A4.2:**

```js
let message = `${student.name} de idade ${student.age} pesa ${student.weight} kg`;
```

```js
let student = {};
```

**A5:**

```js
let students = [];
```

**A6:**

```js
students = [student];
```

**A7:**

```js
console.log(students[0]);
```

**A8:**

```js
let marcos = {
  name: "Marcos",
  age: 32,
  weight: 99.9,
  isSubscribed: false,
};
```

```js
students[1] = marcos;
```

**A9:**

```js
console.log(a);
var a = 1;
```

undefined why I am trying to display the value of a variable before even assigning a value to it and how the javascript works in a linear way, ie from top to bottom to display the value of the variable the right would be:

```js
var a = 1;
console.log(a);
```
