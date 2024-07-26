<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> cardekho.com</title>
</head>

<body>
    <h2>login form <img src="download.jpeg" style="float:right ;height:100px ;width:154px" usemap="#workmap" alt=""></h2>
    <map name="workmap">
        <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
        <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
        <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
      </map>
    <form action="backend.php">
    
        <div>
           Name:<input type="text" id="name">
        </div>
        <br>
        <div>
            role: <input type="text" name="myrole">
        </div>
        <br>
        <div>
            email: <input type="email" name="myemail">
        </div>
        <br>
        <div> date:<input type="date" name="mydate" ></div>
        <br>
        <div>favourite color :<input type="color"> </div>
        <br>
        <div>
            gender: male<input type="radio" name="mygender"> female <input type="radio" name="mygender"> other<input
                type="radio" name="mygender">
        </div>
        <br>
        <div>
            any suggestion:<br><textarea name="" id="" cols="20" rows="5"></textarea>
        </div>
        <br>
        <div>
            <label for="car">car</label>
            <select name="mycar" id="car">
                <option value="d">bMW</option>
                <option value="k">audi q2</option>
                <option value="s">rolls royce q2</option>
            </select>
        </div>
        <div>
            <input type="submit" name="mysubmi">
            <input type="reset" name="myreset">

        </div>

    </form>


</body>

</html>
