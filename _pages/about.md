---
permalink: /
title: "欢迎访问王博士的个人主页！"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* ====================
     1. 产品展示模块样式 (已调整尺寸)
     ==================== */
  .product-item {
    display: flex; /* 开启弹性布局，实现左图右文 */
    align-items: center; /* 垂直居中 */
    margin-bottom: 20px; /* 增加一点间距以适应更大的卡片 */
    padding: 15px; /* 增加内边距 */
    border: 1px solid #f0f0f0; 
    border-radius: 6px; 
    background-color: #fff;
    transition: box-shadow 0.2s;
  }
  
  .product-item:hover {
    box-shadow: 0 4px 12px rgba(0,0,0,0.08); /* 悬停阴影稍微加深 */
  }

  /* 左侧图片容器 - 宽度由 120px 增加到 170px (+40%) */
  .product-img-box {
    flex: 0 0 170px; 
    margin-right: 25px; /* 间距也稍微拉大 */
    border-radius: 4px;
    overflow: hidden;
    border: 1px solid #eee;
    background-color: #f9f9f9;
  }

  /* 图片本身 */
  .product-img-box img {
    display: block;
    width: 100%;
    height: auto;
    aspect-ratio: 4 / 3; /* 锁定 4:3 比例 */
    object-fit: cover; 
    margin: 0; 
  }

  /* 右侧文字 */
  .product-info {
    flex: 1; 
    font-size: 0.95em;
    line-height: 1.6;
  }

  .product-name {
    font-weight: bold;
    font-size: 1.2em; /* 标题字体稍微调大 */
    color: #333;
    display: block;
    margin-bottom: 6px;
  }

  .product-spec {
    color: #666;
    font-size: 0.95em;
    display: block; /* 独占一行 */
    margin-bottom: 6px;
  }

  .product-desc {
    color: #444;
    font-size: 0.95em;
    display: block;
    /* 可以在这里写具体的描述样式，目前留空 */
  }

  /* ====================
     2. 之前的交互与折叠样式 (保持不变)
     ==================== */
  details > summary {
    list-style: none;
    cursor: pointer;
    padding: 0; 
    transition: color 0.2s;
  }
  
  details > summary::-webkit-details-marker { display: none; }

  details > summary:hover { color: #0056b3; }

  .expand-icon {
    color: #999;
    margin-left: 5px; 
    margin-right: 0px;
    font-size: 0.8em;
    display: inline-block;
    transition: transform 0.2s ease;
  }
  
  details > summary:hover .expand-icon { color: #333; }

  .expand-icon::before { content: "►"; }
  
  details[open] .expand-icon { transform: rotate(90deg); }

  .details-content {
    margin-top: 5px; 
    margin-bottom: 10px; 
    padding: 15px; 
    background-color: #f9f9f9; 
    border-left: 3px solid #ccc; 
    font-size: 0.95em;
    line-height: 1.6;
    text-align: justify; 
  }

  .section-sub-title {
    font-weight: bold;
    color: #333;
    margin-top: 10px;
    margin-bottom: 5px;
    display: block;
  }
  .section-sub-title:first-child { margin-top: 0; }

  .details-content ul { margin: 0; padding-left: 20px; }
  .details-content li { margin-bottom: 3px; }
</style>

<div style="text-align: justify; text-justify: inter-word; hyphens: auto;" markdown="1">

我是王学荣博士，具备30年医疗器械、制药行业跨国公司质量和法规管理经验和产品研发管理经验，同时具备环氧乙烷灭菌、辐照灭菌、湿热蒸汽灭菌全知识链的技术和经验。

<h1 style="border-bottom: 1px solid #e1e4e8; padding-bottom: 0.5em; margin-bottom: 0.3em; margin-top: 30px;">特供产品</h1>

<div class="product-item">
  <div class="product-img-box">
    <img src="https://via.placeholder.com/600x450/e0e0e0/888888?text=Product+1" alt="环氧乙烷标准品">
  </div>
  <div class="product-info">
    <span class="product-name">环氧乙烷工作标准品 (EO)</span>
    <span class="product-spec">规格：10 mg/mL</span>
    <span class="product-desc">产品描述：</span> </div>
</div>

<div class="product-item">
  <div class="product-img-box">
    <img src="https://via.placeholder.com/600x450/e0e0e0/888888?text=Product+2" alt="2-氯乙醇标准品">
  </div>
  <div class="product-info">
    <span class="product-name">2-氯乙醇工作标准品 (ECH)</span>
    <span class="product-spec">规格：50 mg/mL</span>
    <span class="product-desc">产品描述：</span>
  </div>
</div>

<div class="product-item">
  <div class="product-img-box">
    <img src="https://via.placeholder.com/600x450/e0e0e0/888888?text=Product+3" alt="化学指示探针">
  </div>
  <div class="product-info">
    <span class="product-name">化学指示探针</span>
    <span class="product-spec">尺寸：2 mm * 10 mm</span>
    <span class="product-desc">产品描述：</span>
  </div>
</div>


<h1 style="border-bottom: 1px solid #e1e4e8; padding-bottom: 0.5em; margin-bottom: 0.3em; margin-top: 30px;">工作经历</h1>

* <details>
    <summary>
      2021年02月 – 至今<span class="expand-icon"></span>，<strong>独立灭菌技术专家</strong>，邓肯灭菌工作室
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>新型环保+安全环氧乙烷灭菌过程的开发、验证和确认。</li>
        <li>现有环氧乙烷灭菌过程的改善、增效服务。</li>
        <li>环氧乙烷灭菌过程的专项审核服务。</li>
        <li>环氧乙烷灭菌过程的PCD的设计和定制服务。</li>
        <li>环氧乙烷灭菌产品的包装、灭菌装载的设计制服务。</li>
        <li>灭菌设备等同性的证明的咨询和服务。</li>
        <li>环氧乙烷灭菌气体的安全数据、理化特性、燃爆特性的咨询和服务。</li>
        <li>环氧乙烷灭菌过程的废气处理的咨询和服务。</li>
        <li>环氧乙烷灭菌过程的废气处理专用设备的设计、制作监理和安装服务。</li>
        <li>环氧乙烷灭菌、辐照灭菌、湿热蒸汽灭菌的咨询和服务。</li>
        <li>环氧乙烷浓度的监测咨询和服务。</li>
        <li>环氧乙烷浓度探头的计量校正咨询和服务。</li>
        <li>日常灭菌过程定期参数专项审核服务。</li>
        <li>灭菌服务商的第二方审核代理服务，不符合事项的跟踪和解决。</li>
        <li>环氧乙烷灭菌、辐照灭菌、湿热蒸汽灭菌的重要外审前的预审服务。</li>
        <li>环氧乙烷灭菌、辐照灭菌、湿热蒸汽灭菌的过程的合格调查处理和疑难问题的解决服务。</li>
        <li>无菌产品生产相关的微生物控制的咨询和服务。</li>
        <li>灭菌相关的产品生物负载量的、B&F 适宜性测试和产品无菌测试的验证。</li>
        <li>无菌产品生产相关的微生物控制和测试的专项审核服务。</li>
        <li>灭菌过程控制文件的编写和审核服务。</li>
        <li>灭菌过程验证方案和报告的编写和审核服务。</li>
        <li>灭菌相关的产品生物负载量的、B&F 适宜性测试和产品无菌测试的验证方案和报告的审核服务。</li>
        <li>环氧乙烷灭菌过程的安全、环保和职业健康的咨询和服务。</li>
        <li>灭菌技术方面的高级进阶培训服务。</li>
        <li>产品注册资料中灭菌部分内容的编制和审核服务。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      2021年01月 – 2021年02月<span class="expand-icon"></span>，<strong>灭菌改进项目专家</strong>，江苏省长丰医疗实业有限公司
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>新型环保+安全环氧乙烷灭菌过程的开发、验证和确认。</li>
        <li>环氧乙烷灭菌过程的废气处理专用设备的立项、设计、监理。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      2017年07月 – 2020年12月<span class="expand-icon"></span>，<strong>资深灭菌专家</strong>，碧迪快速诊断产品（苏州）有限公司
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>负责Hypak产品无菌保证工作，以达到在质量，法规，成本和效益方面的综合绩效目标。</li>
        <li>建立灭菌和生产环境控制和监测的操作程序，监督操作程序被严格执行，阶段性评估总结以提高灭菌和无菌保证工作的有效性。</li>
        <li>制定灭菌验证计划，按计划起草验证方案并执行，包括灭菌过程的验证及再验证。</li>
        <li>编制灭菌产品的标准化批记录文件，确保所有的生产控制要素得到精准和适当的记录，满足产品的追溯性的要求。</li>
        <li>管控灭菌和微生物服务供应商的验证执行，管理灭菌供应商及外包供应商相关的质量保证活动，包括技术协议，审核，偏离调查与处理，投诉，BD客户访问等。</li>
        <li>向团队同事提供有关灭菌技术方面的高级进阶专业培训。</li>
        <li>定期联络碧迪亚太和碧迪全球灭菌团队，确保灭菌和微生物相关控制事宜与其保持一致和协调，与此同时，更要保证相关事项符合国内的法律法规要求。</li>
        <li>定期的汇总分析灭菌和污染控制的相关数据，参与管理评审。</li>
        <li>管理与灭菌相关的CAPA活动。</li>
      </ul>
      <span class="section-sub-title">主要业绩：</span>
      <ul>
        <li>建立了高效、低环氧乙烷残留的环氧乙烷专用灭菌工艺。</li>
        <li>验证了HYPAK产品环氧乙烷灭菌过程，建立了灭菌参数放行的量化指标系统。</li>
        <li>建立了灭菌装载升温曲线的数学模型，预测灭菌装载的最冷点、计算达到最低灭菌温度的时间。</li>
        <li>建立整套产品污染控制计划和实施方案（包括洁净区的人员进出要求、环境污染监控点，初始污染菌监控，微生物实验室的各种检测方法）。</li>
        <li>组建、培训了一支有能力的灭菌和微生物污染控制的无菌保证团队。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      1997年11月 – 2016年10月<span class="expand-icon"></span>，<strong>医疗器械生产/质量管理</strong>，金宝医疗器材（上海）有限公司
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>负责质量体系管理并持续改善。</li>
        <li>负责客户投诉管理，并持续改善客户满意度。</li>
        <li>负责协调CAPA项目，持续改善质量成本。</li>
        <li>设定部门目标，监控部门表现，设立部门培训需求和督导团队成员。</li>
        <li>管理检验，试验室测试（化学、生物、物理）。</li>
        <li>管理产品验证和过程工艺验证。</li>
        <li>负责产品和过程的本地化。</li>
        <li>管理产品的灭菌验证和日常的监控（包括环氧乙烷灭菌、蒸汽灭菌和电子束灭菌）。</li>
        <li>生产质量管理：日常生产质量管理、生产和产品放行。</li>
        <li>负责为采购部门提供和材料采购的技术标准和文件。</li>
        <li>日常质量报告：设立年度质量KPI指标并对月度KPI报告进行评审。</li>
        <li>管理团队：考核目标设定及绩效评估；招聘面试；财务预算及控制等。</li>
        <li>负责医疗器械产品的注册工作。</li>
        <li>负责为市场部（销售公司，分销商）参与国内外市场招标提供相关的标准质量文件包。</li>
        <li>负责评审关键材料和灭菌过程的供应商。</li>
      </ul>
      <span class="section-sub-title">主要业绩：</span>
      <ul>
        <li>参与启动团队将Gambro日本知贺工厂生产线迁移至上海，建立了上海质量团队和设施。</li>
        <li>建立了ISO13485质量体系并获得认证。</li>
        <li>1999年取得产品CE注册认证，产品开始独立进入欧洲市场。</li>
        <li>建立了ISO14001环境管理体系并获得认证。</li>
        <li>建立并推行Kaizen/CAPA/PDCA 不断改进质量成本。</li>
        <li>1998年取得血路管（三类）产品在中国的首次注册证书。</li>
        <li>完成了PVC材料的国产化任务和灭菌工艺本地化，使得产品成本下降40%。</li>
        <li>完成了耐辐照PVC材料的国产化任务，为引入电子束灭菌方法扫清了障碍。</li>
        <li>改善环氧乙烷的灭菌参数，提高了灭菌效率15%，节省了灭菌费用。</li>
        <li>建立了注塑、挤压、灭菌、无菌包装等关键过程的验证模版文件。</li>
        <li>按照ISO 10993.1建立了所有血液接触材料的评估文件模版。</li>
        <li>建立了泄漏测试仪系统灵敏度和准确度的监视方法。</li>
        <li>建立了产品无菌包装无菌有效期的评估方法。</li>
        <li>负责评估关键供应商的产品（输液器具、无菌空气传感器、废液收集袋、塑料穿刺针、无菌包装材料）及关键过程（环氧乙烷灭菌、电子束灭菌等）。对供应商的审核标准包括 ISO 13485 (QMS)、21CFR 820 (cGMP)、ISO 11135 (环氧乙烷灭菌) 和 ISO 11607 (灭菌包装材料)等，涵盖质量体系及关键生产测试过程。</li>
        <li>负责产品设计更改的风险评估和管控，配合采购部门的节约成本项目。</li>
        <li>汇编CE技术文档：完成有关技术文档汇编更新及各类技术工作。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      1993年02月 – 1997年11月<span class="expand-icon"></span>，<strong>质量和法规经理</strong>，上海莱士血液制品有限公司
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>负责新产品开发。</li>
        <li>负责建立产品的原料标准、中间体标准和成品标准。</li>
        <li>质量管理体系建立与认证和持续的改进。</li>
        <li>负责产品工艺文件的监督实施。</li>
        <li>负责血液制品的风险管理和控制活动，病毒灭活工艺的可靠性验证。</li>
        <li>负责血液制品新的产品注册文件的汇总编制。</li>
        <li>负责血液制品产品售后监督。</li>
        <li>质量保证部团队建设：人员规划、招聘、培训、考核等。</li>
        <li>负责产品注册工作与SFDA药监部门联络沟通。</li>
      </ul>
      <span class="section-sub-title">主要业绩：</span>
      <ul>
        <li>按照cGMP要求建立了血液制品生产的质量管理体系并且得到SFDA的认证。</li>
        <li>建立了血液制品的风险管理控制体系。在产品生产的各个环节、产品设计变更环节实施风险管理，使得产品关键质量项目实现零投诉。</li>
        <li>对4个血液制品（人血丙种球蛋白、人血酶原复合物，人血第八因子，人血纤维蛋白原）的工艺研发、工艺确认给予了关键性的贡献。</li>
        <li>建立了病毒灭活可靠性验证体系。</li>
        <li>建立了原材料生产商的评估体系。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      1991年09月 – 1993年02月<span class="expand-icon"></span>，<strong>研发部主管</strong>，杜邦农化上海有限公司
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>参与农得时项目，跟美国杜邦公司 Experiment Station 的技术人员合作，全面引进Londax 的过程控制技术。</li>
        <li>建立10%农得时可湿性粉剂的质量分析和控制方法。</li>
        <li>负责农得时复合制剂的本地化开发。</li>
      </ul>
    </div>
  </details>

* <details>
    <summary>
      1990年09月 – 1991年09月<span class="expand-icon"></span>，<strong>生态化学实验室主管</strong>，中国科学院上海昆虫研究所
    </summary>
    <div class="details-content">
      <span class="section-sub-title">工作描述：</span>
      <ul>
        <li>负责昆虫信息的合成和应用研究。</li>
        <li>负责化学实验室的管理。</li>
        <li>开发和设计新型的昆虫诱捕器。</li>
      </ul>
      <span class="section-sub-title">主要业绩：</span>
      <ul>
        <li>合成了杨树透翅蛾的信息素，在葡萄种植园中成功捕获到了目标害虫。</li>
      </ul>
    </div>
  </details>

<h1 style="border-bottom: 1px solid #e1e4e8; padding-bottom: 0.5em; margin-bottom: 0.3em; margin-top: 30px;">教育背景</h1>

* 1985年09月 – 1990年09月，**中国科学院上海药物研究所**，有机化学专业，博士学位
* 1980年09月 – 1985年07月，**华东师范大学**，化学专业（高分子材料方向），学士学位

</div>
