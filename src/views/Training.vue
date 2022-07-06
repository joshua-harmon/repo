<template>
  <section id="depts">
  <div class="box">
  <ul id="bookmarks">
 <li><a href="#">school</a>
   <ul class="sites">
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-002-circuits-and-electronics-spring-2007/">circuits</a></li>
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-302-feedback-systems-spring-2007/">feedback'07</a></li>
     <li><a href="http://ocw.mit.edu/resources/res-6-010-electronic-feedback-systems-spring-2013/">feedback'13</a></li>
     <li><a href="http://ocw.mit.edu/resources/res-6-010-electronic-feedback-systems-spring-2013/course-videos/">videos</a></li>
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-241j-dynamic-systems-and-control-spring-2011/">controls'11</a></li>
     <li><a href="http://ocw.mit.edu/courses/mechanical-engineering/2-04a-systems-and-controls-spring-2013/lecture-notes-labs/">controls'13</a></li>
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/">digitalComm</a></li>
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-003-signals-and-systems-fall-2011/">signals</a></li>
     <li><a href="http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-011-introduction-to-communication-control-and-signal-processing-spring-2010/">commContrl</a></li>
     <li><a href="https://www.elearners.com/l/top-online-certifications-now?trackid=a7c821b6-8934-4d78-b653-a4cdd7b0fe68&key=go_free+college+courses&v=google&a=major+terms+2&c=el+general&cat=free+college+courses&mt=search&ad=320688751826&est=free%20college%20courses&emt=b&device=c&dev=&target=kwd-4077794131&gclid=Cj0KCQjw1pblBRDSARIsACfUG11TQIGPB-D0I1d6ybEl9kKQMLOhtnL7seilaj2RT7IombaWxpA66ygaAgoVEALw_wcB#_ThankYou">eLearners</a></li>  
     <li><a href="https://www.youtube.com/watch?v=qn7z9T-dezw">mitBee</a></li>  
     <li><a href="https://online.coloradotech.edu/ctu/online-education/home-nboe2a-des2-exp-dp?code=6222&siteid=CTU_LinkedIn_SponsoredAds_PRO_General_INT_Static_BTSManTanBackpack&dclid=CIi9kNDL4eECFW8MrQYdRsMH6g">ctuOnline</a></li>  
     <li><a href="https://www.elearners.com/">eLearners</a></li>
    <li><a href="https://www.youtube.com/watch?v=sqxzQkAdJm0">circuits1</a></li>
    <li><a href="https://www.youtube.com/watch?v=sqxzQkAdJm0&t=20s">circuits</a></li>
    <li><a href="https://www.youtube.com/watch?v=89NJj1F_qmQ">eCurriculum</a></li>
    <li><a href="https://www.youtube.com/watch?v=sqxzQkAdJm0&t=79s">circuitAnalysis</a></li>
  </ul>
 </li>
</ul>
</div>
</section>
</template>
<script>
export default {
  name: "Depts",
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