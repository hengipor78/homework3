<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        
        .main {
            width: 100%;
            background: linear-gradient(to top, rgba(0, 0, 0, 0, 5)50%);
            background-position: center;
            background-size: cover;
            height: 100vh;
            text-align: center;
            mask-image: ;
        }
        
        .navbar {
            border-bottom: #6ccc53;
            background-color: gold;
            width: 100%;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .menu ul {
            display: flex;
            list-style: none;
        }
        
        .menu ul li {
            margin: 0 10px;
        }
        
        .cn {
            width: 160px;
            height: 40px;
            background: #ff7200;
            border: none;
            margin-bottom: 10px;
            font-size: 18px;
            border-radius: 20px;
            cursor: pointer;
        }
        
        .cn a {
            text-decoration: none;
            color: #fff;
            display: block;
            width: 100%;
            height: 100%;
            text-align: center;
            line-height: 40px;
            transition: 0.3s ease;
        }
        
        .cn:hover {
            text-align: center;
            background-color: #fff;
        }
        
        .cn:hover a {
            text-align: center;
            color: #ff7200;
        }
        
        .search {
            display: flex;
            align-items: center;
        }
        
        .srch {
            justify-content: space-between;
            width: 200px;
            height: 40px;
            border-right: none;
            font-size: 16px;
            padding: 10px;
            border-radius: 20px;
            border-bottom-left-radius: 5px;
            border-top-left-radius: 5px;
            color: #5e2c57;
            margin-left: 2px;
        }
        
        .btn {
            width: 160px;
            height: 40px;
            background: #ff7200;
            border: none;
            margin-bottom: 10px;
            margin-left: 20px;
            font-size: 20px;
            border-radius: 20px;
            cursor: pointer;
        }
        
        .btn a {
            text-decoration: none;
            color: #fff;
            display: block;
            width: 100%;
            height: 100%;
            text-align: center;
            line-height: 40px;
            transition: 0.3s ease;
        }
        
        .btn:hover {
            background-color: #34996f;
        }
        
        .btn:hover a {
            color: #ff7200;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .intro {
            text-align: center;
            margin-bottom: 20px;
        }
        
        .intro-image {
            width: 210px;
            height: 200px;
        }
        
        .intro-image1 {
            float: right;
            padding-right: 50px;
            margin-top: 30px;
        }
        
        .intro-text {
            padding: 150px;
            text-align: center;
        }
        
        .text-padding {
            border: 1px solid gold;
            border-radius: 5px;
        }
        
        h2 {
            margin-bottom: 10px;
        }
        
        ul {
            list-style: none;
            padding: 0;
        }
        
        li {
            margin-bottom: 10px;
            justify-content: space-between;
        }
    </style>
</head>

<body>
    <div class="main ">
        <div class="navbar ">
            <div class="menu ">
                <ul>
                    <li><button class="cn "><a href="# ">ទំព័ដើម</a></button></li>
                    <li><button class="cn "><a href="# ">សៀវភៅ HTML</a></button></li>
                    <li><button class="cn "><a href="# ">អំពីយើង</a></button></li>
                </ul>
            </div>
        </div>
        <div class="container ">
            <section class="intro ">
                <p>
                    <img src="https://www.bing.com/th?id=OIP.QPITbeQOZQqS2ZdwRjSdoAHaEp&w=193&h=150&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2 " alt="Books " class="intro-image ">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quaerat harum recusandae
                    eveniet voluptatibus veritatis incidunt ducimus impedit, maxime cupiditate alias nisi tempora delectus dolore minima totam fugiat assumenda repellat. Dicta??
                </p>
            </section>
            <div class="intro-image1 ">
                <img src="https://www.bing.com/th?id=OIP.QPITbeQOZQqS2ZdwRjSdoAHaEp&w=193&h=150&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2 " alt="Books ">
            </div>
            <div class="intro-text ">
                <h2>Text & Padding</h2>
            </div>
            <section class="text-padding ">
                <div class="content-box ">
                    <ul>
                        <li>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. In vero adipisci quis accusantium quibusdam dolorem doloribus ullam esse enim. Non soluta eaque consequuntur reprehenderit fuga in odio doloribus rerum eos? Quis non debitis explicabo quos facere
                            totam ab repellendus esse aliquam. Non ad dolorum quisquam eaque neque molestiae reiciendis magni assumenda nemo facilis minus modi natus, iure aperiam necessitatibus voluptatibus.
                        </li>
                    </ul>
                    <ul>
                        <li>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. In ipsa unde iusto aperiam alias quam quod hic nemo nulla libero quaerat impedit quibusdam culpa quae tempore, rerum porro iure sit! Facilis quia, corrupti nam dicta reiciendis hic ea labore eligendi
                            numquam impedit sunt voluptatem voluptates aspernatur cumque expedita nobis voluptatum, illum alias mollitia quas fugit. Expedita repellat voluptatibus magni sint? Voluptate, reprehenderit ratione molestias incidunt soluta
                            explicabo cupiditate doloremque omnis earum perferendis, ullam itaque ut. Deleniti perspiciatis quos ullam reiciendis dolores. Id labore animi iure expedita odio, dolor perspiciatis necessitatibus. Doloribus dicta labore cumque
                            sunt nulla similique repellat quo beatae quas ipsa et nisi rerum perferendis, accusamus, commodi eius voluptates. Veritatis consequatur repellat magnam, aperiam debitis excepturi dolorum eveniet eaque? Numquam, commodi natus
                            qui a dolorum amet? Dolor dolores tempore corrupti quaerat, iusto sap.
                        </li>
                    </ul>
                </div>
            </section>
        </div>
    </div>
</body>

</html>
