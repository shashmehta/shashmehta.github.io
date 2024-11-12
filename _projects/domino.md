---
layout: page
title: Domino Animation
description: A fun animation I made to experiment with rigid body animation
img: assets/img/domino.png
importance: 2
category: Fun
giscus_comments: false
---


<!-- Text -->
<br>
<p class="project-text">This is one of my favorite projects becuase it let me experiment with rigid bodies and strengthen my skills in materials and shading. I was really going for that "satisfying" 3d animation look that you see all over the internet, and it came out really well. One thing I wished I had added was a domino falling sound effect, but I was unable to find a suitable sound that was free.</p>

---

<!-- Youtube Video -->
<br>
<div class="YT-Video">
    <iframe src="https://www.youtube.com/embed/EXJsybOjGQQ?si=GqeigQkWH2Was3oc" frameborder="0" allowfullscreen></iframe>
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