Percobaan
=========
<html>
  <head>
		<title>Registrasi Data CV</title>
	</head>

	<body>
		<h2>Form CV</h2>
		<form action="" method="POST">
			<label>Nama: </label>
			<input type="text" size="30" name="nama"><br>
			<label>Nickname: </label>
			<input type="text" size="16" name="uname" maxlength="16"><br>
			<label>TTL: </label>
			<input type="text" size="16" name="pass" maxlength="16"><br>
			<label>Jenis Kelamin: </label>
			<input type="radio" name="jk" value="pria" checked><span> Pria</span>
			<input type="radio" name="jk" value="wanita"><span> Wanita</span>
			<br>
			<label>Alamat: </label>
			<input type="text" size="35" name="pass" maxlength="16"><br>
			<label>Deskripsikan diri anda: <label><br>
			<textarea style="height:100px;width:500px" name="desc"></textarea>
			<hr><br>
			<label>Jabatan apa yang anda harapkan di perusahaan ini?</label><br>
			<select name="dengar">
			<option value="Front Officer">Front Officer</option>
			<option value="Drill Technician">Drill Technician</option>
			<option value="Machine Operator">Machine Operator</option>
			<option value="Contractor">Contractor</option>
			</select><br>
			<input type="submit" value="SUBMIT">
			<input type="reset" value="RESET">
		</form>
	</body>
</html>

		
		
