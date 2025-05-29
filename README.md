# Calculator-in-HTML


<div class="calculator">
    <input type="text" class="display" id="display" disabled>
    <div class="buttons">
        <button class="button" onclick="clearDisplay()">C</button>
        <button class="button" onclick="backspace()">DEL</button>
        <button class="button" onclick="calculate()">=</button>
        <button class="button" onclick="addToDisplay('/')">/</button>
        <button class="button" onclick="addToDisplay('7')">7</button>
        <button class="button" onclick="addToDisplay('8')">8</button>
        <button class="button" onclick="addToDisplay('9')">9</button>
        <button class="button" onclick="addToDisplay('*')">*</button>
        <button class="button" onclick="addToDisplay('4')">4</button>
        <button class="button" onclick="addToDisplay('5')">5</button>
        <button class="button" onclick="addToDisplay('6')">6</button>
        <button class="button" onclick="addToDisplay('-')">-</button>
        <button class="button" onclick="addToDisplay('1')">1</button>
        <button class="button" onclick="addToDisplay('2')">2</button>
        <button class="button" onclick="addToDisplay('3')">3</button>
        <button class="button" onclick="addToDisplay('+')">+</button>
        <button class="button" onclick="addToDisplay('0')">0</button>
        <button class="button" onclick="addToDisplay('.')">.</button>
    </div>
    <div class="scientific-buttons">
        <button class="scientific-button" onclick="addToDisplay('sin(')">sin</button>
        <button class="scientific-button" onclick="addToDisplay('cos(')">cos</button>
        <button class="scientific-button" onclick="addToDisplay('tan(')">tan</button>
        <button class="scientific-button" onclick="addToDisplay('log(')">log</button>
        <button class="scientific-button" onclick="addToDisplay('sqrt(')">sqrt</button>
    </div>
</div>
