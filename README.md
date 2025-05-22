<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Website Kelas XI TKJ 1</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background-color: #d2b48c;
    }
    header {
      background-color: #228b22;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    section {
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .column {
      width: 45%;
      padding: 10px;
      background-color: lightgrey;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      border-radius: 5px;
      margin-bottom: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }
    th {
      background-color: #708090;
    }
    footer {
      background-color: #228b22;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }
    @media (max-width: 768px) {
      .column {
        width: 90%;
      }
    }

    .btn-hari {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 20px;
      justify-content: center;
    }
    .btn-hari button {
      padding: 10px 15px;
      border: none;
      border-radius: 8px;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .btn-hari button:hover {
      transform: scale(1.05);
    }
    .senin { background: linear-gradient(to right, #ff7e5f, #feb47b); }
    .selasa { background: linear-gradient(to right, #6a11cb, #2575fc); }
    .rabu { background: linear-gradient(to right, #56ab2f, #a8e063); }
    .kamis { background: linear-gradient(to right, #ff9966, #ff5e62); }
    .jumat { background: linear-gradient(to right, #00c9ff, #92fe9d); }
    .sabtu { background: linear-gradient(to right, #f7971e, #ffd200); }
    .semua { background: linear-gradient(to right, #8e2de2, #4a00e0); }
  </style>
</head>
<body>
  <header>
    <h1>Kelas XI TKJ 1</h1>
  </header>

  <section>
    <div class="column">
      <h2>Tentang Kelas</h2>
      <img src="Kelastkj1.jpg" alt="Foto Kelas">
      <p>Deskripsi Kelas: Kelas ini adalah tempat untuk belajar berbagai mata pelajaran dan tempat untuk mengasah skill terkait Teknik Komputer Jaringan (TKJ)</p>
      <h3>Guru Pembimbing</h3>
      <ul>
        <li><strong>Bahasa Indonesia:</strong> Pak Dimas</li>
        <li><strong>MP-Bil:</strong> Pak Dimas</li>
        <li><strong>Agama Islam:</strong> Pak Zainal</li>
        <li><strong>Praktek:</strong> Pak Sigit</li>
        <li><strong>PKK:</strong> Pak Ulil</li>
        <li><strong>Sejarah:</strong> Pak Selamet</li>
        <li><strong>KK-Tkj(1):</strong> Bu Fitria</li>
        <li><strong>KK-Tkj(2):</strong> Bu Yulia</li>
        <li><strong>MP-Tkj:</strong> Bu Yulia</li>
        <li><strong>Matematika:</strong> Bu Rose</li>
        <li><strong>Bahasa Jawa:</strong> Bu Aulia</li>
        <li><strong>Bahasa Inggris:</strong> Bu Laili</li>
        <li><strong>BK:</strong> Bu Lilik</li>
      </ul>
      <h3>Kontak</h3>
      <p><strong>Nama Sekolah:</strong> SMK Antartika Surabaya</p>
      <p><strong>Alamat Sekolah:</strong> Jl. Banyu Urip Kidul Gg.II No.37</p>
      <p><strong>Nomor Telepon:</strong> (031) 5611101</p>
      <p><strong>Email:</strong> smkantartikasurabaya@gmail.com</p>
      <p><strong>Media Sosial:</strong> IG: @smkantartikasurabaya</p>
      <h1>Pengantar Wali Kelas – Bu Yulia</h1>
    <p>Assalamu’alaikum warahmatullahi wabarakatuh,</p>
    <p>Salam sejahtera untuk kita semua.</p>

    <p>Puji syukur kita panjatkan ke hadirat Tuhan Yang Maha Esa atas limpahan rahmat dan karunia-Nya, sehingga kita semua dapat menjalani tahun ajaran ini dengan penuh semangat dan kebersamaan.</p>

    <p>Saya, Bu Yulia, selaku wali kelas, merasa sangat bersyukur dan bangga dapat mendampingi putra-putri Bapak/Ibu dalam proses belajar dan tumbuh bersama selama satu tahun ini. Setiap hari adalah kesempatan untuk belajar, tidak hanya bagi siswa, tetapi juga bagi saya pribadi sebagai pendidik.</p>

    <p>Saya menyaksikan banyak hal luar biasa yang tumbuh dari anak-anak kita—semangat, kerja keras, rasa ingin tahu, serta persahabatan yang tulus. Semua ini menjadi kenangan berharga yang akan terus melekat di hati kita semua.</p>

    <p>Terima kasih kepada para orang tua atas dukungan dan kerja samanya selama ini. Semoga apa yang telah kita upayakan bersama membawa hasil terbaik dan menjadi bekal berharga bagi masa depan anak-anak.</p>

    <p>Akhir kata, mari terus kita jalin komunikasi dan kerja sama demi pendidikan yang lebih baik. Semoga Allah SWT senantiasa memberikan keberkahan dan perlindungan bagi kita semua.</p>

    <p>Wassalamu’alaikum warahmatullahi wabarakatuh.</p>
    
    <img src="walikelas.jpg" alt="Foto Wali Kelas">
    </div>

    <div class="column">
      <h2>Jadwal Pelajaran Kelas XI TKJ1</h2>

      <div class="btn-hari">
        <button class="senin" onclick="filterHari('Senin')">Senin</button>
        <button class="selasa" onclick="filterHari('Selasa')">Selasa</button>
        <button class="rabu" onclick="filterHari('Rabu')">Rabu</button>
        <button class="kamis" onclick="filterHari('Kamis')">Kamis</button>
        <button class="jumat" onclick="filterHari('Jumat')">Jumat</button>
        <button class="sabtu" onclick="filterHari('Sabtu')">Sabtu</button>
        <button class="semua" onclick="filterHari('')">Tampilkan semua</button>
      </div>

      <table id="jadwal">
        <thead>
          <tr>
            <th>Hari</th>
            <th>Jam</th>
            <th>Mata Pelajaran</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Senin</td><td>13.00-14.00</td><td>KK-TKJ(1)</td></tr>
          <tr><td></td><td>14.00-15.00</td><td>PKK</td></tr>
          <tr><td></td><td>15.00-15.30</td><td>Istirahat</td></tr>
          <tr><td></td><td>15.30-16.30</td><td>KK-TKJ</td></tr>
          <tr><td></td><td>16.30-17.00</td><td>Matematika</td></tr>
          <tr><td>Selasa</td><td>13.00-14.00</td><td>KK-TKJ</td></tr>
          <tr><td></td><td>14.00-15.00</td><td>Sejarah</td></tr>
          <tr><td></td><td>15.00-15.30</td><td>Istirahat</td></tr>
          <tr><td></td><td>15.30-16.30</td><td>KK-TKJ</td></tr>
          <tr><td></td><td>16.30-16.45</td><td>Matematika</td></tr>
          <tr><td></td><td>16.45-17.00</td><td>BK</td></tr>
          <tr><td>Rabu</td><td>13.00-14.00</td><td>B. Inggris</td></tr>
          <tr><td></td><td>14.00-15.00</td><td>B. Indo</td></tr>
          <tr><td></td><td>15.00-15.30</td><td>Istirahat</td></tr>
          <tr><td></td><td>15.30-16.00</td><td>B. Inggris</td></tr>
          <tr><td></td><td>16.00-17.00</td><td>Agama</td></tr>
          <tr><td>Kamis</td><td>13.00-14.00</td><td>PKK</td></tr>
          <tr><td></td><td>14.00-15.00</td><td>KK-TKJ</td></tr>
          <tr><td></td><td>15.00-15.30</td><td>Istirahat</td></tr>
          <tr><td></td><td>15.30-16.30</td><td>PKK</td></tr>
          <tr><td></td><td>16.30-16.45</td><td>Agama</td></tr>
          <tr><td></td><td>16.45-17.00</td><td>MP-TKJ</td></tr>
          <tr><td>Jumat</td><td>08.00-11.00</td><td>Praktek</td></tr>
          <tr><td>Sabtu</td><td>13.00-14.00</td><td>MP-BIL</td></tr>
          <tr><td></td><td>14.00-15.00</td><td>B.Indo</td></tr>
          <tr><td></td><td>15.00-15.30</td><td>Istirahat</td></tr>
          <tr><td></td><td>15.30-16.30</td><td>PKN</td></tr>
          <tr><td></td><td>16.30-17.00</td><td>B. Jawa</td></tr>
        </tbody>
      </table>
    </div>
  </section>

  <footer>
    <p>&copy; 2023 Kelas XI TKJ 1</p>
  </footer>

  <script>
  function filterHari(hari) {
    const rows = document.querySelectorAll("#jadwal tbody tr");
    let currentDay = "";
    rows.forEach(row => {
      const cells = row.querySelectorAll("td");
      if (cells[0].textContent.trim() !== "") {
        currentDay = cells[0].textContent.trim();
      }
      if (!hari || currentDay === hari) {
        row.style.display = "";
      } else {
        row.style.display = "none";
      }
    });
  }
</script>
</body>
</html>
