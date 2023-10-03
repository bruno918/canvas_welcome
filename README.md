## installation

```bash
$ npm i wlanvas
```

## welcome

```js
const wlcanvas = require("wlcanvas");
const fs = require("fs");

async function wlc() {
  const welc = await new wlcanvas.welcome()
    .setProfile("picture url")
    .setName("participant")
    .setBg("https://wallpapers.com/images/featured/space-sjryfre8k8f6i3ge.jpg")
    .setMember(01)
    .startGoodbye();
  return welc;
}

wlc().then((data) => {
  fs.writeFileSync("out.svg", data.toBuffer());
});
```

#### result

<img src="https://telegra.ph/file/69cbbf0a637da88afd137.jpg" height="160"></img>

</details>

## goodbye

```js
const wlcanvas = require("wlcanvas");
const fs = require("fs");

async function wlc() {
  const welc = await new goodbye()
    .setProfile("url from img")
    .setName("participant")
    .setBg("https://wallpapers.com/images/featured/space-sjryfre8k8f6i3ge.jpg")
    .setMember(number)
    .startGoodbye();
  return welc;
}

wlc().then((data) => {
  fs.writeFileSync("out.svg", data.toBuffer());
});
```

#### result

<img src="https://telegra.ph/file/91f1a85c6921d51b50c94.jpg" height="160"></img>

</details>

## Thanks to

##### yg-canvas

- [`Original site`](hhttps://www.npmjs.com/package/yg-canvas)
