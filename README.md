console.time polyfill
=====================

Lightweight and simple polyfill for `console.time()` and `console.timeEnd()`.

Can be installed via bower with `bower install console-time --save-dev`.

## Example usage

```javascript
// Start the timer by passing it a key
console.time('myTimer');

// Call timeEnd later to see how long an operation took
setTimeout(function() {
  console.timeEnd('myTimer');
}, 2000);

// It should then log out something like..
'myTimer: 2000ms'
```

For more information on `console.time()` visit [MDN](https://developer.mozilla.org/en-US/docs/Web/API/console.time).
