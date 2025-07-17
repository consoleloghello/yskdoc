---
layout: default
title: 综合题库文档中心
description: 地面火炬、给水加压泵站、罐区、锅炉等设备题库查询系统
nav_order: 1
---

# 综合题库文档中心

**随时查询 • 移动适配 • 持续更新**

---

## 📚 题库分类导航

<div class="grid-container">
  <div class="card">
    <h3><a href="/ground-flare/">地面火炬系统</a></h3>
    <ul>
      <li><a href="/ground-flare/multiple-choice">选择题</a></li>
      <li><a href="/ground-flare/fill-in-blank">填空题</a></li>
      <li><a href="/ground-flare/true-false">判断题</a></li>
      <li><a href="/ground-flare/short-answer">简答题</a></li>
    </ul>
  </div>

  <div class="card">
    <h3><a href="/water-pump/">给水加压泵站</a></h3>
    <ul>
      <li><a href="/water-pump/multiple-choice">选择题</a></li>
      <li><a href="/water-pump/fill-in-blank">填空题</a></li>
      <li><a href="/water-pump/true-false">判断题</a></li>
      <li><a href="/water-pump/short-answer">简答题</a></li>
    </ul>
  </div>

  <div class="card">
    <h3><a href="/tank-area/">罐区系统</a></h3>
    <ul>
      <li><a href="/tank-area/multiple-choice">选择题</a></li>
      <li><a href="/tank-area/fill-in-blank">填空题</a></li>
      <li><a href="/tank-area/true-false">判断题</a></li>
      <li><a href="/tank-area/short-answer">简答题</a></li>
    </ul>
  </div>

  <div class="card">
    <h3><a href="/boiler/">锅炉系统</a></h3>
    <ul>
      <li><a href="/boiler/multiple-choice">选择题</a></li>
      <li><a href="/boiler/fill-in-blank">填空题</a></li>
      <li><a href="/boiler/true-false">判断题</a></li>
      <li><a href="/boiler/short-answer">简答题</a></li>
    </ul>
  </div>
</div>

---

## 🔍 快速搜索
<input type="text" id="searchInput" placeholder="输入关键词搜索题库...">
<div id="searchResults"></div>

---

## 📱 使用提示
1. **手机访问**：本页面已适配移动端，可随时通过手机浏览器访问
2. **内容更新**：题库持续更新，建议收藏本站
3. **紧急查询**：按`Ctrl+F`可使用浏览器内置搜索功能

---

<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  margin: 30px 0;
}
.card {
  border: 1px solid #e1e4e8;
  border-radius: 6px;
  padding: 20px;
  transition: all 0.3s;
}
.card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
#searchInput {
  width: 100%;
  padding: 12px;
  border: 2px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}
</style>

<script>
// 简易搜索功能（需配合后续的搜索插件完善）
document.getElementById('searchInput').addEventListener('keyup', function(e) {
  if (e.key === 'Enter') {
    alert('搜索功能需配合jekyll-search插件使用，将在后续配置中完善');
  }
});
</script>