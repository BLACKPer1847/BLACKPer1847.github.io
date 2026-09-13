---
layout: page
permalink: /publications/index.html
title: 作品集
---

## 作品集
<div class="publications-grid">

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/paper1.svg" alt="Innovative covariance-based framework">
      <a href="https://www.tandfonline.com/doi/abs/10.1080/03610918.2026.2635000" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://www.tandfonline.com/doi/abs/10.1080/03610918.2026.2635000" target="_blank" rel="noopener">Innovative covariance-based framework: symmetry assessment and exponentiality testing under multiplicative distortion measurement Errors</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Siming Deng</strong>, Jun Zhang, Jiongtao Zhong</div>
      <div class="publication-conference"><span class="pub-venue">Communications in Statistics - Simulation and Computation, 2026</span> <a href="https://www.tandfonline.com/doi/abs/10.1080/03610918.2026.2635000" target="_blank">[paper]</a></div>
      <div class="publication-details">SCI, first author</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/paper2.svg" alt="A New Logarithmic Multiplicative Distortion">
      <a href="https://onlinelibrary.wiley.com/doi/10.1002/sam.11708" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://onlinelibrary.wiley.com/doi/10.1002/sam.11708" target="_blank" rel="noopener">A New Logarithmic Multiplicative Distortion for Correlation Analysis</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Siming Deng</strong>, Jun Zhang</div>
      <div class="publication-conference"><span class="pub-venue">Statistical Analysis and Data Mining, 2024</span> <a href="https://onlinelibrary.wiley.com/doi/10.1002/sam.11708" target="_blank">[paper]</a></div>
      <div class="publication-details">SCI, JCR: Q1, first author, Top Cited Article - WILEY 2025</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/paper3.svg" alt="A Revisit to Pearson Correlation Coefficient">
      <a href="https://www.tandfonline.com/doi/full/10.1080/03610918.2024.2333352" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://www.tandfonline.com/doi/full/10.1080/03610918.2024.2333352" target="_blank" rel="noopener">A Revisit to Pearson Correlation Coefficient under Multiplicative Distortions</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Siming Deng</strong>, Jun Zhang, Yingcong Huang, Jiongtao Zhong & Xiaozhen Yang</div>
      <div class="publication-conference"><span class="pub-venue">Communications in Statistics - Simulation and Computation, 2024</span> <a href="https://www.tandfonline.com/doi/full/10.1080/03610918.2024.2333352" target="_blank">[paper]</a></div>
      <div class="publication-details">SCI, first author, Highly Cited Paper - Web of Science</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/paper4.svg" alt="Covariance Ratio under Multiplicative Distortion">
      <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2295240" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2295240" target="_blank" rel="noopener">Covariance Ratio under Multiplicative Distortion Measurement Errors</a>
      </div>
      <div class="publication-authors">Jiongtao Zhong, <strong class="author-highlight">Siming Deng</strong>, Jun Zhang & Zhenghui Feng</div>
      <div class="publication-conference"><span class="pub-venue">Communications in Statistics - Theory and Methods, 2023</span> <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2295240" target="_blank">[paper]</a></div>
      <div class="publication-details">SCI, 2nd-author</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/paper5.svg" alt="Estimation of Correlation Coefficient">
      <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2288794" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2288794" target="_blank" rel="noopener">Estimation of Correlation Coefficient with Monotone Transformation and Multiplicative Distortions</a>
      </div>
      <div class="publication-authors">Jun Zhang, Xuan Yu, <strong class="author-highlight">Siming Deng</strong>, Jiongtao Zhong, Yisheng Zhou & Bingqing Lin</div>
      <div class="publication-conference"><span class="pub-venue">Communications in Statistics - Theory and Methods, 2023</span> <a href="https://www.tandfonline.com/doi/full/10.1080/03610926.2023.2288794" target="_blank">[paper]</a></div>
      <div class="publication-details">SCI, 3rd-author</div>
    </div>
  </div>

</div>


<script>
(function() {
  if ('IntersectionObserver' in window) {
    var observer = new IntersectionObserver(function(entries) {
      entries.forEach(function(entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add('animate-in');
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.08, rootMargin: '0px 0px -40px 0px' });
    document.querySelectorAll('.publication-card').forEach(function(card) {
      observer.observe(card);
    });
  } else {
    document.querySelectorAll('.publication-card').forEach(function(card) {
      card.classList.add('animate-in');
    });
  }
})();
</script>

---
