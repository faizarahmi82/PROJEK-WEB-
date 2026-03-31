<!DOCTYPE html>
<html>
<body>

<h3>Masukkan Nilai:</h3>

<input type="number" id="nilaiInput">
<button onclick="Proses()">Proses</button>

<p id="hasil"></p>

<script>
function Proses() {
    let nilai = document.getElementById("nilaiInput").value;
    let hasil = "";

    if (nilai >= 90) {
        hasil = "A";
    } else if (nilai >= 75) {
        hasil = "B";
    } else if (nilai >= 60) {
        hasil = "C";
    } else {
        hasil = "D";
    }

    document.getElementById("hasil").innerHTML = hasil;
}
</script>

</body>
</html>
</html>
