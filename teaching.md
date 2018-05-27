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
        <a title="Digital Signal Processing" href="http://rslab-tech.disi.unitn.it/moodle/course/view.php?id=17" target="_blank">Digital Signal Processing</a>, Main Lecturer from 2013 to 2018 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
      </span>
      <span class="list-group-item list-group-item-action">
        <a title="Remote Sensing Systems" href="http://rslab-tech.disi.unitn.it/moodle/course/view.php?id=10" target="_blank">Remote Sensing Systems</a>, Supporting Lecturer from 2015 to 2016 at the Department of Information Engineering and Computer Science, University of Trento, Italy.
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
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="dspImg">
  <div id="caption"></div>
</div>


<script>
// Get the modal
var modal = document.getElementById('myModal');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('myImg');
var modalImg = document.getElementById("dspImg");
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
</script>