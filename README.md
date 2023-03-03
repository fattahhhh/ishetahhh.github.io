<!DOCTYPE html>
<html>
<head>
	<title>Form Registrasi Perpustakaan</title>
	<style>
		body {
			background-color: #F5F5F5;
		}

		form {
			background-color: #ffffff00;
			border: 2px solid #bd2b2b;
			border-radius: 5px;
			padding: 20px;
			margin: 20px auto;
			max-width: 500px;
		}

		h1 {
			text-align: center;
			color: #e40e0e;
		}

		label {
			display: block;
			font-weight: bold;
			margin-bottom: 5px;
		}

		input[type=text], select, textarea {
			width: 100%;
			padding: 12px;
			border: 1px solid #ccc;
			border-radius: 4px;
			box-sizing: border-box;
			margin-bottom: 10px;
		}

		input[type=radio] {
			margin: 0 10px 0 5px;
		}

		input[type=submit] {
			background-color: #ff1e1e8f;
			color: white;
			padding: 12px 20px;
			border: none;
			border-radius: 4px;
			cursor: pointer;
			font-size: 16px;
			margin-top: 10px;
		}

		input[type=submit]:hover {
			background-color: #000000fa;
		}
	</style>
</head>
<body>
	<h1>Form Registrasi Perpustakaan</h1>
	<form>
		<label for="nama">Nama:</label>
		<input type="text" id="nama" name="nama" required>

		<label for="kelas">Kelas dan Jurusan:</label>
		<input type="text" placeholder="Contoh: X Teknik Jaringan Komputer" id="kelas" name="kelas" required>

		<label for="nis">NIS:</label>
		<input type="text" id="nis" name="nis" required>

		<label for="jk">Jenis Kelamin:</label>
		<input type="radio" id="jk" name="jk" value="Laki-laki" required> Laki-laki
		<input type="radio" id="jk" name="jk" value="Perempuan" required> Perempuan

		<label for="asal">Asal Sekolah:</label>
		<input type="text" id="asal" name="asal" required>

		<label for="alamat">Alamat:</label>
		<textarea id="alamat" name="alamat" required></textarea>

		<input type="submit" value="Daftar">
	</form>
</body>
</html>
