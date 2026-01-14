---
permalink: /students/
title: "指导学生"
---

<div class="section-container">
  <div class="concept-card">
    <div class="concept-content">
      <p>课题组提倡在高效的科研节奏与健康的生活状态之间达成平衡。我们相信，良好的科研产出源于专注与持续，而非无休止的消耗。因此，我们重视规律而充实的工作时间，也希望你能在投入科研时保持高效与自觉，共同营造勤奋踏实的团队氛围。</p>
      
      <p>我们同样注重松弛平等的师生关系与团队文化。导师不会过度施压，但也绝不做所谓的"羊导"。我们相信，真正的充实感来自于对工作的投入与对生活的热爱。因此，我们期待你能在科研时间内保持高效与专注，而闲暇时则挥洒朝气、玩出精彩。课题组会不定期组织爬山、聚餐、轰趴、春秋游等休闲活动，希望同学们在学习工作之余，能够精彩地过好每一天，培养一两项爱好，假期出去走走看看，纵览祖国的大好河山与人文风貌（课题组亦会通过学科竞赛、学术会议等形式支持大家"游学"）。如果你愿意分享生活中的点滴，这里也会是一个愿意倾听的集体。</p>
      
      <p>在这样的环境中，我们见证了团队的持续成长，也收获了扎实的成果：历届研究生毕业时大多有北核以上的论文发表或授权发明专利，在校期间多人荣获一等奖学金、专项奖学金、学术会议最佳论文奖，立项省级科研项目等。这些成果属于每一个为工作倾注心力、也为生活蓄满能量的成员。</p>
      
      <p>我们欢迎有自我驱动力、乐观积极、愿意并肩成长的同学加入。希望同学在读研期间能够保持主动、持续投入，但抱有"我只是想要个学历，别对我那么高要求，周围人都是这么混混的"想法的同学，还请相互放过。读研是一段需要真诚投入的旅程，彼此认同，方能同行。</p>
      
      <div class="callout">
        <p>期待与你一起，认真科研，认真生活。对课题组研究方向感兴趣并认可我们理念的同学，欢迎发送邮件与我联系。</p>
      </div>
    </div>
  </div>
</div>

<style>
/* ========== 学生页面专用样式 ========== */
.section-container {
  margin: 0 auto;
  padding: 0 10px; /* 进一步缩小边距，最大化可用宽度 */
  box-sizing: border-box;
  width: 100%;
}

/* 概念卡片：大幅扩大最大宽度 */
.concept-card {
  max-width: 1800px; /* 从1600px提升到1800px，更宽 */
  margin: 20px auto 30px;
  background: white;
  border: 1px solid #e8edf2;
  border-radius: 15px;
  padding: 30px 40px; /* 恢复稍大的内边距，保持内容舒展 */
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.08);
}

.concept-content p {
  margin-bottom: 20px;
  line-height: 1.8;
  color: #333;
  font-size: 16px;
  text-align: justify;
}

.callout {
  background: linear-gradient(135deg, #f0f8ff 0%, #e6f7ff 100%);
  border-left: 4px solid #3498db;
  border-radius: 8px;
  padding: 20px 25px;
  margin-top: 25px;
  position: relative;
  overflow: hidden;
}

.callout::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  width: 80px;
  height: 80px;
  background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="%233498db" opacity="0.1"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/></svg>');
  background-size: contain;
}

.callout p {
  margin: 0;
  font-size: 17px;
  font-weight: 500;
  color: #1a4b8c;
  font-style: normal;
  line-height: 1.7;
}

.students-table-section {
  margin: 0 auto;
  padding: 0 10px; /* 与卡片保持一致的最小边距 */
  width: 100%;
}

.table-title {
  color: #333 !important;
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 25px;
  padding-bottom: 10px;
  border-bottom: 2px solid #e8edf2;
}

.table-container {
  width: 100%;
  max-width: 1880px; /* 表格比卡片宽80px，保持“宽一点”的视觉效果 */
  margin: 0 auto 30px;
  border-radius: 6px;
  border: 1px solid #e8edf2;
}

/* 表格：固定布局，优化列宽适配更宽容器 */
.students-table {
  width: 100%;
  table-layout: fixed;
  border-collapse: collapse;
  background: white;
  font-size: 15px;
}

.students-table thead {
  background-color: #f8f9fa !important;
  border-bottom: 2px solid #e8edf2;
}

.students-table th {
  padding: 12px 15px !important;
  text-align: left;
  font-weight: 600;
  color: #333 !important;
  font-size: 14px;
  border-bottom: 2px solid #e8edf2;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

/* 研究生表格列宽：适配更宽容器，增加内容展示空间 */
.students-table.graduate-table th:nth-child(1),
.students-table.graduate-table td:nth-child(1) {
  width: 90px; /* 入学年份：略宽一点 */
}
.students-table.graduate-table th:nth-child(2),
.students-table.graduate-table td:nth-child(2) {
  width: 110px; /* 姓名：略宽一点 */
}
.students-table.graduate-table th:nth-child(3),
.students-table.graduate-table td:nth-child(3) {
  width: 400px; /* 硕士论文：大幅加宽，减少换行 */
}
.students-table.graduate-table th:nth-child(4),
.students-table.graduate-table td:nth-child(4) {
  width: calc(100% - 600px); /* 成果与荣誉：剩余宽度更充足 */
}

/* 本科生表格列宽：适配更宽容器 */
.students-table.undergraduate-table th:nth-child(1),
.students-table.undergraduate-table td:nth-child(1) {
  width: 90px; /* 年份：略宽一点 */
}
.students-table.undergraduate-table th:nth-child(2),
.students-table.undergraduate-table td:nth-child(2) {
  width: 350px; /* 姓名团队：大幅加宽，减少换行 */
}
.students-table.undergraduate-table th:nth-child(3),
.students-table.undergraduate-table td:nth-child(3) {
  width: 350px; /* 成果：略宽一点 */
}
.students-table.undergraduate-table td:nth-child(4) {
  width: calc(100% - 890px); /* 备注：剩余宽度 */
}

.students-table tbody tr {
  border-bottom: 1px solid #f0f4f8;
}

.students-table tbody tr:last-child {
  border-bottom: none;
}

.students-table tbody tr:hover {
  background-color: #f8fafc;
}

.students-table td {
  padding: 12px 15px !important;
  vertical-align: top;
  color: #333;
  line-height: 1.5;
  word-wrap: break-word;
  overflow-wrap: break-word;
}

.name-bold {
  font-weight: 600;
  color: #333;
}

.table-divider {
  border: none;
  height: 1px;
  background-color: #e8edf2;
  margin: 30px 10px; 
}

.page__content,
.main-content {
  margin-bottom: 80px !important;
  padding-bottom: 40px !important;
}

.students-table-section:last-of-type {
  margin-bottom: 60px;
}

/* ========== 响应式设计：适配不同宽度屏幕 ========== */
/* 超大屏（2000px+）：最大化宽度 */
@media (min-width: 2000px) {
  .concept-card {
    max-width: 1900px;
  }
  .table-container {
    max-width: 2000px;
  }
}

/* 大屏（1600px+）：保持宽幅 */
@media (max-width: 1800px) {
  .concept-card {
    max-width: 1600px;
  }
  .table-container {
    max-width: 1680px;
  }
}

/* 中大屏（1400px+）：适度收缩 */
@media (max-width: 1600px) {
  .concept-card {
    max-width: 1500px;
  }
  .table-container {
    max-width: 1580px;
  }
  /* 适配列宽 */
  .students-table.graduate-table th:nth-child(3),
  .students-table.graduate-table td:nth-child(3) {
    width: 350px;
  }
  .students-table.undergraduate-table th:nth-child(2),
  .students-table.undergraduate-table td:nth-child(2) {
    width: 450px;
  }
}

/* 中屏（1024px+）：进一步收缩 */
@media (max-width: 1400px) {
  .concept-card {
    max-width: 1300px;
  }
  .table-container {
    max-width: 1380px;
  }
  .students-table.graduate-table th:nth-child(3),
  .students-table.graduate-table td:nth-child(3) {
    width: 300px;
  }
  .students-table.undergraduate-table th:nth-child(2),
  .students-table.undergraduate-table td:nth-child(2) {
    width: 400px;
  }
}

/* 小屏（768px+）：适配常规屏幕 */
@media (max-width: 1024px) {
  .concept-card {
    max-width: 100%;
  }
  .table-container {
    max-width: 100%;
  }
  .students-table.graduate-table th:nth-child(3),
  .students-table.graduate-table td:nth-child(3) {
    width: 250px;
  }
  .students-table.undergraduate-table th:nth-child(2),
  .students-table.undergraduate-table td:nth-child(2) {
    width: 350px;
  }
}

/* 手机屏：紧凑显示 */
@media (max-width: 768px) {
  .concept-card {
    padding: 25px 20px;
  }
  .students-table {
    font-size: 14px;
  }
  .students-table th,
  .students-table td {
    padding: 10px 12px !important;
  }
  .students-table.graduate-table th:nth-child(3),
  .students-table.graduate-table td:nth-child(3) {
    width: 200px;
  }
  .students-table.undergraduate-table th:nth-child(2),
  .students-table.undergraduate-table td:nth-child(2) {
    width: 300px;
  }
}

@media (max-width: 480px) {
  .students-table {
    font-size: 13px;
  }
  .students-table th,
  .students-table td {
    padding: 8px 10px !important;
  }
  .students-table.graduate-table th:nth-child(1),
  .students-table.graduate-table td:nth-child(1) {
    width: 70px;
  }
  .students-table.graduate-table th:nth-child(3),
  .students-table.graduate-table td:nth-child(3) {
    width: 180px;
  }
  .students-table.undergraduate-table th:nth-child(2),
  .students-table.undergraduate-table td:nth-child(2) {
    width: 250px;
  }
}
</style>

<div class="students-table-section">
  <h2 class="table-title">指导研究生情况</h2>
  
  <div class="table-container">
    <table class="students-table graduate-table">
      <thead>
        <tr>
          <th>入学年份</th>
          <th>姓名</th>
          <th>硕士论文（研究方向）</th>
          <th>成果与荣誉</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2025</td>
          <td class="name-bold">陈梦</td>
          <td>多模态虚假新闻识别</td>
          <td>一等奖学金</td>
        </tr>
        <tr>
          <td>2025</td>
          <td class="name-bold">董闯豪</td>
          <td>财务欺诈识别</td>
          <td></td>
        </tr>
        <tr>
          <td>2025</td>
          <td class="name-bold">姜伟栋</td>
          <td>谣言早期检测</td>
          <td></td>
        </tr>
        <tr>
          <td>2024</td>
          <td class="name-bold">骆茜</td>
          <td>基于大模型的虚假评论识别</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
        </tr>
        <tr>
          <td>2024</td>
          <td class="name-bold">刘敏</td>
          <td>基于RAG的审计发现结论生成</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
        </tr>
        <tr>
          <td>2023</td>
          <td class="name-bold">陈宇光</td>
          <td>基于传播预测的社交媒体虚假新闻早期识别研究（开题）</td>
          <td>Early detection of rumors based on propagation prediction in social media，论文，SCI二区<br>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
        </tr>
        <tr>
          <td>2023</td>
          <td class="name-bold">尹天祺</td>
          <td>考虑模态缺失的社交媒体多模态虚假新闻检测研究（开题）</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
        </tr>
        <tr>
          <td>2023</td>
          <td class="name-bold">宋昌昊</td>
          <td>基于大模型的上市公司财务舞弊识别研究（开题）</td>
          <td>2025江苏省研究生实践创新计划立项<br>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
        </tr>
        <tr>
          <td>2022</td>
          <td class="name-bold">魏晨阳</td>
          <td>基于异构信息网络的问答社区欺诈信息检测方法研究</td>
          <td>Enhancing GNN-based CQA Spam Detection: Question-Answer-Pair Perspective with Supervised Neighbor Selection, CBD 2024 Best Student Paper Award</td>
        </tr>
        <tr>
          <td>2022</td>
          <td class="name-bold">康钟元</td>
          <td>融合先验知识的科技文献主题识别与演化趋势预测方法研究</td>
          <td>基于先验生命周期的科技文献研究主题发展趋势预测（已录用，北核）</td>
        </tr>
        <tr>
          <td>2021</td>
          <td class="name-bold">吴海波</td>
          <td>基于深度学习的审计定性依据和审计建议推荐方法</td>
          <td>Learning problem-to-suggestion semantic mapping for audit suggestions recommendation in government audit reports，论文，SCI一区，CCF B<br>与伍之昂教授联合培养</td>
        </tr>
        <tr>
          <td>2019</td>
          <td class="name-bold">许明铭</td>
          <td>基于异质数据融合学习的在线问答社区欺诈检测研究</td>
          <td>Collusive spam detection from Chinese community question answering sites: A collective classification framework，论文，SCI一区，CCF B<br>于南财培养</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<hr class="table-divider" />

<div class="students-table-section">
  <h2 class="table-title">指导本科生情况</h2>
  
  <div class="table-container">
    <table class="students-table undergraduate-table">
      <thead>
        <tr>
          <th>年份</th>
          <th>姓名（团队）</th>
          <th>成果</th>
          <th>备注</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2025年</td>
          <td class="name-bold">陈稳、汪乔羿、钱珉宇、胡汪昊、苏星语</td>
          <td>大学生创新创业训练计划项目、国家级</td>
          <td></td>
        </tr>
        <tr>
          <td>2025年</td>
          <td class="name-bold">张倓硕、张璟晗、沈子辰、陈信通、彭贵栓</td>
          <td>大学生创新创业训练计划项目、省级</td>
          <td></td>
        </tr>
        <tr>
          <td>2025年</td>
          <td class="name-bold">唐文静、沈诗典、钱秋霖、朱纯瑜、陈笑悦</td>
          <td>中国大学生计算机设计大赛，江苏省三等奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2023年</td>
          <td class="name-bold">吴菡玥、李诗音、葛煜琦、徐发、金海涛、苏容锦</td>
          <td>"挑战杯"中国大学生创业计划竞赛，国家铜奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2022年</td>
          <td class="name-bold">徐发、李心怡、赵梦颖</td>
          <td>中国大学生计算机设计大赛，全国二等奖、江苏省特等奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2019年</td>
          <td class="name-bold">华璇</td>
          <td>蓝桥杯，江苏省一等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2018年</td>
          <td class="name-bold">宛子涵</td>
          <td>蓝桥杯，全国三等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017年</td>
          <td class="name-bold">沈童</td>
          <td>蓝桥杯，全国三等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017年</td>
          <td class="name-bold">袁秦盟</td>
          <td>蓝桥杯，全国一等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017年</td>
          <td class="name-bold">沈童、赵子维、程雯菲</td>
          <td>中国大学生计算机设计大赛，全国三等奖</td>
          <td>南财</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<!-- 添加额外的底部间距 -->
<div style="height: 60px;"></div>
