# SOCIAL-SERVICE
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .menu-bar {
            text-align: center;
            background: linear-gradient(180deg, rgba(0, 0, 0, 0) calc(50% - 5px), rgba(192, 192, 192, 1) calc(60%), rgba(0, 0, 0, 0) 50%);
        }

        .menu-bar ul {
            display: inline-flex;
            list-style: none;
        }

        .menu-bar ul li {
            width: 170px;
            margin: 15px;
            padding: 15px;
        }

        .menu-bar ul li a {
            text-decoration: none;
            color: black;
        }

        .menu-bar ul li a:hover {
            border: 1px solid black;
            border-radius: 3px;
        }

        .sub-menu {
            display: none;
        }

        .menu-bar ul li:hover .sub-menu {
            display: block;
            position: absolute;
            background: white;
            margin-top: 15px;
            margin-left: -15px;
        }

        .menu-bar ul li:hover .sub-menu ul {
            display: block;
            margin: 10px;
        }

        .menu-bar ul li:hover .sub-menu ul li {
            width: 150px;
            padding: 10px;
            border-bottom: 1px dotted whitesmoke;
            background: transparent;
            border-radius: 0;
            text-align: left;
        }

        .menu-bar ul li:hover .sub-menu ul li:last-child {
            border-bottom: none;
        }

        .menu-bar ul li:hover .sub-menu ul li a:hover {
            color: black;
        }

        .sub-menu-1 {
            display: none;
        }

        .hover-me:hover .sub-menu-1 {
            display: block;
            position: absolute;
            margin-top: -40px;
            margin-left: 140px;
            background: lightgray;

        }

        .img {
            float: right;
            width: 40%;
        }

        .img img {
            height: auto;
            width: 100%;
            padding-right: 2%;
            padding-top: 10%;
            box-shadow: 2px 5px lightgray;
        }

        .registration-form {

            width: 250px;
            height: 350px;
            position: absolute;
            border: 2px;
            border-style: solid;
            background-color: rgba(0, 0, 0, 0.5);
            box-shadow: 2px 2px 15px rgba(0, 0, 0, 0.3);
            color: #fff;
        }

        .registration-form h2 {
            text-align: center;
            font-family: 'Oswald', sans-serif;
            padding: 20px;
        }

        form .ok {
            margin: 40px;
        }

        label {
            cursor: pointer;
            font-family: sans-serif;
            font-size: 18px;
            font-style: normal;
        }

        input .name {
            width: 300px;
            border: 1px solid #ddd;
            border-radius: 3px;
            outline: 0;
            padding: 7px;
            background-color: #fff;
            box-shadow: inset 1px 1px 5px rgba(0, 0, 0, 0.3);
        }

        .submit {
            width: 200px;
            padding: 7px;
            font-size: 27px;
            font-family: sans-serif;
            font-weight: 600;
            border: none;
            border-radius: 3px;

            color: #fff;
            cursor: pointer;

            margin-bottom: 20px;
        }
    </style>
</head>

<body>
    <div id="mouse">
        <h1>social services</h1>
    </div>
    <div class="menu-bar">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">CATEGORY</a>
                <div class="sub-menu">
                    <ul>
                        <li class="hover-me"><a href="#">government schemes</a>
                            <div class="sub-menu-1">
                                <ul>
                                    <li><a href="tut94.html">MGNREGA</a></li>
                                    <li><a href="tut95.html">NRLM</a></li>
                                    <li><a href="tut101.html">SGSY</a></li>
                                    <li><a href="tut96.html">NRHM</a></li>
                                    <li><a href="tut97.html">SSA</a></li>
                                    <li><a href="tut98.html">MDM</a></li>
                                    <li><a href="tut99.html">NBA</a></li>
                                    <li><a href="tut100.html">NHM</a></li>
                                </ul>

                            </div>


                        </li>

                    </ul>
                </div>
            </li>
            <li><a href="tut102.html">WHY TO JOIN US ?</a></li>
            <li><a href="#">LOGIN</a></li>
        </ul>
    </div>
    <div class="img">
        <img src="p2.jpg">
    </div>
    <div class="registration-form">
        <h2>register now</h2>
        <form id="ok" method="post">
            <label> name :</label>
            <br>
            <input type="text" name="fname" id="name" placeholder="enter your full name">
            <br><br>
            <label> email id :</label>
            <br>
            <input type="text" name="fname" id="email id" placeholder="enter your valid email id">
            <br><br>
            <label> phone no. : </label>
            <br>
            <input type="text" name="phone" id="name" placeholder="enter your phone no.">
            <br><br>
            <label> gender : </label>
            <br>
            &nbsp;&nbsp;&nbsp;
            <input type="radio" name="gender" id="male">
            &nbsp;
            <span id="male">male</span>
            &nbsp;&nbsp;&nbsp;&nbsp;
            <input type="radio" name="gender" id="female">
            &nbsp;
            <span id="female">female</span>
            <br><br>
            <input type="submit" value="submit" name="submit" id="submit">

        </form>

    </div>



</body>

</html>
