
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
<script>
$(document).ready(function(){

	$(".btn-slide").click(function(){	  $("#panel").slideToggle("slow");	  $(this).toggleClass("active");	});

});
</script>
<style>
    body{
      color:#000000;
      text-align:left;
    }
    #banner h1 a:hover{
color: #fc3a63;
position: relative; 
top: 1px;
left: 1px;
}
    .fan{
      font-family:fantasy;
    }
    .ch{
      font-family:Microsoft JhengHei;
    }
    .text-center{
      text-align:center;
    }
    .text-right{
      text-align:right;
    }
    .yellow-text {
      color: yellow;
    }
    .blue-text {
      color: blue;
    }
    .red-text {
      color: red;
    }
    .title{
      font-size=20px;
      color: red;
    }
  .smaller-image {
    width: 100px;
  }
  .thick-green-border {
    border-color: #C10066;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }
  </style>
  <marquee>
<strong>Welcome</strong>
</marquee>
  <title>
  My webpage.
  </title>
  <p class="blue-text text-center" span style="font-size:30px">
    My Personal Page
  </p>
  <h1 class="blue-text text-center" span style="font-size:25px">    
    <a href="https://github.com/NoNuclear">顧中彥</a>
  </h1>
  <a href="#"><img class="smaller-image thick-green-border text-center text-center" alt="Me?" src="https://avatars0.githubusercontent.com/u/26366534?v=3&s=96"></a>

  <p class="blue-text fan" span style="font-size:22px">
    <span style="font-family:fantasy;">
    Welcome.
    </span>
    
  </p>
  
  <body background="http://blog.joaoko.net/wp-content/uploads/2009/07/Pattern.01.png">
    <p class="title" span style="font-size:20px"><l>興趣</l></p>
    <ul class ="ch" span style="font-size:20px">
      <li>LOL</li>
      <li>爐石</li>
   </ul>
   <p class="title" span style="font-size:20px"><l>專長</l></p>
   <ul class ="ch" span style="font-size:20px">      
      <li>睡覺</li>
      <li>除了打程式</li>
   </ul>
  </body>
  <p span style="font-size:20px color: yellow"><l>music</l></p>
  <div style="position:relative;width:267px;height:25px;overflow:hidden;">
  <div style="position:absolute;top:-276px;left:-5px">
    <iframe width="300" height="300" 
      src="https://www.youtube.com/embed/EXwZ_xr3Pfk?rel=0&autoplay=1">
    </iframe>
  </div>
</div>
</html>

