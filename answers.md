# Answers

## 🧱 Variables

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

---

## 📑 Array

**B:1:**

```js
let overTheTable = ["Keyboard", "Mouse", "Headset"];
```

**B:2:**

```js
let mouse = overTheTable[1];

console.log(mouse);
```

**B:3:**

```js
let nextItem = overTheTable.push("Mask");
```

**B:4**

```js
let removeLastItem = overTheTable.pop();
```

**B:5:**

```js
let removeFirstItem = overTheTable.shift();
```

**B:6:**

```js
let newItem = overTheTable.unshift("Pen");
```

**B:7:**

```js
let position = overTheTable.indexOf("Mouse");
```

**B:8:**

```js
let removeMouse = overTheTable.splice(position, 0);
```

**B:9:**

```js
let shoppingList = ["Rice", "Beans", "Macaroni", "Cookie"];

let position = 1;
let number = 2;

let itemsRemoved = shoppingList.splice(position, number);

console.log(itemsRemoved);
console.log(shoppingList);

// number defines the number of items to be removed from the position (position variable) towards the end of the array
```

**B10:**

```js
let atHouseHave = ["Couch", "TV", "Stove", "Fridge"];

let addText = (text) => text + " - have";

let copy = atHouseHave.map(addText);

// modified
console.log(copy);

// original
console.log(atHouseHave);
```

**B:11:**

```js
let numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

let filteredNumbers = (number) => number < 4;

let copy = numbers.filter(filteredNumbers);
```
