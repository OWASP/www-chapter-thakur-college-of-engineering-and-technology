---
title: pastevents
displaytext: Past Events
layout:  null
tab: true
order: 2
tags: OWASP TCET
---



## Gallery

<div class="gallery">
   <div class="gallery-item">
        <img src="./assets/images/PAST EVENTS/owasp_banner(3).png" alt="Event 1">
        <div class="gallery-text">
            <p>Event Name: <strong>Hands-on With Linux</strong></p>
            <p>Date: February 2, 2024</p>
            <p>Time: 2:30 PM- 4:30 PM</p>
            <p>Platform: TCET CAMPUS</p>
            <p>Speaker: Ms. Rhea Rajput, Mr. Sharez Shaikh, Mr. Shivam Mishra, Mr. Vaibhav Singh</p>
        </div>
   </div>
   <div class="gallery-item">
        <img src="./assets/images/PAST EVENTS/Web Attacks(1).png" alt="Event 2">
        <div class="gallery-text">
            <p>Event Name: <strong>Common Web Attacks</strong></p>
            <p>Date: January 27, 2024</p>
            <p>Time: 2:30 PM - 4:30 PM</p>
            <p>Platform: Zoom</p>
             <p>Speaker: Mr. Vaibhav Singh</p>
        </div>
   </div>
     <div class="gallery-item">
        <img src="./assets/images/PAST EVENTS/OWASP.png" alt="Event 2">
        <div class="gallery-text">
            <p>Event Name: <strong>Common Tools For Attackers</strong></p>
            <p>Date: January 19, 2024</p>
            <p>Time: 4:30 PM - 6:30 PM</p>
            <p>Platform: Zoom</p>
             <p>Speaker: Mr. Shivam Mishra</p>
        </div>
   </div>
     <div class="gallery-item">
        <img src="./assets/images/PAST EVENTS/Green White Modern Business Flyer (Instagram Post).png" alt="Event 2">
        <div class="gallery-text">
            <p>Event Name: <strong>Chapter Inauguration & Interaction With Industry Experts</strong></p>
            <p>Date: October 14, 2023</p>
            <p>Time: 4:30 PM- 6:30 PM </p>
            <p>Venue: TCET Campus</p>
             <p>Speaker: Mr. Yash Roongta, Mr. Himanshu Sharma, Mr. Rohan Rane</p>
        </div>
   </div>
   <!-- Add more gallery items as needed -->
</div>

<style>
    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        grid-gap: 20px;
    }

 .gallery-item {
    position: relative;
    object-fit: contain;
}

.gallery-text {
    position: absolute;
    bottom: 0;
    left: 0;
    visibility: hidden; /* Hide the text by default */
    opacity: 0; /* Start with opacity 0 */
    background-color: rgba(255, 255, 255, 0.8);
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
    transition: visibility 0s, opacity 0.5s; /* Add transition effect */
}

.gallery-item:hover .gallery-text {
    visibility: visible; /* Show the text on hover */
    opacity: 1; /* Make the text fully visible */
}

.gallery-item img {
    width: 350px;
    height: auto;
}

</style>
