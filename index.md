<!DOCTYPE html>
<html>
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial scale=1.0">
    <meta name="keywords" content="HTML, CSS">
    <meta name="description" content="random">
        <title>My Website</title>
        
    <style>
        *{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}
.banner{
    width: 100%;
    height: 100vh;
    background-image: url(nature3.jpg);
    background-size: cover;
    background-position: center;
}
.navbar{
    width:85%;
    margin: 0 10px;
    text-transform: uppercase;
    padding: 43px 0;
    align-items: center;
    justify-content:space-between;
    font-size:large;
    font-weight: 549;
    float: left;
    position: relative;
    left: 30px;

}
.navbar ul li{
    list-style-type: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}
.navbar ul li a{
    text-decoration: none;
    color: white;
}
.navbar ul li::after{
    content: '';
    height: 3px;
    width: 0%;
    background: #009688;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.35s;
}
.navbar ul li:hover:after{
    width: 100%
}
.content{
    width: 100%;
    position: absolute;
    top: 50%;
    text-align: center;
    color: rgb(136, 140, 137);
}
.content h1{
    color: white;
    text-transform: uppercase;
    margin-bottom: 8px;
    font-size: 40px;
}
.content p{
    font-size: 20px;
}
.button{
    font-size: 18px;
    width: 190px;
    padding: 18px;
    text-align: center;
    margin: 20px 10px;
    border-radius: 40px;
    font-weight: bold;
    border: none;
    color: white;
    background: rgb(38, 114, 55);
    position: relative;
    bottom: -5px;
    right: 15px;
}
.button:hover{
    color: black;
    background: rgb(125, 231, 128);
    transition: 0.5s;
}
.button a{
    text-decoration: none;
    color: black;
}
    </style>
    </head>
    <body>
        
        <div class="banner">
            <button class="button"><span><a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">This is a button</a></span></button>
            <div class="navbar">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Info</a></li>
                    <li><a href="#">More</a></li>
                </ul>
            </div>
            <div class="content">
                <h1>Pictures Of Stuff</h1>
                <p>Pictures of food and other stuff idk. Just random stuff I guess. blah blah I want this line to be long</p>
            </div>
        </div>
    </body>
</html>
