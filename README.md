 <!DOCTYPE html>
<html>

<head>
<style>
body {
  background-color: #333333; */this is background color for the page*/
  margin: 0;
}
.main {
  padding: 16px;
  margin-top: 30px;
  height: 1500px; /* Used in this example to enable scrolling */
}

.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed;
  z-index: +1; /*dette gjør så navbaren går over alt annet*/
  top: 0;
  width: 100%;
  
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}

#welcome-section {
  background-color: lightgreen;
  color: black;
  padding: 40px;
  font-size:50px;
  text-align: center;
}

.knowledge {
 color: snow;
 font-size: 30px;
 text-align: center;
}

.project-tile{
  color: white;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(100px, auto);
  grid-gap: 30px;
  width:100%;
  height: 100%;
  float:left;
  padding:50px 15px;
  
}

.tile-1{
  background-color: mediumseagreen;
  grid-column: 2;
  grid-row: 1;
  text-align: center;
}

.tile-2{
  background-color: mediumseagreen;
  grid-column: 3;
  grid-row: 1;
  text-align: center;
}

.tile-3{
  background-color: mediumseagreen;
  grid-column: 2;
  grid-row: 2;
  text-align: center;
}

.tile-4{
  background-color: mediumseagreen;
  grid-column: 3;
  grid-row: 2;
  text-align: center;
}

</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>

<body>
<section id="navbar">
<div class="navbar">
  <a href="#welcome-section">Home</a>
  <a href="#knowledge">Knowledge</a>
  <a href="#about">About</a>
  <a href="https://github.com/Maximum2lol">GitHub</a>
</div>
  </section>

<section id="welcome-section">
  <h1> Jonas Portfolio </h1>
</section>
  
<section id="projects">
  
<section class="knowledge" id="knowledge">
  <h1>What I can do</h1> 
      
    <div class="project-tile">
      <a style="text-decoration: none; color: white;" href="https://www.youtube.com/watch?v=oHg5SJYRHA0" target="_blank"> 
      <section class="tile-1">
        <h1>Git</h1>
        <p>Decent</p>
        Click here to go to Git
        </a>
       </section>
     
      <a style="text-decoration: none; color: white;" href="https://www.youtube.com/watch?v=oHg5SJYRHA0" target="_blank">
       <section class="tile-2">
          <h1>FreeCodeCamp</h1>
          <p>Decent</p>
        Click here to go to FreeCodeCamp
        </a>
       </section>
     
      <a style="text-decoration: none; color: white;" href="https://www.youtube.com/watch?v=oHg5SJYRHA0" target="_blank">
      <section class="tile-3">
       <h1>The Odin Project</h1>
        <p>Decent</p>
         Click here to go to The Odin Project
        </a>
      </section>
 <a style="text-decoration: none; color: white;" href="https://www.youtube.com/watch?v=oHg5SJYRHA0" target="_blank">
      <section class="tile-4">
       <h1>Arduino</h1>
       <p>Decent</p>       
        Click here to go to Arduino
       </a>
    </section>
  </div> 
</section>
 
<section id="about">
    <div class="project-title">
    <h2>Contact</h2>
    <p>Contact me by using mail: email som skalbrukesforåkontaktemeg@kontaktmegmail.com</p>
  </div>
  </section>

<script>

</script>

</body>
</html> 
