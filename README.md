# Ex.06 Restaurant Website
# Date: 15.05.2026
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection. 

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
index.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Velvet Plate Restaurant</title>

    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:serif;
        }

        body{
            background:#fff8f0;
            color:#621733;
        }

        header{
            background:#621733;
            color:white;
            padding:20px;
            text-align:center;
        }

        nav{
            background:#000000;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        nav a:hover{
            color:rgb(57, 161, 1);
        }

        .banner{
            width:100%;
            height:80px;
            background:url('banner.jpg');
            background-size:cover;
            background-position:center;
        }

        .welcome{
            text-align:center;
            padding:0px;
        }

        .welcome h2{
            color:#8b0000;
            margin-bottom:20px;
            font-size:40px;
        }

        .welcome p{
            font-size:20px;
            line-height:35px;
        }

        .special{
            display:flex;
            justify-content:center;
            gap:30px;
            padding:40px;
            flex-wrap:wrap;
        }

        .card{
            width:300px;
            background:white;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 0 10px gray;
            text-align:center;
        }

        .card img{
            width:100%;
            height:220px;
        }

        .card h3{
            padding:15px;
            color:#8b0000;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:30px;
        }

    </style>
</head>

<body>

    <header>
        <h1>THE VELVET PLATE RESTAURANT</h1>
        <p>Delicious Food | Great Ambience | Fresh Ingredients</p>
    </header>

    <nav>
    <a href="/">Home</a>
    <a href="/menu/">Menu</a>
    <a href="/administration/">Administration</a>
    <a href="/contact/">Contact</a>
</nav>

    <div class="banner"></div>

    <section class="welcome">
        <h2>Welcome to Spice Garden</h2>

        <p>
            The Velvet Plate Restaurant offers a variety of delicious Indian,
            Chinese, and Continental dishes prepared with fresh ingredients.
            Enjoy a wonderful dining experience with your friends and family.
        </p>
    </section>

    <section class="special">

        <div class="card">
            <img src="/static/images/img7.webp">
            <h3>Chicken Biryani</h3>
        </div>

        <div class="card">
            <img src="/static/images/img19.jpg">
            <h3>HYDERABADI CHICKEN DUM BIRYANI</h3>
        </div>

        <div class="card">
            <img src="/static/images/img20.jpg">
            <h3>TANDOORI CHICKEN</h3>
        </div>

        <div class="card">
            <img src="/static/images/img21.jpg">
            <h3>ANDHRA CHILLI CHICKEN</h3>
        </div>


    </section>

    <footer>
        KARTHIK KRISHNA
    </footer>

</body>
</html>
```
```
menu.html

<!DOCTYPE html>
<html>
<head>
    <title>Menu - Spice Garden</title>

    <style>

        body{
            font-family:serif;
            background:#fff8f0;
            margin:0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#000000;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .menu-container{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
            padding:40px;
        }

        .menu-item{
            background:white;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 0 10px gray;
            text-align:center;
        }

        .menu-item img{
            width:100%;
            height:220px;
        }

        .menu-item h3{
            color:#8b0000;
            padding:10px;
        }

        .menu-item p{
            padding-bottom:15px;
            font-size:18px;
            font-weight:bold;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>

</head>

<body>

<header>
    <h1>OUR MENU</h1>
</header>

<nav>
    <a href="/">Home</a>
    <a href="/menu/">Menu</a>
    <a href="/administration/">Administration</a>
    <a href="/contact/">Contact</a>
</nav>

<div class="menu-container">

    <div class="menu-item">
        <img src="/static/images/img7.webp">
        <h3>Chicken Biryani</h3>
        <p>₹250</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img8.jpg">
        <h3>Paneer Butter Masala</h3>
        <p>₹220</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img9.jpg">
        <h3>Veg Fried Rice</h3>
        <p>₹180</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img10.webp">
        <h3>Pizza</h3>
        <p>₹300</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img11.jpg">
        <h3>Burger</h3>
        <p>₹150</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img12.avif">
        <h3>French Fries</h3>
        <p>₹120</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img13.jpeg">
        <h3>Ice Cream</h3>
        <p>₹90</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img14.jpg">
        <h3>Chicken 65</h3>
        <p>₹240</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img15.jpg">
        <h3>Masala Dosa</h3>
        <p>₹100</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img16.avif">
        <h3>Pasta</h3>
        <p>₹210</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img17.jpg">
        <h3>Sandwich</h3>
        <p>₹130</p>
    </div>

    <div class="menu-item">
        <img src="/static/images/img18.jpg">
        <h3>Momos</h3>
        <p>₹160</p>
    </div>

</div>

<footer>
    KARTHIK KRISHNA
</footer>

</body>
</html>
```
```
administration.html

<!DOCTYPE html>
<html>
<head>
    <title>Administration</title>

    <style>

        body{
            margin:0;
            font-family:serif;
            background:#fff8f0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#000000;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .team{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
            padding:40px;
        }

        .member{
            background:white;
            border-radius:10px;
            overflow:hidden;
            text-align:center;
            box-shadow:0 0 10px gray;
        }

        .member img{
            width:100%;
            height:250px;
        }

        .member h3{
            color:#8b0000;
            margin-top:10px;
        }

        .member p{
            padding-bottom:15px;
            font-size:18px;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

    </style>

</head>

<body>

<header>
    <h1>ADMINISTRATION</h1>
</header>

<nav>
    <a href="/">Home</a>
    <a href="/menu/">Menu</a>
    <a href="/administration/">Administration</a>
    <a href="/contact/">Contact</a>
</nav>

<div class="team">

    <div class="member">
        <img src="/static/images/img1.jpeg">
        <h3>DEETCHANA</h3>
        <p>Manager</p>
    </div>
    <div class="member">
        <img src="/static/images/img2.avif">
        <h3>SUNANINA</h3>
        <p>Head Chef</p>
    </div>

    <div class="member">
        <img src="/static/images/img3.avif">
        <h3>KIARA</h3>
        <p>Assistant Chef</p>
    </div>

    <div class="member">
        <img src="/static/images/img4.avif">
        <h3>DIYA</h3>
        <p>Receptionist</p>
    </div>

    <div class="member">
        <img src="/static/images/img5.jpg">
        <h3>NAVYA</h3>
        <p>Food Supervisor</p>
    </div>

    <div class="member">
        <img src="/static/images/img6.jpeg">
        <h3>SONA</h3>
        <p>Service Manager</p>
    </div>

</div>

<footer>
    KARTHIK KRISHNA
</footer>

</body>
</html>
```
```
contact.html

!DOCTYPE html>
<html><
<head>
    <title>Contact Us</title>

    <style>

        body{
            margin:0;
            font-family:serif;
            background:#fff8f0;
        }

        header{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
        }

        nav{
            background:#000000;
            padding:15px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:20px;
            font-size:18px;
            font-weight:bold;
        }

        .contact-box{
            width:70%;
            margin:auto;
            background:white;
            margin-top:50px;
            padding:40px;
            border-radius:10px;
            box-shadow:0 0 10px gray;
            line-height:40px;
            font-size:22px;
        }

        h2{
            color:#8b0000;
            margin-bottom:20px;
        }

        footer{
            background:#8b0000;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:50px;
        }

    </style>

</head>

<body>

<header>
    <h1>CONTACT US</h1>
</header>

<nav>
    <a href="/">Home</a>
    <a href="/menu/">Menu</a>
    <a href="/administration/">Administration</a>
    <a href="/contact/">Contact</a>
</nav>

<div class="contact-box">

    <h2>The Velvet Plate Restaurant</h2>

    <p><b>Address:</b> Beach Road, Maldives</p>

    <p><b>Phone:</b> +91 6303033151</p>

    <p><b>Email:</b> thevelvetplate@gmail.com</p>

    <p><b>Working Hours:</b> 10 AM to 11 PM</p>

</div>

<footer>
    KARTHIK KRISHNA
</footer>

</body>
</html>
```

# OUTPUT:
<img width="1046" height="653" alt="{01A41233-9365-4268-A3C9-FF360BC98185}" src="https://github.com/user-attachments/assets/b865ddde-98ee-4135-bfa6-1ad08f95ba42" />

<img width="1047" height="655" alt="{2AB05A32-E35D-4E78-B949-81E515DBBB5F}" src="https://github.com/user-attachments/assets/aa4161b9-619b-4a91-9185-7dca17dc6f92" />

<img width="1044" height="656" alt="{6FF62A96-A94A-4722-9796-01C35DA82E2F}" src="https://github.com/user-attachments/assets/10b10983-b1d1-41d3-abe4-b92393629fe0" />

<img width="1046" height="653" alt="{74C0CA34-F0C1-47A3-84F0-DB78FDBCEAAC}" src="https://github.com/user-attachments/assets/d72a55d3-be85-47a9-b37a-733c51c2bf23" />

<img width="1043" height="652" alt="{FA0B88D2-6230-4E18-9780-223FDD2300FF}" src="https://github.com/user-attachments/assets/8ac39392-f5fe-43f2-93a2-c243d3b27c1e" />

<img width="1048" height="656" alt="{0BFB6D44-D269-4B96-A8A5-8B064643D093}" src="https://github.com/user-attachments/assets/4a311d84-85e7-461d-a5c3-fc185525a1d5" />


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
