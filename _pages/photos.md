---
layout: page
permalink: /photos/
title: photo album
description: some digital shots, but mostly dabbling in film. taken mostly on fujifilm jelly camera and olympus infinity zoom.
nav: true
nav_order: 3
---
<style>
    .hover-card {
        position: relative;
        overflow: hidden;
    }
    .card-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.5); /* Dark background */
        color: #fff; /* Text color */
        opacity: 0;
        transition: opacity 0.3s;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        max-height: 93%; 
    }
    .hover-card:hover .card-overlay {
        opacity: 1; /* Show the overlay on hover */
    }
    .card-text {
        color: white;
        text-align: center;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
<!-- Gallery -->
<div class="row">
  <div class="col-lg-4 col-md-12 mb-4 mb-lg-0">
   <div class="hover-card">
    <img
      src="../assets/img/bluffs.jpg"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Film"
    />
    </div>
  <div class="hover-card">
    <img
      src="../assets/img/IMG_4764.jpg"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Sunset at beach"
    />
    <div class="card-overlay">
        <p class="card-text">Finally caught a summer sunset at Tower Beach, Vancouver</p>
    </div>
   </div>

    <div class="hover-card">
    <img
      src="../assets/img/sunset1.JPG"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="UBC sunset"
    />
    <div class="card-overlay">
        <p class="card-text">One of the prettiest sunsets I have seen while walking back from class.</p>
    </div>
   </div>

   <div class="hover-card">
    <img
      src="../assets/img/film1.jpg"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Film"
    />
    <div class="card-overlay">
        <p class="card-text">Playing around with digitally processing some negatives.</p>
    </div>
   </div>


  </div>

  <div class="col-lg-4 mb-4 mb-lg-0">
     <div class="hover-card">
    <img
      src="../assets/img/sunset.jpg"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Film"
    />
    </div>  
    <div class="hover-card">
    <img
      src="../assets/img/banff.JPG"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Hiking in Banff"
    />
    <div class="card-overlay">
        <p class="card-text">Taken while hiking in Banff. Not edited!</p>
    </div>
    </div>

    <div class="hover-card">
    <img
      src="../assets/img/audi.png"
      class="w-100 shadow-1-strong rounded mb-4"
      alt="Audi under bridge"
    />
    <div class="card-overlay">
        <p class="card-text">Quick shot of my favourite Audi</p>
    </div>
    </div>

  </div>

  <div class="col-lg-4 mb-4 mb-lg-0">
    
    <div class="hover-card">
    <img
      src="../assets/img/kalamaka.jpg"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Film"
    />
    </div>

    <div class="hover-card">
    <img
      src="../assets/img/film2.JPG"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="Film"
    />
    <div class="card-overlay">
        <p class="card-text">Film capturing my friends and I lighting sparklers.</p>
    </div>
   </div>
   <div class="hover-card">
    <img
      src="../assets/img/IMG_5516.JPG"
      class="w-100 shadow-1-strong rounded mb-4 z-depth-1 img-fluid"
      alt="More friends and cars!"
    />
    <div class="card-overlay">
        <p class="card-text">Friends and cars! I love fixing and working on cars </p>
    </div>
   </div>

  </div>
</div>
<!-- Gallery -->
