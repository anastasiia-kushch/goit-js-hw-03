# goit-js-hw-02

This repository contains three JavaScript functions solving different tasks.

## `task-1.js` - `slugify(title)`

Generates a URL-friendly slug from a given title.  
**Params:**

- `title` (string) – input title

**Example:**

```js
slugify('Arrays for beginners'); // "arrays-for-beginners"
```

## `task-2.js` - `makeArray(firstArray, secondArray, maxLength)`

Combines two arrays into a new one, ensuring it does not exceed the specified maximum length.  
**Params:**

- `firstArray` (array) – first array of elements
- `secondArray` (array) – second array of elements
- `maxLength` (number) – maximum allowed length of the resulting array

**Example:**

```
makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3); // ["Mango", "Poly", "Ajax"]
```

---

## `task-3.js` - `filterArray(numbers, value)`

Filters an array, returning only numbers greater than a specified value.  
**Params:**

- `numbers` (array) – array of number
- `value` (number) – threshold value

**Example:**

```
filterArray([1, 2, 3, 4, 5], 3); // [4, 5]
```
