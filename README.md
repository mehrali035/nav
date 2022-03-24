# nav
<style>
# @import url('https://fonts.googleapis.com/css2?family=Anton&family=Poppins:wght@700&family=Work+Sans:ital,wght@0,500;1,400&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Work Sans', sans-serif;
}
:root{
    --heading:rgb(0 10 45);
    --para: #777;
    --para-tint:#e4e4e4;
    --white:#fff;
    --black:#212529;
    --helper:#8490ff;
    --helper-tint:#f3f3ff;
    --bg:rgb(249 249 255);
    --gradient:linear-gradient(0deg,rgb(132 144 255)0%, rgb(98 189 252)100%);
    --grdientsupport:-webkit-linear-gradient(0deg,rgb(132 144 255)0%, rgb(98 189 252)100%);
    --shadow: 0px 0px 20px 0px rgb(132 144 255 / 20%);

}
html{
    font-size: 62.5%;
}
h1,h2,h3,h4{
    font-family: 'Poppins', sans-serif;
}
h1{
    color: var(--heading);
    font-size: 6rem;
    font-weight: 600;
}
h3{
    font-size: 1.8rem;
    font-weight: 400;
}
p{
    color: var(--para);
    line-height: 1.6;
    font-weight: 1.7;
}
a{
    text-decoration: none;
}
li{
    list-style: none;
}
/*==================== Header Section start ==================== */

.header{
  padding: 0 4.8rem;
  height: 7rem;
  background-color: var(--bg);
  display: flex;
  align-items: center;
  justify-content: space-between;

}
.header .logo{
    height: 4rem;
    clip-path: circle();

}
.navbar-lists{
    display: flex;
    gap: 5rem;
}
.navbar-link:link,
.navbar-link:visited{
    display: inline-block;
    font-size: 1.2rem;
    font-weight: 500;
    text-transform: uppercase;
    color: var(--black);
    transition: color 0.3s linear; 
}
.navbar-link:hover,
.navbar-link:active{
    color: var(--helper);
}
</style>


!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>

<body>
    <header class="header">
        <img src="logo.jpg" alt="our logo" class="logo">
        <nav class="navbar">
            <ul class="navbar-lists">
                <li><a href="#" class="navbar-link home-link">Home</a></li>
                <li><a href="#" class="navbar-link about-link">About</a></li>
                <li><a href="#" class="navbar-link services-link">Services</a></li>
                <li><a href="#" class="navbar-link portfolio-link">Portfolio</a></li>
                <li><a href="#" class="navbar-link contact-link">Contact</a></li>
            </ul>
        </nav>
    </header>

</body>

</html>
