# My Favorite Javascript Functions

### `Square`

This Function squares a number

```js
const square = function (number) {
  return number * number;
};
```
### `Factorial`

This Function gives the factorial of a number

```js
const factorial = function fac(n) {
  return n < 2 ? 1 : n * fac(n - 1);
};
```
### `Map`

This function receives a function defined by a function expression and executes it for every element of the array received as a second argument

```js
function map(f, a) {
  const result = new Array(a.length);
  for (let i = 0; i < a.length; i++) {
    result[i] = f(a[i]);
  }
  return result;
}

```
### `Cube`

This Function cubes a number

```js
const cube = function (x) {
  return x * x * x;
};
```
