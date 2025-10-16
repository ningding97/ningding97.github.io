---
layout: page
permalink: /students/
title: students
description: Our lab information is at <a href="https://c3i.ee.tsinghua.edu.cn/en/">TsinghuaC3I</a>.
nav: false
nav_order: 5
---

<style>
/* Custom container for students page only */
.students-page-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Override the default container width for this page */
@media (min-width: 768px) {
  .post {
    max-width: 100% !important;
  }

  .container {
    max-width: 1200px !important;
  }
}

.students-list {
  list-style: none;
  padding-left: 20px;
  line-height: 1.8;
}

.students-list li {
  padding: 0.3rem 0;
  position: relative;
}

.students-list li:before {
  content: '•';
  position: absolute;
  left: -15px;
  color: #999;
}

.students-list strong {
  font-weight: 500;
}

.students-list a {
  color: #6b8e6b;
  text-decoration: none;
}

.students-list a:hover {
  text-decoration: underline;
}

.student-popup {
  position: absolute;
  bottom: 100%;
  left: 0;
  margin-bottom: 10px;
  margin-left: -10px;
  transform: scale(0);
  background: white;
  border-radius: 12px;
  padding: 1.2rem;
  box-shadow: 0 10px 35px rgba(0, 0, 0, 0.18);
  z-index: 1000;
  opacity: 0;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  pointer-events: none;
  width: 320px;
}

.students-list li:hover .student-popup {
  transform: scale(1);
  opacity: 1;
  pointer-events: auto;
}

@media (max-width: 768px) {
  .student-popup {
    left: 0;
    bottom: auto;
    top: 100%;
    margin-top: 10px;
    margin-bottom: 0;
    transform: scale(0);
  }

  .students-list li:hover .student-popup {
    transform: scale(1);
  }
}

.popup-content {
  display: flex;
  align-items: center;
  gap: 1rem;
}

.popup-avatar {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  background-color: #e8ebe9;
}

.popup-avatar.default {
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #e8ebe9 0%, #dde0dd 100%);
  color: #6b8e6b;
  font-size: 36px;
  font-weight: 300;
}

.popup-info {
  flex: 1;
}

.popup-info h5 {
  margin: 0 0 0.3rem 0;
  color: #333;
  font-size: 1rem;
}

.popup-info p {
  margin: 0;
  color: #666;
  font-size: 0.8rem;
  line-height: 1.3;
}

.section-divider {
  margin: 3rem 0 2rem 0;
}
</style>

## Current Students

<div class="students-page-container">

<ul class="students-list">
  <li>
    <strong><a href="#">Li Sheng</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/student1.jpg" alt="Li Sheng" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>LS</div>'">
        <div class="popup-info">
          <h5>Li Sheng</h5>
          <p>Tsinghua University</p>
          <p>Ph.D. student</p>
          <p>2026 (expected)</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://scholar.google.com/citations?user=T8_JIfkAAAAJ&hl=en" target="_blank">Zijie Qiu</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/zijie.jpeg" alt="Zijie Qiu" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>ZQ</div>'">
        <div class="popup-info">
          <h5>Zijie Qiu</h5>
          <p>Tsinghua & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2026 (expected)</p>
        </div>
      </div>
    </div>
  </li>
  <li>
    <strong><a href="#">Jiale Yu</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/student1.jpg" alt="Jiale Yu" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>JY</div>'">
        <div class="popup-info">
          <h5>Jiale Yu</h5>
          <p>Tsinghua & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2026 (expected)</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://yangjl2003.github.io/" target="_blank">Junlin Yang</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/junlin.png" alt="Junlin Yang" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>JY</div>'">
        <div class="popup-info">
          <h5>Junlin Yang</h5>
          <p>Tsinghua University</p>
          <p>w/ Prof. Bowen Zhou</p>
          <p>Ph.D. student</p>
          <p>2026 (expected)</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://lilhongxy.github.io/" target="_blank">Xiangyu Hong</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/hongxiangyu.png" alt="Xiangyu Hong" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>XH</div>'">
        <div class="popup-info">
          <h5>Xiangyu Hong</h5>
          <p>Tsinghua University</p>
          <p>w/ Prof. Bowen Zhou</p>
          <p>Ph.D. student</p>
          <p>2026 (expected)</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://yuczhang.com/" target="_blank">Yuchen Zhang</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/zhangyuchen.jpeg" alt="Yuchen Zhang" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>YZ</div>'">
        <div class="popup-info">
          <h5>Yuchen Zhang</h5>
          <p>PKU & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://lindsay-13.github.io/" target="_blank">Shang Qu</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/qushang.jpg" alt="Shang Qu" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>SQ</div>'">
        <div class="popup-info">
          <h5>Shang Qu</h5>
          <p>Tsinghua & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://c3i.ee.tsinghua.edu.cn/en/author/haozhan-li/" target="_blank">Haozhan Li</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/lihaozhan.jpg" alt="Haozhan Li" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>HL</div>'">
        <div class="popup-info">
          <h5>Haozhan Li</h5>
          <p>Tsinghua University</p>
          <p>w/ Prof. Bowen Zhou</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="#">Siyan Gao</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/gaosiyan.jpg" alt="Siyan Gao" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>SG</div>'">
        <div class="popup-info">
          <h5>Siyan Gao</h5>
          <p>Tsinghua University</p>
          <p>w/ Prof. Bowen Zhou</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="https://yuchenfan48.github.io/" target="_blank">Yuchen Fan</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/fanyuchen.jpg" alt="Yuchen Fan" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>YF</div>'">
        <div class="popup-info">
          <h5>Yuchen Fan</h5>
          <p>SJTU & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>

  <li>
    <strong><a href="#">Yuhan Chen</a></strong> 
    <div class="student-popup">
      <div class="popup-content">
        <img src="/assets/img/chenyuhan.jpg" alt="Yuhan Chen" class="popup-avatar" onerror="this.outerHTML='<div class=\'popup-avatar default\'>YC</div>'">
        <div class="popup-info">
          <h5>Yuhan Chen</h5>
          <p>Tongji & SH AI LAB</p>
          <p>Ph.D. student</p>
          <p>2025 -</p>
        </div>
      </div>
    </div>
  </li>
</ul>

<div class="section-divider"></div>



## Undergrads/Advisees/Visitors & Alumni

<ul class="students-list">
  <li>
    <strong>Yuxin Zuo</strong>
  </li>

  <li>
    <strong><a href="https://scholar.google.com/citations?user=Q3a25IEAAAAJ&hl=en" target="_blank">Xingtai Lv</a></strong> 
  </li>

  <li>
    <strong><a href="https://cds.nyu.edu/team/yulin-chen/" target="_blank">Yulin Chen</a></strong> 
  </li>
</ul>

</div>
