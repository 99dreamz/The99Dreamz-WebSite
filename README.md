<!DOCTYPE html>
<html>
<head>

<title>Alex's WebSite</title>
	
<style>
.item1 { grid-area: header; }
.item2 { grid-area: main; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'main   main   main   main   main   main';
  grid-gap: 10px;
   border: 6px solid #00ffff;
  background-color: white;
  padding: 10px;
}
.grid-container > div {
  background-image: url("../images/black.jpg");
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}

/* Style the header */
.header {
    background-color: white;
    padding: 20px;
    text-align: center;
}

/* Style the top navigation bar */
.link {
    overflow: hidden;
    background-color: black;
}

/* Style the topnav links */
.link a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

/* Change color on hover */
.link a:hover {
    background-color: #ddd;
    color: black;
}
body {
	background-color: lightblue;
}

p {
	font-family: verdana;
	font-size: 20px;
}
a {
	color: Blue;
}
</style>

</head>

<body>
<div class="grid-container">



  <div class="item1">

<div class="header">


Alex's WebSite
</div>

<div class="link">
 <a href="https://www.youtube.com/">YouTube</a> <a href="">Video list's</a> <a href="">Learn Code</a><a href="http://www.westada.tech/a1/alexk/">My School WebSite</a> 
</div>

</div>

  <div class="item2">
</div>
 

</div>










</body>
</html>
