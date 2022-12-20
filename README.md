```js
#! /bin/node

function greet(you) {
  return `
    Hi, ${you}! Im ${this.name}, 

    Im Just A ${this.stack} Developer,
    Im Coding Since ${this.coded},
    I Use ${this.os} Btw.
  `;
}

const info = {
  name: "SX Spy Agent",
  stack: "Front-End",
  since: 2021,
  os: "Arch Linux",
}

greet.bind(info);
console.log(greet("Github");

//EOF
```
