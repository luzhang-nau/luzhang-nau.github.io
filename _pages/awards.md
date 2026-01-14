---
permalink: /awards/
title: "获奖信息"
---

<div class="awards-section">
  <div class="awards-container">
    
    <div class="awards-category">
      <h2 class="category-title">学生培养方面</h2>
      <div class="awards-list">
        <div class="award-item">
          <span class="award-text">江苏省大学生计算机设计大赛 优秀指导教师（2022）</span>
        </div>
        <div class="award-item">
          <span class="award-text">蓝桥杯全国软件和信息技术专业人才大赛 优秀指导教师（2017、2018、2019）</span>
        </div>
      </div>
    </div>
    
    <hr class="category-divider" />
    
    <div class="awards-category">
      <h2 class="category-title">科研方面</h2>
      <div class="awards-list">
        <div class="award-item">
          <span class="award-text">IEEE Cybermatics Congress Best Application Paper Award（2023）</span>
        </div>
        <div class="award-item">
          <span class="award-text">江苏发展研究奖一等奖（2023）</span>
        </div>
        <div class="award-item">
          <span class="award-text">江苏省通信学会科技进步三等奖（2018）</span>
        </div>
      </div>
    </div>
    
  </div>
</div>

<style>
.awards-section {
  margin: 40px 0;
}

.awards-container {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 20px;
}

.awards-category {
  margin-bottom: 40px;
}

.category-title {
  color: #333; 
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 2px solid #e0e0e0; 
}

.category-divider {
  border: none;
  height: 1px;
  background-color: #e0e0e0; 
  margin: 40px 0;
}

.awards-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.award-item {
  background: white;
  border: 1px solid #e0e0e0;
  border-radius: 6px;
  padding: 16px 20px;
  transition: all 0.2s ease;
  position: relative;
}

.award-item:hover {
  background-color: #f8f9fa; 
  border-color: #d0d0d0; 
}

.award-text {
  color: #333;
  font-size: 16px;
  line-height: 1.5;
  font-weight: 500;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .awards-container {
    padding: 0 15px;
  }
  
  .category-title {
    font-size: 24px;
  }
  
  .award-item {
    padding: 14px 15px;
  }
  
  .award-text {
    font-size: 15px;
  }
}

@media (max-width: 480px) {
  .category-title {
    font-size: 22px;
  }
  
  .award-item {
    padding: 12px 15px;
  }
  
  .award-text {
    font-size: 14px;
  }
}
</style>
