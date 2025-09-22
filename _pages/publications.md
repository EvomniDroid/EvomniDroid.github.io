---
layout: archive                            # 页面布局：使用归档页面模板
title: "Publications (First author)"       # 页面标题：发表论文（第一作者）
permalink: /publications/                  # 页面永久链接：/publications/
author_profile: true                       # 显示作者信息栏：启用
---

<!-- 条件显示Google Scholar链接 -->
{% if site.author.googlescholar %}          <!-- 如果配置了Google Scholar链接 -->
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  <!-- 提示文字：您也可以在我的Google Scholar档案中找到我的文章 -->
{% endif %}                                 <!-- 条件判断结束 -->

{% include base_path %}                     <!-- 包含基础路径配置 -->

## In submission    <!-- 二级标题：投稿中的论文 -->

## 2025    <!-- 二级标题：2025年发表的论文 -->

<!-- 循环遍历2025年的论文 -->
{% for post in site.publications reversed %}    <!-- 倒序遍历所有论文 -->
  {% if post.year == 2025 %}                   <!-- 如果论文年份是2025年 -->
    {% include archive-single.html %}          <!-- 包含单篇论文显示模板 -->
  {% endif %}                                   <!-- 条件判断结束 -->
{% endfor %}                                    <!-- 循环结束 -->

## 2024    <!-- 二级标题：2024年发表的论文 -->

<!-- 循环遍历2024年的论文 -->
{% for post in site.publications reversed %}    <!-- 倒序遍历所有论文 -->
  {% if post.year == 2024 %}                   <!-- 如果论文年份是2024年 -->
    {% include archive-single.html %}          <!-- 包含单篇论文显示模板 -->
  {% endif %}                                   <!-- 条件判断结束 -->
{% endfor %}                                    <!-- 循环结束 -->

## 2023    <!-- 二级标题：2023年发表的论文 -->

<!-- 循环遍历2023年的论文 -->
{% for post in site.publications reversed %}    <!-- 倒序遍历所有论文 -->
  {% if post.year == 2023 %}                   <!-- 如果论文年份是2023年 -->
    {% include archive-single.html %}          <!-- 包含单篇论文显示模板 -->
  {% endif %}                                   <!-- 条件判断结束 -->
{% endfor %}                                    <!-- 循环结束 -->

## 2022    <!-- 二级标题：2022年发表的论文 -->

<!-- 循环遍历2022年的论文 -->
{% for post in site.publications reversed %}    <!-- 倒序遍历所有论文 -->
  {% if post.year == 2022 %}                   <!-- 如果论文年份是2022年 -->
    {% include archive-single.html %}          <!-- 包含单篇论文显示模板 -->
  {% endif %}                                   <!-- 条件判断结束 -->
{% endfor %}                                    <!-- 循环结束 -->

## 2020    <!-- 二级标题：2020年发表的论文 -->

<!-- 循环遍历2020年的论文 -->
{% for post in site.publications reversed %}    <!-- 倒序遍历所有论文 -->
  {% if post.year == 2020 %}                   <!-- 如果论文年份是2020年 -->
    {% include archive-single.html %}          <!-- 包含单篇论文显示模板 -->
  {% endif %}                                   <!-- 条件判断结束 -->
{% endfor %}                                    <!-- 循环结束 -->
