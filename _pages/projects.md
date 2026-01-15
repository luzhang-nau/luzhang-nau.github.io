---
permalink: /projects/
title: "科研项目"
---

<style>
/* 外层容器：固定1080px宽度，居中显示，不影响页面其他部分 */
.projects-wrapper {
  width: 1080px; /* 固定显示宽度为1080px */
  margin: 0 auto; /* 水平居中，避免偏左/偏右 */
  padding: 0 10px;
  box-sizing: border-box; /* 内边距计入宽度，总宽度仍为1080px */
}

/* 项目列表：仅调整符号位置/间隔，其余样式不变 */
.projects-container {
  font-family: "Microsoft Yahei", Arial, sans-serif;
  font-size: 18px; /* 字体放大 */
  line-height: 2;
  list-style: none; /* 取消默认列表样式 */
  padding-left: 30px; /* 核心调整：和论文模块一致的符号起始位置 */
  margin: 0;
}

/* 放大列表符号（用li原生列表符号，不绝对定位，避免超界） */
.projects-container li {
  list-style-type: disc; /* 大号圆点符号 */
  list-style-position: outside; /* 核心调整：改为outside，和论文模块一致（换行对齐文字） */
  margin-bottom: 15px;
  padding-left: 8px; /* 核心调整：和论文模块一致的符号与文字间隔 */
}
/* 单独放大符号大小 */
.projects-container li::marker {
  font-size: 24px; /* 符号放大到参考图大小 */
  color: #333;
}

/* 项目名称样式：蓝色、加粗 */
.project-name {
  color: #1a73e8;
  font-weight: 500;
}

/* 主持/参与标签 */
.project-role {
  font-weight: 500;
  margin-left: 8px;
}

/* 项目信息行：自动换行+缩进对齐，保证内容完整 */
.project-info {
  display: block;
  padding-left: 35px; /* 缩进对齐，比符号位置更靠内 */
  white-space: normal; /* 自动换行，适配1080px宽度 */
}
</style>

<div class="projects-wrapper">
  <ul class="projects-container">
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
