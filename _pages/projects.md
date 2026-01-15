---
permalink: /projects/
title: "科研项目"
---

<style>
/* 外层容器：固定1080px宽度，居中显示，取消右侧限制 */
.projects-wrapper {
  width: 1080px; /* 固定显示宽度为1080px */
  margin: 0 auto; /* 水平居中 */
  padding: 0 10px;
  box-sizing: border-box; /* 内边距计入宽度，总宽度仍为1080px */
  font-family: "Microsoft Yahei", Arial, sans-serif;
  font-size: 18px;
  line-height: 1.9;
  color: #333;
}

/* 科研项目列表：保留和论文页面一致的符号/间距样式 */
.projects-list {
  list-style: disc outside;
  padding-left: 30px; /* ·符号起始位置不变 */
  margin: 20px 0 0;
}

.projects-list li {
  margin-bottom: 25px; /* 行间距不变 */
  padding-left: 8px;   /* ·符号与文字间隔不变 */
  text-align: left;
  display: block; /* 强制列表项为块级元素，确保换行 */
  word-wrap: break-word; /* 强制长文字换行，避免溢出 */
  word-break: break-all; /* 兼容中英文换行 */
}

/* ·符号样式：大小保持和论文页面一致 */
.projects-list li::marker {
  font-size: 20px;
  color: #333;
}

/* 项目名称样式：恢复蓝色+加粗突出 */
.project-name {
  font-weight: 600;
  color: #1a73e8; /* 恢复蓝色（谷歌默认链接蓝） */
  display: inline-block; /* 确保名称后可正常换行 */
}

/* 主持/参与标识样式：统一格式 */
.project-role {
  margin: 0 8px;
  color: #d90000; /* 标红突出主持/参与身份 */
  font-weight: 500;
}

/* 项目信息样式：默认字体，强制换行 */
.project-info {
  color: #333;
  display: block; /* 强制项目信息单独换行 */
  margin-top: 5px; /* 与上一行保持小间距，视觉更清晰 */
}

/* 响应式适配：小屏幕自动适配宽度，取消固定1080px */
@media (max-width: 1080px) {
  .projects-wrapper {
    width: calc(100vw - 40px); /* 小屏幕占满可用宽度，仅留左右20px边距 */
    font-size: 16px;
    line-height: 1.8;
  }
  .projects-list {
    padding-left: 25px;
  }
  .projects-list li {
    margin-bottom: 20px;
    padding-left: 8px;
  }
  .projects-list li::marker {
    font-size: 18px;
  }
}
</style>

<div class="projects-wrapper">
  <ul class="projects-list">
    <li>
      <span class="project-name">大模型范式下融合多源异质数据的财务舞弊识别研究</span><span class="project-role">（主持）</span>
      <span class="project-info">招商银行股份有限公司南京分行-南京审计大学统计金融联合实验室招标课题，2025JLSF302，2025/11-2027/10，在研。</span>
    </li>
    <li>
      <span class="project-name">海量数据环境下基于多侧面行为混合学习的隐蔽网络水军识别方法研究</span><span class="project-role">（主持）</span>
      <span class="project-info">计算机网络和信息集成教育部重点实验室开放课题，K9-9-2023-03，2024/04-2026/03，在研。</span>
    </li>
    <li>
      <span class="project-name">面向应急管理的个性化信息服务及其可解释性研究</span><span class="project-role">（参与）</span>
      <span class="project-info">教育部人文社会科学青年项目，23YJC870003，2023/10-2025/10，在研。</span>
    </li>
    <li>
      <span class="project-name">面向国家审计的大数据治理与分析关键技术及中台研发</span><span class="project-role">（参与）</span>
      <span class="project-info">江苏省重点研发计划（产业前瞻与关键核心技术）项目，BE2023089，2023/09-2026/09，在研。</span>
    </li>
    <li>
      <span class="project-name">基于多视图行为特征融合的问答社区群体欺诈识别研究</span><span class="project-role">（主持）</span>
      <span class="project-info">江苏省高校自然科学研究重大项目，22KJA520005，2022/07-2025/08，结题。</span>
    </li>
    <li>
      <span class="project-name">面向生产过程能效评估的海量及不健全信息粒计算处理方法研究</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金面上项目，61973151，2020/01-2023/12，结题。</span>
    </li>
    <li>
      <span class="project-name">异质行为数据融合的电子商务虚假评论者识别研究</span><span class="project-role">（主持）</span>
      <span class="project-info">国家自然科学基金青年项目，71801123，2019/01-2021/12，结题。</span>
    </li>
    <li>
      <span class="project-name">社交媒体消费社群形成与演化机理研究</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金面上项目，71871109，2019/01-2022/12，在研。</span>
    </li>
    <li>
      <span class="project-name">散粮集装箱运输全过程追溯技术研究及装备研发</span><span class="project-role">（主持）</span>
      <span class="project-info">国家重点研发计划子课题，2018YFD0401404-4，2018/07-2020/12，结题。</span>
    </li>
    <li>
      <span class="project-name">融合行为模式和关系网络的广告虚假攻击检测研究</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金青年项目，71701089，2018/01-2020/12，结题。</span>
    </li>
    <li>
      <span class="project-name">面向中小微企业的智能化信息服务平台</span><span class="project-role">（主持）</span>
      <span class="project-info">江苏省工业和信息产业转型升级专项，2017/09-2019/12，结题。</span>
    </li>
    <li>
      <span class="project-name">面向Online-to-Offline智能商务的大数据融合与应用</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金重大研究计划，91646204，2017/01-2020/12，结题。</span>
    </li>
    <li>
      <span class="project-name">超大规模复杂网络社区抽取、演化及应用研究</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金面上项目，71571093，2016/01-2019/12，结题。</span>
    </li>
    <li>
      <span class="project-name">面向金融市场走势预测的在线论坛公众情绪挖掘与演化分析算法研究</span><span class="project-role">（参与）</span>
      <span class="project-info">国家自然科学基金青年项目，61502222，2016/01-2018/12，结题。</span>
    </li>
    <li>
      <span class="project-name">社会化电子商务中恶意用户检测关键技术研究</span><span class="project-role">（主持）</span>
      <span class="project-info">江苏省高校自然科学研究面上项目，15KJB520012，2015/07-2017/06，结题。</span>
    </li>
  </ul>
</div>
