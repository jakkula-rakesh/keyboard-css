<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>keyboard</title>
    <style>
        body{
            background-color: #02bdd5 ;
        }
        #container{
            display: grid;
            grid-template-columns: repeat(12,1fr);
            grid-template-rows: repeat(5,50px);
            gap: 20px;
            width: 80%;
            border-radius: 20px;
            margin: auto;
            background-color: #262c2c ;
            padding: 30px;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            

        }
        #container > div{
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #263b38;
            color: beige;
            border-radius: 5px;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            font-size: 15px;
            font-style: bold;

            
        }
        #container > div:hover{
            background-color: rgb(129, 129, 73);
            color: black;
            cursor: pointer;
        }
        #enter{
            grid-column: 11/span 2;
        }
        #shift{
            grid-column: 11/span 2;
        }
        #space{
            grid-column: 5/span 4;
        }
    </style>
</head>
<body >
    <div id="container">
    <div>~</div>
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>0</div>
    <div>Delete</div>
    <div>Tab</div>
    <div>Q</div>
    <div>W</div>
    <div>E</div>
    <div>R</div>
    <div>T</div>
    <div>Y</div>
    <div>U</div>
    <div>I</div>
    <div>O</div>
    <div>P</div>
    <div>\</div>
    <div>Caps</div>
    <div>A</div>
    <div>S</div>
    <div>D</div>
    <div>F</div>
    <div>G</div>
    <div>H</div>
    <div>J</div>
    <div>K</div>
    <div>L</div>
    <div id="enter">Enter</div>
    <div>Shift</div>
    <div>Z</div>
    <div>X</div>
    <div>C</div>
    <div>V</div>
    <div>B</div>
    <div>N</div>
    <div>M</div>
    <div><</div>
    <div>></div>
    <div id="shift">Shift</div>
    <div>🌍</div>
    <div>Ctrl</div>
    <div>Option</div>
    <div>alt</div>
    <div id="space">Space</div>
    <div>alt</div>
    <div>option</div>
    <div>←</div>
    <div>→</div>
 </div>  
</body>
</html>
