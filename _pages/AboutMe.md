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
  width: 4px;
  background-color: #6D7B8D;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 4px 20px;
  position: relative;
  background-color: #F0FFFF;
  border: 1px solid #6F4E37;
  width: 50%;
}


/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}




/* The actual content */
.content {
  padding: 10px 15px;
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


  
  /* Make all right containers behave like the left ones */
  .right {
  left: 0%;
  }
}
</style>
</head>
<body>

 <h2>Me throughout the years...</h2>
 
<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2> Episode 1997 :</h2>
        <p>style="color:#8C001A">The one where you said "Hello World!"
          <img src="/images/2.JPG">
        </p>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2> Episode 2000
        <br>The one where you could just eat and sleep all day, and no one would complain!
         <img src="/images/3.JPEG">  
      </h2>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>Episode 2005
        <br>The one where you started your "BSM" journey!
        <img src="/images/5.JPG">
      </h2>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>Episode 2010
        <br>The one where you everyone started calling you - "RDx"! 
        <img src="/images/6.JPG">
      </h2>
    </div>
  </div>
  <div class="container left">
    <div class="content">
      <h2>Episode 2015
        <br>The one where you started your "Coding" journey! 
        <img src="/images/1.JPEG">
      </h2>
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>Episode 2020
        <br>The one where you are on the threshold of exciting new opportunities! 
         <img src="/images/4.JPG">
      </h2>   
    </div>
  </div>
</div>

</body>
</html>
  


 
 

 


  

     



