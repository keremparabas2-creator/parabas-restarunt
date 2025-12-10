# parabas-restarunt[parabas restaurant html.txt](https://github.com/user-attachments/files/24082921/parabas.restaurant.html.txt)
<!DOCTYPE html>
<html>
<head>
<title>Benim Oyun Sitem</title>
<style>
    body { background:#222; color:white; font-family:Arial; text-align:center; }
    button { padding:15px; font-size:20px; margin:10px; }
</style>
</head>
<body>

<h1>Mini Savaş Oyunu</h1>
<p>Rakibe saldırabilmek için butona tıkla!</p>

<button onclick="saldir()">Saldır</button>
<p id="sonuc"></p>

<script>
function saldir() {
    let sans = Math.random();
    if(sans > 0.5){
        document.getElementById("sonuc").innerHTML = "Kazandın!";
    } else {
        document.getElementById("sonuc").innerHTML = "Kaybettin!";
    }
}
</script>

</body>
</html>
