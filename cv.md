<p align="center">
  <img src="https://avatars.githubusercontent.com/u/14216389" align="center" height="200" >
</p>
<p align="center">
  ***Serhii Koamrychev***
</p>


```js
if (!Math.trunc) { // if no such function
  // implement it
  Math.trunc = function(number) {
    // Math.ceil and Math.floor exist even in ancient JavaScript engines
    // they are covered later in the tutorial
    return number < 0 ? Math.ceil(number) : Math.floor(number);
  };
}
```
