# Website Dinamis 

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Dinamis</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    .container {
      padding: 20px;
    }
    input, button {
      padding: 10px;
      margin: 10px;
    }
    .output {
      margin-top: 20px;
      font-weight: bold;
      color: #007BFF;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Website Dinamis</h1>
    <p>Masukkan nama Anda:</p>
    <input type="text" id="inputNama" placeholder="Nama Anda">
    <button onclick="tampilkanNama()">Tampilkan</button>
    <div class="output" id="output"></div>
  </div>

  <script>
    function tampilkanNama() {
      const inputNama = document.getElementById("inputNama").value;
      const output = document.getElementById("output");

      if (inputNama) {
        output.textContent = `Halo, ${inputNama}! Selamat datang di website kami.`;
      } else {
        output.textContent = "Silakan masukkan nama Anda!";
      }
    }
  </script>
</body>
</html>




