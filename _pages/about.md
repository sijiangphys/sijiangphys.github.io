---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year Ph.D. student at [Center for Quantum Information, IIIS](https://cqi.tsinghua.edu.cn/en/) at Tsinghua University, where I am fortunate to be advised by Professor [Dong-Ling Deng](https://iiis.tsinghua.edu.cn/en/People/Faculty/DengDongling.htm). Previously, I graduated from Yao class, IIIS, Tsinghua University. 

My research focuses on non-equilibrium quantum dynamics and quantum simulations. A major theme of my work involves investigating ergodicity-breaking mechanisms, like prethermalization and dynamical freezing, and finding out their potential applications in quantum information science, particularly for quantum memory and sensing. I am also interested in quantum error corrections, from the perspective of non-equilibrium processes and phases of matter. 

# Publications and Preprints
{% for post in site.publications reversed %}
    [{{post.title}}]({{post.link}})
    {{ post.authors }}
    {{ post.excerpt }} 
{% endfor %}