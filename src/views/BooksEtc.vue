<template>
  <section id="booksEtc">
  <div class="box">
  <ul id="bookmarks">
 <li><a href="#">books</a>
   <ul class="sites">
    <li><a href="https://www.youtube.com/watch?v=JesYd5Rk-_0">engBooks</a></li>  
    <li><a href="http://www.coe.ufrj.br/~julio/Fundamentals%20Of%20Electric%20Circuits.pdf">elecCircuits</a></li>
    <li><a href="http://circuitsx.blogspot.com/2015/04/free-download-fundamentals-of-electric.html">elecCircuits</a></li>
    <li><a href="http://www.summarydownload.xyz/finder/douglas-c-giancoli-physics-for-scientists-engineers-with-modern-phy">physics</a></li>
    <li><a href="http://faculties.sbu.ac.ir/~sadough/pdf/Advanced%20Engineering%20Mathematics%2010th%20Edition.pdf">engineering</a></li>
    <li><a href="https://archive.org/details/SolutionManualOfAdvancedEngineeringMathematicsByErwinKreyszig9thEdition">solutions</a></li>
    <li><a href="http://www.talkingelectronics.com/Download/Malvino_Electronic-Principles.pdf">solidState</a></li>
    <li><a href="http://www.analog.com/library/analogDialogue/archives/39-06/Chapter%206%20Interfacing%20to%20Data%20Converters%20F.pdf">circuits</a></li>
    <li><a href="http://www.clir.org/pubs/resources/ad-converters-pohlmann.pdf">paper</a></li>
  </ul>
 </li>
   <li><a href="#">patents</a>
   <ul class="sites">
    <li><a href="https://www.epo.org/index.html">european</a></li>
    <li><a href="http://www.ic.gc.ca/opic-cipo/cpd/eng/introduction.html">canadian</a></li>
    <li><a href="http://patft.uspto.gov/">unitedStates</a></li>
<li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-912-introduction-to-copyright-law-january-iap-2006/">copyright</a></li>
    <li><a href="https://www.youtube.com/watch?v=OsIihrcqJYA">uselessPats</a></li>  
  </ul>
 </li>
 <li><a href="#">books</a>
   <ul class="sites">
    <li><a href="https://www.youtube.com/watch?v=JesYd5Rk-_0">engBooks</a></li>  
    <li><a href="http://www.coe.ufrj.br/~julio/Fundamentals%20Of%20Electric%20Circuits.pdf">elecCircuits</a></li>
    <li><a href="http://circuitsx.blogspot.com/2015/04/free-download-fundamentals-of-electric.html">elecCircuits</a></li>
    <li><a href="http://www.summarydownload.xyz/finder/douglas-c-giancoli-physics-for-scientists-engineers-with-modern-phy">physics</a></li>
    <li><a href="http://faculties.sbu.ac.ir/~sadough/pdf/Advanced%20Engineering%20Mathematics%2010th%20Edition.pdf">engineering</a></li>
    <li><a href="https://archive.org/details/SolutionManualOfAdvancedEngineeringMathematicsByErwinKreyszig9thEdition">solutions</a></li>
    <li><a href="http://www.talkingelectronics.com/Download/Malvino_Electronic-Principles.pdf">solidState</a></li>
    <li><a href="http://www.analog.com/library/analogDialogue/archives/39-06/Chapter%206%20Interfacing%20to%20Data%20Converters%20F.pdf">circuits</a></li>
    <li><a href="http://www.clir.org/pubs/resources/ad-converters-pohlmann.pdf">paper</a></li>
  </ul>
 </li>
</ul>
</div>
</section>
</template>
<script>
export default {
  name: "BooksEtc",
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