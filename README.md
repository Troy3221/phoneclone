# phoneclone
this is a phone clone web page
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">

  <title>phone clone</title>
  <style type="text/css">
    .gt {
      width: 250px;
     height: 450px;
     background-image: url('https://wallpaperaccess.com/full/3038475.jpg');
     margin-left: 50px;
     border-radius: 10px;
     border: 10px solid black;
     margin-top: 50px;
   }
   .cr {
    border-radius: 500%;
    height: 15px;
    width: 15px;
    border: 2px solid black;
    margin-left: 100px;
    margin-top: 50px;
   }
  .c {
    width: 13px;
    height: 13px;
    border: 2px solid black;
    margin-bottom: 20px;
  }
  .t {
 width: 13px;
    height: 13px;
    border: 2px solid black;
    
}
 
 .y {
  width: 35px;
  height: 35px;
  margin-top:-150px;
  margin-left: 500px;
 }
  .a {
  width: 35px;
  height: 30px;
  margin-left: 500px;
  margin-top: 30px;
 }
 .v {
  margin-bottom:-25px;
  margin-left: 200px;
 }
 .wr {
   margin-left: 700px;
   margin-top:-20px;
  }
   #time {
    color:Alice Blue;
    font-family:arial;
    font-size:250%;
    }
  .cd {
   width: 12px;
   height: 15px; 
    }
  .fg {
    width: 12px;
   height: 15px; 
  }
  #time {
    margin-top: 25px;
  }
  .po {
    width: 200px;
    height: 20px;
    border-radius: 20px;
    border: 2px solid black;
    background-color: white;
  }

  </style>
</head>
<body>


<div class="gt">
<p class="v">86%</p>
<div id="time"></div>
<div id="date"></div>


<br><center><a href="https://google.com/search?igu=1"><br>  <div class="po">search here</div> </a></center>


 <table cellpadding="4px" cellspacing="4px" width="100%">


   <tr><td><a href="https://youtube.com" target="_blank" >  <img height="30px" width="30px" class="s" src="https://www.freeiconspng.com/thumbs/youtube-logo-png/hd-youtube-logo-png-transparent-background-20.png"></a> </td>

    <br><br><br><br>

   <td><button onclick="myFunction()"><img height="30px" width="30px" class="cd" src="https://www.kindpng.com/picc/m/109-1095065_camera-cam-device-photo-shot-mode-mobile-phone.png"></button></td>

  <td><a href="https://google.com/search?igu=1"> <img height="30px" width="30px" class="s" src="https://pbs.twimg.com/profile_images/1455185376876826625/s1AjSxph_400x400.jpg"> </a></td>
  
  <td><a href="https://www.google.com/photos"><img height="30px" width="30px" xwidth="50%" src="https://media.istockphoto.com/vectors/gallery-icon-vector-id953463676?k=20&m=953463676&s=170667a&w=0&h=5eVQZWhvtwJH2Ag6Za0FGkhm-Dpg70GlFRUEmPyhQN8="></a></td>

</tr>

<tr>
  
<td>
  <a href="https://amazon.com" target="_blank"> <img height="30px" width="30px" class="s" src="https://image.similarpng.com/very-thumbnail/2020/11/Amazon-icon-in-flat-design-on-transparent-background-PNG.png"></a>

</td>

<td><a href="https://whatsapp.com" target="_blank"><img height="30px" width="30px" xwidth="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6b/WhatsApp.svg/640px-WhatsApp.svg.png"></a></td>

<td>
<a href="https://sololearn.com" target="_blank"> <img height="30px" width="30px" src="https://iconape.com/wp-content/png_logo_vector/sololearn.png" width="25px"> </a>
</td>

<td><button onclick="myFunction2()"><img height="25px" width="25px" src="https://toppng.com/uploads/preview/phone-icon-11549498584attf3ik674.png"></button></td>

</tr>

 </table>



  </div>


<div class="fg"></div>

<div class="ghh"> </div>



<script type="text/javascript">


function time(){
var d = new Date();
var hours = d.getHours();
var mins = d.getMinutes();

document.getElementById("time").innerHTML = hours + ":" + mins

}

setInterval(time, 1000);

var p = new Date();
var date = p.getDate();
var mins = (p.getMonth()+1);
var year = p.getFullYear();

document.getElementById("date").innerHTML = date + "/" + mins + "/" + year 

function myFunction() {
  alert("Camera is broken.");
}

function myFunction2() {
  alert("ERROR");
}
</script>



</body>
