---
layout: page
title: Alejandro Parga MD PhD
---

As a neuro-electrophysiologist with medical training and advanced research skills in laboratory methods and
computational analysis, I am an expert on the synaptic plasticity of neuronal circuits and their alterations in
functional brain disorders. In my research, I bring together microscopy and electrophysiological tools to
investigate perception. My strengths are in the interpretation of neuro-anatomical studies and the cell biology
involved in neuronal circuits. My goal is to decode the neuronal informational flow that creates the mind and
translate this knowledge into concrete applications that potentiate brain-computer interface technology.

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
        <img src="/content/images/p1.png" class="img-responsive" style="max-width:100%;height:auto;">
    	<div class="overlay">
        <a href="/pages/project1.html" title="Tracing Neuronal Circuits">
    		<div class="text">Tracing Neuronal Circuits</div>
        </a>
    	</div>
  	  </div>
   </div>
  <div class="column"> 
      <div class="container">
        <img src="/content/images/p2.png" class="img-responsive" style="max-width:100%;height:auto;">
    	  <a href="/pages/project2.html" title="Cortical Spreading Depression">
        <div class="overlay">
    		  <div class="text">Cortical Spreading Depression</div>
    	  </div>
        </a>
  	  </div>
  </div>
  <div class="column">
    <a href="/pages/project3.html" title="Neurogenesis and Tonic Inhibition">
    	<div class="container">
        <img src="/content/images/p3.png" class="img-responsive" style="max-width:100%;height:auto;">
    	  <div class="overlay">
   	 		  <div class="text">Neurogenesis and Tonic Inhibition</div>
    	  </div>
   	  </div>
    </a>
   </div>
</div>
