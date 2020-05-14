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

####4. 
