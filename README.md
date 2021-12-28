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

### Home Page code:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Amazon Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/images.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">amazon</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/1r.jpg" alt="Homemade products" />
          <div class="contenttext">
            <b>Hello! Thanks for dropping into our store.
              We hope you found something you love. The amazon store is a space for people
              by people.
              Our aim is to create a space which celebrates the love of handmade product makers.
            </b>
              <br /><br><br>
              We take a lot of effort to try and provide customers like you with an awesome
              range of products that connects with you, is unique and most importantly is of great
              quality.
              We hope we have been able to give you this today. However, if you are less
              than happy with something you have picked from us, please feel free to reach out to me or
              my colleagues on the contact numbers mentioned at the end of this & we will be happy to
              assist you.
              <br>
              To tell you a bit more about us, here are 4 quick facts about us:
              <ul>
                <li>We're a young Saveetha Engineering College student</li>
                <li>Our first store was launched in M.G.R Street, Chennai & response we now
                have 8 physical stores across Bangalore, Mumbai, Chennai, Hyderabad, Pune and Surat.</li>
                <li>We sell only original merchandise, which means the content producers
                get a royalty per piece we sell.</li>
              </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Amazon Private Limited, Developed by Hariharan M.
      </div>
    </div>
  </body>
</html>

~~~
### Product Page code:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Amazon Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Amazon Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gft.jpg" alt="product image">
                  </div>
                  <div class="itemname">Amazon gift card</div>
                  <div class="itemprice">Price: Rs.1000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/lap.png"  alt="product image">
                  </div>
                  <div class="itemname">Lenovo Ideapad</div>
                  <div class="itemprice">Price: Rs.10,00,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/echo_dot.jpg"  alt="product image">
                </div>
                <div class="itemname">Echo Dot</div>
                <div class="itemprice">Price: Rs.10,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/hoddie.jpg"  alt="product image">
                </div>
                <div class="itemname">Hoddie for Female</div>
                <div class="itemprice">Price: Rs.900 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ip.png"  alt="product image">
                </div>
                <div class="itemname">iphone-8</div>
                <div class="itemprice">Price: Rs.48,000</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/mask.jpg"  alt="product image">
                </div>
                <div class="itemname">Mask for men(3 layered)</div>
                <div class="itemprice">Price: Rs.120 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ram.jpg"  alt="product image">
                </div>
                <div class="itemname">Crucial 8gb-2400mhz</div>
                <div class="itemprice">Price: Rs.8900 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/shoe.jpg"  alt="product image">
                </div>
                <div class="itemname">Amazon shoe</div>
                <div class="itemprice">Price: Rs.1999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ssd.jpg"  alt="product image">
                </div>
                <div class="itemname">Samsung 1Tb SSD</div>
                <div class="itemprice">Price: Rs.11000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/stick.jpg"  alt="product image">
                </div>
                <div class="itemname">Fire Stick for TV</div>
                <div class="itemprice">Price: Rs.2999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/tab.jpg"  alt="product image">
                </div>
                <div class="itemname">Amazon Fire tab</div>
                <div class="itemprice">Price: Rs.9999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/watch.png"  alt="product image">
                </div>
                <div class="itemname">Rolex Watch</div>
                <div class="itemprice">Price: Rs.15000 </div>
              </div>
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Obed Otto.
      </div>
    </div>
  </body>
</html>

~~~
### People Page code:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>Avengers Private Limited</title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/icon.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner">Avengers</div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem">
<a href="/static/products.html">Products</a>
</div>
<div class="menuitemselected"><a href="/static/people.html">People</a></div>
<div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
</div>
<div class="content">
<div class="productcontent">
<h1>Our Leadership</h1>
<div class="productitems">
<div class="productitem">
<div class="itemimage">
<img src="/static/img/andrewt.png" alt="Andrew Garfield">
</div>
<div class="itemname">Andrew Garfield</div>
<div class="itemprice"><b>Chairman</b></div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/emat.png" alt="Emma Stone">
</div>
<div class="itemname">Emma Stone</div>
<div class="itemprice"><b>Chief Executive Officer</b></div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/zent.png" alt="Zendaya">
</div>
<div class="itemname">Zendaya</div>
<div class="itemprice"><b>Managing Director</b></div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/tomt.png" alt="Tom Holland">
</div>
<div class="itemname">Tom Holland</div>
<div class="itemprice"><b>Chief Operating Officer</b></div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/galgt.png" alt="Gal Gadot">
</div>
<div class="itemname">Gal Gadot</div>
<div class="itemprice"><b>Executive Director</b></div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/tobyt.png" alt="Tobby">
</div>
<div class="itemname">Tobby</div>
<div class="itemprice"><b>Director</b></div>
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Amazon Private Limited, Developed by Harihran M
</div>
</div>
</body>
</html>
~~~
### Contact Page code:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>Amazon Private Limited</title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/images.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner">Amazon</div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem">
<a href="/static/products.html">Products</a>
</div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="content">
<div class="productcontent">
<h2>Contact Info</h2>
<div>Saveetha Engineering College,
kanchepuram high way<br>
kanchepuram 600 068, India<br>
Customer Care:1800 129 2183<br>
E-mail: amazonpvt@gmail.com
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Amazon Private Limited, Developed by Hariharan M
</div>
</div>
</body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./images/1.jpg)

### Product Page:

![output](./images/2pr.jpg)

### People Page:

![output](./images/3pe.jpg)

### Contact Page:

![output](./images/4c.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
