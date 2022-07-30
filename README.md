<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flipkart.com</title>
    <style>@import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Water+Brush&display=swap');
        *{
            margin: 0;padding: 0;
        }
        .head{
            height: 8vh;
            background-color: rgb(36, 80, 190);
            font-family: 'Baloo Bhai 2', cursive;
        }
        nav{
            display: flex;
            }
            .logo{
                display: flex;
                align-items: center;
            }
        nav ul {
            height: 56px;
                display: flex;
                justify-content: flex-start;
                align-items: center;
        }
        nav ul li {
            padding: 23px;
            list-style: none;
        }
        nav ul li a {
        color: white;
        text-decoration: none;
        
        }
        nav ul li:hover{
            font-weight: bolder;
        }
        .search{
            align-items: center;
            display: flex;
        }
        #scr{
            height: 38px;
         width: 400px;
        justify-content: center;
        animation: tushar 4s ease-in-out 1s infinite alternate-reverse ;
        }
        @keyframes tushar {
            from{
                width: 400px;height: 38px;}
            to{
                width: 100px;height: 38px; }
             }
        .btn{
            background-color:  rgb(36, 80, 190);
            color: white;
            display: flex;
            height: 23px;
            width: 55px;
            margin: 14px;
            align-items: center;
            justify-content: center;
            border: 2px solid white;
            
        }
        button:hover{
            width: 55px;
            height: 20px;
        }
        .cantenar{
            margin: 5px;
        min-height: 80vh;
        }
        .slider{ 
            margin: 5px;
            display: flex;
            justify-content: center;
        }
        footer{
            height: 12vh;
            background-color: rgb(29, 128, 209);
            color: aliceblue;
            font-family: 'Baloo Bhai 2', cursive;
        }
        .flex-all-center{
    display: flex ;
    justify-content: center;
    align-items: center;
}
        </style>
    
</head>
<body>
    <header class="head">
        <nav>
            <div class="logo">
                <img src="FP.PNG" alt="logo" width="110px">
            </div>
         <ul>
           <li><a href="home.html"> home</a></li>
           <li><a href="about.html">about</a></li>
           <li><a href="contect.html">contect</a></li>
         </ul>
         <div class="search" >
            <input type="search" placeholder="prodect/mobail/shoes" id="scr" >
           <button class="btn">search</button>
        </div>
        </nav> 
    </header>
    <main>
        <div class="slider" >
            <img src="https://source.unsplash.com/1000x500/?shooping, ecommerce" alt="">
        </div>
    </main>
    <footer class="flex-all-center">
        <p>copyrights &copy; flipcart.com all rights are resvered</p>
    </footer>
</body>
</html>
