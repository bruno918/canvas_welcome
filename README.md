##  installation 
```bash
$ npm i yg-canvas
```

## welcome
``` js
const yg-canvas = require("yg-canvas")
const fs = require("fs")

async function await() {
const welcome = await new yg-canvas.welcome()
.setProfile("https://raw.githubusercontent.com/squad-404/knights-canvas/main/assets/img/default-avatar.png")
.setName("yogi prasetya")
.setBg("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLn5-nn4-7EOA0THMNo9yaRXKegd28AAZ86ZUWgnQC6Ew6b8nrYzXsJITC&s=10")
.setMember("3")
.toAttachment();
return welcome
}

await().then((data) => {
fs.writeFileSync('out.svg', data.toBuffer())
})
```
#### result
<img src="https://telegra.ph/file/69cbbf0a637da88afd137.jpg" height="160"></img>
</details>

## goodbye
``` js
const yg = require("yg-canvas")
const fs = require("fs")

//async await
async function await() {
const goodbye = await new yg.goodbye()
.setProfile("https://raw.githubusercontent.com/squad-404/knights-canvas/main/assets/img/default-avatar.png")
.setName("yogi prasetya")
.setBg("linkbg")
.setMember("3")
.startGoodbye();
return goodbye
}

//start && saving to svg
await().then((data) => {
fs.writeFileSync('out.svg', data.toBuffer())
})
```

#### result
<img src="https://telegra.ph/file/91f1a85c6921d51b50c94.jpg" height="160"></img>
</details>

## Thanks to
##### refrence for canvas
* [`squad 404 team`](https://github.com/squad-404)

##### request && report bug
* [`whatsapp`](https://wa.me/62895613293360)
