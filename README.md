# Virtual-lab-kimia
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Virtual Lab Kimia</title>
<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f0f7ff;
  color: #183153;
}
header {
  background: #145da0;
  color: white;
  padding: 24px;
  text-align: center;
}
main { padding: 18px; max-width: 1000px; margin: auto; }
section {
  background: white;
  padding: 18px;
  margin: 16px 0;
  border-radius: 12px;
}
iframe { width: 100%; height: 520px; border: 0; }
input, textarea, button {
  padding: 10px; margin: 5px 0; max-width: 100%;
}
textarea { width: 95%; }
button {
  background: #145da0; color: white;
  border: 0; border-radius: 6px;
}
</style>
</head>
<body>
<header>
  <h1>Virtual Lab Kimia</h1>
  <p>Eksperimen Konsentrasi Larutan</p>
</header>
<main>
<section>
  <h2>1. Tujuan Praktikum</h2>
  <p>Memahami pengaruh jumlah zat terlarut
  dan volume larutan terhadap konsentrasi.</p>
</section>

<section>
  <h2>2. Dasar Teori</h2>
  <p>Konsentrasi molar menyatakan jumlah mol zat
  terlarut dalam setiap liter larutan.</p>
  <p><b>M = n / V</b></p>
  <p>M = molaritas (mol/L), n = jumlah mol,
  V = volume larutan (L).</p>
</section>

<section>
  <h2>3. Laboratorium Virtual PhET</h2>
  <p>Ubah jumlah zat terlarut dan volume,
  lalu amati perubahan konsentrasi.</p>
  <iframe
    src="https://phet.colorado.edu/sims/html/concentration/latest/concentration_en.html"
    title="Simulasi Konsentrasi Larutan PhET"
    allowfullscreen>
  </iframe>
  <p>Jika simulasi tidak tampil,
  <a href="https://phet.colorado.edu/en/simulations/concentration"
  target="_blank">buka PhET di tab baru</a>.</p>
</section>

<section>
  <h2>4. Lembar Kerja Praktikum</h2>
  <p>Catat hasil yang benar-benar kamu amati.</p>
  <label>Jumlah zat terlarut (mol)</label><br>
  <input id="mol" type="number" min="0"
  step="any" placeholder="Contoh: 0.2"><br>
  <label>Volume larutan (L)</label><br>
  <input id="vol" type="number" min="0"
  step="any" placeholder="Contoh: 0.5"><br>
  <button onclick="hitung()">Hitung Molaritas</button>
  <p id="hasil"></p>
  <label>Pengamatan dan kesimpulan</label><br>
  <textarea id="catatan" rows="4"
  placeholder="Tuliskan hasil eksperimen..."></textarea>
</section>

<section>
  <h2>5. Evaluasi</h2>
  <p>Jika 0,2 mol zat terlarut terdapat dalam
  0,5 L larutan, berapakah molaritasnya?</p>
  <button onclick="jawab('a')">A. 0,1 M</button>
  <button onclick="jawab('b')">B. 0,4 M</button>
  <button onclick="jawab('c')">C. 2,5 M</button>
  <p id="nilai"></p>
</section>
</main>

<script>
function hitung() {
  const n = Number(document.getElementById('mol').value);
  const v = Number(document.getElementById('vol').value);
  const out = document.getElementById('hasil');
  if (document.getElementById('mol').value === '' ||
      document.getElementById('vol').value === '' ||
      !Number.isFinite(n) || !Number.isFinite(v) ||
      n < 0 || v <= 0) {
    out.textContent = 'Masukkan mol ≥ 0 dan volume > 0.';
    return;
  }
  out.textContent = 'Molaritas = ' + (n / v).toFixed(3) + ' M';
}
function jawab(p) {
  document.getElementById('nilai').textContent =
    p === 'b' ? 'Benar! M = 0,2 / 0,5 = 0,4 M.'
    : 'Belum tepat. Gunakan rumus M = n / V.';
}
</script>
</body>
</html>
