---
layout: page
permalink: /publications/index.html
title: 作品集
---

## 作品集
<div class="publications-grid">

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/line.png" alt="Kina Maps Project">
      <a href="/publications/project-9900/" class="publication-overlay" target="_blank" rel="noopener">
        <span>查看细节</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="/publications/project-9900/" target="_blank" rel="noopener">数据仓储管理系统</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Zhaoyuan Xu</strong>, Lu Zhang, Han Bao, Yuchen Wang, Chi Man Fu</div>
      <div class="publication-conference"><span class="pub-venue"></span> <a href="/publications/project-9900/" target="_blank">[相关截图和报告]</a></div>
      <div class="publication-details">前端负责人</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/Hamster.png" alt="UE Game">
      <a href="https://drive.google.com/drive/folders/1Kso2G-yHmuZwRNfWsCkuCDw2hempk9X0?usp=drive_link" class="publication-overlay" target="_blank" rel="noopener">
        <span>获取Demo和源码</span>
      </a>
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a href="https://drive.google.com/drive/folders/1Kso2G-yHmuZwRNfWsCkuCDw2hempk9X0?usp=drive_link" target="_blank" rel="noopener">UE游戏项目：仓鼠球</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Zhaoyuan Xu</strong>, Weihang Wang, Ruojin Zhou, Linghan Wangh</div>
      <div class="publication-conference"><span class="pub-venue">访问我的谷歌云盘以下载试玩Demo及项目文件</span> <a href="https://drive.google.com/drive/folders/1Kso2G-yHmuZwRNfWsCkuCDw2hempk9X0?usp=drive_link" target="_blank">[谷歌云盘]</a></div>
      <div class="publication-details">项目负责人 & 核心开发</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/images/papers/Mercury.jpg" alt="Mercury Project">
    </div>
    <div class="publication-info">
      <div class="publication-title">
        <a target="_blank" rel="noopener">私人网站Mercury</a>
      </div>
      <div class="publication-authors"><strong class="author-highlight">Zhaoyuan Xu</strong></div>
      <div class="publication-conference"><span class="pub-venue">项目推进中，暂无预览</span> <a target="_blank">[推进中]</a></div>
      <div class="publication-details">私人站点</div>
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
