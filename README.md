```js
#! /bin/node

const chalk = require("chalk");

function greet(you) {
  return `
    Hi, ${you}! Im ${this.name}, 

    Im Just A ${this.stack} Developer,
    Im An Asian Person At ${this.country},
    Ive Been Coding Since ${this.coded},
    I Use ${this.os} Btw.

    More Info Of Me At ${this.site}.
    Bye...
  `;
}

const info = {
  name: "SX Spy Agent",
  stack: "Front-End",
  country: "Indonesia",
  coded: 2021,
  os: "Arch Linux",
  site: "sx9.is-a.dev",
}

let hello = greet.bind(info);
console.log(chalk.cyan(hello("Github")));

//EOF
```
