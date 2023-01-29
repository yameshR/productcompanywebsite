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
home.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Nova</title>
     <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>   
    <div class="container">
      <div class="title">NOVA</div>
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">product</a>
           <div class="menuitem"><a href ="People.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">contact us</a></div
        </div>
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="images.jfif" alt="img">
          <div class="contenttext">
            An adventure game is a video game in which the player assumes the role of a protagonist
            in an interactive story driven by exploration and/or puzzle-solving. The genre's focus on 
            story allows it to draw heavily from other narrative-based media, literature and film,
            encompassing a wide variety of literary genres. Many adventure games are designed for
            single player, since this emphasis on story and character makes multiplayer design difficult.
            <br>
            Adventure games continue to be popular in the form of visual novels, which
            make up nearly 70% of PC games released in Japan.Asian countries have also found
            markets for adventure games for portable and mobile gaming devices. Japanese 
            adventure-games tend to be distinct from Western adventure  games and have 
            their own separate development history.
          </div>
        </div>
       
      </div>
      <div class="footer">
        Copyright &#169; 2023  Lexical Private Limited, Developed by Yamesh
      </div>
    </div>
  </body>
</html>
```
product.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NOVA</title>
     <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>
    <div class="container">
      <div class="banner">NOVA</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRjg7XLRNypFgPxctEeC22iejUzaA-9E6uE-A&usqp=CAU" alt="product image">
                  </div>
                  <div class="itemname">FOOTBALL EVO</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3mL825i9sgv56UeoByzlOtSQdwDFhmS2Z2w&usqp=CAU"  alt="product image">
                  </div>
                  <div class="itemname">CRICKET CRACKS</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Limited, Developed by Yamesh
      </div>
    </div>
  </body>
</html>
```
people.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NOVA</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
   
    </head>
    <body>
    <div class="container">
      <div class="banner">NOVA</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://images.pexels.com/photos/5668774/pexels-photo-5668774.jpeg?auto=compress&cs=tinysrgb&w=600" alt="founder">
                </div>
                <div class="itemname">JACK</div>
                <div class="itemprice">Founder</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://images.pexels.com/photos/3770296/pexels-photo-3770296.jpeg?auto=compress&cs=tinysrgb&w=600"  alt="manager">
                </div>
                <div class="itemname">FRED</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src=" https://images.pexels.com/photos/6888761/pexels-photo-6888761.jpeg?auto=compress&cs=tinysrgb&w=600"  alt="hr">
              </div>
              <div class="itemname">TONY</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://images.pexels.com/photos/8453802/pexels-photo-8453802.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Marketing">
              </div>
              <div class="itemname">PAULINO</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://images.pexels.com/photos/8261813/pexels-photo-8261813.jpeg?auto=compress&cs=tinysrgb&w=600"  alt="staff">
            </div>
            <div class="itemname">MINA</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="https://images.pexels.com/photos/5920774/pexels-photo-5920774.jpeg?auto=compress&cs=tinysrgb&w=600"  alt="Operation">
          </div>
          <div class="itemname">BEN</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2023 Lexical Private Limited, Developed by Yamesh
    </div>
  </div>
</body>
</html>
```
contactus.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NOVA</title>
     <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>
    <div class="container">
      <div class="banner">NOVA</div>
      <div class="menu">
        <div class="menuitem"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitemselected"><a href="contactus.html">Contact Us</a></div>
      </div>
      <hr>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            NOVA Private Limited ,Chennai-600 028
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.MOHAMED GOWS(MARKETING MANAGER):8220156869<br><br>
              Mrs.MADHAVAN(OPERATION MANAGER):9865432145<br><br>
              Mr.SACHIN SAGAR(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:Lexicalprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 LEXICAL Limited, Developed by yamesh
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
