### kadence
---
https://github.com/kadence/kadence

```
npm install -g @kadenceproject/kadence
kadence --help
```

```js
class Bucket extends Map {
  constructor() {
    super();
  }
  
  get length() {
    return super.size;
  }
  
  get head() {
    return [...super.entries()].shift();
  }
  
  get tail() {
    return [...super.entries()].pop();
  }
}
```

```
```


