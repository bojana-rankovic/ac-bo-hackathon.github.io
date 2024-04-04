---
number: 41 # leave as-is, maintainers will adjust
title: RAMBO I - Retrieval augmented initialization for Bayesian optimization strategy
topic: general
team_leads:
  - Bojana Ranković (EPFL) @bojana-rankovic
  - Andres M. Bran (EPFL) @doncamilom
  - Magdalena Lederbauer (EPFL) @mlederbauer
  - Anna Borisova (EPFL) @AnnaKelmanson
  - Geemi Wellawatte (EPFL) @geemi725
  - Philippe Schwaller (EPFL) @pschwllr


github: [schwallergroup/rambo-I](https://github.com/schwallergroup/rambo-I)
# youtube_video: <your-video-id>

---

<div>
  <a href="https://twitter.com/6ojaHa/status/1773734082637095155" title="Play video">
    <div class="video-container">
      <img alt="RAMBO" src="https://video.twimg.com/ext_tw_video/1773717276400750592/pu/vid/avc1/1102x720/ZqAm0K0IcY3l78c6.mp4">
      <span class="play-button bi bi-play-fill"></span>
    </div>
  </a>
</div>

<div>
  <a href="https://twitter.com/6ojaHa/status/1773734082637095155" title="Play video">
    <div class="video-container">
        <source src="https://video.twimg.com/ext_tw_video/1773717276400750592/pu/vid/avc1/1102x720/ZqAm0K0IcY3l78c6.mp4" type="video/mp4">
    </div>
  </a>
</div>

This project aims to incorporate literature or internal database knowledge to jump-start Bayesian optimization by finding relevant studies that match the design space of the reaction to optimize. By using Retrieval Augmented Generation (RAG) we can map the optimization parameters to the closest point in the literature space and use knowledge from the literature to select the initial points for the Bayesian optimization process. 

Check out [our submission post on X](https://twitter.com/6ojaHa/status/1773734082637095155)!

References:

1. Lewis, Patrick, et al. "Retrieval-augmented generation for knowledge-intensive nlp tasks." Advances in Neural Information Processing Systems 33 (2020): 9459-9474.
