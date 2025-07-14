# reservasi-klinik
<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Reservasi Klinik</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>
    <div class="container">
        <h1>Reservasi Klinik</h1>
        <form id="formReservasi">
            <input type="text" id="nama" placeholder="Nama Pasien" required />
            <select id="gender" required>
        <option value="">-- Jenis Kelamin --</option>
        <option value="Laki-laki">Laki-laki</option>
        <option value="Perempuan">Perempuan</option>
      </select>
            <select id="layanan" required>
        <option value="">-- Pilih Layanan --</option>
        <option value="Umum">Umum</option>
        <option value="Gigi">Gigi</option>
        <option value="Spesialis">Spesialis</option>
      </select>
            <input type="date" id="tanggal" required />
            <button type="submit">Tambah Reservasi</button>
        </form>

        <h2>Daftar Reservasi</h2>
        <table id="tabelReservasi">
            <thead>
                <tr>
                    <th>No</th>
                    <th>Nama</th>
                    <th>JK</th>
                    <th>Layanan</th>
                    <th>Tanggal</th>
                    <th>Aksi</th>
                </tr>
            </thead>
            <tbody></tbody>
        </table>
    </div>

    <script src="script.js"></script>
</body>

</html>
