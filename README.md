# Lab7Web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
    echo "Hello World";
    ?>
</body>
</html>

Menambahkan variable pada program.
?>
    <h1>Menggunakan Variable</h1>
    <?php
        $nim = "312310004";
        $nama = 'SUCI MAOLIA';
        echo "NIM : " . $nim . "<br>";
        echo "Nama : $nama";
    ?>
    
predenfine variable $_GET
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Predefine Variable</h1>
<?php
echo 'Selamat Datang ' . $_GET['nama'];
?>

membuat form input
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
<h2>Form Input</h2>
<form method="post">
    <label>Nama: </label>
    <input type="text" name="nama">
    <input type="submit" value="Kirim">
</form>
<?php
echo 'Selamat Datang ' . $_GET['nama'];
?>


