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
```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="company.html">Home</a></div>
        <div class="menuitem"><a href="product.html">Products</a></div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="static/images/iron.png" style="width:300px; height:300px;" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
                Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ

      </div>
    </div>
  </body>
</html>

```

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
    </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img1.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Simple Steps</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Author edision </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img4.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally PRIME</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img5.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Essential</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img6.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Power of simplcity </div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img7.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Impleating</div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img8.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Advance</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img9.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST 4th edision</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>

              
            
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
      </div>
    </div>
  </body>
</html>
```

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
        <div class="menuitemselected">
          <a href="product.html">Products</a>
        </div>
        <div class="menuitem"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
    </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img1.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Simple Steps</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img2.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Author edision </div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img3.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img4.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally PRIME</div>
                  <div class="itemprice">Price: Rs.18,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img5.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Essential</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img6.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Power of simplcity </div>
                  <div class="itemprice">Price: Rs.13,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img7.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Impleating</div>
                  <div class="itemprice">Price: Rs.14,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img8.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Advance</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="static/images/img/img9.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally GST 4th edision</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>

              
            
              
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
      </div>
    </div>
  </body>
</html>
```

```
<!DOCTYPE html>
{% load static %}
<html lang="en">
  <head>
    <title>Aj-Private Limited</title>
    <link rel="stylesheet" href="static/css/layout.css" />
    <link rel="icon" href="static/images/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">AJ-Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="company.html">Home</a></div>
         <div class="menuitem">
          <a href="product.html">Products</a></div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="contact.html">Contact Us</a></div>
        
        <div class="content">
        <div class="productcontent">    
          <h1>People Of Company </h1>
          <figure>

        
        <p>
            <img src="static/images/img2/pre.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>PRESIDENT</h2></figcaption>
        <hr>
        
      
        <p>
            <img src="static/images/img2/fou.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>FOUNDER</h2></figcaption>
        <hr>
        
        
       <p>
            <img src="static/images/img2/mang.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>CO-FOUNDER</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/head.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>DIRECTOR</h2></figcaption>
        <hr>
        
        
        <p>
            <img src="static/images/img2/vk.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>MANAGER</h2></figcaption>
        <hr>

        <p>
            <img src="static/images/img2/aj.png"
        width="332px" height="277px"> 
        </p>
        <figcaption> <h2>HEAD</h2></figcaption>
        <hr>
       </figure>
          </div>
      </div>
       <div class="footer">
       Copyright &#169; 2022 YUHAMA-Private.LTD, Developed by YUVARAJ
     </div>
    </div>
    
    
    
  </body>
 
</html>
```
## OUTPUT:

### Home Page:
![de4d3cc6-f499-4e9b-940f-a88c0ff0f5e6](https://user-images.githubusercontent.com/118343998/215250005-a47c59c8-3b18-4b2c-87c4-99b6b4ed20b1.jpeg)


![8a84ea69-1b68-4716-9451-1079cab7522b](https://user-images.githubusercontent.com/118343998/215250016-7d18ead5-2b6d-436b-b4e1-7f143fd43894.jpeg)
![18e017f5-46d3-43c6-ac05-4696c4fcf933](https://user-images.githubusercontent.com/118343998/215250018-3002425f-ea5d-454a-b3be-afab24ebd06d.jpeg)

![f96f4030-f2b7-4d5e-8ead-352f3d5a3f32](https://user-images.githubusercontent.com/118343998/215250022-b3dad8e6-c804-4379-aed3-4bd9a3dbada7.jpeg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
