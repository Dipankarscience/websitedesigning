# websitedesigning
Website designing using html and css only.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dipankar's Gym</title>
    <link
        href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@600&family=Bangers&family=Fondamento&family=Galada&display=swap"
        rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            font-family: 'Fondamento', cursive;
        }

        body {
            background-image: url("body2.jpg");
            color: white;
            font-family: 'Galada', cursive;
        }

        .left {
            display: block;
            position: absolute;
            top: 13px;
            left: 13px;
            padding: 5px;
        }
        .left img {
            width: 100px;
            display: block;
            margin: auto;
            padding: 5px;
        }

        .mid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: auto;
            padding: 10px;
            text-align: center;
            width: 50%;
        }

        .right {
            display: block;
            position: absolute;
            top: 13px;
            right: 13px;
            padding: 10px;
            width: 150px;
        }
        .right .btn{
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-around;
            padding: 5px;
        }
        .btn button{
            border: 2px solid white;
            border-radius: 5px;
            width: 80px;
            height: 40px;
        }
       .btn button:hover{
            background-color: cadetblue;
            text-decoration: underline;
        }
        .nav {
            display: inline-block;
            border: 2px solid white;
            border-radius: 4px;
            width: 100px;
            height: 40px;
            text-decoration: none;
            color: white;
            padding: 10px;
            font-size: 15px;
            margin: 13px auto;
            font-weight: bold;
        }

        h1 {
            font-size: 45px;
            text-align: center;
            margin: 18px auto;
        }

        .nav:hover {
            text-decoration: underline;
            background-color: red;
        }

        .nav:active {
            background-color: darkblue;
        }

        .nav:visited {
            color: darkturquoise;
        }

        .formgr {
            border: 2px solid white;
            position: absolute;
            border-radius: 10px;
            left: 100px;
            top: 250px;
            height: 400px;
            width: 500px;
            padding: 20px;
        }
        form .inputs{
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            padding: 5px;
            align-items: center;
        }
        input{
            width: 330px;
            border-radius: 5px;
            font-size: 15px;
            text-align: center;
        }
        #btn{
            width: 330px;
            border-radius: 5px;
            font-size: 15px;
            text-align: center;
            color: white;
            background-color: black;
        }
        .right button{
            border: 2px solid white;
            cursor: pointer;
            background-color: black;
            color: white;
            
        }
        .descrip {
           
            position: absolute;
            border-radius: 10px;
            right: 60px;
            top: 180px;
            height: 600px;
            width: 400px;
            padding: 20px;
            text-align: center;
            font-size: 17px;
        }
        .signin{
            position: absolute;
            bottom: 5px;
            top: 700px;
            border: 2px solid darkblue;
            width: 100%;
            height: 20%;
            background-color: cadetblue;
        }
        .signin form div{
            display: inline-block;
        }
        .signin form div input{
            background-color: black;
            color: white;
        }
    </style>
</head>

<body>
    <div class="left">
        <img src="https://i.pinimg.com/originals/c3/0c/97/c30c97416dcf2ce17a92b5d0545fb2a4.png" alt="">
        <h2>FITNESS GYM</h2>
    </div>
    <h1>WELCOME TO OUR WEBSITE</h1>
    <div class="mid">
        <a href="https://google.com" class="nav" target="_blank">Home</a>
        <a href="https://yahoo.com" class="nav" target="_blank">About Us</a>
        <a href="https://youtube.com" class="nav" target="_blank">Contact Us</a>
        <a href="https://facebook.com" class="nav" target="_blank">History</a>
        <div class="right">
            <div class="btn"><button>Call Us</button></div>
            <div class="btn"><button>Login</button></div>
        </div>
        <div class="formgr">
           <div class="heading">
               <h2>JOIN US BY FILLING THIS FORM</h2>
           </div>
            <form action="backend.php">
                <div  class="inputs">
                    <input type="text" placeholder="Enter your name">
                </div>
                <div class="inputs">
                    <input type="number" placeholder="Enter your phone number" >
                </div>
                <div class="inputs">
                    <input type="date" placeholder="Enter your DOB" >
                </div>
                <div class="inputs">
                    <input type="number" placeholder="Age" >
                </div>
                <div class="inputs"> 
                    <input type="email" placeholder="Enter your email ID" >
                </div>
                <div class="inputs"> 
                    <input type="text" placeholder="Enter your address" >
                </div>
                <div class="inputs"> 
                    <input type="submit" placeholder="submit" id="btn">
                </div>
            </form>
        </div>
        <div class="descrip">
            <h3>Description</h3>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora quidem suscipit obcaecati aut cumque, hic nihil illum commodi repellat maxime vero delectus accusantium ullam eveniet qui magni facere culpa, eaque incidunt laborum atque corporis, provident perferendis. Saepe soluta vero facere enim minima facilis officia eos omnis nihil architecto ipsam repudiandae, vitae voluptatibus. Cupiditate totam ipsum voluptas porro provident, aperiam praesentium dignissimos eligendi fugiat maiores veritatis eius magnam consequatur accusamus maxime laudantium enim recusandae quaerat? Inventore exercitationem, adipisci quisquam reprehenderit odio, quis ipsa laborum hic temporibus iure maxime possimus eos mollitia similique perferendis quia cupiditate. Numquam excepturi veritatis molestiae est eveniet?
        </div>
        <div class="signin">
            <h3>Sign In to our website</h3>
             <form action="backend.php">
                 <div>
                    <input type="email" placeholder="Enter your email">
                 </div>
                 <div>
                     <input type="password" placeholder="Enter Your Password">
                 </div>
                 <div>
                     <input type="password" placeholder="Confirm Password">
                </div>
                <div>
                    <input type="submit" placeholder="Submit">
                </div>
             </form>
        </div>
</body>

</html>
