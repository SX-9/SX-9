```js
#! /bin/node

function greet(you) {
  return `
    Hi, ${you}! Im ${this.name}, 

    Im Just A ${this.stack} Developer,
    Im Coding Since ${this.coded},
    I Use ${this.os} Btw.

    More Info Of Me At ${this.site}.
    Bye...
  `;
}

const info = {
  name: "SX Spy Agent",
  stack: "Front-End",
  coded: 2021,
  os: "Arch Linux",
  site: "sx9.is-a.dev",
}

let hello = greet.bind(info);
console.log(hello("Github"));

//EOF
```
