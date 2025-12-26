# Ex.06 Restaurant Website
## Date:26/12/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
pararest.html
<html>
    <head>
        <title>Home Page</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <i><h1 class="homehead">Casa di Nonna </h1></i>
        <i><h2 style="text-align: center;font-size: 50px;color: aliceblue;">One Bite, Full Delight...</h2></i>
        <div class="img">
            <img src="home.png" class="restbg1">
            <img src="home1.png" class="restbg2">
            <img src="home2.png" class="restbg3">
        </div>
        <nav class="nav2">
            <ul>
                <li><a href="pararest.html" style="color: white;">Home</a></li>
                <li><a href="menu.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 style="text-align: center;" class="footer2">&copy;PARVESHWARAN R (25018243)</h2>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Menu</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h1 class="menuhead">Menu</h1>
        
        <div class="mainbox">
            <div class="box1">
            <img src="menu1.jpg" class="food1">
            <h3 style="text-align: center;">Spaghetti Carbonara</h3>
            <h4>RS : 149</h4>
        </div>
        <div class="box2">
            <img src="menu2.jpg" class="food2">
            <h3 style="text-align: center;">margherita Pizza</h3>
            <h4>RS : 299</h4>
        </div>
        <div class="box3">
            <img src="menu3.jpg" class="food3">
            <h3 style="text-align: center;">Lasagna</h3>
            <h4>RS : 99</h4>
        </div>
        <div class="box4">
            <img src="menu4.jpg" class="food4">
            <h3 style="text-align: center;">Caprese Salad </h3>
            <h4>RS : 299</h4>
        </div>
        <div class="box5">
            <img src="menu5.jpg" class="food5">
            <h3 style="text-align: center;">Risotto alla Milanese</h3>
            <h4>RS : 49</h4>
        </div>
        </div>
        <nav class="nav3">
            <ul>
                <li><a href="home.html" style="color: white;">Home</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer3">&copy; PARVESHWARAN R (25018243)</h2>
    </body>
</html>

admin.html
<html>
    <head>
        <title>Admin Site</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <h1 class="adminhead">Administration Team</h1>
        <div class="adminbox">
            <div class="admin1">
                <img src="CEO.png" class="one">
                <h3>PARVESHWARAN R</h3>
                <h3>CEO</h3>
            </div>
            <div class="admin2">
                <img src="maket.jpg" class="two">
                <h3>robert</h3>
                <h3>Head of Marketing</h3>
            </div>
            <div class="admin3">
                <img src="chef.jpg" class="three">
                <h3>Sanji</h3>
                <h3>Chief Cook</h3>
            </div>
            <div class="admin4">
                <img src="op man.webp" class="four">
                <h3>john</h3>
                <h3>Operation Manager</h3>
            </div>
            <div class="admin5">
                <img src="hr.jpg" class="five">
                <h3>Tony</h3>
                <h3>HR Manager</h3>
            </div>
            <div class="admin6">
                <img src="sec.webp" class="six">
                <h3>david</h3>
                <h3>Security</h3>
            </div>
        </div><br><br>
        <nav class="nav4">
            <ul>
                <li><a href="home.html" style="color: white;">Home</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer4">&copy;  PARVESHWARAN R (25018243)</h2>
    </body>
</html>
rest.html

<html>
    <head>
        <title>My Restaurant</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
            <h1 style="font-size: 100px;" class="Contact">Contact</h1>
            <div class="tablestyle">
            <table class="table">
                <tr>
                    <td><h1>Visit us at</h1></td>
                </tr>
                <tr>
                    <td><h3>54/50:madurai swamy madam street chennai 11</h3></td>
                </tr>
                <tr>
                    <td><h1>Phone Number</h1></td>
                </tr>
                <tr>
                    <td><h3>7550001476</h3></td>
                </tr>
                <tr>
                    <td><h1>Email ID:</h1></td>
                </tr>
                <tr>
                    <td><h3>littlesiddhu@gmail.com</h3></td>
                </tr>
            </table>
        </div>
        <nav class="nav">
            <ul>
                <li><a href="home.html" style="color: white;">Home</a></li>
                <li><a href="menue.html" style="color: white;">Menu</a></li>
                <li><a href="admin.html" style="color: white;">Admin</a></li>
                <li><a href="rest.html" style="color: white;">Contact</a></li>
            </ul>
        </nav>
        <h2 class="footer">&copy; M.Vetrivel [25011461]</h2>
    </body>
</html>
style.css
body{
    background-image: url("home3.png");
}
.contact
{
    font-size: 100px;
    margin-left: 70%;
    display: inline;
    color: silver;
}
.table
{
    margin-left: 70%;
    margin-top: 20px;
    color: silver;
}
.nav ul
{
    display: flex;
    list-style: none;
    gap: 250px;
    margin-top: 130px;
    border: solid 3px;
    font-size: 50px;
    color: whitesmoke;
    border-radius: 15px;
}
.footer
{
    text-align: center;
    background-color: black;
    color: white;
}
.homehead
{
    margin-left: 300px;
    font-size: 100px;
    color: antiquewhite;
    display: inline;
}
.restbg1
{
    width: 450px;
    height: 350px;
    margin-left: 50px;
    border: solid 3px whitesmoke;
    display: inline;
}
.restbg2
{
    width: 450px;
    height: 350px;
    margin-left: 50px;
    border: solid 3px whitesmoke;
    display: inline;
}
.restbg3
{
    width: 400px;
    height: 350px;
    margin-left: 50px;
    border: solid 3px whitesmoke;
    display: inline ;
}
.footer2
{
    text-align: center;
    color: aliceblue;

    background-color:black;
}
.nav2 ul
{
    display: flex;
    list-style: none;
    gap: 300px;
    border: solid 3px;
    font-size: 30px;
    color: rgb(183, 174, 174);
    border-radius: 15px;
}
.search
{
    margin-left: 450px;
    width: 650px;
    height: 40px;
}
.menuhead
{
    text-align: center;
    font-size: 100px;
    color: rgb(255, 255, 255);
}
.button
{
    margin-left: 10px;
    height: 40px;
}
.mainbox
{
    display: flex;
    gap: 50px;
    margin-top: 25px;
    margin-left: 80px;
}
.food1
{
    height: 300px;
    width: 250px;
}
.box1
{
    color: white;
    border: solid 3px;
    background-color: black;
}
box1 h3,h4
{
    text-align: center;
}
.food2
{
    height: 300px;
    width: 250px;
}
.box2
{
    color: white;
    border: solid 3px;
    background-color: black;
}
.food3
{
    height: 300px;
    width: 250px;
}
.box3
{
    color: white;
    border: solid 3px;
    background-color: black;
}
.food4
{
    height: 300px;
    width: 250px;
}
.box4
{
    color: white;
    border: solid 3px;
    background-color: black;
}
.box5
{
    color: white;
    border: solid 3px;
    background-color: black;
}
.food5
{
    height: 300px;
    width: 250px;
}
.nav3 ul
{
    display: flex;
    list-style: none;
    gap: 400px;
    border: solid 3px;
    font-size: 30px;
    color: rgb(255, 255, 255);
    border-radius: 15px;
    background-color: black;
}
.footer3
{
    text-align: center;
    background-color: black;
    color: white;
}
.adminhead
{
    font-size: 100px;
    text-align: center;
    font-style: oblique;
    color: antiquewhite;
}
.adminbox
{
    display: flex;
    gap: 50px;
    margin-top: 25px;
    margin-left: 70px;
}
.one
{
    height: 300px;
    width: 200px;
    border: solid 3px;
}
.admin1
{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.admin1 h3
{
    text-align: center;
    color: black;
}
.admin2
{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.admin2 h3{
    text-align: center;
    color: black;
}
.two
{
    height: 300px;
    width: 200px;
    border: solid 3px;
}
.three
{
    height: 300px;
    width: 200px;
    border: solid 3px;
}
.admin3
{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.admin3 h3
{
    text-align: center;
    color: black;
}
.admin4 h3{
    text-align: center;
    color: black;
}
.admin4{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.four
{
    height: 300px;
    width: 200px;
    border: solid 3px;
}
.five
{
    height: 300px;
    width: 200px;
    border: solid 3px;
}
.admin5
{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.admin5 h3{
    text-align: center;
    color: black;
}
.admin6 h3{
    text-align: center;
    color: black;   
}
.admin6{
    color: white;
    border: solid 3px;
    background-color: silver;
}
.six
{
    height: 300px;
    width: 200px;
    border: solid 3px;   
}
.nav4 ul
{
    display: flex;
    list-style: none;
    gap: 400px;
    border: solid 3px;
    font-size: 30px;
    color: rgb(255, 255, 255);
    border-radius: 15px;
    background-color: black;
}
.footer4
{
    text-align: center;
    background-color: black;
    color: white;
}

```

## OUTPUT:
![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (51).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
