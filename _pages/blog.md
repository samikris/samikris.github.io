---
layout: page
title: thoughts
permalink: /blog/
nav: true
nav_order: 4
---

<style>
/* This CSS styles our blog list */
.blog-container {
  max-width: 700px;  /* Keep content readable width */
  margin: 0 auto;     /* Center the container */
}

.blog-post {
  margin-bottom: 3rem;  /* Space between posts */
}

.blog-post h3 {
  margin-bottom: 0.5rem;  /* Space below title */
  font-size: 1.5rem;      /* Make titles prominent */
}

.blog-post h3 a {
  color: inherit;           /* Use default text color */
  text-decoration: none;    /* Remove underline */
}

.blog-post h3 a:hover {
  color: #2698BA;          /* Color on hover */
}

.post-meta {
  color: #828282;          /* Gray color for date */
  font-size: 0.9rem;       /* Slightly smaller */
  margin-bottom: 0.5rem;   /* Space before excerpt */
}

.post-excerpt {
  line-height: 1.6;        /* Comfortable reading */
  margin-bottom: 0.5rem;   /* Space before read more */
}

.read-more {
  color: #2698BA;          /* Link color */
  text-decoration: none;
  font-size: 0.9rem;
}

.read-more:hover {
  text-decoration: underline;
}

/* Simple divider between posts */
hr.post-divider {
  border: none;
  border-top: 1px solid #e8e8e8;
  margin: 2.5rem 0;
}
</style>

<div class="blog-container">

  <!-- BLOG POST 1 -->
  <div class="blog-post">
    <h3><a href="/blog/2025/ml-sensors/">Starting a Blog</a></h3>
    <div class="post-meta">September 7, 2025</div>
    <div class="post-excerpt">
      Trying to start writing a blog/journal to get in the habit of sharing my thoughts and keeping track of my ideas...
    </div>
    <a href="/blog/2025/ml-sensors/" class="read-more">Read more →</a>
  </div>
  
  <hr class="post-divider">

</div>
