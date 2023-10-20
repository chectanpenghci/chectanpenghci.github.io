---
layout: page
permalink: /projects/index.html
title: Projects
---

Lastest Update: 18th Oct 2023

<button class="collapse-btn">design</button>
<div class="content">
  <p>
    In the DHE classroom, students use digital tools to assist in understanding intangible cultural heritage (ICH), which comprises intricate knowledge. However, studentsmay still encounter obstacles when trying to produce creative designs. To address this issue, we propose a framework that adopts a human-engaged computing perspective to enhance the understanding and design of ICHthrough phased synergized engagement between engaged students and engaging digital tools. To validate the effectiveness of the proposed framework, we designed, implemented, and tracked Cantonese Porcelain (CP) Creative Design courses over five years. 
    <img src="/images/dhe.jpg">
  </p>
</div>

<button class="collapse-btn">design</button>
<div class="content">
  <p>
    In the DHE classroom, students use digital tools to assist in understanding intangible cultural heritage (ICH), which comprises intricate knowledge. However, studentsmay still encounter obstacles when trying to produce creative designs. To address this issue, we propose a framework that adopts a human-engaged computing perspective to enhance the understanding and design of ICHthrough phased synergized engagement between engaged students and engaging digital tools. To validate the effectiveness of the proposed framework, we designed, implemented, and tracked Cantonese Porcelain (CP) Creative Design courses over five years. 
    <img src="/images/dhe.jpg">
  </p>
</div>

<button class="collapse-btn">design</button>
<div class="content">
  <p>
    In the DHE classroom, students use digital tools to assist in understanding intangible cultural heritage (ICH), which comprises intricate knowledge. However, studentsmay still encounter obstacles when trying to produce creative designs. To address this issue, we propose a framework that adopts a human-engaged computing perspective to enhance the understanding and design of ICHthrough phased synergized engagement between engaged students and engaging digital tools. To validate the effectiveness of the proposed framework, we designed, implemented, and tracked Cantonese Porcelain (CP) Creative Design courses over five years. 
    <img src="/images/dhe.jpg">
  </p>
</div>

.content {
  display: none;
}

.show {
  display: block;
}

const collapseBtn = document.querySelector('.collapse-btn');
const content = document.querySelector('.content');

collapseBtn.addEventListener('click', function() {
  content.classList.toggle('show');
});