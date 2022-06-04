<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="fontawesome-free-6.1.1-web/css/all.min.css">
    <link rel="stylesheet" href="js.js">
    <link rel="stylesheet" href="main.css">
    <title>Document</title>
</head>
<body>
    <div class="navbar">
        <img src="../sass loyixa/channels4_profile.jpg" alt="UZ | JaGa" style="width: 69px;">
    <div class="icon-bar">
        <a class="active" href="#">Home <i class="fa fa-home"></i></a> 
        <a href="#">Search <i class="fa fa-search"></i></a> 
        <a href="#">Language <i class="fa fa-globe"></i></a>
        <a href="#">Massage <i class="fa fa-envelope"></i></a> 
        <a href="#">Trash <i class="fa fa-trash"></i></a> 
      </div>
    </div>
      <img id="myImg" src="bosh.jpg" alt="This is a image" style="width:100%;max-width:500px">

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- The Close Button -->
  <span class="close">&times;</span>

  <!-- Modal Content (The Image) -->
  <img class="modal-content" id="img01">

  <!-- Modal Caption (Image Text) -->
  <div id="caption"></div>
</div>
<script>
    // Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}
</script>

<div class="timeline">
    <div class="container left">
      <div class="content">
        <h2>2022</h2>
        <p>Xaker</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <h2>2021</h2>
        <p>PRO</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <h2>2020</h2>
        <p>PRO</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <h2>2019</h2>
        <p>NooB</p>
      </div>
    </div>
</div>
<div id="div1" class="fa"></div>

<script>
function chargebattery() {
  var a;
  a = document.getElementById("div1");
  a.innerHTML = "&#xf244;";
  setTimeout(function () {
      a.innerHTML = "&#xf243;";
    }, 1000);
  setTimeout(function () {
      a.innerHTML = "&#xf242;";
    }, 2000);
  setTimeout(function () {
      a.innerHTML = "&#xf241;";
    }, 3000);
  setTimeout(function () {
      a.innerHTML = "&#xf240;";
    }, 4000);
}
chargebattery();
setInterval(chargebattery, 5000);
</script>

<div class="star">
    <span class="heading">User Rating</span>
<span class="fa fa-star checked"></span>
<span class="fa fa-star checked"></span>
<span class="fa fa-star checked"></span>
<span class="fa fa-star checked"></span>
<span class="fa fa-star"></span>
<p>4.1 average based on 254 reviews.</p>
<hr style="border:3px solid #f1f1f1">

<div class="row">
  <div class="side">
    <div>5 star</div>
  </div>
  <div class="middle">
    <div class="bar-container">
      <div class="bar-5"></div>
    </div>
  </div>
  <div class="side right">
    <div>150</div>
  </div>
  <div class="side">
    <div>4 star</div>
  </div>
  <div class="middle">
    <div class="bar-container">
      <div class="bar-4"></div>
    </div>
  </div>
  <div class="side right">
    <div>63</div>
  </div>
  <div class="side">
    <div>3 star</div>
  </div>
  <div class="middle">
    <div class="bar-container">
      <div class="bar-3"></div>
    </div>
  </div>
  <div class="side right">
    <div>15</div>
  </div>
  <div class="side">
    <div>2 star</div>
  </div>
  <div class="middle">
    <div class="bar-container">
      <div class="bar-2"></div>
    </div>
  </div>
  <div class="side right">
    <div>6</div>
  </div>
  <div class="side">
    <div>1 star</div>
  </div>
  <div class="middle">
    <div class="bar-container">
      <div class="bar-1"></div>
    </div>
  </div>
  <div class="side right">
    <div>20</div>
  </div>
</div>
</div>

<h1>My Web Page</h1>

<div id="piechart"></div>

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>

<script type="text/javascript">
// Load google charts
google.charts.load('current', {'packages':['corechart']});
google.charts.setOnLoadCallback(drawChart);

// Draw the chart and set the chart values
function drawChart() {
  var data = google.visualization.arrayToDataTable([
  ['Task', 'Hours per Day'],
  ['Work', 8],
  ['Eat', 2],
  ['TV', 4],
  ['Gym', 2],
  ['Sleep', 8]
]);

  // Optional; add a title and set the width and height of the chart
  var options = {'title':'My Average Day', 'width':550, 'height':400};

  // Display the chart inside the <div> element with id="piechart"
  var chart = new google.visualization.PieChart(document.getElementById('piechart'));
  chart.draw(data, options);
}
</script>
<h1>3D Flip Box (Vertical)</h1>
<h3>Hover over the box below:</h3>

<div class="flip-box">
  <div class="flip-box-inner">
    <div class="flip-box-front">
      <h2>Salom</h2>
    </div>
    <div class="flip-box-back">
      <h2>Xayr</h2>
    </div>
  </div>
</div>
<div class="container">
    <iframe class="responsive-iframe" src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>
  </div>
</body>
</html>
