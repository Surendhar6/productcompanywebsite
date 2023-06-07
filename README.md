# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
i) home.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>A.S.Electricals</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Feel good through our Store</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official Website of our electrical Store</p>
                    </div>
                    <p>Buy all electrical gagets and items online from <span style="background-color:rgb(112, 137, 112)">A.S.Electricals</span>
                         for Rs.500- | Buy electronics in ONE SIZE online | 7 Days Returns | Trend setting models | And much more</p>
                    <br>
                <center>
                    <img src="/static/img/home1.jpeg">
                    <img src="/static/img/home3.jpeg">
                    <img src="/static/img/home2.jpeg">
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by SURENDHAR</footer></div>
            </div>
        </div>
    </body>
</html>
```

ii) style.css
```
.home{
    height: 700px;
    width: 85%;
    border: 12px solid rgb(68, 139, 74);
    padding-left:10px;
    padding-right:10px;
    margin-left: auto;
    margin-right:auto;
    background-color:rgb(105, 177, 22);
}
.content{
    border:1px solid whitesmoke;
    background-color: white;
    width:95%;
    height:1190px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;
}
.header{
    height: 128px;
    width:100%;
    background-image: url(/static/images/header.jpg);
    background-size: cover;
    
}
.logo{
    height:18%;
    width: 10%;
    position:absolute;
    background-image: url(/static/images/icon.png);
    background-size:cover;
    
}
.prod{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:550px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.prod:hover{
    background-color:red
}
.people{
    height:auto;
    width:auto;
    position:relative;
    bottom:10px;
    left:700px;
    border:4px solid transparent;
    text-align:center;
    display: inline;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.people:hover{
    background-color:red;
}
.contact{
    height:20px;
    width:10%;
    position:relative;
    bottom:45px;
    left:1000px;
    border:4px solid transparent;
    text-align:center;
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.contact:hover{
    background-color:red;
}
        
.h{
    height:20px;
    width:10%;
    position:relative;
    top:30px;
    left:200px;
    border:4px solid transparent;
    text-align:center;
    
    padding:15px;
    font-family:'Gill Sans MT';
    font-size: large;  
}
.h:hover{
    background-color:red;
    overflow:hidden;
}
.footer{
    border: 15px solid rgb(54, 187, 88);
    width:98%;
    height:10px;
    position:relative;
    bottom: 1px;
    background-color:rgb(54, 187, 88);
    text-align:center;

}
.title{
    border:2px solid pink;
    background-color:yellow;
    padding:1px;
    width:99.7%;
    height: 70px;
    text-align:center;
    font-family:'Impact';
    margin-left:auto;
    margin-right: auto;
    
}
.content{
    border:1px solid red;
    background-color: white;
    width:98%;
    height:400px;
    padding:10px;
    margin-left:auto;
    margin-right:auto;

}
```

iii) contact.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        ECR, Chennai, TamilNadu, India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 9790000211</li>
                        <li><b>Mobile</b>: 9025670266</li>
                        <li><b>Facebook</b>: bhaifb</li>
                        <li><b>Email Id:</b>sure@mail.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Use our services and Beautify Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Surendhar</footer></div>
            </div>
        </div>
    </body>
</html>
```

iv) people.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:rgb(234, 241, 241);
        }
        .text{
        color:rgb(76, 14, 14);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid rgb(6, 7, 6);
            background-color:rgb(95, 101, 105);
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/img/founder.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color: rgb(10, 1, 1);
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/img/maldini.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: rgb(20, 5, 5);
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/img/becham.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color: rgb(17, 3, 3);
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/img/pep.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: rgb(25, 7, 7);
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/img/klopp.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:220px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: rgb(25, 7, 7);
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/img/jose.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:250px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color: rgb(19, 4, 4);
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Aashique</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>Paolo Maldini</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2>David Beckham</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>Josep Guardiola</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Jurgen] Klopp</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>Jose Mourinho </h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had made you more HOPEFULL!</div>
                </div>
                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 SURENDHAR</footer></div>
            </div>
        </div>
    </body>
</html>
```

v)product.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1555px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:green
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid rgb(33, 61, 136);
            background-color: white;
            width:98%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/img/product1.jpeg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:200px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: grey;
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(/static/img/product2.jpeg);
            background-size: 350px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:250px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: sandybrown;
            position:relative;
            right:380px;
        }
        .ph3{
            background-image: url(/static/img/product3.jpeg);
            background-size: 370px;
            background-position-x: center;
            background-repeat: no-repeat;
            height:350px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color: rgb(19, 16, 12);
            position:relative;
            right:380px;
        }
        .ph4{
            background-image: url(/static/img/product4.jpeg);
            background-position-x: center;
            height:300px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:1130px;
            background-size: 350px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: burlywood;
            position:relative;
            left:270px;
            bottom: 1130px;
        }
    
        .ph5{
            background-image: url(/static/img/product5.jpeg);
            background-position-x: center;
            height:380px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:1100px;
            background-size: 355px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: cadetblue;
            position:relative;
            left:270px;
            bottom: 1100px;
        }

        .bot{
            text-align:center;
            font-size:larger;
            color:white;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>Ceiling Fan<br> Price: 1900</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Naveen's Air Cooler<br> Price: 1899.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>LED Bulb<br> Price: 199.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Iron Box<br> Price: 699.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Water Heater<br> Price: 3999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 9025670266</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by SURENDHAR</footer></div>
            </div>
        </div>
    </body>
</html>
```

## OUTPUT:

### Home Page:
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/71b88330-a462-422e-9d87-88b63a91d6f6)

### Product Page:
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/a6f008df-6b72-477d-bbaa-d714c81fbf0b)
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/11fa3669-4e63-4e77-81f2-64a2f30ae61e)

### People Page:
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/60c07ae0-9533-4cb8-826e-82b0ed5ae816)
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/335877f0-bfe3-42bb-ac97-8a89a1b10703)
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/46ef66c2-7385-49ed-a630-446b266b5ede)

### Contact Page:
![image](https://github.com/Surendhar6/productcompanywebsite/assets/118352907/dc28f208-6752-44c3-a210-82ca10ee89be)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
