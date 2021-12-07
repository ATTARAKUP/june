# june
Make it a web page on a home search site.
<!DOCTYPE html>
<html>

<head>
    <title>
        OurHome
    </title>
    <meta charset="UTF-8">
    <meta http-equiv="Content-Type" content="text/html; charset=UFT-8" />
    <link rel="stylesheet" href="Ourhome.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@300&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0px;
            padding: 0px;
            font-family: 'Noto Sans Thai', sans-serif;
            background-color: #000000;
            background-image: url('');
            background-position: center;
            background-size: 100%;
            background-repeat: no-repeat;
        }
        
        .ourhome {
            color: rgb(255, 255, 255);
            width: 220px;
            font-size: 50px;
        }
        
        .june {
            position: absolute;
            top: 80px;
            left: 1600px;
        }
        
        .june1 {
            width: 200px;
            height: 30px;
            padding: 0 5px;
        }
        
        .june2 {
            top: 5%;
            left: 90%;
        }
        
        button {
            background-color: chocolate;
            border: none;
            height: 30px;
            color: cyan;
            font-weight: bold;
            cursor: pointer;
            transition: .5s;
        }
        
        button:hover {
            background-color: darkmagenta;
            transition: .5s;
        }
        
        .list1 {
            background-color: aquamarine;
            color: black;
            list-style-type: none;
            width: 170px;
            padding: 5px;
            font-size: 25px;
            padding: 0;
            margin: 0;
        }
        
        .list1>li {
            border: 1px solid darkblue;
        }
        
        .list2>li {
            border: 1px solid red;
        }
        
        .list1 :hover {
            background-color: rgb(218, 80, 70);
            color: rgb(255, 255, 255);
            list-style-type: none;
            width: 170px;
            padding: 5px;
            font-size: 25px;
            padding: 0px;
            margin: 0;
        }
        
        .list2 {
            background-color: aquamarine;
            color: black;
            list-style-type: none;
            position: absolute;
            font-size: 25px;
            width: 170px;
            right: 10px;
            top: 150px;
            padding: 0px;
            margin: 0;
        }
        
        .list2 :hover {
            background-color: rgb(117, 78, 207);
            color: rgb(255, 255, 255);
            list-style-type: none;
            width: 170px;
            padding: 5px;
            font-size: 25px;
            padding: 0;
            margin: 0;
        }
        
        .recommend {
            position: absolute;
            color: white;
            top: 130px;
            left: 200px;
        }
        
        .flexboxrec {
            display: flex;
            box-sizing: border-box;
            flex-direction: row;
            margin-left: -10px;
            margin-right: -10px;
        }
        
        .boxrec {
            display: block;
            box-sizing: border-box;
            width: 33.33%;
            padding-left: 10px;
            padding-right: 10px;
            margin-bottom: 20px;
        }
        
        .rec1 {
            background-color: blue;
            border: 2px solid violet;
            padding: 16px;
        }
        
        .rec2 {
            background-color: blue;
            border: 2px solid violet;
            padding: 16px;
        }
        
        .rec3 {
            background-color: blue;
            border: 2px solid violet;
            padding: 16px;
        }
        
        .popular {
            position: absolute;
            color: rgb(255, 250, 250);
            top: 360px;
            left: 200px;
        }
        
        .flexboxpop {
            display: flex;
            flex-direction: row;
            position: absolute;
            top: 430px;
            left: 190px;
        }
        
        .pop1 {
            color: azure;
            background-color: blueviolet;
            border: 2px solid skyblue;
            width: 145px;
            height: 140px;
            margin: 10px;
            padding: 10px;
        }
        
        .pop2 {
            color: azure;
            background-color: blueviolet;
            border: 2px solid skyblue;
            width: 145px;
            height: 140px;
            margin: 10px;
            padding: 10px;
        }
        
        .pop3 {
            color: azure;
            background-color: blueviolet;
            border: 2px solid skyblue;
            width: 145px;
            height: 140px;
            margin: 10px;
            padding: 10px;
        }
        
        .contact {
            position: absolute;
            left: 50px;
            top: 80%;
        }
    </style>
</head>

<body>
    <h1 class="ourhome">OurHome</h1>
    <div class="june">
        <input type="search" class="june1" placeholder="Search...">
        <button class="june2">Search</button>
    </div>

    <ul class="list1">
        <li>บ้านเดี่ยว</li>
        <li>บ้านแฝด</li>
        <li>ทาวน์เฮ้าส์</li>
        <li>ทาวน์โฮม</li>
        <li>ประกาศขาย-เช่า</li>
        <li>คำนวณสินเชื่อ</li>
        <li>พูดคุย</li>
        <li>บทความ</li>
        <li>ติดต่อเรา</li>
    </ul>
    <ul class="list2">
        <li>หน้าแรก</li>
        <li>ลงชื่อเข้าใช้</li>
        <li>ตัวกรอง</li>
        <li>รายการที่ชอบ</li>
        <li>รายการโปรด</li>
    </ul>
    <h1 class="recommend">โครงการแนะนำ</h1<br>
        <div class="flexboxrec">
            <div class="boxrec">
                <div class="rec1">
                    <h6>recommend1</h6>
                </div>
            </div>
            <div class="boxrec">
                <div class="rec2">
                    <h6>recommend2</h6>
                </div>
            </div>
            <div class="boxrec">
                <div class="rec3">
                    <h6>recommend3</h6>
                </div>
            </div>
        </div>
        <h1 class="popular">โครงการยอดนิยม</h1><br>
        <div class="flexboxpop">

            <div class="pop1">
                <h6>popular1</h6>
            </div>
            <div class="pop2">
                <h6>popular2</h6>
            </div>
            <div class="pop3">
                <h6>popular3</h6>
            </div>

        </div>

        <form class="contact">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="gmail">Gmail:</label><br>
            <input type="gmail" id="gmail" name="gmail"><br>
            <label for="tel">Problem:</label><br>
            <input type="text" id="tel" name="tel"><br>
            <input type="submit" value="Submit">
        </form>

</body>

</html>
