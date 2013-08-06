<!DOCTYPE html>

<html>

 <head>

  <title>Introducing JavaScript</title>

  <link rel="stylesheet" type="text/css" href="bootstrap.js">

   <script> 

    var Name="JavaScript";

    var Nickname="JS";

    var Extension=".js";

    var Creator="Brandon Eich";

    var Year="1995";

   </script>

  </head>

  <body>

   <h1>Introducing JavaScript</h1>

     <script>

     function myFunction()

      {

         document.getElementById("name").innerHTML=Name;

         document.getElementById("nickname").innerHTML=Nickname;

         document.getElementById("extension").innerHTML=Extension;

         document.getElementById("creator").innerHTML=Creator;

         document.getElementById("year").innerHTML=Year;

      }

     </script>


     <button type="button" onclick="myFunction()">Meet JavaScript</button>

     <p>Name: <span id="name"></span></p>

     <p>Nickname: <span id="nickname"></span></p>

     <p>Extesion: <span id="extension"></span></p>

     <p>Creator: <span id="creator"></span></p>

     <p>Year: <span id="year"></span></p>

   </body>

 </html>
