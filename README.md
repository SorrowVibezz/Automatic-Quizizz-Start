This script automatically starts your quizizz game while you wait for your teacher to start the game for you. **(WORKS FOR LIVE QUIZIZZ ONLY)**

__Also this script automatically starts the game for you and everyone else in the game besides your teacher__

# Requirements
1. Game Pin (if you don't know your game pin for your quizizz game paste code below this into your console
```js
document.body.firstChild.__vue__.$store._vm.$data.$$state.game.data.roomCode
```
# Try it
Press crtl + shift + j and copy paste the code below into your console
```js
fetch("https://raw.githubusercontent.com/glixzzy/Automatic-Quizizz-Start/main/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
