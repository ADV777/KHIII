
<p align="center">
  <img width="460" height="300" src="https://vignette.wikia.nocookie.net/disney/images/f/f5/Kingdom_Hearts_III_Logo.png/revision/latest/scale-to-width-down/516?cb=20130625151326">  </p>
  

 
# Kingdom Hearts TGS 2018 Trailer


[![Watch the video](https://img.youtube.com/vi/xNnd-YAKjCU/hqdefault.jpg)](http://www.youtube.com/watch?v=xNnd-YAKjCU&v)


  <p align="center">  
<a href="https://www.kingdomhearts.com/home/us"> "Kingdom Hearts Official Page" </p>

var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none"; 
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block"; 
  dots[slideIndex-1].className += " active";
}
