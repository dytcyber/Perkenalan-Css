# Perkenalan-Css
penggunaan tag style pada html dan pada eksistensi css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">PRODUCT</a></li>
            <li><a href="#">GALLERY</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">MY INVENTORY</a></li>
        </ul>
    </nav>
    
    <section>
        <div>
            <img id="arkademy-class" src="Hidayat.jpeg" alt="Gambar Profile">
        </div>

        <div>
            <h1>NurHidayat Turilah</h1>
            <p>Front End Designer</p>
            <a href="#">Contact</a>
            <a href="#">Resume</a>
        </div>

        <div>
            <div>
                <p>Availability</p>
                <p>Full Time</p>
            </div>
            <div>
                <p>Age</p>
                <p>24</p>
            </div>
            <div>
                <p>Location</p>
                <p>Palu, Indonesia</p>
            </div>
            <div>
                <p>Years Experience</p>
                <p>4 bulan</p>
            </div>
            <div>
                <p>E-mail</p>
                <p>hturilah50@gmail</p>
            </div>
        </div>
    </section>

    <section>
        <form method="#" action="#">
            <div>
            <label>Name</label>
            <input type="text" name="name" placeholder="Masukkan Nama Anda">
            
            </div>
            <div>
                <label>Role</label>
                <input type="text" name="Role">
            </div>
            <div>
                <label>Availability</label>
                <input type="text" name="availability">
            </div>
            <div>
                <label>Age</label>
                <input type="number" name="age">
            </div>
            <div>
                <label>Location</label>
                <input type="text" name="location">
            </div>
            <div>
                <label>Years Experience</label>
                <input type="number" name="years experience">
            </div>
            <div>
                <label>E-mail</label>
                <input type="E-mail" name="E-mail">
            </div>
            <div>
                <input type="submit" name="submit" value="SUBMIT">
            </div>
        </form>
    </section>
</body>
</html>
