# forEach

The forEach() method is a higher-order function available for arrays in JavaScript. It allows you to iterate over each element in an array and apply a provided callback function to each element. This is a more concise and expressive way to perform iterations compared to using traditional for loops. Here's the syntax:

```javascript
array.forEach(callback(currentValue[, index[, array]]) {
  // Your code here
});

```

**callback:** The function to execute for each element in the array.
**currentValue:** The current element being processed in the array.
**index (optional):** The index of the current element in the array.
**array (optional):** The array on which forEach() is called