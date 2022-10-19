---
title: "who-wuda-thunk"
date: 2022-10-19
---


## _breathe_ 
>"You are just as likely to solve a problem
>
>by being unconventional and determined
>
>as by being brilliant"
>  
>  _**sir james dyson**_

***

# who wuda thunk?

_unfamilar terrain wicked, but me wickeda dan_

***

after countless _(mindless)_ installations of "node" and enough
insight to find node modules 🤝 thor's hammer jokes relatable, i finally had to understand what [node-modules] are.

🧷 basically, you invoke any of them and **boom-** _your app bags an extra layer of complexity._

🧷 these kind sires for instance 👇


![Web capture_19-10-2022_35418_replit com](https://user-images.githubusercontent.com/67290908/196591069-3ae1b32a-2b16-49b3-9353-c78e02d2b660.jpeg)

***

## ..one episode of over-excitement later
did a bit of snooping on repos owned by internet strangers and this guy 👉 `express` won't stop showing up.

🧷 thankfully, [MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction) pulled up- rather expressive.

***

this guy too 👉 `app.use()` sort of had me stumbling.

🧷 [Express Docs](https://expressjs.com/en/4x/api.html#app.use) came in handy 👇

![Web capture_29-9-2022_1155_expressjs com](https://user-images.githubusercontent.com/67290908/196576558-6387e652-ea5b-41a9-8d54-ff33b11898c9.jpeg)

***

🧷 Fell into a rabbit hole about [ports](https://computer.howstuffworks.com/web-server8.html).

***

## ...aaand thus began me woes

![Web capture_19-10-2022_25233_replit com](https://user-images.githubusercontent.com/67290908/196579815-e118a3dd-52e0-4ae2-84cd-6630a239bbd8.jpeg)

the sdk requires that the `HTML FILE` for conversion be stationed in a `zip file`.

one question... _why? why me?_

🧷 well, imagine how elated i was when after hours of brute-applying all shades of solutions, it finally [clicked.](https://www.digitalocean.com/community/tutorials/how-to-work-with-zip-files-in-node-js#step-1-setting-up-the-project)
pardon me for ever speaking so flippantly about node-modules.

***

## fr fr i thought i was done
now, imagine how my face dropped, when i encountered yet another.. _woe_ 

the pdf file showed up empty and i had no idea why, until when, ofcourse, i headed right back to the docs 👇

![Web capture_19-10-2022_31416_replit com](https://user-images.githubusercontent.com/67290908/196582509-30ece3d7-5635-4f73-95c8-985d7a22386d.jpeg)


![Web capture_29-9-2022_3437_opensource adobe com](https://user-images.githubusercontent.com/67290908/196582947-73591f4b-aa86-4247-8cf4-4552c5ff6f3b.jpeg)

🧷 i was missing some `js-code` in the `source-html`. 

🧷 with the `js-code`, star-boi `data-to-merge` will show up in the empty fields @ `source-html`  

🧷 _i.e populate._

🧷 sample files came in handy 👇

```javascript
<script src="./json.js"></script>
  
  <script type="text/javascript">
    
      function populate()
      {
          let document = window.document;
          document.getElementById("title").innerHTML = String(window.json.title);
          document.getElementById("sub-title").innerHTML = String(window.json.sub_title);
      }
    </script>
  ```
  _(i still have no idea how this works `<script src="./json.js"></script>`)_
  
  ***
  
## guess who showed up again? `problem` 👇
  
  ![Web capture_19-10-2022_34113_downloads](https://user-images.githubusercontent.com/67290908/196586019-8efdf61b-0e74-412c-bd1b-b2d032899ff7.jpeg)
  
  
  multiple attempts to fetch the pdf via the client but _the server just won't budge_

  ..where did i go wrong?
  
  ***
  
  🧷 all it took was a formal request 👇
  
![Web capture_19-10-2022_34733_replit com](https://user-images.githubusercontent.com/67290908/196587043-c3963f14-b6e3-4ae7-8a3c-a0097af21983.jpeg)

 🧷 plus these guys to handle ...and deliver 👇

![Web capture_19-10-2022_34942_replit com](https://user-images.githubusercontent.com/67290908/196587168-5f486ab1-0777-49fd-94df-2cf021279188.jpeg)

  🧷 and kaboom! 👇
  
![Web capture_19-10-2022_3550_downloads](https://user-images.githubusercontent.com/67290908/196587612-acd679b4-2f1a-455f-938e-3892aa092665.jpeg)

## did i mention?

believe me, i went on another [bout](https://twitter.com/Rahmatuhu/status/1582191412048560128) of _why isn't it working_ 

 🧷 because an unwanted slash made it's way in ..somehow.. 👇

![Web capture_19-10-2022_35918_replit com](https://user-images.githubusercontent.com/67290908/196588251-afa1da99-46ce-406e-8283-6af9e4d5fdca.jpeg)

***

## whew!

now that we've made it "work", let's put it to work.

***

thank you for reading 🚀

