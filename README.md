# List
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        ul li a{
            text-decoration: none;
            color: aliceblue;
            display: block;
        
        }
        ul li{
            background-color:black;
            height: 60px;
            width: 120px;
            text-align:center;
            line-height:60px;
            display: block;
            float:left;
            border-right: solid white 2px;


        }
        ul li:hover{
            background-color:yellow;
            

        }
        ul li:hover a{
            color:red;
        }
        ul li ul li{
            margin-left: -40px;
            display: none;
        }
        ul li:hover ul li{
            display:block;
        }
        ul li:hover ul li ul li{
            position:relative;
            left:120px;
            top:-60px;
            display: none;
        }
        ul li ul li:hover ul li{
            top:-5px;
            position:relative;
            background-color: rgb(10, 243, 68);
        }
        ul li ul li:hover ul li{
            display: block;
        }
       
    </style>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <ul>
        <li><a href="">Home</a>
            <ul>
                <li>
                    <a href="">Department</a>
                    <ul>
                        <li><a href="">Electronics</a></li>
                        <li><a href="">Maths</a></li>
                    </ul>
                </li>
                <li>
                    <a href="">Examination</a>
                    <ul>
                        <li><a href="">Regular</a></li>
                        <li><a href="">Private</a></li>
                    </ul>
                </li>
            </ul>
        </li>
        <li><a href="">About</a></li>
        <li><a href="">Contact</a></li>
    </ul>
    
</body>
</html>
