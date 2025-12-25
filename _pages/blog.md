---
# 头部Front Matter（必须保留，确保Jekyll正确解析）
layout: archive
title: "Blog Posts & External Links"
permalink: /year-archive/
---

# My Academic Notes & External Resources
<!-- 本地博客列表 -->
<div class="mb-8">
  <h3 class="text-xl font-medium text-gray-800 mb-4">本地博客</h3>
  <ul style="list-style: none; padding-left: 0;">
    {% for post in site.posts %}
      <li style="margin-bottom: 15px; padding-bottom: 10px; border-bottom: 1px solid #eaeaea;">
        <a href="{{ post.url }}" class="text-blue-600 hover:text-blue-800 font-medium">
          {{ post.title }}
        </a>
        <p class="text-gray-500 text-sm mt-1">
          {{ post.date | date: "%Y-%m-%d" }} | {{ post.categories | join: ", " }}
        </p>
      </li>
    {% endfor %}
  </ul>
</div>

<!-- 外部链接列表（从_config.yml渲染） -->
<div>
  <h3 class="text-xl font-medium text-gray-800 mb-4">外部博客/文章</h3>
  <ul style="list-style: none; padding-left: 0;">
    {% for link in site.external_blog_links %}
      <li style="margin-bottom: 15px; padding-bottom: 10px; border-bottom: 1px solid #eaeaea;">
        <a href="{{ link.url }}" target="_blank" class="text-blue-600 hover:text-blue-800 font-medium">
          {{ link.title }} <span class="text-gray-400 text-sm">[外部链接]</span>
        </a>
        <p class="text-gray-500 text-sm mt-1">
          {{ link.date }} | {{ link.category }}
        </p>
      </li>
    {% endfor %}
  </ul>
</div>

<!-- 可选：添加LaTeX公式示例（AcademicPages已内置MathJax，支持LaTeX渲染） -->
<div class="mt-8 pt-4 border-t border-gray-200">
  <h3 class="text-xl font-medium text-gray-800 mb-4">LaTeX公式演示（示例）</h3>
  <p>行内公式：$E=mc^2$，$\sum_{i=1}^{n} x_i = \bar{x} \cdot n$</p>
  <p>独立公式：</p>
  $$
  \min_{w,b} \frac{1}{2} \|w\|^2 + C \sum_{i=1}^{m} \xi_i
  $$
  $$
  \frac{\partial L}{\partial \theta} = \frac{1}{N} \sum_{i=1}^{N} (y_i - \hat{y}_i) \cdot x_i
  $$
</div>