### mori
---
https://github.com/swannodette/mori

```js
// spec/mori-spec.js
var mori = require("../mori");

describe("Map", function () {
  it("demostrates mapping a function over a vector", function () {
    var inc = function (n) { return n + 1; };
      outArr = mori.intoArray(mori.map(inc, mori.vector(1,2,3,4,5)));
    expect(outArr).toEqual([2,3,4,5,6]);
  });
  
});




```

```
```

```
```

