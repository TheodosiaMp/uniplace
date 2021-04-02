# uniplace
<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
height: 720px;
width: 1280px;
left: -516px;
top: -862px;
border-radius: 0px;
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  background: #FFFFFF;
}


/* Header/logo Title */
.header {

  height: 60px;
width: 208px;
left: 173px;
top: 39px;
border-radius: nullpx;
  text-align: center;
  background: white;
  color: #89191F;
  font-family: Poppins;
font-size: 40px;
font-style: normal;
font-weight: 700;
line-height: 60px;
letter-spacing: 0em;
text-align: left;

}

/*ELLPSE1*/
.ellipse {
height: 1176px;
width: 1176px;
left: 396px;
top: -596px;
border-radius: 0px;
position: absolute;
color: #A31111 71%;
background: #A31111 71%;

}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}


/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: #333;
}

/* Style the navigation bar links */
.navbar a {
background: #333333;
color: white;
 font-family: Poppins;
font-size: 20px;
font-style: normal;
font-weight: 400;
line-height: 30px;
letter-spacing: 0em;
text-align: left;
  padding: 14px 20px ;
  text-decoration: none ;
  height: 30px ;
width: 60px;
left: 446px ;
top: 53px ;
border-radius: nullpx;

}

/* Right-aligned link */
.navbar a.right {
  float: right;
  
}

/* Change color on hover */
.navbar a:hover {
  background-color: green;
  color: red;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}



/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
  <meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.SXHMA{
height: 81px;
width: 257px;
left: 149px;
top: 485px;
border-radius: 1000000px;
padding: 10px;
backround:rgba(63 , 17, 17, 0.71);
color: #AA1922;
}

<div class="oval"></div>


</style>
</head>
<body>

<div class="header">
  <h1>UniPlace</h1>
</div>

<div class="navbar">
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#" class="right">Link</a>
</div>

<div class="row">
  <div class="side">
    <h2>About Us</h2>
    <h5>Photooo:</h5>
    <div class="fakeimg" style="height:200px;">Image</div>

    <p>The Right Place For Students</h3>
    
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div>
  </div>
  
  <div class="main">
    <h2>TITLE HEADING</h2>
    <h5>Title description</h5>
    
    <div class="fakeimg" style="height:200px;">Image</div>
    
    <p>Some text..</p>
    <p>TEXTT.</p>
    <br>
    <h2>TITLE HEADING</h2>
    <h5>Title description, Sep 2, 2017</h5>
    <div class="fakeimg" style="height:200px;">Image</div>
    <p>Some text</p>
    <p>SOME TEXT</p>
  </div>
</div>

<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>
