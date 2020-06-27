---

title: "About Me"
permalink: /aboutme/
author_profile: true

---


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

body {
  background-color: white;
  font-family: Helvetica, sans-serif;
}

/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;
  margin: 0 auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #6D7B8D;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: #F0FFFF;
  border: 1px solid #6F4E37;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -18px;
  background-color: #F0FFFF;
  border: 4px solid #6F4E37;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}


/* Fix the circle for containers on the right side */
.right::after {
  left: -30px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: #F0FFFF;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .timeline::after {
  left: 31px;
  }
  
  /* Full-width containers */
  .container {
  width: 100%;
  padding-left: 70px;
  padding-right: 25px;
  }


  /* Make sure all circles are at the same spot */
  .left::after, .right::after {
  left: 15px;
  }
  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style>
</head>
<body>

<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>1997</h2>
      <p>Birth Pictures</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2000</h2>
      <p>Childhood Pictures</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2005</h2>
      <p>School Pictures</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2010</h2>
      <p>Highschool Pictures</p>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>2015</h2>
      <p>College Pictures</p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2020</h2>
      <p>Office Pictures</p>
    </div>
  </div>
</div>

</body>
</html>
  


 
 

 


  

     



