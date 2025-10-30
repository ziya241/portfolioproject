<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IV-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <header class="header">
         <a href="#" class="logo"><img src="ziya.png"></a>
        <nav class="navbar">
             <a href="#">HOME</a>
             <a href="#">ABOUT</a> 
             <a href="#">SKILLS</a> 
             <a href="#">WORKS</a> 
             <a href="#">CONTACTS</a> 
        </nav>
    </header>
    <section class=" home">
        <div class="home-content">
            <h3>Hello, It's Me</h3>
            <h1>Ziya Fatima</h1>
            <h3>And I'm a <span class="text" ></span></h3>
            <p>Web Developer and designer from lucknow. I create websites to do business do better.</p>
            <div class="home-sci">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-instagram'></i></a>
                <a href="#"><i class='bx bxl-whatsapp-square'></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
                  </div>
            <a href="#" class="btn-box">More About Me</a>
        </div>
    </section>
<script src="script.JS"></script>
</body>
</html>
*
{
    margin:0;
    padding:0;
    box-sizing: border-box;
    font-family: "poppins",sans-serif;
}
body
{
color:#D4B87B;
}
.header
{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    padding: 20px 10px;
    background-color:#D4B87B;
    display:flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}
.logo
{
 
 cursor:default;

}
.navbar
a {
    font-weight: 12;
    margin: 0 10px;
    font-size: 25px;
    background-color:#D4B87B;
    text-decoration : #D4B87B;
   color: aqua;
   transition: .3s;
}
.navbar a:hover{
    color:#D4B87B;
}
.home{
    width: 100%;
    justify-content: space-between;
    height:100vh;
    background-color:#2B2420 ;
    background-size: cover;
    display:flex;
    align-items: center;
    padding: 70px 10% 0;
}
.home-content{
    max-width: 600px;
}
.home-content h3{
    font-size: 32px;
    font-weight: 700;
}
.home-content h3 :nth-of-type(2){
    margin-bottom:30px;
}
.home-content h3 span {
    color:#D4B87B;
}
.home-content h1{
    font-size: 56px;
    font-weight: 700;
    margin: 3px 0;
}
.home-sci a {
    display: inline-flex;
    justify-content: center;
    width: 40px;
    height: 40px;
    background: transparent;
    border: #D4B87B;
    border-radius: 50%;
    font-size: 20px;
    color: #D4B87B;
    text-decoration: none;
    margin: 30px 15px 3px 0; 
}
.home-sci a:hover {
background: #D4B87B;
color: #2B2420;
box-shadow: 0 0 20px #D4B87B;
}
.btn-box{
    display: inline-block;
    padding: 12px 28px;
    background: #D4B87B;
    border-radius: 40px;
    font-size: 16px;
    color:#2B2420;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
}
.btn-box:hover {
    box-shadow: 0 0 5px #D4B87B,
    0 0 25px #D4B87B, 0 0 50px #D4B87B,
    0 0 #D4B87B, 0 0 200px #D4B87B
}
@keyframes slideRight{
    0%{
        trasform: translatex(-100px);
        opacity:0;
    }
    100%{
        trasform: translatex(100px);
        opacity:1;
    }
}
