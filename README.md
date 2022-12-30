# coding_ninja_KOC11_Cipherschools
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            padding: 0px;
            margin: 0px;
        }

        .container {
            display: grid;
            grid-template-columns: auto 700px 400px;
        }

        .mid {
            border: 2px solid rgb(71, 71, 145);
            height: 300px;
            background-image: url("pexels-photo-87223 xzzxxczxc.jpeg");
            background-size: 100% 100%;
            margin: 0px;
        }

        .item {
            height: 60px;
        }

        #logo {
            background-color: aqua;
        }

        #list {
            margin: 0px;
        }

        #list li {
            display: inline-block;
            margin: 0px 0px 0px 80px;
            font-size: larger;
        }

        .button1 {
            margin: 16px 0px 0px 50px;
            width: 130px;
            background-color: rgba(182, 180, 252, 0.758);
            padding: 4px;
        }

        .button2 {
            margin: 16px 0px 0px 50px;
            background-color: rgba(182, 180, 252, 0.758);
            width: 130px;
            padding: 4px;
        }

        .image {
            /* width: 100% ; */
            background-size: 100% 100%;
        }

        .search {

            width: 550px;
            margin: 150px 0px 0px 500px;
            padding: 0px;
        }

        #location {
            background-color: rgba(182, 180, 252, 0.758);
            width: 150px;
            padding: 5px;
            margin: 0px;
        }

        #type {
            background-color: rgba(182, 180, 252, 0.758);
            width: 150px;
            padding: 5px;
        }

        #Budget {
            background-color: rgba(182, 180, 252, 0.758);
            width: 150px;
            padding: 5px;
        }

        #botton {
            padding: 4px;
        }

        #logo {
            background-size: 100% 100%;
            background-image: url("Screenshot_2.png");
        }

        .list :hover {
            cursor: pointer;
            background-color: rgba(182, 180, 252, 0.758);
        }
        .photo{
            border: 4px solid black;
            border-collapse: collapse;
            display: grid;
            grid-template-columns: auto auto auto auto;
            height: 210px;
            /* margin: 5px; */
            

        }
        .photo1{
            border: 3px solid black;
            grid-template-columns: 200px auto auto;
        }
        .photo1{
            border: 3px solid black;
            background-image: url("https://images.pexels.com/photos/323780/pexels-photo-323780.jpeg?auto=compress&cs=tinysrgb&w=600");
            background-size: 100% 100%;
        }.photo2{
            border: 3px solid black;
            background-image: url("https://images.pexels.com/photos/1396132/pexels-photo-1396132.jpeg?auto=compress&cs=tinysrgb&w=600");
            background-size: 100% 100%;
        }.photo3{
            border: 3px solid black;
            background-image: url("https://images.pexels.com/photos/206172/pexels-photo-206172.jpeg?auto=compress&cs=tinysrgb&w=600");
            background-size: 100% 100%;
        }
        .photo4{
            border: 3px solid black;
            background-image: url("https://images.pexels.com/photos/164558/pexels-photo-164558.jpeg?auto=compress&cs=tinysrgb&w=600");
            background-size: 100% 100%;
        }
        .thank{
            /* border: 2px solid black; */
            /* margin: 5px; */
            height: 150px;
        }
        .about{
            /* border: 2px solid black; */
            width: 70px;
            margin: 5px 0px 0px 0px;
            border: 2px solid black;
            background-color: rgba(182, 180, 252, 0.758);
            padding: 3px;

        }
        .thankyou{
            /* border: 2px solid black;  */
            background-color: rgba(182, 180, 252, 0.758);
            margin: -79px 0px 0px 1000px;
            width: 260px;
            padding: 7px;
            font-size: 25px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="item" id="logo">
            <!-- <img src="Screenshot_2.png" alt=""> -->


        </div>
        <div class="item" id="list">
            <ul class="list">
                <li>Buy</li>
                <li>Rent</li>
                <li>Sell</li>
                <li>contact us</li>
            </ul>
        </div>
        <div class="item" id="login">
            <form action="">
                <input type="button" value="Signup" class="button1">
                <input type="button" value="login" class="button2">
            </form>
        </div>
    </div>
    <div class="mid">
        <div class="search">
            <label for="Location" class="location"></label>
            <select name="Location" id="location">
                <option value="1" selected>Location</option>
                <option value="2">Delhi</option>
                <option value="3">Mumbai</option>
                <option value="4">Bangluru</option>
                <option value="5">Jaipur</option>
                <option value="6">Chennai</option>
                <option value="7">Kolkata</option>
                <option value="8">Hyderabad</option>
                <option value="9">Surat</option>
                <option value="10">Ahmedabad</option>
            </select>

            <select name="Property type" id="type">
                <label for="Property Type" class="type"></label>

                <option value="1" selected>Property Type</option>
                <option value="2">2BHK</option>
                <option value="3">3BHK</option>
                <option value="4">4BHK</option>
                <option value="5">5BHk</option>
            </select>

            <label for="Budget" class="Budget"></label>
            <select name="Budget" id="Budget">
                <option value="1" selected>Budget</option>
                <option value="2">1cr-1.5cr</option>
                <option value="3">1.5cr-2cr</option>
                <option value="4">2cr-2.5cr</option>
                <option value="5">2.5cr-3cr</option>
                <option value="6">3cr-3.5cr</option>
                <option value="7">3.5cr-4cr</option>
                <option value="8">4cr and above</option>
            </select>
            <input type="button" value="Search" id="botton" placeholder="Search">
        </div>
    </div>

    <div class="photo">
        <div class="photo1"></div>
        <div class="photo2"></div>
        <div class="photo3"></div>
        <div class="photo4"></div>
    </div>
    <div class="thank">
         <div class="about">
            About Us
         </div>
         <p> Shubham Properties has very good, experienced professionals who know real estate and have lived <br> and worked  through a number of market cycles and can make transactions happen. You can have absolute <br> confidence that the  team at Shubham Properties has the capability to assist you in navigating through <br> what may be more challenging times.
        </p>
        <div class="thankyou">
            Thank you for chosing us
        </div>
    </div>
</body>

</html>
