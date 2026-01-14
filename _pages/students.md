---
permalink: /students/
title: "指导学生"
---

<div class="section-container">
  <h2 class="section-title">课题组理念</h2>
  
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
.section-container {
  margin: 40px 0;
}

.section-title {
  color: #1a4b8c;
  font-size: 32px;
  font-weight: 700;
  margin-bottom: 30px;
  padding-bottom: 15px;
  border-bottom: 3px solid #3498db;
  display: flex;
  align-items: center;
  gap: 15px;
  position: relative;
}

.section-title::after {
  content: "";
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 100px;
  height: 3px;
  background: linear-gradient(to right, #3498db, #1a4b8c);
}

.concept-card {
  background: white;
  border: 1px solid #e8edf2;
  border-radius: 15px;
  padding: 35px 40px;
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.08);
  transition: all 0.3s ease;
}

.concept-card:hover {
  box-shadow: 0 12px 40px rgba(0, 0, 0, 0.12);
  transform: translateY(-3px);
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

/* 表格样式 */
.students-table-section {
  margin: 50px 0;
}

.table-title {
  color: #1a4b8c;
  font-size: 28px;
  font-weight: 600;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 2px solid #e8edf2;
}

.table-container {
  overflow-x: auto;
  margin-bottom: 40px;
  border-radius: 8px;
  border: 1px solid #e8edf2;
}

.students-table {
  width: 100%;
  border-collapse: collapse;
  background: white;
  font-size: 15px;
}

.students-table thead {
  background-color: #1a4b8c;
}

.students-table th {
  padding: 16px 12px;
  text-align: left;
  font-weight: 600;
  color: white;
  font-size: 15px;
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
  padding: 14px 12px;
  vertical-align: top;
  color: #333;
  line-height: 1.5;
}

.status-in-study,
.status-graduated {
  color: #333;
  font-weight: 500;
}

.name-bold {
  font-weight: 600;
  color: #333;
}

.table-divider {
  border: none;
  height: 1px;
  background-color: #e8edf2;
  margin: 40px 0;
}

@media (max-width: 768px) {
  .section-title {
    font-size: 26px;
  }
  
  .concept-card {
    padding: 25px 20px;
  }
  
  .concept-content p {
    font-size: 15px;
  }
  
  .table-title {
    font-size: 22px;
  }
  
  .students-table {
    font-size: 14px;
  }
  
  .students-table th,
  .students-table td {
    padding: 10px 8px;
  }
}
</style>

<div class="students-table-section">
  <h2 class="table-title">指导研究生情况</h2>
  
  <div class="table-container">
    <table class="students-table">
      <colgroup>
        <col style="width: 12%">
        <col style="width: 13%">
        <col style="width: 30%">
        <col style="width: 30%">
        <col style="width: 15%">
      </colgroup>
      <thead>
        <tr>
          <th>入学年份</th>
          <th>姓名</th>
          <th>硕士论文（研究方向）</th>
          <th>成果与荣誉</th>
          <th>备注</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2025年</td>
          <td class="name-bold">陈梦</td>
          <td>多模态虚假新闻识别</td>
          <td>一等奖学金</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2025年</td>
          <td class="name-bold">董闯豪</td>
          <td>财务欺诈识别</td>
          <td></td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2025年</td>
          <td class="name-bold">姜伟栋</td>
          <td>谣言早期检测</td>
          <td></td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2024年</td>
          <td class="name-bold">骆茜</td>
          <td>基于大模型的虚假评论识别</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2024年</td>
          <td class="name-bold">刘敏</td>
          <td>基于RAG的审计发现结论生成</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2023年</td>
          <td class="name-bold">陈宇光</td>
          <td>基于传播预测的社交媒体虚假新闻早期识别研究（开题）</td>
          <td>Early detection of rumors based on propagation prediction in social media，论文，SCI二区<br>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2023年</td>
          <td class="name-bold">尹天祺</td>
          <td>考虑模态缺失的社交媒体多模态虚假新闻检测研究（开题）</td>
          <td>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2023年</td>
          <td class="name-bold">宋昌昊</td>
          <td>基于大模型的上市公司财务舞弊识别研究（开题）</td>
          <td>2025江苏省研究生实践创新计划立项<br>2025中国大学生服务外包创新创业大赛，国家级三等奖</td>
          <td><span class="status-in-study">在读</span></td>
        </tr>
        <tr>
          <td>2022年</td>
          <td class="name-bold">魏晨阳</td>
          <td>基于异构信息网络的问答社区欺诈信息检测方法研究</td>
          <td>Enhancing GNN-based CQA Spam Detection: Question-Answer-Pair Perspective with Supervised Neighbor Selection, CBD 2024 Best Student Paper Award</td>
          <td><span class="status-graduated">毕业去向：九江国泰</span></td>
        </tr>
        <tr>
          <td>2022年</td>
          <td class="name-bold">康钟元</td>
          <td>融合先验知识的科技文献主题识别与演化趋势预测方法研究</td>
          <td>基于先验生命周期的科技文献研究主题发展趋势预测（已录用，北核）</td>
          <td><span class="status-graduated">毕业去向：中国石化</span></td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<hr class="table-divider" />

<div class="students-table-section">
  <h2 class="table-title">指导本科生情况</h2>
  
  <div class="table-container">
    <table class="students-table">
      <thead>
        <tr>
          <th style="width: 15%">年份</th>
          <th style="width: 35%">姓名（团队）</th>
          <th style="width: 35%">成果</th>
          <th style="width: 15%">备注</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2025</td>
          <td class="name-bold">陈稳、汪乔羿、钱珉宇、胡汪昊、苏星语</td>
          <td>大学生创新创业训练计划项目、国家级</td>
          <td></td>
        </tr>
        <tr>
          <td>2025</td>
          <td class="name-bold">张倓硕、张璟晗、沈子辰、陈信通、彭贵栓</td>
          <td>大学生创新创业训练计划项目、省级</td>
          <td></td>
        </tr>
        <tr>
          <td>2025</td>
          <td class="name-bold">唐文静、沈诗典、钱秋霖、朱纯瑜、陈笑悦</td>
          <td>中国大学生计算机设计大赛，江苏省三等奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2023</td>
          <td class="name-bold">吴菡玥、李诗音、葛煜琦、徐发、金海涛、苏容锦</td>
          <td>"挑战杯"中国大学生创业计划竞赛，国家铜奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2022</td>
          <td class="name-bold">徐发、李心怡、赵梦颖</td>
          <td>中国大学生计算机设计大赛，全国二等奖、江苏省特等奖</td>
          <td></td>
        </tr>
        <tr>
          <td>2019</td>
          <td class="name-bold">华璇</td>
          <td>蓝桥杯，江苏省一等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2018</td>
          <td class="name-bold">宛子涵</td>
          <td>蓝桥杯，全国三等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017</td>
          <td class="name-bold">沈童</td>
          <td>蓝桥杯，全国三等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017</td>
          <td class="name-bold">袁秦盟</td>
          <td>蓝桥杯，全国一等奖</td>
          <td>南财</td>
        </tr>
        <tr>
          <td>2017</td>
          <td class="name-bold">沈童、赵子维、程雯菲</td>
          <td>中国大学生计算机设计大赛，全国三等奖</td>
          <td>南财</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
