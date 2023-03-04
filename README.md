![Hello World!](banner.png)
<div align="center">
  <h1>:computer: Hello World!</h1>
  <img src="https://skillicons.dev/icons?i=vite,vue,firebase,linux,nodejs,vscode&perline=6&theme=dark">
</div>

```js
#! /bin/node

import chalk from "chalk";

function greet(you) {
  return `
    Hi, ${you}! Im ${this.name},

    Im A ${this.stack} Developer,
    An Asian At ${this.country},
    And An ${this.os} User Btw.
    Ive Been Coding Since ${this.coded}
    And Now Im A ${this.pro ? "Pro" : "Newbie"}.

    More Info Of Me At ${this.site}.
    Bye...
  `;
}

const info = {
  name: "SX Spy Agent",
  stack: "Front-End",
  country: "Indonesia",
  coded: 2021,
  pro: true,
  os: "Arch Linux",
  site: "sx9.is-a.dev",
}

let hello = greet.bind(info);
console.log(chalk.cyan(hello("Github")));

//EOF
```
