---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>waypig</h1>
        <h2>一个行走的猪</h2>
<a href="http://weibo.com/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="22"/></a>
<a href="http://www.zhihu.com/" target="_blank"><img src="https://static.zhihu.com/static/favicon.ico" alt="" width="22"/></a>
<a href="http://www.douban.com/" target="_blank"><img src="http://www.douban.com/favicon.ico" alt="" width="22"/></a>
<a href="http://instagram.com" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
