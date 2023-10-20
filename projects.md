---
layout: page
permalink: /projects/index.html
title: Projects
---

Lastest Update: 18th Oct 2023

<button id="toggleBtn">展开/折叠</button>
<div id="content">这里是要展开/折叠的内容</div>

<button id="toggleBtn">展开/折叠</button>
<div id="content">这里是要展开/折叠的内容</div>

var toggleBtn = document.getElementById("toggleBtn");
var content = document.getElementById("content");

toggleBtn.addEventListener("click", function() {
  if (content.style.display === "none") {
    content.style.display = "block";
  } else {
    content.style.display = "none";
  }
});
