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
          <div class="award-header">
            <h3 class="award-name">江苏省大学生计算机设计大赛 优秀指导教师</h3>
            <span class="award-year">2022</span>
          </div>
        </div>
        
        <div class="award-item">
          <div class="award-header">
            <h3 class="award-name">蓝桥杯全国软件和信息技术专业人才大赛 优秀指导教师</h3>
            <span class="award-year">2017、2018、2019</span>
          </div>
          <div class="award-note">连续三年</div>
        </div>
      </div>
    </div>
    
    <hr class="category-divider" />
    
    <div class="awards-category">
      <h2 class="category-title">科研方面</h2>
      <div class="awards-list">
        <div class="award-item">
          <div class="award-header">
            <h3 class="award-name">IEEE Cybermatics Congress Best Application Paper Award</h3>
            <span class="award-year">2023</span>
          </div>
          <div class="award-note international">国际会议最佳论文</div>
        </div>
        
        <div class="award-item">
          <div class="award-header">
            <h3 class="award-name">江苏发展研究奖一等奖</h3>
            <span class="award-year">2023</span>
          </div>
          <div class="award-note">省部级</div>
        </div>
        
        <div class="award-item">
          <div class="award-header">
            <h3 class="award-name">江苏省通信学会科技进步三等奖</h3>
            <span class="award-year">2018</span>
          </div>
          <div class="award-note">省部级</div>
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
  color: #1a4b8c;
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 25px;
  padding-bottom: 10px;
  border-bottom: 2px solid #e8edf2;
}

.category-divider {
  border: none;
  height: 1px;
  background-color: #e8edf2;
  margin: 40px 0;
}

.awards-list {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.award-item {
  background: white;
  border: 1px solid #e8edf2;
  border-radius: 8px;
  padding: 25px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
}

.award-item:hover {
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.08);
  border-color: #d1e8ff;
  transform: translateY(-3px);
}

.award-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 3px;
  background: linear-gradient(to right, #1a4b8c, #3498db);
}

.award-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 10px;
  flex-wrap: wrap;
  gap: 15px;
}

.award-name {
  color: #2c3e50;
  font-size: 18px;
  font-weight: 600;
  margin: 0;
  line-height: 1.4;
  flex: 1;
  min-width: 200px;
}

.award-year {
  background: #1a4b8c;
  color: white;
  padding: 5px 15px;
  border-radius: 15px;
  font-size: 14px;
  font-weight: 500;
  white-space: nowrap;
  flex-shrink: 0;
}

.award-note {
  color: #666;
  font-size: 14px;
  font-style: italic;
  padding: 5px 0;
}

.award-note.international {
  color: #d35400;
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
    padding: 20px;
  }
  
  .award-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }
  
  .award-name {
    font-size: 16px;
    min-width: auto;
  }
  
  .award-year {
    align-self: flex-start;
  }
}

@media (max-width: 480px) {
  .category-title {
    font-size: 22px;
  }
  
  .award-item {
    padding: 15px;
  }
  
  .award-name {
    font-size: 15px;
  }
}
</style>
