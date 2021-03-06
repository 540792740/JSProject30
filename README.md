### 30 JS Projects

####1. DrumKit
* This project will provide a simulation drum by click keyboard
* Add Class: `key.classList.add('playing');`
* `document.querySelectorAll('.key').forEach(key => ...)`
    
####2. Clock
* This project is create a clock with hour-hand, min-hand and sec-hand.
* `transition-timing-function: cubic-bezier(0.16, 0.24, 0.57, 1.29);`
* `const now = new Date()`; <br> 
    `const second = now.getSeconds();` <br> 
    `const min = now.getMinutes();`
* `document.querySelector('.second-hand').style.transform = rotate(${minDegrees}deg)`;
* `transition: all 0.5s;`
* `transform-origin: 100%;`  -> move hand to the end
####3. Update CSS variables with JS
* This project is the way to dynamic change Spacing and blur.
* `<input id="spacing" type="range" name="spacing" min="10" max="200" value="10" data-sizing="px">`
* Using --space by define in :root{] and using with `--spacing`  <br> 
    `:root{--spacing: 10px;}` <br>
    `img{ padding: var(--spacing);}`
* `document.querySelectorAll('.controls input')`  <br> 
    `forEach(input => input.addEventListener('change', handleUpdate))`

####4. Array Cardio
* `array.filter(inventor => (inventor.year >= 1500))`
* `console.table(fifteen)` -> table console
* `const fullNames = inventors.map(inventor => inventor.first + " " + inventor.last)` <br>
  `const fullNames = inventors.map(inventor => `${inventor.first} ${inventor.last}`)`
* `const links = Array.from(category.querySelectorAll('a'));`
  `const links = [...category.querySelectorAll('a')];`    

* <h4>Hash table</h4>:
    `const transportation = data.reduce(function (obj, item) {`
           `if(!obj[item]){obj[item] = 0;}`   <br>
           `obj[item]++;` <br>
           `return obj`   <br>
         `},{});`

####5. Flex Panel
* `justify-content: center;`    <br>
  `align-items: center;`
* `.panel > *:first-child{transform: translateY(-100%);}`
* `myDIV:hover { width: 400px;}`
  `document.getElementById("myDIV").addEventListener("transitionend", myFunction);`

####6. Ajax
* `function numberWithCommas(x){ return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ',');}`
* Promise.then(data => arr.push(...data)

####7. Array
* const isAdult = people.**some**(person => (new Date()).getFullYear() - 19 >= person.year)
* const isAdult = people.**every**(person => (new Date()).getFullYear() - 19 >= person.year)
* const isAdult = people.**find** (comment => comment.id === 823423)
* const index = comments.**findIndex**(comment => comment.id === 823423);
* Delete
    `const newCommand = [`  <br>
            `...comments.slice(0, index),`<br>
            `...comments.slice(index + 1)`<br>
    `];`

#### 8. Canvas
* Make line become round: <br>
    `ctx.lineJoin ='round';` <br>
    `ctx.lineCap = 'round';` <br>
    `ctx.lineWidth = 20`
* The way to change color:  <br>
    ctx.strokeStyle = `hsl(${hue}, 100%, 50%)`;


* `console.group()`  <br>
  `console.groupEnd()`
* `console.time('for loop');` <br>
  `for(let i = 0; i < 1000; i++){} `  <br>
  `console.timeEnd('for loop'); `
