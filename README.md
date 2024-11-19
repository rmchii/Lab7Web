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

![Screenshot (404)](https://github.com/user-attachments/assets/50a9c0f5-378d-493c-ba29-60ebc3c3fc63)

![Screenshot (405)](https://github.com/user-attachments/assets/f24869ea-345b-467c-b5c9-2466df51b0d9)

Menambahkan variable pada program.
?>
    <h1>Menggunakan Variable</h1>
    <?php
        $nim = "312310004";
        $nama = 'SUCI MAOLIA';
        echo "NIM : " . $nim . "<br>";
        echo "Nama : $nama";
    ?>
![Screenshot (406)](https://github.com/user-attachments/assets/8e417a0d-a934-4f01-92ee-caa66b026ef4)

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

![Screenshot (409)](https://github.com/user-attachments/assets/c9f39ac5-8827-45ac-bd7e-0a2b86d4e2ae)

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

![Screenshot (410)](https://github.com/user-attachments/assets/81d78354-a98f-4bd2-8a9e-8c2277eac021)

operator
<?php
       $gaji = 1000000;
       $pajak = 0.1;
       $thp = $gaji - ($gaji*$pajak);
       echo "Gaji sebelum pajak = Rp. $gaji <br>";
       echo "Gaji yang dibawa pulang = Rp. $thp";
    ?>
![Screenshot (411)](https://github.com/user-attachments/assets/7fabc92a-d189-4302-a386-0574afa36a5b)

kondisi IF
<?php
    $nama_hari = date("l");
    if ($nama_hari == "Sunday") {
        echo "Minggu";
    } elseif ($nama_hari == "Monday") {
        echo "Senin";
    } else {
        echo "Selasa";
}
?>
![Screenshot (412)](https://github.com/user-attachments/assets/b18ed485-28b8-4c52-93cd-a32c3bde192e)

kondisi switch
<?php
    $nama_hari = date("l");
    switch ($nama_hari) {
        case "Sunday":
            echo "Minggu";
            break;
        case "Monday":
            echo "Senin";
            break;
        case "Tuesday":
            echo "Selasa";
            break;
        default:
            echo "Sabtu";
    }
    ?>
![Screenshot (412)](https://github.com/user-attachments/assets/35b39d2a-71be-45be-9c89-d0ed51bb967d)

perulangan for
<?php
echo "Perulangan 1 sampai 10 <br />";
for ($i=1; $i<=10; $i++) {
    echo "Perulangan ke: " . $i . '<br />';
}
echo "Perulangan Menurun dari 10 ke 1 <br />";
for ($i=10; $i>=1; $i--) {
    echo "Perulangan ke: " . $i . '<br />';
}
?>
![Screenshot (413)](https://github.com/user-attachments/assets/2a2130e5-2d40-4125-aeec-a4b54e35c64e)

perulangan while
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
while ($i<=10) {
    echo "Perulangan ke: " . $i . '<br />';
    $i++;
}
?>
![Screenshot (414)](https://github.com/user-attachments/assets/2a437ac1-e8e1-4a79-a6e7-23bc1deec85f)

perulangan dowhile
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
do {
    echo "Perulangan ke: " . $i . '<br />';
    $i++;
} while ($i<=10);
?>
![Screenshot (415)](https://github.com/user-attachments/assets/dba76193-d3d5-4666-8721-fb3d3bb5ba8e)


