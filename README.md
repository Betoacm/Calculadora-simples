# Personal
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Logica de programacao Javascript</title>
</head>
<body>
    <h1>Lógica de programação</h1>

    <button onclick="somar()">+</button>
    <button onclick="subtrair()">-</button>
    <button onclick="multiplicar()">*</button>
    <button onclick="dividir()">/</button>
    
    <div id ='output'></div>

    <script>

       var n1 = prompt('digite um numero');
        n1 = parseFloat(n1)
        escreve();


        function escreve(){
            var output = document.querySelector('#output');
            output.innerHTML = n1;
        }
      
        function somar(){
            var n = prompt('digite outro numero');
            n = parseFloat(n);
            //n1 = n1 + n;
            n1 += n;
            escreve()
        }
        function subtrair(){
            var n = prompt('digite outro numero');
            n = parseFloat(n);
            //n1 = n1 - n;
            n1 -= n;
            escreve()
        }
        function multiplicar(){
            var n = prompt('digite outro numero');
            n = parseFloat(n);
            //n1 = n1 * n;
            n1 *= n;
            escreve()
        }
        function dividir(){
            var n = prompt('digite outro numero');
            n = parseFloat(n);
            //n1 = n1 / n;
            n1 /= n;
            escreve()
        }
    </script>

    
</body>
</html>
