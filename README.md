# class-assignments
<!DOCTYPE html>

<html>
    <head>
        <style>
            input{
                width: 300px;
                font-size: 20px;
            }
            button{
                width: 230px;
                font-size: 20px;
            }
            .button_div{
                margin-top: 10px;
            }
            #container{
                padding: 10px;
                margin: 10px;
            }
        </style>
    </head>

    <body>
        <div id="container">
            <div class="input_div">
                <input placeholder="Enter the value of X" id="num1"/>
                <input placeholder="Enter the value of Y" id="num2"/>
                <input placeholder="Result will appear here" id="res" disabled/>
            </div>

            <div class="button_div">
                <button onclick="">Addition (X + Y)</button>
                <button onclick="">Subtraction (X - Y)</button>
                <button onclick="">Multiplication (X * Y)</button>
                <button onclick="">Division (X / Y)</button>
            </div>            
        </div>

    </body>
</html>