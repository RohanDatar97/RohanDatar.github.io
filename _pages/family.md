---

title: "Family"
permalink: /family/
author_profile: true

---


div id="slideshow">
   <div>
     <img src="/images/HBD.JPG">
   </div>
   <div>
     <img src="/images/5.JPEG">
   </div>
   <div>
     <img src="/images/6.JPG">
   </div>
</div>

#slideshow {
  margin: 80px auto;
  position: relative;
  width: 240px;
  height: 240px;
  padding: 10px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
}

#slideshow > div {
  position: absolute;
  top: 10px;
  left: 10px;
  right: 10px;
  bottom: 10px;
}

$("#slideshow > div:gt(0)").hide();

setInterval(function() {
  $('#slideshow > div:first')
    .fadeOut(1000)
    .next()
    .fadeIn(1000)
    .end()
    .appendTo('#slideshow');
}, 3000);
