### 3D app is made of html,css and javascript
<!DOCTYPE html>
<html lang="en">

<head>

    <title>Cocacola webpage</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">Cocacola</h2>
            </div>
            <div class="menu">
                <ul>
                    <li>
                        <a href="">COKE</a>
                    </li>
                    <li>
                        <a href="">FANTA</a>
                    </li>
                    <li>
                        <a href="">SPRITE</a>
                    </li>
                    <li>
                        <a href="">STONEY</a>
                    </li>
                    <li>
                        <a href="">KREST</a>
                    </li>
                </ul>
            </div>
            <div class="search">
                <input type="srch" type="search" name="" placeholder="type to text">
                <a href="#"><button class="btn">search</button></a>
            </div>
            <div class="content">
                <h1>Cocacola<br><span>Company</span><br>limited</h1>
                <p class="para">Taste the feeling for cocacola zero sugar</p>
                <button class="cn"><a href="#">WElcome</a></button>
                <div class="icon">
                    <a href="#">
                        <ion-icon name="logo-facebook"></ion-icon>
                    </a>
                    <a href="#">
                        <ion-icon name="logo-instagram"></ion-icon>
                    </a>
                    <a href="#">
                        <ion-icon name="logo-Twitter"></ion-icon>
                    </a>
                    <a href="#">
                        <ion-icon name="logo-google"></ion-icon>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <script src="https://www.cocacola.co.uk/brands"></script>
</body>

</html>
css
* {
    margin: 0;
    padding: 0;
}

.main {
    width: 100%;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.5)50%, rgba(0, 0, 0, 0.5)50%), url(co.jpg.webp);
    background-position: center;
    background-size: cover;
    height: 109vh;
}

.navbar {
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon {
    width: 200px;
    float: left;
    height: 70px;
}

.logo {
    color: orange;
    font-size: 35px;
    font-family: Arial;
    padding left: 1px;
    float: left;
    padding top: 10px;
}

.menu {
    width: 400px;
    float: left;
    height: 70px;
}

ul {
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li {
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px
}

ul li a {
    text-decoration: none;
    color: antiquewhite;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover {
    color: brown;
}

.search {
    width: 330px;
    float: left;
    margin-left: 270px;
}

.src {
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px;
    margin-top: 13px;
    color: beige;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom: 5px;
    border-top: 5px;
}

.btn {
    width: 100px;
    height: 40px;
    background: orange;
    border: 2px;
    margin-top: 13px;
    color: beige;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}

.btn {
    outline: none;
}

.srch:focus {
    outline: none;
}

.content {
    width: 1200px;
    height: auto;
    margin: auto;
    color: white;
    position: relative;
}

.content.par {
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}

.contenth1 {
    font-family: 'Times New Roman';
    font-size: 50px;
    padding: 50px;
    margin-top: 10%;
    letter-spacing: 2px;
}

.content.cn {
    width: 160px;
    height: 40px;
    background: red;
    border: none;
    margin-bottom: 20px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
}

.cn:hover {
    background-color: white;
}

.btnn a {
    text decoration: none;
    color: black
}

.icons a {
    text-decoration: none;
    color: black;
}

icons ion-icons {
    color: red;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
}
