```js
#! /bin/node

function greet(you) {
  return `
    Hi, ${you}! Im ${this.name}, 

    Im Just A ${this.stack} Developer,
    Ive Been Coding Since ${this.coded},
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

# $ ssh sx-9@github -p 1151

![](https://github-readme-stats.vercel.app/api?username=SX-9&count_private=true&show_icons=true&theme=tokyonight&hide_border=true&border_radius=20&text_bold=true&custom_title=this.github.stats();#gh-dark-mode-only)
![](https://github-readme-stats.vercel.app/api/top-langs?username=SX-9&count_private=true&show_icons=true&theme=tokyonight&hide_border=true&border_radius=20&text_bold=true&custom_title=this.github.langs();#gh-dark-mode-only)
