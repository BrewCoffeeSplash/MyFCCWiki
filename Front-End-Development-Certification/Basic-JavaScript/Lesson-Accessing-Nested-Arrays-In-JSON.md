# Author
![@Rafase282](https://avatars0.githubusercontent.com/Rafase282?&s=128)

Created by Rafase282

[Github](https://github.com/Rafase282) | [FreeCodeCamp](http://www.freecodecamp.com/rafase282) | [CodePen](http://codepen.io/Rafase282/) | [LinkedIn](https://www.linkedin.com/in/rafase282) | [Website](https://rafase282.github.io/) | [E-Mail](mailto:rafase282@gmail.com)

# Lesson: Accessing Nested Arrays in JSON
As we have seen in earlier examples, `JSON objects` can contain both _nested objects_ and _nested arrays_. Similar to accessing nested objects, `Array bracket
` notation can be chained to access nested arrays.

Here is an example of how to access a nested array:

```js
var ourPets = {
  "cats": [
    "Meowzer",
    "Fluffy",
    "Kit-Cat"
  ],
  "dogs": [
    "Spot",
    "Bowser",
    "Frankie"
  ]
};
ourPets.cats[1]; // "Fluffy"
ourPets.dogs[0]; // "Spot"
```
