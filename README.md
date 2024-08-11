
[Uploading t*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}
.banner{
    height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(0,0,0,0.75) ,rgba(0,0,0,0.75)) ,url(./istockphoto-1375651222-612x612.jpg);
    background-position: center;
    background-size: cover;
}
.navbar{
  width: 85%;
  margin: auto;
  padding: 35px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;



}
.logo{
    width: 120px;
    cursor: pointer;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
     
}
.navbar ul li a{
    color: aliceblue;
    text-decoration: none;
    text-transform: uppercase;
}
.navbar ul li::after{
    content: '';
    height: 3px;
    width: 0;
    background: aqua;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.5s
}
.navbar ul li:hover::after{
    
    width: 100%;
}
.content{
    width: 100%;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
    color: aliceblue;
}
.content h1{
    font-size: 70px;
    margin-top: 80px;
}
.content p{
    margin: 20px auto;
    font-weight: 100;
    line-height: 25px;
}
button{
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    border-radius: 25px;
    font-weight: bold;
    border: 2px solid aqua;
    background: transparent;
    color: aliceblue;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    
    

}
span{
    background: aqua;
    height: 100%;
    width: 0;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}
button:hover span{
    width: 100%;
}
button :hover{
    border: none;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./train.css">
</head>
<body>
    <div class="banner">
        <div class="navbar">
            <img src="logo.png" class="logo">
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">BEDROOM</a></li>
                <li><a href="#">KITCHEN</a></li>
                <li><a href="#">DINING</a></li>
                <li><a href="#">BACKYARD</a></li>
            </ul>
        </div>
        <div class="content">
            <h1>WEBSITE FOR DESINING YOUR HOUSE</h1>
            <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis magni quibusdam et provident maiores quas, cupiditate odit autem.</P>
            <button type="button"><SPAN></SPAN>DESCRIBE MORE</button>
            <button type="button"><SPan></SPan>DESCRIBE MORE</button>
        </div>



    </div>
    
</body>
</html>rain.css…]()

