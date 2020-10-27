# My First README

My repo explaining README.md
#Tic-Tac-Toe


## Steps to install on local computer
1. Go to repo on Github profil
2. `fork` and `clone` repo
3. clone to computer
``` text
git clone https://github.com/NikkiHmltn/tic-tac-toe
```
4. Got to `tic-tac-toe` directory
5. Open `index.html` in directory
``` text
cd open index.html
```

``` css
.X::before {
  content: 'x';
  text-align: center;
  width: 100px;
  height: 100px;
  font-size: 70px;;
}

.O::after {
  content: 'o';
  text-align: center;
  width: 100px;
  height: 100px;
  font-size: 70px;;
}
```
```html
 <div class="board">

    <div class="box" id='box1'></div>
    <div class="box" id='box2'></div>
    <div class="box" id='box3'></div>
    <div class="box" id='box4'></div>
    <div class="box" id='box5'></div>
    <div class="box" id='box6'></div>
    <div class="box" id='box7'></div>
    <div class="box" id='box8'></div>
    <div class="box" id='box9'></div>

  </div>
```

``` javascript
function placeMark(box, currentMark){
    box.classList.add(currentMark);
    checkWin();
    document.querySelector(".display").innerText = `${currentMark}'s turn next!`
```

