---
permalink: /projects/
title: "科研项目"
---

<style>
/* 科研项目页面样式 */
.projects-section {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 20px;
}

.project-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.project-item {
  margin-bottom: 25px;
  padding-bottom: 25px;
  border-bottom: 1px solid #eaeaea;
  position: relative;
}

.project-item:last-child {
  border-bottom: none;
  margin-bottom: 0;
}

.project-number {
  position: absolute;
  left: -30px;
  top: 0;
  color: #999;
  font-size: 14px;
}

.project-content {
  margin-left: 20px;
}

.project-title {
  font-size: 18px;
  font-weight: 600;
  color: #333;
  margin-bottom: 6px;
  line-height: 1.4;
}

.project-role {
  display: inline-block;
  font-weight: 500;
  color: #555;
  margin-left: 10px;
}

.project-details {
  font-size: 15px;
  color: #555;
  line-height: 1.5;
  margin-top: 4px;
}

.project-id {
  color: #0066cc;
  font-family: monospace;
  margin-right: 12px;
}

.project-duration {
  color: #666;
  margin-right: 12px;
}

.project-status {
  display: inline-block;
  padding: 2px 8px;
  border-radius: 4px;
  font-size: 13px;
  font-weight: 500;
}

.status-active {
  background-color: #e8f5e8;
  color: #2e7d32;
}

.status-completed {
  background-color: #f5f5f5;
  color: #666;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .projects-section {
    padding: 30px 15px;
  }
  
  .project-number {
    position: static;
    display: inline-block;
    margin-right: 8px;
  }
  
  .project-content {
    margin-left: 0;
  }
  
  .project-title {
    font-size: 16px;
  }
  
  .project-details {
    font-size: 14px;
  }
  
  .project-role {
    margin-left: 8px;
  }
}

@media (max-width: 480px) {
  .project-details {
    display: flex;
    flex-direction: column;
    gap: 4px;
  }
  
  .project-id,
  .project-duration,
  .project-status {
    margin-right: 0;
  }
}
</style>

<div class="projects-section">
  <ol class="project-list">
    <li class="project-item">
      <span class="project-number">[1]</span>
      <div class="project-content">
        <h3 class="project-title">大模型范式下融合多源异质数据的财务舞弊识别研究<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">2025JLSF302</span>
          <span class="project-duration">2025/11-2027/10</span>
          <span class="project-status status-active">在研</span>
        </div>
        <p class="project-description">招商银行股份有限公司南京分行-南京审计大学统计金融联合实验室招标课题</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[2]</span>
      <div class="project-content">
        <h3 class="project-title">海量数据环境下基于多侧面行为混合学习的隐蔽网络水军识别方法研究<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">K93-9-2023-03</span>
          <span class="project-duration">2024/04-2026/03</span>
          <span class="project-status status-active">在研</span>
        </div>
        <p class="project-description">计算机网络和信息集成教育部重点实验室开放课题</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[3]</span>
      <div class="project-content">
        <h3 class="project-title">面向应急管理的个性化信息服务及其可解释性研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">23YJC870003</span>
          <span class="project-duration">2023/10-2025/10</span>
          <span class="project-status status-active">在研</span>
        </div>
        <p class="project-description">教育部人文社会科学青年项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[4]</span>
      <div class="project-content">
        <h3 class="project-title">面向国家审计的大数据治理与分析关键技术及中台研发<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">BE2023089</span>
          <span class="project-duration">2023/09-2026/09</span>
          <span class="project-status status-active">在研</span>
        </div>
        <p class="project-description">江苏省重点研发计划（产业前瞻与关键核心技术）项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[5]</span>
      <div class="project-content">
        <h3 class="project-title">基于多视图行为特征融合的问答社区群体欺诈识别研究<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">22KJA520005</span>
          <span class="project-duration">2022/07-2025/08</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">江苏省高校自然科学研究重大项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[6]</span>
      <div class="project-content">
        <h3 class="project-title">面向生产过程能效评估的海量及不健全信息粒计算处理方法研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">61973151</span>
          <span class="project-duration">2020/01-2023/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金面上项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[7]</span>
      <div class="project-content">
        <h3 class="project-title">异质行为数据融合的电子商务虚假评论者识别研究<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">71801123</span>
          <span class="project-duration">2019/01-2021/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金青年项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[8]</span>
      <div class="project-content">
        <h3 class="project-title">社交媒体消费社群形成与演化机理研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">71871109</span>
          <span class="project-duration">2019/01-2022/12</span>
          <span class="project-status status-active">在研</span>
        </div>
        <p class="project-description">国家自然科学基金面上项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[9]</span>
      <div class="project-content">
        <h3 class="project-title">散粮集装箱运输全过程追溯技术研究及装备研发<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">2018YFD0401404-4</span>
          <span class="project-duration">2018/07-2020/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家重点研发计划子课题</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[10]</span>
      <div class="project-content">
        <h3 class="project-title">融合行为模式和关系网络的广告虚假攻击检测研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">71701089</span>
          <span class="project-duration">2018/01-2020/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金青年项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[11]</span>
      <div class="project-content">
        <h3 class="project-title">面向中小微企业的智能化信息服务平台<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">江苏省工业和信息产业转型升级专项</span>
          <span class="project-duration">2017/09-2019/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[12]</span>
      <div class="project-content">
        <h3 class="project-title">面向Online-to-Offline智能商务的大数据融合与应用<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">91646204</span>
          <span class="project-duration">2017/01-2020/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金重大研究计划</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[13]</span>
      <div class="project-content">
        <h3 class="project-title">超大规模复杂网络社区抽取、演化及应用研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">71571093</span>
          <span class="project-duration">2016/01-2019/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金面上项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[14]</span>
      <div class="project-content">
        <h3 class="project-title">面向金融市场走势预测的在线论坛公众情绪挖掘与演化分析算法研究<span class="project-role">参与</span></h3>
        <div class="project-details">
          <span class="project-id">61502222</span>
          <span class="project-duration">2016/01-2018/12</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">国家自然科学基金青年项目</p>
      </div>
    </li>

    <li class="project-item">
      <span class="project-number">[15]</span>
      <div class="project-content">
        <h3 class="project-title">社会化电子商务中恶意用户检测关键技术研究<span class="project-role">主持</span></h3>
        <div class="project-details">
          <span class="project-id">15KJB520012</span>
          <span class="project-duration">2015/07-2017/06</span>
          <span class="project-status status-completed">结题</span>
        </div>
        <p class="project-description">江苏省高校自然科学研究面上项目</p>
      </div>
    </li>
  </ol>
</div>
