![Serhii Komarychev](pngwing.com (4).png)
![Serhii Komarychev](https://avatars.githubusercontent.com/u/14216389?s=460&u=71ce0d6e83d62ebc247453bddfab70f9ac54d753&v=4)

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
