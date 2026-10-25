<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Virtual Lab Kimia untuk mempelajari konsentrasi dan molaritas larutan menggunakan simulasi PhET.">
<title>Virtual Lab Kimia | Konsentrasi Larutan</title>
<style>
:root{--blue:#145da0;--navy:#183153;--pale:#edf6ff;--teal:#dff7f2;--line:#d7e2ef;--white:#fff;--muted:#5d6b7b}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:#f4f8fc;color:var(--navy);font:16px/1.6 Arial,Helvetica,sans-serif}
header{background:linear-gradient(130deg,#124b82,#168aad);color:#fff;padding:36px 18px 28px}
.hero,.wrap{max-width:1100px;margin:auto}.eyebrow{letter-spacing:.12em;font-size:.78rem;font-weight:bold;color:#d5edff}
h1{font-size:clamp(2rem,5vw,3.2rem);line-height:1.12;margin:.35em 0}header p{max-width:700px}
nav{position:sticky;top:0;z-index:10;background:#fff;border-bottom:1px solid var(--line);display:flex;gap:8px;overflow:auto;padding:10px max(12px,calc((100vw - 1100px)/2))}
nav a{white-space:nowrap;text-decoration:none;color:var(--blue);font-weight:bold;padding:8px 11px;border-radius:8px}nav a:hover{background:var(--pale)}
.wrap{padding:18px}.card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:20px;margin:18px 0;box-shadow:0 4px 14px #1831530a}
h2{margin:.1em 0 .5em;font-size:1.55rem}h3{margin-bottom:.35em}p{margin:.55em 0}.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}
.tile{background:var(--pale);border-radius:12px;padding:16px}.muted,small{color:var(--muted)}
button,.button{display:inline-block;background:var(--blue);color:white;border:0;border-radius:9px;padding:11px 15px;font-weight:bold;cursor:pointer;text-decoration:none;font-size:1rem}
button:hover,.button:hover{filter:brightness(.92)}button.secondary{background:#e5eef8;color:var(--navy)}button.danger{background:#9b2c2c}
input,select,textarea{width:100%;max-width:100%;padding:11px;border:1px solid #aebfd1;border-radius:8px;font:inherit;background:white;color:var(--navy)}
label{font-weight:bold;display:block;margin:10px 0 4px}iframe{width:100%;height:clamp(360px,65vw,650px);border:0;border-radius:12px;background:#f1f5f9}
.actions{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}.formula{font-size:1.35rem;font-weight:bold;background:var(--teal);padding:14px;border-radius:10px;display:inline-block}
table{border-collapse:collapse;width:100%;margin:12px 0;font-size:.95rem}th,td{border:1px solid var(--line);padding:9px;text-align:left}th{background:var(--pale)}.table-wrap{overflow-x:auto}
.notice{border-left:4px solid #e0a126;padding:10px 14px;background:#fff8e7;border-radius:5px}
.result{font-weight:bold;padding:12px;background:var(--pale);border-radius:8px;min-height:42px;margin-top:10px}
.question{padding:14px;border:1px solid var(--line);border-radius:12px;margin:12px 0}.question label{font-weight:normal;display:flex;align-items:flex-start;gap:8px}.question input{width:auto;margin-top:6px}
footer{background:#153b60;color:#fff;padding:24px;text-align:center;margin-top:28px}
@media(max-width:700px){.grid{grid-template-columns:1fr}.card{padding:15px}.wrap{padding:12px}nav a{font-size:.9rem}}
@media print{nav,.actions,button,iframe{display:none!important}body{background:white}.card{box-shadow:none;break-inside:avoid}}
</style>
</head>
<body>
<header>
  <div class="hero">
    <div class="eyebrow">PEMBELAJARAN KIMIA • LABORATORIUM VIRTUAL</div>
    <h1>Virtual Lab: Konsentrasi Larutan</h1>
    <p>Jelajahi hubungan jumlah zat terlarut, volume larutan, dan molaritas melalui simulasi PhET, kalkulator, lembar kerja, dan evaluasi mandiri.</p>
    <a class="button" href="#lab">Mulai Eksperimen</a>
  </div>
</header>
<nav aria-label="Navigasi utama">
  <a href="#tujuan">Tujuan</a><a href="#materi">Materi</a><a href="#video">Video</a><a href="#lab">Simulasi PhET</a><a href="#kalkulator">Kalkulator</a><a href="#lkpd">LKPD</a><a href="#kuis">Kuis</a>
</nav>
<main class="wrap">
<section class="card" id="tujuan">
  <h2>1. Tujuan Pembelajaran</h2>
  <ul>
    <li>Menjelaskan zat terlarut, pelarut, larutan, dan konsentrasi.</li>
    <li>Menghitung molaritas dengan satuan mol/L atau M.</li>
    <li>Menganalisis pengaruh perubahan jumlah mol dan volume terhadap molaritas.</li>
    <li>Mencatat hasil simulasi dan menyusun kesimpulan berdasarkan bukti.</li>
  </ul>
  <div class="grid">
    <div class="tile"><b>Waktu yang disarankan</b><br>40–60 menit</div>
    <div class="tile"><b>Peralatan</b><br>Browser dan koneksi internet</div>
  </div>
</section>

<section class="card" id="materi">
  <h2>2. Materi Singkat</h2>
  <h3>Konsep dasar</h3>
  <p><b>Zat terlarut</b> adalah zat yang dilarutkan. <b>Pelarut</b> adalah zat yang melarutkan. Campuran homogen yang terbentuk disebut <b>larutan</b>.</p>
  <p>Molaritas menyatakan jumlah mol zat terlarut dalam setiap liter larutan.</p>
  <div class="formula">M = n / V</div>
  <ul>
    <li><b>M</b> = molaritas (mol/L atau M)</li>
    <li><b>n</b> = jumlah zat terlarut (mol)</li>
    <li><b>V</b> = volume akhir larutan (L)</li>
  </ul>
  <h3>Hubungan yang perlu diuji</h3>
  <ul>
    <li>Jika jumlah mol naik sementara volume tetap, molaritas naik.</li>
    <li>Jika volume naik sementara jumlah mol tetap, molaritas turun.</li>
    <li>Warna larutan pada simulasi dapat membantu membandingkan konsentrasi, tetapi warna bukan pengukuran universal untuk semua zat.</li>
    <li>Jika larutan mencapai batas kelarutan, penambahan zat terlarut tidak selalu meningkatkan jumlah zat yang larut.</li>
  </ul>
  <div class="notice">Penting: gunakan volume larutan dalam liter (L), bukan mililiter (mL). Konversi: 1000 mL = 1 L.</div>
</section>

<section class="card" id="video">
  <h2>3. Video Pembelajaran</h2>
  <p>Tonton video pengantar tentang molaritas atau konsentrasi larutan. Video di bawah menggunakan pencarian YouTube agar guru dapat memilih video yang paling sesuai dengan kurikulum.</p>
  <div class="actions">
    <a class="button" target="_blank" rel="noopener" href="https://www.youtube.com/results?search_query=molaritas+konsentrasi+larutan+kimia+SMA">Cari video: Molaritas dan Konsentrasi</a>
    <a class="button secondary" target="_blank" rel="noopener" href="https://phet.colorado.edu/in/simulations/concentration">Buka laman resmi PhET</a>
  </div>
  <p class="muted">Untuk menampilkan video tertentu di halaman ini, guru dapat mengganti area ini dengan kode embed resmi video yang dipilih dan diizinkan untuk disematkan.</p>
</section>

<section class="card" id="lab">
  <h2>4. Laboratorium Virtual PhET</h2>
  <p><b>Petunjuk:</b> pilih zat terlarut yang tersedia, ubah jumlah zat dan volume sesuai kontrol simulasi, lalu amati indikator konsentrasi. Catat hasil aktual yang ditampilkan PhET pada LKPD.</p>
  <iframe src="https://phet.colorado.edu/sims/html/concentration/latest/concentration_en.html" title="Simulasi PhET Concentration" loading="lazy" allowfullscreen></iframe>
  <div class="actions">
    <a class="button" href="https://phet.colorado.edu/sims/html/concentration/latest/concentration_en.html" target="_blank" rel="noopener">Buka PhET di tab baru</a>
    <a class="button secondary" href="https://phet.colorado.edu/sims/html/molarity/latest/molarity_en.html" target="_blank" rel="noopener">Buka simulasi Molarity</a>
  </div>
  <p class="muted">Jika simulasi tidak muncul di dalam halaman, gunakan tombol untuk membukanya di tab baru. Koneksi internet diperlukan. Simulasi PhET merupakan layanan eksternal dan tidak mengirim data percobaan ke LKPD website ini secara otomatis.</p>
</section>

<section class="card" id="kalkulator">
  <h2>5. Kalkulator Molaritas</h2>
  <p>Masukkan jumlah mol zat terlarut dan volume akhir larutan. Kalkulator ini menghitung berdasarkan rumus M = n/V.</p>
  <div class="grid">
    <div><label for="mol">Jumlah zat terlarut (mol)</label><input id="mol" type="number" min="0" step="any" placeholder="Contoh: 0.2"></div>
    <div><label for="volume">Volume akhir larutan (L)</label><input id="volume" type="number" min="0.000001" step="any" placeholder="Contoh: 0.5"></div>
  </div>
  <div class="actions"><button type="button" onclick="hitungMolaritas()">Hitung molaritas</button><button class="secondary" type="button" onclick="resetKalkulator()">Reset</button></div>
  <div id="hasilHitung" class="result" aria-live="polite">Hasil perhitungan akan tampil di sini.</div>
  <p><b>Contoh:</b> 0,20 mol dalam 0,50 L larutan menghasilkan M = 0,20/0,50 = 0,40 M.</p>
</section>

<section class="card" id="lkpd">
  <h2>6. LKPD — Lembar Kerja Peserta Didik</h2>
  <p><b>Nama:</b> catat identitas seperlunya sesuai arahan guru. <b>Kelas:</b> tuliskan kelas. Lakukan percobaan dengan mengubah satu variabel setiap kali agar hubungan sebab-akibat lebih mudah dianalisis.</p>
  <div class="grid">
    <div><label for="nama">Nama peserta didik</label><input id="nama" type="text" placeholder="Nama"></div>
    <div><label for="kelas">Kelas</label><input id="kelas" type="text" placeholder="Contoh: XI IPA 1"></div>
  </div>
  <h3>Rumusan masalah</h3>
  <p>Bagaimana perubahan jumlah zat terlarut atau volume larutan memengaruhi konsentrasi?</p>
  <h3>Hipotesis</h3>
  <label for="hipotesis">Tuliskan prediksi sebelum melakukan percobaan</label>
  <textarea id="hipotesis" rows="3" placeholder="Menurut saya, jika ... maka ... karena ..."></textarea>
  <h3>Tabel pengamatan</h3>
  <p>Isi data berdasarkan hasil yang benar-benar ditampilkan simulasi. Satuan dan jenis zat terlarut harus dicatat. Jika simulasi tidak menunjukkan mol secara langsung, jangan menebak nilai mol; catat indikator yang tersedia dan jelaskan keterbatasannya.</p>
  <div class="table-wrap">
    <table id="tabelPengamatan">
      <thead><tr><th>No.</th><th>Zat terlarut</th><th>Jumlah mol (jika tersedia)</th><th>Volume larutan (L)</th><th>Konsentrasi yang ditampilkan</th><th>Warna/observasi</th></tr></thead>
      <tbody>
        <tr><td>1</td><td><input aria-label="Zat terlarut baris 1"></td><td><input type="number" min="0" step="any" aria-label="Mol baris 1"></td><td><input type="number" min="0" step="any" aria-label="Volume baris 1"></td><td><input aria-label="Konsentrasi baris 1"></td><td><input aria-label="Observasi baris 1"></td></tr>
        <tr><td>2</td><td><input aria-label="Zat terlarut baris 2"></td><td><input type="number" min="0" step="any" aria-label="Mol baris 2"></td><td><input type="number" min="0" step="any" aria-label="Volume baris 2"></td><td><input aria-label="Konsentrasi baris 2"></td><td><input aria-label="Observasi baris 2"></td></tr>
        <tr><td>3</td><td><input aria-label="Zat terlarut baris 3"></td><td><input type="number" min="0" step="any" aria-label="Mol baris 3"></td><td><input type="number" min="0" step="any" aria-label="Volume baris 3"></td><td><input aria-label="Konsentrasi baris 3"></td><td><input aria-label="Observasi baris 3"></td></tr>
      </tbody>
    </table>
  </div>
  <div class="actions"><button type="button" onclick="tambahBaris()">Tambah baris pengamatan</button><button type="button" onclick="unduhLKPD()">Unduh LKPD (.csv)</button><button type="button" class="secondary" onclick="window.print()">Cetak / Simpan PDF</button></div>
  <label for="analisis">Analisis hasil</label><textarea id="analisis" rows="4" placeholder="Bandingkan hasil percobaan. Variabel apa yang diubah? Apa yang tetap?"></textarea>
  <label for="kesimpulan">Kesimpulan</label><textarea id="kesimpulan" rows="4" placeholder="Jawab rumusan masalah berdasarkan data pengamatan."></textarea>
  <p class="muted">Unduhan CSV berisi data yang kamu isi di tabel dan catatan LKPD. Data hanya diolah di browser pada perangkat ini.</p>
</section>

<section class="card" id="kuis">
  <h2>7. Kuis Pemahaman</h2>
  <p>Pilih satu jawaban untuk setiap soal, lalu tekan “Periksa jawaban”.</p>
  <form id="formKuis">
    <div class="question"><b>1. Rumus molaritas adalah ...</b>
      <label><input type="radio" name="q1" value="a"> M = V/n</label>
      <label><input type="radio" name="q1" value="b"> M = n/V</label>
      <label><input type="radio" name="q1" value="c"> M = n × V</label>
      <label><input type="radio" name="q1" value="d"> M = n + V</label>
    </div>
    <div class="question"><b>2. Sebanyak 0,30 mol zat terlarut dibuat menjadi 0,60 L larutan. Molaritasnya adalah ...</b>
      <label><input type="radio" name="q2" value="a"> 0,18 M</label>
      <label><input type="radio" name="q2" value="b"> 0,30 M</label>
      <label><input type="radio" name="q2" value="c"> 0,50 M</label>
      <label><input type="radio" name="q2" value="d"> 2,00 M</label>
    </div>
    <div class="question"><b>3. Jika jumlah mol tetap dan volume larutan diperbesar, molaritas akan ...</b>
      <label><input type="radio" name="q3" value="a"> Meningkat</label>
      <label><input type="radio" name="q3" value="b"> Menurun</label>
      <label><input type="radio" name="q3" value="c"> Selalu tetap</label>
      <label><input type="radio" name="q3" value="d"> Selalu menjadi nol</label>
    </div>
    <div class="question"><b>4. Sebelum memasukkan volume ke rumus M = n/V, volume harus dinyatakan dalam ...</b>
      <label><input type="radio" name="q4" value="a"> Liter</label>
      <label><input type="radio" name="q4" value="b"> Gram</label>
      <label><input type="radio" name="q4" value="c"> Derajat Celsius</label>
      <label><input type="radio" name="q4" value="d"> Meter</label>
    </div>
    <div class="question"><b>5. Cara yang tepat menguji pengaruh jumlah mol terhadap molaritas adalah ...</b>
      <label><input type="radio" name="q5" value="a"> Mengubah mol dan volume sekaligus tanpa mencatat perubahan</label>
      <label><input type="radio" name="q5" value="b"> Menjaga volume tetap dan mengubah jumlah mol</label>
      <label><input type="radio" name="q5" value="c"> Mengubah zat, volume, dan mol setiap saat tanpa kontrol</label>
      <label><input type="radio" name="q5" value="d"> Mengamati warna saja tanpa mencatat variabel</label>
    </div>
    <button type="button" onclick="periksaKuis()">Periksa jawaban</button>
    <button type="reset" class="secondary" onclick="document.getElementById('hasilKuis').textContent='Jawaban direset.'">Reset kuis</button>
  </form>
  <div class="result" id="hasilKuis" aria-live="polite">Nilai dan umpan balik akan muncul di sini.</div>
</section>

<section class="card">
  <h2>8. Refleksi</h2>
  <label for="refleksi">Apa temuan paling penting dari eksperimen ini? Apa keterbatasan simulasi atau data yang kamu gunakan?</label>
  <textarea id="refleksi" rows="4" placeholder="Tuliskan refleksi singkat..."></textarea>
  <div class="actions"><button onclick="unduhLKPD()" type="button">Unduh data LKPD</button><button class="secondary" type="button" onclick="window.print()">Cetak halaman</button></div>
</section>

<section class="card">
  <h2>Referensi</h2>
  <ul>
    <li><a href="https://phet.colorado.edu/in/simulations/concentration" target="_blank" rel="noopener">PhET — Concentration</a></li>
    <li><a href="https://phet.colorado.edu/en/simulations/molarity" target="_blank" rel="noopener">PhET — Molarity</a></li>
  </ul>
  <p class="muted">Simulasi PhET disediakan oleh University of Colorado Boulder. Website ini adalah bahan pembelajaran pendamping, bukan produk resmi PhET.</p>
</section>
</main>
<footer><b>Virtual Lab Kimia: Konsentrasi Larutan</b><br>Belajar sains melalui eksplorasi dan bukti.</footer>
<script>
function hitungMolaritas(){
 const ns=document.getElementById('mol').value, vs=document.getElementById('volume').value;
 const out=document.getElementById('hasilHitung');
 const n=Number(ns), v=Number(vs);
 if(ns===''||vs===''||!Number.isFinite(n)||!Number.isFinite(v)||n<0||v<=0){
   out.textContent='Masukkan jumlah mol ≥ 0 dan volume larutan > 0 L.';return;
 }
 out.textContent='Molaritas = '+n+' mol / '+v+' L = '+(n/v).toLocaleString('id-ID',{maximumFractionDigits:5})+' M';
}
function resetKalkulator(){document.getElementById('mol').value='';document.getElementById('volume').value='';document.getElementById('hasilHitung').textContent='Hasil perhitungan akan tampil di sini.';}
function periksaKuis(){
 const kunci={q1:'b',q2:'c',q3:'b',q4:'a',q5:'b'};
 const penjelasan=[
  'Molaritas adalah jumlah mol zat terlarut dibagi volume larutan dalam liter.',
  'M = 0,30 mol / 0,60 L = 0,50 M.',
  'Dengan jumlah mol tetap, volume yang lebih besar menghasilkan molaritas lebih kecil.',
  'Satuan volume pada rumus molaritas adalah liter.',
  'Mengubah satu variabel dan menjaga variabel lain tetap membantu menguji pengaruhnya.'
 ];
 let skor=0, belum=[];
 Object.keys(kunci).forEach((q,i)=>{
  const pilih=document.querySelector('input[name="'+q+'"]:checked');
  if(!pilih) belum.push(i+1);
  else if(pilih.value===kunci[q]) skor++;
 });
 const out=document.getElementById('hasilKuis');
 if(belum.length){out.textContent='Jawab semua soal terlebih dahulu. Belum dijawab: '+belum.join(', ')+'.';return;}
 out.textContent='Nilai: '+skor+'/5 ('+(skor*20)+'%). '+(skor===5?'Hebat, semua jawaban benar.':'Baca umpan balik berikut dan pelajari kembali materi.')+' '+penjelasan.join(' ');
}
function tambahBaris(){
 const tbody=document.querySelector('#tabelPengamatan tbody'), nomor=tbody.rows.length+1;
 const tr=document.createElement('tr');
 const cells=['Zat terlarut','Mol','Volume','Konsentrasi','Observasi'];
 tr.innerHTML='<td>'+nomor+'</td>'+cells.map((c,i)=>'<td><input '+(i===1||i===2?'type="number" min="0" step="any" ':'type="text" ')+'aria-label="'+c+' baris '+nomor+'"></td>').join('');
 tbody.appendChild(tr);
}
function csvEscape(v){return '"'+String(v??'').replace(/"/g,'""')+'"';}
function unduhLKPD(){
 const rows=[['LKPD Virtual Lab Kimia - Konsentrasi Larutan'],['Nama',document.getElementById('nama').value],['Kelas',document.getElementById('kelas').value],['Hipotesis',document.getElementById('hipotesis').value],[],['No','Zat terlarut','Jumlah mol','Volume larutan (L)','Konsentrasi ditampilkan','Warna/observasi']];
 document.querySelectorAll('#tabelPengamatan tbody tr').forEach(tr=>{
  rows.push(Array.from(tr.cells).map((td,i)=>i===0?td.textContent:(td.querySelector('input')?.value||'')));
 });
 rows.push([],['Analisis',document.getElementById('analisis').value],['Kesimpulan',document.getElementById('kesimpulan').value],['Refleksi',document.getElementById('refleksi').value]);
 const csv='\\ufeff'+rows.map(r=>r.map(csvEscape).join(',')).join('\\r\\n');
 const blob=new Blob([csv],{type:'text/csv;charset=utf-8;'});
 const url=URL.createObjectURL(blob), a=document.createElement('a');
 a.href=url;a.download='LKPD_Konsentrasi_Larutan.csv';document.body.appendChild(a);a.click();a.remove();URL.revokeObjectURL(url);
}
</script>
</body>
</html>
