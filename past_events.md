---
title: Past Events
layout: null
tab: true
order: 1
tags: OWASP TCET
---

<!DOCTYPE html>
<html>
<head>
<style>
  /* Style the tab buttons */
  .tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
  }

  /* Style the tab content */
  .tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
  }
</style>
</head>
<body>

<h2>Past Events</h2>

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'event1')">Event 1</button>
  <button class="tablinks" onclick="openTab(event, 'event2')">Event 2</button>
</div>

<div id="event1" class="tabcontent">
  <h3>Event 1</h3>
  <p><strong>Date:</strong> October 10, 2023</p>
  <p><strong>Location:</strong> Virtual</p>
  <p><strong>Event Overview:</strong> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, nisl non hendrerit.</p>
  <p><strong>Event Photos:</strong></p>
  <img src="event1_image1.jpg" alt="Image 1">
  <img src="event1_image2.jpg" alt="Image 2">
  <img src="event1_image3.jpg" alt="Image 3">
  <p><strong>Event Videos:</strong></p>
  <ul>
    <li><a href="event1_video1_link">Watch Video 1</a></li>
    <li><a href="event1_video2_link">Watch Video 2</a></li>
    <li><a href="event1_video3_link">Watch Video 3</a></li>
  </ul>
  <p><strong>Event Highlights:</strong> Highlight any special moments or key takeaways from Event 1.</p>
</div>

<div id="event2" class="tabcontent">
  <h3>Event 2</h3>
  <p><strong>Date:</strong> November 15, 2023</p>
  <p><strong>Location:</strong> Thakur College of Engineering and Technology</p>
  <p><strong>Event Overview:</strong> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, nisl non hendrerit.</p>
  <p><strong>Event Photos:</strong></p>
  <img src="event2_image1.jpg" alt="Image 1">
  <img src="event2_image2.jpg" alt="Image 2">
  <img src="event2_image3.jpg" alt="Image 3">
  <p><strong>Event Videos:</strong></p>
  <ul>
    <li><a href="event2_video1_link">Watch Video 1</a></li>
    <li><a href="event2_video2_link">Watch Video 2</a></li>
    <li><a href="event2_video3_link">Watch Video 3</a></li>
  </ul>
  <p><strong>Event Highlights:</strong> Highlight any special moments or key takeaways from Event 2.</p>
</div>

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Open the first tab by default
document.getElementById("event1").style.display = "block";
</script>

</body>
</html>
