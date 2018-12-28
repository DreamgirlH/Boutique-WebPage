# Boutique-WebPage
website
<!DOCTYPE html>
<html>

<head>

    <style>
        .newDiv {
            background-color: lightgreen;
        
        }
        
        .updatedDiv {
            background-color: green
        }
        
        .size {
            size: "60px"
        }
        
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            display: flex;
            justify-content: center;
        }
        
        li {
            float: left;
        }
        
        li a {
            display: block;
            color: seagreen;
            text-align: center;
            padding: 16px;
            text-decoration: hsl(hue, saturation, lightness);
        }
        #yo{
            float: right;
        }
        #sub{
            alib   
        }
    </style>


    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ"
        crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n"
        crossorigin="anonymous"></script>
    <!--<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>-->
    <link rel="stylesheet" href="./font-awesome-4.7.0/css/font-awesome.css">
    <!-- <i class="fa fa-facebook" aria-hidden="true"></i>
<i class="fa fa-instagram" aria-hidden="true"></i>
<i class="fa fa-search" aria-hidden="true"></i>
<i class="fa fa-twitter" aria-hidden="true"></i>
<i class="fa fa-pinterest-square" aria-hidden="true"></i>
<i class="fa fa-shopping-cart" aria-hidden="true"></i>
<i class="fa fa-user-circle-o" aria-hidden="true"></i> -->
</head>

<body>
    <div id="d1" class="newDiv">
        Habiba's Boutique
        <div id="yo" style="width:300px;">
            <a href="#" onClick="alert('Thanks for watching our Boutique dresses');">Click</a>
            <a href="#" onClick="alert('Special Eid Collection');">Click</a>
        </div>

    </div>

    <div id="d2" class="newdiv" style="display:flex;justify-content:space-between">
        <div style="width:300px;"> <img src="download.png" hieght="150px" width="105px" /></div>
            </div>

    <div id = "sub">
        Email "Lucky Draw"
        </br>
        <input type = "email" size = "25px" id="mail">
        </br>
        </br>
      <input type = "button" value = "submit" onclick="checkAddress('mail');">

        </div>








    <h2 class="page-title">Summer Collection 2017</h2>




    <ul>
        <li><a href="https://www.gulahmedshop.com/collections/eid-ul-azha-collection-2017">WOMEN</a></li>
        <li><a href="#MEN">MEN</a></li>
        <li><a href="#IDEAS HOME">IDEAS HOME</a></li>
        <li><a href="#SALE">SALE</a></li>
        <li><a href="#LOOK BOOK">LOOK BOOK</a></li>

        <li>
            <a href="http://www.facebook.com/Habiba's Boutique"> <i class="fa fa-facebook" aria-hidden="true"></i></a>
        </li>


        <li>
            <a href="http://instagram.com/Habiba's Boutique"> <i class="fa fa-instagram" aria-hidden="true"></i></a>
        </li>
        <li>
            <a href="/search"> <i class="fa fa-search" aria-hidden="true"></i></a>
        </li>
        <li>
            <a href="http://twitter.com/Habiba's Boutique"> <i class="fa fa-twitter" aria-hidden="true"></i></a>
        </li>
        <li>
            <a href="http://www.pinterest.com/Habiba's Boutique"> <i class="fa fa-pinterest-square" aria-hidden="true"></i></a>
        </li>
        <li>
            <a href="#cart"><i class="fa fa-shopping-cart" aria-hidden="true"></i> <span>cart</span></a>
        </li>
        <li>
            <a href="Login"><i class="fa fa-user-circle-o" aria-hidden="true"></i><span>Login</span></a>
        </li>
    </ul>

    <script>
        function checkAddress(field){
            var val = document.getElementById("mail").value;
            if  (val === "habibahjaved27@gmail.com"){
                alert ("You are Lucky person We gave you 20% discount on every dress This offer is only valid for you and only for limmited time");
            }
            
            else {
                alert("Try for Next Time");
            }
        }
        </script>




</body>

</html>
