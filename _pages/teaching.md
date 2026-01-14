---
permalink: /teaching/
title: "课程信息"
---

<div class="teaching-section">
  <div class="courses-container">
    
    <div class="section-header">
      <h2 class="section-title">本科生课程</h2>
    </div>
    
    <div class="course-grid">
      <div class="course-card">
        <div class="course-header">
          <h3 class="course-title">Python编程基础</h3>
          <span class="course-badge">春学期</span>
        </div>
        <div class="course-info">
          <div class="info-item">
            <span class="info-label">授课对象：</span>
            <span class="info-value">人工智能专业本科生</span>
          </div>
          <div class="info-item">
            <span class="info-label">授课时间：</span>
            <span class="info-value">春学期</span>
          </div>
        </div>
      </div>
      
      <div class="course-card">
        <div class="course-header">
          <h3 class="course-title">Python高级编程</h3>
          <span class="course-badge">秋学期</span>
        </div>
        <div class="course-info">
          <div class="info-item">
            <span class="info-label">授课对象：</span>
            <span class="info-value">人工智能专业本科生、数据科学与大数据技术本科生</span>
          </div>
          <div class="info-item">
            <span class="info-label">授课时间：</span>
            <span class="info-value">秋学期</span>
          </div>
        </div>
      </div>
    </div>
    
    <hr class="section-divider" />
    
    <div class="section-header">
      <h2 class="section-title">研究生课程</h2>
    </div>
    
    <div class="course-grid">
      <div class="course-card">
        <div class="course-header">
          <h3 class="course-title">高级数据库技术</h3>
          <span class="course-badge">春学期</span>
        </div>
        <div class="course-info">
          <div class="info-item">
            <span class="info-label">授课对象：</span>
            <span class="info-value">计算机技术专业硕士生</span>
          </div>
          <div class="info-item">
            <span class="info-label">授课时间：</span>
            <span class="info-value">春学期</span>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</div>

<style>
.teaching-section {
  margin: 40px 0;
}

.courses-container {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 20px;
}

.section-header {
  margin-bottom: 30px;
}

.section-title {
  color: #1a4b8c;
  font-size: 28px;
  font-weight: 600;
  padding-bottom: 10px;
  border-bottom: 2px solid #e8edf2;
}

.section-divider {
  border: none;
  height: 1px;
  background-color: #e8edf2;
  margin: 40px 0;
}

.course-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 25px;
  margin-bottom: 40px;
}

.course-card {
  background: white;
  border: 1px solid #e8edf2;
  border-radius: 8px;
  padding: 25px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
}

.course-card:hover {
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.08);
  transform: translateY(-3px);
  border-color: #d1e8ff;
}

.course-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 20px;
  padding-bottom: 15px;
  border-bottom: 1px solid #f0f4f8;
}

.course-title {
  color: #2c3e50;
  font-size: 20px;
  font-weight: 600;
  margin: 0;
  line-height: 1.3;
}

.course-badge {
  background: #1a4b8c;
  color: white;
  padding: 5px 15px;
  border-radius: 15px;
  font-size: 14px;
  font-weight: 500;
  white-space: nowrap;
}

.course-info {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.info-item {
  display: flex;
  align-items: flex-start;
  gap: 8px;
}

.info-label {
  color: #333;
  font-weight: 500;
  font-size: 15px;
  min-width: 80px;
  flex-shrink: 0;
}

.info-value {
  color: #333;
  font-size: 15px;
  line-height: 1.5;
  flex: 1;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .courses-container {
    padding: 0 15px;
  }
  
  .section-title {
    font-size: 24px;
  }
  
  .course-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }
  
  .course-card {
    padding: 20px;
  }
  
  .course-title {
    font-size: 18px;
  }
  
  .info-item {
    flex-direction: column;
    gap: 5px;
  }
  
  .info-label {
    min-width: auto;
  }
}

@media (max-width: 480px) {
  .course-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }
  
  .section-title {
    font-size: 22px;
  }
  
}
</style>
