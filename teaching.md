---
id: 74
title: Teaching
date: 2014-01-15T18:01:24+00:00
author: admin
layout: page
guid: http://www.begumdemir.com/?page_id=74
---
<div class="col-lg-12 text-left">
  <h3>Teaching</h3>
  <div class="row m-0">
    <div class="col-lg-8 p-0 text-left">
      <span class="list-group-item list-group-item-action">
        <a title="https://www.rsim.tu-berlin.de/menue/teaching/" target="_blank">Image Processing for Remote Sensing</a>, TU Berlin, Faculty of Electrical Engineering and Computer Science, Summer Term 2019.
      </span>
      <span class="list-group-item list-group-item-action">
        <a title="https://www.rsim.tu-berlin.de/menue/teaching/" target="_blank">Machine Learning for Remote Sensing Data Analysis</a>, TU Berlin, Faculty of Electrical Engineering and Computer Science, Winter Term  2018.
      </span>
      <span class="list-group-item list-group-item-action">
        <a title="Digital Signal Processing" href="https://rslab-tech.disi.unitn.it/moodle/course/view.php?id=17" target="_blank">Digital Signal Processing</a>, Main Lecturer from 2013 to 2018 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
      </span>
      <span class="list-group-item list-group-item-action">
        <a title="Remote Sensing Systems" href="https://rslab-tech.disi.unitn.it/moodle/course/view.php?id=10" target="_blank">Remote Sensing Systems</a>, Supporting Lecturer from 2015 to 2016 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
      </span>
      <span class="list-group-item list-group-item-action">Pattern Recognition, Supporting Lecturer in 2013 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
      </span>
      <span class="list-group-item list-group-item-action">Advanced Remote Sensing Systems for Environment, Supporting Lecturer in 2013 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
      </span>
    </div>
    <div class="col-lg-4 text-left">
      <img class="rounded img-pointer" id="dspImg" src="./assets/images/dsp_1.jpg" style="margin-right: 10px" align="left" width="300px" >
    </div>
  </div>  
</div>

<!-- Modal -->
<!-- The Modal -->
<div id="modalBox" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImg">
  <div id="caption"></div>
</div>

<script>
// Get the modal
var modal = document.getElementById('modalBox');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('dspImg');
var modalImg = document.getElementById("modalImg");
var captionText = document.getElementById("caption");

img.onclick = function(){
    modal.style.display = "block";
    modalImg.src = this.src;
    captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
    modal.style.display = "none";
}

modal.addEventListener('click',function(){
  this.style.display="none";
})
</script>

<style type="text/css">
 /* Style the Image Used to Trigger the Modal */
#dspImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
    display: none; /* Hidden by default */
    position: fixed; /* Stay in place */
    z-index: 1; /* Sit on top */
    padding-top: 100px; /* Location of the box */
    left: 0;
    top: 0;
    width: 100%; /* Full width */
    height: 100%; /* Full height */
    overflow: auto; /* Enable scroll if needed */
    background-color: rgb(0,0,0); /* Fallback color */
    background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
    z-index: 2030;
}

/* Modal Content (Image) */
.modal-content {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
    text-align: center;
    color: #ccc;
    padding: 10px 0;
    height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
    animation-name: zoom;
    animation-duration: 0.6s;
}

@keyframes zoom {
    from {transform:scale(0)}
    to {transform:scale(1)}
}

/* The Close Button */
.close {
    position: absolute;
    top: 15px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    transition: 0.3s;
}

.close:hover,
.close:focus {
    color: #bbb;
    text-decoration: none;
    cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
    .modal-content {
        width: 100%;
    }
}  
</style>
