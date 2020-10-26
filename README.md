# TUGAS1-KALKULATOR
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUGAS1-KALKULATOR</title>
</head>
<body>
    <input type="number" id="angka1">
    <input type="number" id="angka2">
    <button onclick="hitungtambah()">Hitung!</button>
    <br/>
    <p id="hasiloutput"></p>
    <script>
        function hitungtambah(){
            var angka1= document.getElementById('angka1').value;
            var angka2= document.getElementById('angka2').value;
            var hasil = parseInt(angka1) + parseInt(angka2);
            document.getElementById('hasiloutput').innerHTML = hasil;
        }
    </script>
</body>
</html># TUGAS1-KALKULATOR
