
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
    <title>Design Navbar</title>

    <style>
        *{
            padding: 0;
            margin: 0;
        }
        nav{
            height: 50px;
            background-color: rgb(183, 93, 93);
            display: flex;
            justify-content: space-around;
            align-items: center;
            /* padding-left: 80px; */
        }
        .logo{
            align-content: center;
        }
        .company-name{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-weight: bold;
            /* margin: 2px 10px; */
        }
        .company-name span{
            font-size: 10px;
            font-weight: normal;
        }
        .option{
            padding-left: 200px;
        }
        .option ul{
            list-style: none;
            gap: 20px;
            display: flex;
        }
        .option ul li{
            justify-content: center;
            align-items: center;
        }
    </style>

</head>
<body>
    
    <header>
        <nav>
            <div class="logo">
                <img src="https://static.vecteezy.com/system/resources/previews/047/656/219/non_2x/abstract-logo-design-for-any-corporate-brand-business-company-vector.jpg" alt="" width="35px">
            </div>

            <div class="company-name">
                <p>UltraEdit</p>
                <span>An idea company</span>
            </div>

            <div class="option">
                <ul>
                    <li>Products <i class="fa-solid fa-angle-down"></i></li>
                    <li>Pricing <i class="fa-solid fa-angle-down"></i></li>
                    <li>Resources <i class="fa-solid fa-angle-down"></i></li>
                    <li>About us <i class="fa-solid fa-angle-down"></i></li>
                    <li><i class="fa-solid fa-comments-dollar"></i></li>
                </ul>
            </div>

        </nav>
    </header>

</body>
</html>
