---
layout: frontpage
title: "SangWoo Park"
description: "SangWoo Park is an Assistant Professor in Industrial Engineering at New Jersey Institute of Technology"
keywords: "SangWoo, Park, Optimization, Nonconvex optimization, Power systems, Energy systems, Renewable Energy, Machine Learning,
Research, UC Berkeley, NJIT, University of California Berkeley, New Jersey Institute of Technology, Optimal Power Flow,
State Estimation, Nonlinear State Estimation, Topology Error Detection, Javad Lavaei, Ph.D., California, San Francisco,
Math, Statisitics, AI, Reinforcement Learning, Demand Response, Power Flow, Security Constrained Optimal Power Flow,
Johns Hopkins, Johns Hopkins University, JHU, Baltimore, Korea, South Korea" 
---

<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="manifest" href="/site.webmanifest">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">

<!-- <div class="navbar">
  <div class="navbar-inner">
      <ul class="nav">
          <li><a href="{{ BASE_PATH }}/broman_cv.pdf">cv</a></li>
          <li><a href="https://github.com/kbroman">github</a></li>
          <li><a href="https://kbroman.org/blog">blog</a></li>
          <li><a rel="me" href="https:///fosstodon.org/@kbroman">mastodon</a></li>
      </ul>
  </div>
</div> -->

<div class="red-banner" style="margin-bottom: -15px;">
  NJIT OptiML-Lab
</div>

<table class="wide">
<tr>
  <td class="figure">	
    <img src="publpics/smart_city_01.jpg" alt="" title="smart_city"/>
  </td>
</tr>
</table>


At OptiML-Lab, we utilize optimization theory, machine learning and domain specific knowledge to develop innovative 
computational methods that are scalable and reliable. With main applications in power systems,
transportation systems, and supply chains, our research provide innovative solutions that help large-scale industrial systems 
to operate in a safe and economic way.

<!-- <table class="wide">
<tr>
  <td class="left">
    <a href="publpics/cyber-security.html">
        <img src="publpics/IoT.jpg" alt="" title="" style="width: 100%; height: auto"/>
    </a>
  </td>
  <td class="right">
    <a href="publpics/demand-response.html">
        <img src="publpics/smart_home.jpg" alt="" title="" style="width: 100%; height: auto"/>
    </a>
  </td>
</tr> -->

### <a name="projects"></a>Projects
<div class="figure-container">
  <div class="figure">
    <a href="publpics/cyber-security.html" class="hover-effect">
      <img src="publpics/IoT.jpg" alt="" title="">
      <div class="hover-text">Grid Cybersecurity</div>
    </a>
  </div>
  <div class="figure">
    <a href="publpics/demand-response.html" class="hover-effect">
      <img src="publpics/smart_home.jpg" alt="" title="">
      <div class="hover-text">Grid Flexibility</div>
    </a>
  </div>
</div>

<div class="figure-container">
  <div class="figure">
    <a href="publpics/transportation.html" class="hover-effect">
      <img src="publpics/transportation_02.jpg" alt="" title="">
      <div class="hover-text">Transportation Systems</div>
    </a>
  </div>
  <div class="figure">
    <a href="publpics/supply-chain.html" class="hover-effect">
      <img src="publpics/supply_chain.jpg" alt="" title="">
      <div class="hover-text">Circular Supply Chains (CSC)</div>
    </a>
  </div>
</div>

<!-- <div class="navbar">
  <div class="navbar-inner">
      <ul class="nav">
          <li><a href="morefigs.html">more figures</a></li>
      </ul>
  </div>
</div> -->

<style>
  .red-banner {
   background-color: crimson;
   color: white;
   padding: 10px 5px 10px 5px; /* Increase the padding for more space */
   text-align: center;
   display: flex; /* Use flexbox for vertical centering */
   justify-content: center; /* Center vertically */
   align-items: center; /* Vertically center the content */
   height: 40px; /* Adjust the height as needed */
   font-size: 20px; /* Adjust the font size as needed */
   margin: 0; /* Remove margin to eliminate space */
   }
   
   .figure-container {
   display: flex;
   flex-wrap: wrap;
   justify-content: space-between;
   }	
   
  .figure {
    flex: 1 0 45%;
    margin-bottom: 10px; /* Adjust the margin as needed */
	# height: 200px; /* Set a fixed height for the figures */
    overflow: hidden; /* Hide any overflowing content */
   }
   
  .figure img {
    width: 100%;
    height: 100%;
	object-fit: cover; /* Crop the image to fit the fixed height */
  }
  
  .hover-effect {
    position: relative;
    display: inline-block;
  }

  .hover-effect img {
    display: block;
    max-width: 100%;
    height: auto;
  }

  .hover-text {
    position: absolute;
    top: 0;
    left: 0;
    display: none;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7);
    color: white;
    text-align: center;
    padding-top: 40%;
    opacity: 0;
    transition: opacity 0.3s ease;
  }

  .hover-effect:hover .hover-text {
    display: block;
    opacity: 1;
  }
</style>