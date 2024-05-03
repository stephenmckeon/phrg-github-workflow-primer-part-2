# My 4 Favorite JavaScript Functions

### map()
This function allows you to iterate over an array's elements and transform each element based on a provided function, returning a new array with the transformed elements. It's great for applying a function to each element of an array without mutating the original array.

```
const array1 = [1, 4, 9, 16];
const map1 = array1.map((x) => x * 2);
console.log(map1);
```

### filter()
This function iterates over an array and returns a new array containing only the elements that pass a provided condition. It's perfect for selecting elements from an array based on certain criteria, without altering the original array.

```
const words = ['spray', 'elite', 'exuberant', 'destruction', 'present'];
const result = words.filter((word) => word.length > 6);
console.log(result);
```

### reduce()
This function is incredibly versatile and powerful. It reduces an array to a single value by applying a function to each element and accumulating the result. It's useful for tasks like summing up values, calculating averages, or even flattening arrays.

```
const words = ['spray', 'elite', 'exuberant', 'destruction', 'present'];
const result = words.filter((word) => word.length > 6);
console.log(result);
```

### find()
This function returns the first element in an array that satisfies a provided testing function. It's handy for retrieving a single element from an array based on a specific condition, especially when you only need one matching element.
```
const words = ['spray', 'elite', 'exuberant', 'destruction', 'present'];
const result = words.filter((word) => word.length > 6);
console.log(result);
```