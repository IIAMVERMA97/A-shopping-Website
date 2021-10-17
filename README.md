# A-shopping-Website
This site was made for online shopping by html and CSS.

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My Shop</title>
    <link href="https://use.fontawesome.com/releases/v5.0.8/css/all.css" rel="stylesheet">
<link rel="shortcut icon" href="tez.png" type="image/png" style="border-radius:10px;">
    <link rel="stylesheet" type="text/css" href="style.css"/>
    <header class="header1">
<div id=header><p>World's Fastest Growing Site for Online Shopping</p></div>
    </header>
    <script type="text/javascript">
      function openSlideMenu(){
        document.getElementById('side-menu').style.width='250px';
        document.getElementById('main');
      }
      function closeSlideMenu(){
        document.getElementById('side-menu').style.width='0px';
        document.getElementById('main').style.marginLeft='0px';
      }
      // When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
    if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
        document.getElementById("myBtn").style.display = "block";
    } else {
        document.getElementById("myBtn").style.display = "none";
    }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
    document.body.scrollTop = 0; // For Safari
    document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
}
    </script>
    <header id=mainheader>
      <div id=1st class=logo>
        <span id=ist ><a href="http://www.facebook.com">Shopper's </a></span>&nbsp;<span id=iist ><a href="http://www.facebook.com">street</a></span>
      </div>
      <!--search area-->
      <div id=search>
        <form action="" method="post">

          <select class="select-cat" title="select category">
            <option selected=selected><a href="#" class=all>All</a></option>
            <option><a href="#">All Categories</a></option>
            <option><a>Lifestyle</a></option>
            <option><a>Electronics</a></option>
            <option><a>Grocery</a></option>
            <option><a>Sports</a></option>
            <option><a>Stationery</a></option>
            <option><a>Music</a></option>
            <option><a>Movies</a></option>
            <option><a>Books</a></option>
            <option><a>Cars</a></option>
            <option><a>Gadgets</a></option>
          </select>

          <input type="text" class="searcharea" list="items" name="searchtext" placeholder="Search">
          <datalist id=items>
          <option value="Moto X4">In Electronics</option>
          <option value="Mi A1">In Electronics</option>
          <option value="LeEco Le 2">In Electronics</option>
          <option value="LeEco Le 1s">In Electronics</option>
          <option value="HP Pavillion">In Electronics</option>
          <option value="Acer Predator">In Electronics</option>
          <option value="Honor 9i">In Electronics</option>
          <option value="Mobile Back Covers">in Accesories</option>
          <option value="Moto G5 S plus">in Electronics</option>
          <option value="Fastrack Watches">in Watches</option>
          <option value="Object Oriented Programming in C++">In Books and Novels</option>

          </datalist>
          <a href="#"><img class="search-btn" src="search.png"></a>
        </form>

      </div>
      <!--Cart and Login-->
      <div id=cart_login>
      <span class=cart><a href="#"><i style="font-size:35px;margin-left:-5px;color:white;margin-top:5px;" class="fas fa-shopping-cart"></i><p class=image-caption >Cart</p></a></span>
    <span class=login><a href="login.html" target="_blank">
      <i style="font-size:35px;color:white;margin-top:5px;margin-left:20px;" class="fas fa-user-circle"></i>
      <p class=image-caption >Login/Signup</p></a><span>
      </div>
    </header>
    <div class="divide">
    </div>
    <div class="navigation">
      <span class="open-slide">
    <a href="#" class=open-btn onclick="openSlideMenu()">
    <div></div>
    <div></div>
    <div></div>
    </a>
    </span>
    <div id="side-menu" class="side-nav">
      <a href="#" class="btn-close" onclick="closeSlideMenu()">&times;</a>
      <a href="#"><i class="fas fa-home"></i>&nbsp;Home</a>
      <a href="#"><i class="fas fa-info-circle"></i>&nbsp;About</a>
      <a href="#"><i class="fas fa-wrench"></i>&nbsp;Services</a>
      <a href="#"><i class="far fa-envelope"></i>&nbsp;Contact</a>

    </div>
    <ul class=menu-options>
      <li><a href="index.html">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
      <li><a href="#">Great Deals</a></li>
    </ul>
    </div>
    <button onclick="topFunction()" id="myBtn" title="Go to top">Go To Top</button>
    </head>
  <body>
    <div class="Slider">
      <div id=sliderbox>
        <img src="slider8.jpg"/>
        <img src="slider2.jpg"/>
        <img src="slider3.jpg"/>
        <img src="slider4.jpg"/>
        <img src="slider13.jpg"/>
        <img src="slider6.jpg"/>
        <img src="slider7.jpg"/>
      </div>
    </div>
    <div class="Categories">
      <p id=shop-for>Shop For</p>
      <span><ul id=cat-image-list>
        <li><img src="slider23.jpeg"></li>
        <li><img src="slider20.jpeg"></li>
        <li><img src="slider21.jpeg"></li>
        <li><img src="slider24.jpeg"></li>
        <li><img src="cat5.jpg"></li>
      </ul></span>
    </div>
    <div class="Main-content">
      <h1>Today's Deals</h1>
      <section>
        <div class="product">
          <a href=describe2.html><div class="product-card">
            <div class="product-image">
              <img src="product1/first.jpg" alt=product >
            </div>
            <div class="product-info">
              <h3>₹150</h3>
              <h4>₹<del>549</del></h4>
              <h5>Only 1 left in stock</h5>
            </div>
          </div></a>
        <a href=#>  <div class="product-card">
            <div class="product-image">
              <img src="product6/first.jpg" alt=product >
            </div>
            <div class="product-info">
              <h3>₹800</h3>
              <h4>₹<del>1500</del></h4>
              <h5>Only 3 left in stock</h5>
            </div>
          </div></a>
          <a href="#"><div class="product-card">
            <div class="product-image">
              <img src="product3/first.jpg" alt=product >
            </div>
            <div class="product-info">
              <h3>₹750</h3>
              <h4>₹<del>900</del></h4>
              <h5>Only 5 left in stock</h5>
            </div>
          </div></a>
          <a href="#"><div class="product-card">
            <div class="product-image">
              <img src="product4/first.jpg" alt=product >
            </div>
            <div class="product-info">
              <h3>₹280</h3>
              <h4> ₹<del>288</del> </h4>
              <h5>Only 2 left in stock</h5>
            </div>
          </div></a>
        </div>
      </section>
    </div>
    <div class="Sidebar1">
      <div id=adds>
      <ul class=add_img>
        <li><img src="add2.jpg"/></li>
        <li><img src="offer10.jpg"/></li>
        <li><img src="offer6.jpg"/></li>
        <li><img src="offer7.jpg"/></li>
      </ul>
    </div>

    </div>
    <div class="recent-items">
      here comes the recent-items
    </div>
    <div class="footer">
      <div class="lists">
        <ul>
          <li class=mainl><h3>Get to Know us</h3>
          <ul class="list1">
            <li>  <a href="#">About us</a> </li>
            <li>  <a href="#">Press Release</a> </li>
            <li>  <a href="#">Our Services</a> </li>
            <li>  <a href="#">NGOs Run By Shopper's Street</a> </li>
          </ul></li>
        <li class=mainl>  <h3>Connect with us</h3>
          <ul class="list2">
            <li id=facebook>  <a href="https://www.facebook.com/ashutoshsinghai7"><i class="fab fa-facebook-f"> </i>&nbsp; Facebook </a></li>
            <li id=twitter>  <a href="https://twitter.com/"><i class="fab fa-twitter"></i>&nbsp; twitter</a></li>
            <li id=insta>  <a href="https://www.instagram.com/ashutosh_singhai"><i class="fab fa-instagram"></i>&nbsp; Instagram </a> </li>
            <li id=google>  <a href="https://plus.google.com/u/0/101489217324020959317"><i class="fab fa-google-plus-g"></i>&nbsp; Google+</a></li>
            <li id=youtube>  <a href="https://www.youtube.com/">
              <i class="fab fa-youtube"></i>&nbsp; Youtube </a></li>
          </ul>
        </li>
        <li class=mainl>
          <h3>Payment Methods</h3>
          <ul class="list3">
            <li>  <a href="#">Credit card &nbsp;<i class="fas fa-credit-card"></i></a> </li>
            <li>  <a href="#">Debit card &nbsp; <i class="far fa-credit-card"></i></a> </li>
            <li>  <a href="#">Net Banking</a> </li>
            <li>  <a href="#">Mobile wallets</a> </li>
            <li>
              <ul>
                <li> <a href="https://www.visa.co.in/pay-with-visa/find-a-card/debit-cards.html"><img src="cards-logo.png" height=30px></a> </li>
                <li> <a href="https://www.phonepe.com/en/"><img id=phonepe src="phonepe.png" height=30px></a> </li>
                <li> <a href="https://tez.google.com/"><img id=tez src="tez.png" height=30px></a> </li>
              </ul>
            </li>
          </ul>
        </li>
        <li class=mainl>
          <h3>Let us help You</h3>
          <ul class="list4">
            <li>  <a href="#">Your Account</a> </li>
            <li>  <a href="#">Return Center</a> </li>
            <li>  <a href="#">100% guarenteed Returns</a> </li>
            <li>  <a href="#"><i class="far fa-question-circle"></i>&nbsp;Help</a> </li>
          </ul>
        </li>
</ul>
      </div>
      <div style="clear:both;padding-top:40px;width:95%;margin-left:30px;" class="hr">
<hr style="display:block;height:1px;border:none;background:grey;"/ >
      </div>
      <table class=table-last align=center cellspacing=0px cellpadding=15px border=1px>
        <tr>
          <td>Track Your Orders <img id=track src="trackers.png" height="50" align=middle></td>
          <td>Easy and Fast Returns <img id=return src="returns.png" height="50" align=middle></td>
          <td>Online Cancellations <img id=cancellation src="cancellation.png" height="50" align=middle></td>
        </tr>
      </table>
      <h3 id=partners>Our Business Partners</h3>
      <div class="partners">

<ul>
  <li> <a href="https://www.flipkart.com"><img src="partners/flipkart.png"></a> </li>
  <li> <a href="https://www.amazon.in"><img src="partners/amazon.png"></a> </li>
  <li> <a href="https://www.hp.com"><img src="partners/hp.jpg"></a> </li>
  <li> <a href="http://www.spacex.com"><img src="partners/spacex.png"></a> </li>
  <li> <a href="https://www.microsoft.com"><img src="partners/microsoft.png"></a> </li>
  <li> <a href="https://www.alibaba.com"><img src="partners/alibaba.jpg"></a> </li>
  <li> <a href="https://www.paypal.com/us/home"><img src="partners/paypal.png"></a> </li>
</ul>
      </div>
      Copyright &copy; 2018 Shopper's Street All Rights Reserved.
    </div>
  </body>
</html>
![Screenshot (244)](https://user-images.githubusercontent.com/44067922/137624722-97cff64b-8525-49a0-9e13-c22d9aef4635.png)
![Screenshot (245)](https://user-images.githubusercontent.com/44067922/137624778-1353fa5f-3670-430e-a41e-c54f92717f1b.png)
