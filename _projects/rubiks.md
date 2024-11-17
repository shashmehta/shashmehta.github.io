---
layout: page
title: Rubik's Cube Animation
description: A fun animation I made in Blender to practice my skills
img: assets/img/Rubiks.png
importance: 2
category: Fun
giscus_comments: false
---


<!-- Text -->
<br>
<p class="project-text">This was one of my first independent projects that I made without a tutorial, to practice all the skills I had learned. I started it, expecting to make a realistic Rubik's cube, but decided to go for a more stylised look at the end. I really enjoyed making this project and the end result turned out amazing.</p>

---

<!-- Youtube Video -->
<br>
<div class="YT-Video">
    <iframe src="https://www.youtube.com/embed/C2VuaL9GTGE?si=lTwUSE6fuaDgEV1I" frameborder="0" allowfullscreen></iframe>
</div>
<br>





<!-- Styles --> 
<style>

    /* Description Text */
    .project-text {
        font-size: 1.5rem;
        line-height: 200%;
        text-align: justify;
    }

    :root {
        --aspect-ratio: calc((9 / 16) * 100%); /* 16:9 aspect ratio */
    }

    /* Youtube video */
    .YT-Video {
        position: relative;
        width: 75%; /* Scale the width slightly */
        padding-bottom: var(--aspect-ratio); /* 16:9 aspect ratio (9/16 = 0.5625) */
        height: 0; /* Set height to 0 to use padding-bottom for aspect ratio */
        margin: 0 auto; /* Center the video horizontally */
        display: block; /* Ensure the video is displayed as a block element */
        border: 5px solid white; /* Add a white border */
    }

    .YT-Video iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>