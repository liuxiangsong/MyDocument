# string

- trimLeft(string)

```javascript
String.prototype.trimLeft = function(text) {
  if (text === undefined){
    text = "\s";
}
  return this.replace(new RegExp("^" + text + "+","g"), "");
}; 
```

- trimLeft(trimRight)

```javascript
String.prototype.trimRight = function(text) {
  if (charlist === undefined){
    text = "\s";
  }
  return this.replace(new RegExp("" + text + "+$","g"), "");
};
```