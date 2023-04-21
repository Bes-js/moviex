<h6 align="center">
<img src="https://cdn.discordapp.com/attachments/950167988127006821/1098881241819926528/coollogo_com-292651088.png" width="500px" height="200px" alt="stats" align="center">
<h6/>

<a href="https://www.buymeacoffee.com/beykant" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="120px" height="30px" alt="Buy Me A Coffee"></a>

![npm version](https://img.shields.io/npm/v/moviex?color=purple&label=npm%20i%20moviex&logo=npm&style=flat)
![npm info](https://img.shields.io/npm/dw/moviex?color=purple)


# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FF0000&repeat=false&width=435&lines=%E2%9D%94+How+To+Install%3F)](#)

To Install the `moviex` module, open a console and write the code below.
<br> </br>
For **npm**
```console
npm i moviex
```

For **Yarn**
```console
yarn add moviex
```

# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00EDFF&repeat=false&width=435&lines=%F0%9F%8E%AF+Describing)](#)

For **CommonJS**
```javascript
const moviex = require("moviex");
```

For **ES6**
```javascript
import moviex from "moviex";
```

# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=blue&repeat=false&width=435&lines=✨+Functions)](#)

<a href="https://www.buymeacoffee.com/beykant" target="_blank">Click Here To Get API Token!</a>
```javascript
moviex.setToken("API Token")
// Your API Token, To Get Token Key https://discord.gg/luppux

await moviex.search("Naruto") 
// Movie Or Series Name.

await moviex.genres("anime") 
// Genres; "random","anime","horror","adventure","animation","action","comedy" and "drama".

await moviex.status()
// Shows API Status.
```
# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=blue&repeat=false&width=435&lines=🪄+Example)](#)
```js
const moviex = require("moviex");

moviex.setToken("API TOKEN");

const random = async function(){
let response = await moviex.genres("random");
console.log(response);
}

random();
```
**For API Requests;**
```javascript
// API Token Is 'Bearer Token'.
Base URL; https://api-moviex.vercel.app
Genres URL; https://api-moviex.vercel.app/genres/:type
Search URL; https://api-moviex.vercel.app/search/:name
Status URL; https://api-moviex.vercel.app/status
```

**Example Output;**
```javascript
{
  name: 'Darling in the Franxx',
  url: 'https://www.imdb.com/title/tt7865090',
  plot: 'In a future world where humanity has been driven to endangerment by giant beasts, a strike force is assembled to destroy the monsters and save the world.',
  date: 2018,
  rate: 7.3,
  genres: [ 'animation', 'action', 'drama', 'romance', 'sciFi' ],
  type: 'series',
  banner: 'https://m.media-amazon.com/images/M/MV5BZGVlY2ZhM2ItMWIwZC00YjU0LWJjNjAtZGVlNWJkM2JmZjhmXkEyXkFqcGdeQXVyMzgxODM4NjM@._V1_.jpg',
  writers: 'Naotaka Hayashi,Joel Bergen,Hiroshi Seko,Rino Yamazaki,Masahiko Ôtsuka,Atsushi Nishigori',
  runtime: '24m'
}
```


<br> <br/>
# [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9D06E6&repeat=false&width=435&lines=API+Token+%26+Support+%26+Donate)](#)

[![Discord Banner](https://api.weblutions.com/discord/invite/luppux/)](https://discord.gg/luppux)
<br> </br>
<a href="https://www.buymeacoffee.com/beykant" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="120px" height="30px" alt="Buy Me A Coffee"></a>
