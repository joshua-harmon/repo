<template>
  <section id="departments">
  <div class="box">
  <ul id="bookmarks">

  <li><a href="#">support</a>
   <ul class="sites">
    <li><a href="https://tiny-fudge-cb990b.netlify.app/Home">Home</a></li>  
    <li><a href="https://tiny-fudge-cb990b.netlify.app/about">About</a></li>  
    <li><a href="https://tiny-fudge-cb990b.netlify.app/customerService">CustomerService</a></li>  
    <li><a href="https://tiny-fudge-cb990b.netlify.app/systems">Systems</a></li>  
    <li><a href="https://tiny-fudge-cb990b.netlify.app/linux">Linux</a></li>  
    <li><a href="https://tiny-fudge-cb990b.netlify.app/Contact">Contact</a></li>  
  </ul>
 </li>
  <li><a href="#">coding</a>
   <ul class="sites">
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/Home">Home</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/about">About</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/html5">Html5</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/javascript">Javascript</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/staticPages">StaticPages</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/java">Java</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/python">Python</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/mrePython">MrePython</a></li>  
    <li><a href="https://classy-raindrop-80ce0d.netlify.app/verilog">Verilog</a></li>  
  </ul>
 </li>
  <li><a href="#">hospitality</a>
   <ul class="sites">
    <li><a href="https://tiny-cendol-418236.netlify.app/Home">Home</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/about">about</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/about1">about1</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/farEast">FarEast</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/meditteranean">Meditteranean</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/veganMeat">VeganMeat</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/grain">Grain</a></li>  
    <li><a href="https://tiny-cendol-418236.netlify.app/Contact">Contact</a></li>  
  </ul>
 </li>
  <li><a href="#">engineering</a>
   <ul class="sites">
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/Home">Home</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/electronics">Electronics</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/circuits">Circuits</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/processes">Processes</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/serialControl">SerialControl</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/bench">Bench</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/batteries">Batteries</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/lines">Lines</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/materials">Materials</a></li>  
    <li><a href="https://unique-fenglisu-056e3b.netlify.app/more">More</a></li>  
  </ul>
 </li>
</ul>
</div>
</section>
</template>
<script>
export default {
  name: "Departments",
};
</script>

<style scoped>
*{
    margin:0;
    padding:0;
}
body {
    font:14px/1.3 Arial,sans-serif;
}
.box {
    height: 571px;
    margin: 30px auto;
    padding: 15px;
    width: 771px;
}
#bookmarks,#bookmarks ul {
    background-color: #8899AA;
    list-style: none outside none;
    margin: 0;
    padding: 0;
}
#bookmarks {
    display: block;
    padding: 5px;
    position: relative;
    width: 112px;
    -moz-perspective: 200px;
    -ms-perspective: 200px;
    -webkit-perspective: 200px;
    -o-perspective: 200px;
    perspective: 200px;
}
#bookmarks ul {
    left: -9999px;
    opacity:0;
    overflow: hidden;
    padding: 5px;
    position: absolute;
    top: -9999px;
    -moz-transform: rotateY(70deg);
    -ms-transform: rotateY(70deg);
    -o-transform: rotateY(70deg);
    -webkit-transform: rotateY(70deg);
    transform: rotateY(70deg);
    -moz-transform-origin: 0 0;
    -ms-transform-origin: 0 0;
    -o-transform-origin: 0 0;
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    -moz-transition: -moz-transform 0.3s linear, opacity 0.3s linear;
    -ms-transition: -ms-transform 0.3s linear, opacity 0.3s linear;
    -o-transition: -o-transform 0.3s linear, opacity 0.3s linear;
    -webkit-transition: -webkit-transform 0.3s linear, opacity 0.3s linear;
    transition: transform 0.3s linear, opacity 0.3s linear;
}
#bookmarks li {
    background-color: #FFFFFF;
    position: relative;
}
#bookmarks > li {
    -moz-transform-style: preserve-3d;
    -ms-transform-style: preserve-3d;
    -o-transform-style: preserve-3d;
    -webkit-transform-style: preserve-3d;
    transform-style: preserve-3d;
}
#bookmarks li a {
    background-color: #AABBCC;
    border-color: #DDDDDD #555555 #555555 #DDDDDD;
    border-style: solid;
    border-width: 1px;
    color: #000000;
    display: block;
    font-size: 15px;
    padding: 8px 10px 8px 5px;
    text-decoration: none;
    width:95px;
    -moz-transition: all 0.2s linear;
    -ms-transition: all 0.2s linear;
    -o-transition: all 0.2s linear;
    -webkit-transition: all 0.2s linear;
    transition: all 0.2s linear;
}
#bookmarks li:hover > a {
    background-color: #8899AA;
    border-color: #8899AA;
    color: #FFFFFF;
}
#bookmarks li:hover ul.sites {
    left: 114px;
    opacity:1;
    top: 0;
    -moz-transition-delay: 0.3s;
    -ms-transition-delay: 0.3s;
    -o-transition-delay: 0.3s;
    -webkit-transition-delay: 0.3s;
    transition-delay: 0.3s;
    -moz-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    -o-transform: rotateY(0deg);
    -webkit-transform: rotateY(0deg);
    transform: rotateY(0deg);
}
#bookmarks ul li {
    width: 100%;
}

</style>