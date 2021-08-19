# Animation on JS (EN)

Creating simple animation on JavaScript language.

#### HTML

```
<button onclick="myMove()">Animation</button>
<div id="myContainer">
    <div id="myAnimation"></div>
</div>
```

#### CSS

```
#myContainer {
    width: 400px;
    height: 400px;
    position: relative;
    background: yellow;
}

#myAnimation {
    width: 50px;
    height: 50px;
    position: absolute;
    background: red;
}
```

#### JavaScript

```
function myMove() {
    var elem = document.getElementById('myAnimation')
    var pos = 0
    var id = setInterval(frame, 10)
    function frame() {
        if (pos == 350) {
            clearInterval(id)
        } else {
            pos++
            elem.style.top = pos + 'px'
            elem.style.left = pos + 'px'
        }
    }
}
```

# Анимация на JS (RU)

Создание простой анимации на языке JavaScript.

#### HTML

```
<button onclick="myMove()">Animation</button>
<div id="myContainer">
    <div id="myAnimation"></div>
</div>
```

#### CSS

```
#myContainer {
    width: 400px;
    height: 400px;
    position: relative;
    background: yellow;
}

#myAnimation {
    width: 50px;
    height: 50px;
    position: absolute;
    background: red;
}
```

#### JavaScript

```
function myMove() {
    var elem = document.getElementById('myAnimation')
    var pos = 0
    var id = setInterval(frame, 10)
    function frame() {
        if (pos == 350) {
            clearInterval(id)
        } else {
            pos++
            elem.style.top = pos + 'px'
            elem.style.left = pos + 'px'
        }
    }
}
```
