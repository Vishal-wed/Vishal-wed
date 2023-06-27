<!DOCTYPE html>

<html lang="en">



<head>

    <meta charset="UTF-8">

    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Free Fire</title>

</head>

<style>

    body {

        background-color: rgba(0, 0, 0, 0.775);

    }

    

    img {

        border-radius: 25px;

        height: 160px;

        margin-top: 15px;

        margin-left: 15px;

    }

    

    #ba {

        height: 150px;

        background-color: rgba(255, 255, 255, 0.377);

        border-radius: 25px;

        margin-top: 30px;

    }

    

    #rent {

        font-size: 35px;

        margin-top: -120px;

        margin-left: 680px;

    }

    

    #in1 {

        background-color: rgba(255, 255, 255, 0.436);

        border: none;

        border-bottom: 5px black;

    }

    

    input {

        height: 25px;

        width: 250px;

    }

    

    #t1 {

        text-align: center;

        font-size: 25px;

    }

    

    h3 {

        font-size: 35px;

        text-align: center;

    }

    #card

    {

        align-items: center;

        height: 250px;

        width:  305px;

        background-color: #fff;

        margin-top: 150px;

        margin-left: 130px;

        border-bottom-left-radius: 25px;

        border-bottom-right-radius: 25px;

    }

    #card1

    {

        align-items: center;

        height: 250px;

        width:  305px;

        background-color: #fff;

        margin-top: -253px;

        margin-left: 590px;

        border-bottom-left-radius: 25px;

        border-bottom-right-radius: 25px;

    }

    #card2

    {

        align-items: center;

        height: 250px;

        width:  330px;

        background-color: #fff;

        margin-top: -253px;

        margin-left: 1050px;

        border-bottom-left-radius: 25px;

        border-bottom-right-radius: 25px;

    }

    #text1

    {

        font-size: 30px;

        margin-top: 18px;

        margin-left: 110px;

        background-color: rgba(0, 0, 0, 0.775);

        border-radius: 5px;

        color: #fff;

    }

    #text2

    {

        font-size: 30px;

        margin-top: 20px;

        margin-left: 110px;

        background-color: rgba(0, 0, 0, 0.775);

        border-radius: 5px;

        color: #fff;

    }

    #text3

    {

        font-size: 30px;

        margin-top: 18px;

        margin-left: 90px;

        background-color: rgba(0, 0, 0, 0.775);

        color: #fff;

        border-radius: 5px; 

    }

    #car1

    {

        margin-top: 20px;

        margin-left: 18px;

    }

    #car2

    {

        margin-top: 20px;

        margin-left: 21px;

    }

    #car3

    {

        margin-top: 20px;

        margin-left: 25px;

    }

    #pops_back1

    {

        display: none;

        height: 100%;

        width: 100%;

        background-color: #0000009d;

        position: absolute;

        top: 0;

    }

    #pops1

    {

        text-align: center;

        margin-top: -20px;

        margin-left: 470px;

        background-color: #fff;

        width: 550px;

        font-size: 23px;

        height: 450px;

        border-radius: 25px;

        text-align: center;

    }

    #pops_img1

    {

        margin-top: -25px;

        margin-left: -10px;

    }

    #pops_close1

    {

        border-radius: 50%;

        height: 25px;

        margin-top: 160px;

        margin-left: 1015px;

        cursor: pointer;

    }

    #pops_back2

    {

        display: none;

        height: 100%;

        width: 100%;

        background-color: #0000009d;

        position: absolute;

        top: 0;

    }

    #pops2

    {

        text-align: center;

        margin-top: -20px;

        margin-left: 470px;

        background-color: #fff;

        width: 550px;

        font-size: 23px;

        height: 450px;

        border-radius: 25px;

        text-align: center;

    }

    #pops_img3

    {

        margin-top: -25px;

        margin-left: -10px;

    }

    #pops_close2

    {

        border-radius: 50%;

        height: 25px;

        margin-top: 160px;

        margin-left: 1015px;

        cursor: pointer;

    }

    #pops_back3

    {

        display: none;

        height: 100%;

        width: 100%;

        background-color: #0000009d;

        position: absolute;

        top: 0;

    }

    #pops3

    {

        text-align: center;

        margin-top: -20px;

        margin-left: 470px;

        background-color: #fff;

        width: 550px;

        font-size: 23px;

        height: 450px;

        border-radius: 25px;

        text-align: center;

    }

    #pops_img2

    {

        margin-top: -25px;

        margin-left: -10px;

    }

    #pops_close3

    {

        border-radius: 50%;

        height: 25px;

        margin-top: 160px;

        margin-left: 1015px;

        cursor: pointer;

    }



</style>



<body id="body">

    <div>

        <div id="ba">

            <img id="img" src="logo.png">

            <p id="rent">

                CAR ON RENT

            </p>

        </div>

    </div>

    <div id="card">

        <img src="car1.jpg" id="car1">

        <button id="text1" class="text1">Supra</button>

    </div>

    <div id="card1">

        <img src="car3.jpg" id="car3">

        <button id="text3" class="text3">Mustang</button>

    </div>

    <div id="card2">

        <img src="car2.jpg" id="car2">

        <button id="text2" class="text2">scorpio</button>

    </div>

    <div id="pops_back1">

        <img id="pops_close1" class="pops_close1" src="close.jpg">

        <div id="pops1">

            <img src="car1.jpg" id="pops_img1">

            <p>Toyota Supra</p>

            <P>Cylinders : Inline 6</P>

            <p>Base engine type : GAS</p>

            <p>Horsepower : 220hp @ 5,800rpm</p>

            <p>Torque : 210 ib-ft @ 4,800rpm</p>

            <p>price : 4 Crore</p>

        </div>

    </div>

    <div id="pops_back2">

        <img id="pops_close2" class="pops_close2" src="close.jpg">

        <div id="pops2">

            <img src="car3.jpg" id="pops_img1">

            <p>Mustang 1967</p>

            <P>Cylinders : V 8</P>

            <p>Base engine type : GAS(3.3L)</p>

            <p>Horsepower : 390hp</p>

            <p>RPM : 2,048,280 rpm</p>

            <p>price : 3.5 Crore</p>

        </div>

    </div>

    <div id="pops_back3">

        <img id="pops_close3" class="pops_close3" src="close.jpg">

        <div id="pops3">

            <img src="car2.jpg" id="pops_img1">

            <p>Mahindra scorpio</p>

            <P>Cylinders : Inline 6</P>

            <p>Base engine type : Diesel</p>

            <p>Horsepower : 75bhp</p>

            <p>Body : wild</p>

            <p>price : 20 lakh</p>

        </div>

    </div>

    <script>

        document.getElementById("text1").addEventListener("click",function(){

            document.querySelector("#pops_back1").style.display = "block";

        })

        document.querySelector(".pops_close1").addEventListener("click",function(){

            document.querySelector("#pops_back1").style.display = "none";

        })







        document.getElementById("text3").addEventListener("click",function(){

            document.querySelector("#pops_back2").style.display = "block";

        })

        document.querySelector(".pops_close2").addEventListener("click",function(){

            document.querySelector("#pops_back2").style.display = "none";

        })







        document.getElementById("text2").addEventListener("click",function(){

            document.querySelector("#pops_back3").style.display = "block";

        })

        document.querySelector(".pops_close3").addEventListener("click",function(){

            document.querySelector("#pops_back3").style.display = "none";

        })

    </script>







</body>

</html>
