#  ARRAY README

##  Array чист?

Array дар JavaScript барои нигоҳ доштани якчанд маълумот дар як тағйирёбанда истифода мешавад


```js
let fruit = ["apple", "banana", "orange"];
```

---

# 📍 Index дар Array

```js
let fruit = ["apple", "banana", "orange"];

console.log(fruit[0]);
console.log(fruit[1]);
```

---

# Array Methods

##  push()

Ба охири array элемент илова мекуна

```js
let arr = [1, 2];

arr.push(3);

console.log(arr);
```

## Output

```js
[1, 2, 3]
```

---

##  pop()

Элементи охиринро нест мекун

```js
let arr = [1, 2, 3];

arr.pop();

console.log(arr);
```

###  Output

```js
[1, 2]
```

---

##  shift()

Элементи аввалро нест мекуна

```js
let arr = [1, 2, 3];

arr.shift();

console.log(arr);
```

###  Output

```js
[2, 3]
```

---

##  unshift()

Ба аввали array элемент илова мекунад.

```js
let arr = [2, 3];

arr.unshift(1);

console.log(arr);
```

###  Output

```js
[1, 2, 3]
```

---

##  length

Шумораи элементҳоро нишон медиҳад.

```js
let arr = [1, 2, 3];

console.log(arr.length);
```

###  Output

```js
3
```

---

##  includes()

Месанҷа ки элемент ҳаст ё не

```js
let fruit = ["apple", "banana"];

console.log(fruit.includes("banana"));
```

###  Output

```js
true
```

---

##  indexOf()

Index-и элементро меёба

```js
let fruit = ["apple", "banana"];

console.log(fruit.indexOf("banana"));
```

###  Output

```js
1
```

---

##  slice()

Қисме аз array-ро мегира

```js
let arr = [1, 2, 3, 4]

console.log(arr.slice(1, 3))
```

###  Output

```js
[2, 3]
```

---



##  concat()

Ду array-ро якҷоя мекуна

```js
let a = [1, 2];
let b = [3, 4];

console.log(a.concat(b));
```

###  Output

```js
[1, 2, 3, 4]
```

---
