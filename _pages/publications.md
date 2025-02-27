---
permalink: /publications/
title: "Publications"
# modified: 2024-08-11
---

<style>
  ol.custom-list {
    list-style: none; /* Remove default numbering */
    counter-reset: custom-counter; 
  }

  ol.custom-list li {
    counter-increment: custom-counter; 
    margin-bottom: 5px;
  }

  ol.custom-list li::before {
    content: "[" counter(custom-counter) "] "; 
  }
</style>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-G0LL0BQ7KR"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-G0LL0BQ7KR');
</script>
___
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Conference Papers


<ol class="custom-list">

    <li>
        C. <b>Boldrin</b> and F. Vandin, "Fast and Accurate Triangle Counting in Graph Streams Using Predictions," 
        2024 IEEE International Conference on Data Mining <b>(ICDM)</b>, Abu Dhabi, United Arab Emirates, 2024, pp. 31-40, 
        doi: 10.1109/ICDM59182.2024.00010 (10,9% acceptance rate for regular papers)
        <br>
        <small>
        Resources: 
            <a href="https://ieeexplore.ieee.org/document/10884156">Paper</a>, 
            <a href="https://arxiv.org/pdf/2409.15205">ArXiv Extended Version</a>, 
            <a href="https://github.com/VandinLab/Tonic/">Code</a>, 
            <a href="https://cristianboldrin.github.io/files/TonicTalk.pdf">Slides</a>.
        </small>
    </li>


</ol>



---