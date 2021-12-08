<html>
<head>
<style>
body {
  background-color: #c4c4c4;
}
h1 {
  background-color: powderblue;
  font-family: century gothic;
  font-size: 24px;
}
h2 {
  background-color: powderblue;
  font-family: century gothic;
  font-size: 22px;
}
</style>
</head>
<body>
<h1>Hey, Traveler!</h1>

<p>This is my second website. The first one has been lost to the black hole that is the internet!</p>
  
<h2>The Journey is Long, Not Lonely</h2>
  
<p>This site helps to showcase some of the skills learned in the Computing Fundamentals course available at the Hopper's Roppers website, created by Dennis Devey.</p>
<a href="https://www.roppers.org/">Hopper's Roppers</a>
  
<p>Here is a wonderful pic of a dog. Click the pup to see another!</p>
<img src="https://www.akc.org/wp-content/uploads/2017/11/Treeing-Walker-Coonhound.jpg" alt="A beautiful Treeing Walker Coonhound" id="change" onclick="funcy()">
  
 <script language="javascript">
 function funcy() {
  if (document.getElementById("change").src == "https://www.akc.org/wp-content/uploads/2017/11/Treeing-Walker-Coonhound.jpg")
   {
   document.getElementById("change").src = "https://www.akc.org/wp-content/uploads/2017/11/Treeing-Walker-Coonhound.young_.jpg";
   }
  else
   {
   document.getElementById("change").src = "https://www.akc.org/wp-content/uploads/2017/11/Treeing-Walker-Coonhound.jpg";
   }
  }
 </script>
  
</body>
</html>
