---
layout: page
title: Summer Programming Classes 2024
description: Classes that were taught with my robotics team
img: assets/img/teaching_cover.jpg
importance: 1
category: Classes
horizontal: false
---

---

<!-- Text -->
<br>
<div class="text">
    <p>
    Before the 2023-2024 season Vortex Robotics held our summer training classes in which we helped over 20 students dive deep into the world of robotics. We taught the the basics of hardware and programming and helped them build their own Arduino robots.
    </p>
</div>
<br>
<div class="impact">
    <ul class="list">
    <li>20+ students impacted</li>
    <li>Every student built their own robot</li>
    </ul>
</div>
---

<!-- Videos and Image -->
<div class="row">
    <div class="column">
       <div class="image">
            {% include figure.liquid path="assets/img/teaching_1.jpg" title="Image"%}
        </div>
    </div>
    <div class="column">
       <div class="image">
            {% include figure.liquid path="assets/img/teaching_2.jpg" title="Image"%}
        </div>
    </div>
    <div class="column">
        <div class="image">
            {% include figure.liquid path="assets/img/teaching_3.jpg" title="Image"%}
        </div>
    </div>
</div>




<!-- Styles -->
<style>

    .row {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 20px; /*Optional: Adds space between the columns */
    }

    .column {
        flex: 1;
        text-align: center;
    }

    .column iframe, .column img {
        max-width: 100%;
    }
 
   .YT-Video {
        position: relative;
        width: 100%; /* Adjust the width as needed */
        height: 100%; /* Adjust the height to leave space for the description */       
        border: 5px solid white; /* Add a white border */
    }

    /* Description Text */
    .text {
        font-size: 1.9rem;
        line-height: 200%;
        text-align: center;
        display: block
    }
    .impact {
        text-align: center;
        list-style-position: inside;
        line-height: 300%;
        display: block
    }
    .impact .list {
        text-align: center;
        font-size: 2rem;
        font-weight: 300;
        display: inline-block
    }
    .image {
        max-width: 100%;
        height: 100%;
        border: 5px solid white; /* Add a white border */

    }

</style>
