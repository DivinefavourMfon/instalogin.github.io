<html>
    <head>
        <title>Instagram login</title>
        <link rel="icon" href="instagram.png">
        <style>
           @font-face {
            font-family: ese ;
            src: url(Fontspring-DEMO-blue_vinyl_regular_ps_ot.otf);
           }
           body{
            padding: 0;
            user-select: none;
            margin: 0;
            background-color: rgb(223, 211, 211);
           }
           .container{
            display: grid;
            place-items: center;
            text-align: center;
            margin-top: 10px;
           }
           .diagram{
            width: 320px;
            text-align: center;
            border: 1px solid rgb(173, 166, 166);
            background: white;
            height: fit-content;
           }
           .diagram1{
            width: 320px;
            font-weight: bold;
            font-family: segoe ui;
            text-align: center;
            border: 1px solid rgb(173, 166, 166);
            background: white;
            height: 60px;
            margin-top: 10px;
           }
           .diagram1 a{
            text-decoration: none;
           }
           #pa{
            padding-left: 30px;
            padding-bottom: 30px;
            padding-right: 30px;
            padding-top: 10px;
           }
           input{
            width: 100%;
            font-weight: bold;
            height: 27px;
            background-color: rgb(246, 242, 248);
            border: 1px solid rgb(201, 195, 195);
            border-radius: 3px;
            font-family: segoe ui;
           }
           input::placeholder{
            font-weight: bold;
           }
           #pas{
            margin-top: 10px;
           }
           .enter{
            color: white;
            font-weight: bold;
            margin-top: 15px;
            border-radius: 3px;
            background-color:rgb(107, 107, 233);
            border: none;
            width: 102%;
            height: 30px;
            font-family: Segoe UI;
           }
           .button:hover{
            color: rgb(107, 107, 233);
            background-color: white;
            border: 1px solid rgb(201, 195, 195);
           }
           #cont{
            padding-top: 90px;
            display:inline;
           }
           .line1{
            width: 40%;
            margin-top: 10px;
            height: 1px;
            float: left;
            background: rgb(201, 195, 195);
           }
           .line2{
            width: 40%;
            margin-top: 10px;
            height: 1px;
            float: right;
            background: rgb(201, 195, 195);
           }
           .tsc{
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-weight: bold;
            color: grey;
           }
           .diapa{
            padding: 15px;
           }
           .store{
            width: 170px;
            height:50px ;
            display: inline;
            background-color: rgb(32, 31, 31);
            border-radius: 10px;
            border: none;
            color: white;
           }
           #all{
            display: inline;
           }
           .apple{
            width: 40px;
            background-color: transparent;
            height: 40px;
            float: left;
           }
           .playstore{
            width: 35px;
            background-color: transparent;
            height: 35px;
            float: left;
           }
           .lap{
            padding: 5px;
           }
           @font-face {
            font-family: ese12;
            src: url('Product Sans Bold.ttf');
           }
        </style>
    </head>
    <body>
        <div class="container">
            <div class="diagram">
                <div id="pa">
              <a style="font-family: ese; font-size: 45px;">Instagram</a><br><br>

              <input type="text" placeholder="Phone number, email or username" required><br>
              <input type="password" placeholder="Password" id="pas" required><br>
              <button type="submit" class="enter" >Login</button><br>
              <div style=" font-size: 12px; font-weight: bold; color: grey; font-family: segoe ui; margin-top: 20px;"> Forgot your login details? <a href="#" style="color: darkblue; font-family: segoe ui; font-weight: bold; text-decoration: none;">Get help logging in.</a></div><br>
              <div id="cont">
              <div class="line1"></div>
                <a  class="tsc">OR</a>               
                <div class="line2"></div>
              </div>
                 <div  style="color: rgb(107, 107, 233); font-weight: bold;font-family: system-ui; margin-top: 15px;">
                   <a href="#" style="text-decoration: none; font-size: 17px;"> Login with facbook</a><br><br>
                   <a href="#" style="text-decoration: none; font-size:15x; font-weight:normal;">Forgot password?</a> 
                </div>
                 </div>
            </div>
            <div class="diagram1">
                <div class="diapa">
                   Don't have account? <a href="#"> Sign up</a>
                </div>
            </div>
         <a style="font-family: system-ui; font-weight: normal;"> Get app.</a>  <br>
         <div id="all">
            <button class="store">
                <div class="lap">
                <img src="apple1.png" class="apple">
                <div style="float: left; margin-left: px;"><a style="font-size: 10px;margin-left: -3px;">Download on the</a><br>
                    <a style="font-size: 20px; font-weight: bold;margin-left: 5px;">App Store</a> </div>
                </div>
            </button>

            <button class="store">
                <div class="lap">
                <img src="playstore.png" class="playstore">
                <div style="float: left; "><a style="font-size: 10px;margin-left: 3px; float: left; font-weight: bold;">GET IT ON</a><br>
                    <a style="font-size: 17px; font-weight: bold;margin-left: 5px; font-family: ese12;">Google Play</a> </div>
                </div>
            </button>
        </div>
        </div>
    </body>
</html>
