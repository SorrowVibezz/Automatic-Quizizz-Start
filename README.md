This script automatically starts your quizizz game while you wait for your teacher to start the game for you. **(WORKS FOR LIVE QUIZIZZ ONLY)**

# Requirements
1. Game Pin

# Try it
Press crtl + shift + j and copy paste the code below into your console
```js
fetch("https://raw.githubusercontent.com/glixzzy/Automatic-Quizizz-Start/main/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
