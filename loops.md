Questions

What are the three things you need to provide for a loop? I.e. for(a; b; c;), what are a, b, and c?

A. initialization ; condition ; final-expression

Describe infinite loops and how to avoid them.

A. An infinite loop is a loop whose condition will always be met and will run in perpetuity. It can cause problems such as freezing or crashing your computer. Ensure that your final expression will eventually reach a point where the condition isn't met to end the loop.

Code Practice

Using the `shoppingCart` variable below, use a `for()` loop to iterate over the array and `console.log()` the shopping cart items name.

```
var shoppingCart = [
  {
      id: 0,
      name: 'Mens Shirt',
      price: 20,
      size: 'Large'
  },
  {
  id: 1,
  name: 'kids shirt',
  price: 15,
  size: 'small'
}
]

// write code below

for (let i = 0; i < shoppingCart.length; i++) {
  console.log(shoppingCart[i]);
}
```
