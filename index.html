<!DOCTYPE html>
<html lang="ne">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ठूलो डिजिटल कैल्कुलेटर</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
        }
        .calculator {
            background: #1e1e1e;
            padding: 30px;
            border-radius: 25px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.6);
            width: 480px; /* काफी लाम्चो र चौडा */
            max-width: 95vw;
        }
        .display {
            width: 100%;
            height: 100px; /* धेरै ठूलो डिस्प्ले */
            font-size: 3.5em; /* ठूलो अक्षर */
            text-align: right;
            padding: 20px;
            border: none;
            background: #000;
            color: #0f0; /* क्लासिक ग्रीन ग्लो */
            border-radius: 15px;
            margin-bottom: 25px;
            box-shadow: inset 0 0 20px rgba(0,255,0,0.3);
            letter-spacing: 3px;
        }
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }
        button {
            padding: 30px; /* ठूला बटन */
            font-size: 2em;
            font-weight: bold;
            border: none;
            border-radius: 15px;
            background: #333;
            color: white;
            cursor: pointer;
            transition: all 0.2s;
            box-shadow: 0 5px 15px rgba(0,0,0,0.4);
        }
        button:hover {
            background: #555;
            transform: translateY(-3px);
        }
        button:active {
            transform: translateY(3px);
            box-shadow: 0 2px 8px rgba(0,0,0,0.5);
        }
        .operator {
            background: #ff9500;
            color: white;
        }
        .operator:hover {
            background: #e68a00;
        }
        .equal {
            background: #28a745;
            color: white;
            grid-row: span 2; /* लामो = बटन */
            padding: 60px 30px;
        }
        .equal:hover {
            background: #218838;
        }
        .clear {
            background: #dc3545;
            color: white;
        }
        .clear:hover {
            background: #c82333;
        }
        .zero {
            grid-column: span 2;
        }
    </style>
</head>
<body>
    <div class="calculator">
        <input type="text" class="display" id="result" readonly placeholder="0">
        <div class="buttons">
            <button class="clear" onclick="clearDisplay()">C</button>
            <button class="clear" onclick="deleteLast()">⌫</button>
            <button class="operator" onclick="appendToDisplay('/')">÷</button>
            <button class="operator" onclick="appendToDisplay('*')">×</button>

            <button onclick="appendToDisplay('7')">7</button>
            <button onclick="appendToDisplay('8')">8</button>
            <button onclick="appendToDisplay('9')">9</button>
            <button class="operator" onclick="appendToDisplay('-')">−</button>

            <button onclick="appendToDisplay('4')">4</button>
            <button onclick="appendToDisplay('5')">5</button>
            <button onclick="appendToDisplay('6')">6</button>
            <button class="operator" onclick="appendToDisplay('+')">+</button>

            <button class="zero" onclick="appendToDisplay('0')">0</button>
            <button onclick="appendToDisplay('.')">.</button>
            <button class="equal" onclick="calculate()">=</button>
        </div>
    </div>

    <script>
        function appendToDisplay(value) {
            const display = document.getElementById('result');
            if (display.value === '0' && value !== '.') {
                display.value = value;
            } else {
                display.value += value;
            }
        }

        function clearDisplay() {
            document.getElementById('result').value = '0';
        }

        function deleteLast() {
            const display = document.getElementById('result');
            if (display.value.length === 1 || display.value === 'Error') {
                display.value = '0';
            } else {
                display.value = display.value.slice(0, -1);
            }
        }

        function calculate() {
            const display = document.getElementById('result');
            try {
                let expression = display.value.replace('÷', '/').replace('×', '*');
                display.value = eval(expression);
            } catch {
                display.value = 'Error';
                setTimeout(() => { display.value = '0'; }, 1500);
            }
        }
    </script>
</body>
</html>
