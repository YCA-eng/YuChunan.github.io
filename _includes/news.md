<h2 style="margin: 2px 0px -10px;">
  <a href="./_news/news.html" style="text-decoration: none; color: inherit;">News</a>
</h2>
<br>
<div style="font-size: 16px; line-height: 1.6; letter-spacing: 0.5px; text-align: justify; color: #000000; background-color: #ffffff;">
  {% for item in site.data.news limit:1000 %}
  <p style="margin: 4px 0;">
    <span style="color: #000; font-weight: bold;">[</span><span style="color: #d9534f; font-weight: 700; font-family: 'Times New Roman', Times, serif;">{{ item.time }}</span><span style="color: #000; font-weight: bold;">]</span> {{ item.description }}
  </p>
  {% endfor %}
</div>
