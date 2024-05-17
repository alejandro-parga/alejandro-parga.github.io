---
layout: page
---
<center>
<video width="80%" autoplay loop> 
  <source src="content/images/v2.ogg" type="video/ogg"/>
  <source src="content/images/v2.m4v" type="video/mp4"/>
  <source src="content/images/v2.webm" type="video/webm"/>
Your browser does not support the video tag.
</video>
</center>  
<br>
**Research Summary**<br>
In my research, I integrate neurophysiological, anatomical, and multiomics approaches to investigate the intricate functions of neuronal networks. I excel in orchestrating clinical and research projects, leveraging my experience in both academic and industry settings. My primary objective is to unravel the complexities of neuronal ensembles and their implications for cognitive functions. By elucidating these mechanisms, I aim to translate this knowledge into tangible applications, harnessing advanced technologies to modulate neuronal networks.

<style>
.container {
  position: relative;
  width: 100%;
}

.image {
  display: block;
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: .5s ease;
  background-color:  #78C2AD;
}

.container:hover .overlay {
  opacity: 0.9;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}

@media screen and (max-width: 500px) {
  .column {
    width: 100%;
  }
}
</style>

<div class="row"> 
  <div class="column">
  	  <div class="container">
        <img src="/content/images/p1.png" class="img-responsive" style="max-width:auto;height:120px;">
    	<div class="overlay">
        <a href="/pages/project1.html" title="Tracing Neuronal Circuits">
    		<div class="text">Tracing Neuronal Circuits</div>
        </a>
    	</div>
  	  </div>
   </div>
  <div class="column"> 
      <div class="container">
        <img src="/content/images/p2.png" class="img-responsive" style="max-width:auto;height:120px;">
    	  <a href="/pages/project2.html" title="Opto/Chemogenetics">
        <div class="overlay">
    		  <div class="text">Opto/Chemogenetics</div>
    	  </div>
        </a>
  	  </div>
  </div>
  <div class="column">
    <a href="/pages/project3.html" title="Electrophysiology">
    	<div class="container">
        <img src="/content/images/p3.png" class="img-responsive" style="max-width:auto;height:120px;">
    	  <div class="overlay">
   	 		  <div class="text">Electrophysiology</div>
    	  </div>
   	  </div>
    </a>
   </div>
</div>
