<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 1150" width="100%" height="100%" style="background-color: #F8F9FA; font-family: 'Helvetica Neue', Arial, sans-serif;">
  <defs>
    <!-- 模块1阴影与箭头 -->
    <filter id="shadow1" x="-5%" y="-5%" width="110%" height="110%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#1A5276" flood-opacity="0.1"/>
    </filter>
    <marker id="arrow1" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M0,0 L10,5 L0,10 z" fill="#2E86C1"/>
    </marker>

    <!-- 模块2阴影与箭头 -->
    <filter id="shadow2" x="-5%" y="-5%" width="110%" height="110%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#0B5345" flood-opacity="0.1"/>
    </filter>
    <marker id="arrow2" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M0,0 L10,5 L0,10 z" fill="#1ABC9C"/>
    </marker>

    <!-- 模块3阴影与箭头 -->
    <filter id="shadow3" x="-5%" y="-5%" width="110%" height="110%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#4A235A" flood-opacity="0.1"/>
    </filter>
    <marker id="arrow3" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M0,0 L10,5 L0,10 z" fill="#8E44AD"/>
    </marker>

    <!-- 模块4阴影与箭头 -->
    <filter id="shadow4" x="-5%" y="-5%" width="110%" height="110%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#7E5109" flood-opacity="0.1"/>
    </filter>
    <marker id="arrow4" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M0,0 L10,5 L0,10 z" fill="#E67E22"/>
    </marker>

    <!-- 模块5阴影与箭头 -->
    <filter id="shadow5" x="-5%" y="-5%" width="110%" height="110%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#1E8449" flood-opacity="0.1"/>
    </filter>
    <marker id="arrow5" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M0,0 L10,5 L0,10 z" fill="#2ECC71"/>
    </marker>
  </defs>

  <!-- 总标题 -->
  <text x="600" y="45" font-size="22" font-weight="bold" fill="#2C3E50" text-anchor="middle" letter-spacing="1">基于“医-护-康”模式下的卒中后焦虑与抑郁治疗管理技术路线图</text>

  <!-- ==================== 模块1：研究对象与分组 ==================== -->
  <g id="module-1">
    <!-- 背景 -->
    <rect x="50" y="80" width="1100" height="130" rx="12" ry="12" fill="#F0F8FF" stroke="#4B9CD3" stroke-width="2" filter="url(#shadow1)"/>
    <text x="600" y="105" font-size="15" font-weight="bold" fill="#1E5A99" text-anchor="middle">第一阶段：研究对象与分组（三组平行队列对照）</text>

    <!-- 节点A -->
    <rect x="180" y="130" width="200" height="60" rx="8" ry="8" fill="#E6F2F9" stroke="#2E86C1" stroke-width="1.5" filter="url(#shadow1)"/>
    <text x="280" y="150" font-size="14" font-weight="bold" fill="#1A5276" text-anchor="middle">A组：健康对照组</text>
    <text x="280" y="170" font-size="12" fill="#2C3E50" text-anchor="middle">（无卒中/无干预）</text>

    <!-- 节点B -->
    <rect x="500" y="130" width="200" height="60" rx="8" ry="8" fill="#E6F2F9" stroke="#2E86C1" stroke-width="1.5" filter="url(#shadow1)"/>
    <text x="600" y="150" font-size="14" font-weight="bold" fill="#1A5276" text-anchor="middle">B组：卒中后常规管理组</text>
    <text x="600" y="170" font-size="12" fill="#2C3E50" text-anchor="middle">（常规药物+护理）</text>

    <!-- 节点C -->
    <rect x="820" y="130" width="200" height="60" rx="8" ry="8" fill="#E6F2F9" stroke="#2E86C1" stroke-width="1.5" filter="url(#shadow1)"/>
    <text x="920" y="150" font-size="14" font-weight="bold" fill="#1A5276" text-anchor="middle">C组：医护康共管模式组</text>
    <text x="920" y="170" font-size="12" fill="#2C3E50" text-anchor="middle">（三方协作个体化方案）</text>

    <!-- 向下箭头 -->
    <path d="M280,190 C280,215 280,215 280,240" stroke="#2E86C1" stroke-width="2" fill="none" marker-end="url(#arrow1)"/>
    <path d="M600,190 C600,215 600,215 600,240" stroke="#2E86C1" stroke-width="2" fill="none" marker-end="url(#arrow1)"/>
    <path d="M920,190 C920,215 920,215 920,240" stroke="#2E86C1" stroke-width="2" fill="none" marker-end="url(#arrow1)"/>
  </g>

  <!-- ==================== 模块2：核心模式与干预措施 ==================== -->
  <g id="module-2">
    <!-- 背景 -->
    <rect x="50" y="250" width="1100" height="240" rx="12" ry="12" fill="#F0FFFA" stroke="#20B2AA" stroke-width="2" filter="url(#shadow2)"/>
    <text x="600" y="275" font-size="15" font-weight="bold" fill="#006666" text-anchor="middle">第二阶段：核心模式与干预措施（医护康三方协作 + 五时间节点）</text>

    <!-- 共管模型背景 -->
    <rect x="100" y="295" width="1000" height="50" rx="8" ry="8" fill="#E0F5F5" stroke="#1ABC9C" stroke-width="1.5"/>
    <text x="600" y="315" font-size="14" font-weight="bold" fill="#0B5345" text-anchor="middle">医-护-康三方协作共管模型</text>
    <text x="600" y="333" font-size="12" fill="#2C3E50" text-anchor="middle">（联合查房、病例讨论、动态调整管理策略）</text>

    <!-- 角色节点 -->
    <rect x="150" y="365" width="220" height="60" rx="8" ry="8" fill="#E0F5F5" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="260" y="385" font-size="14" font-weight="bold" fill="#0B5345" text-anchor="middle">临床医生</text>
    <text x="260" y="405" font-size="12" fill="#2C3E50" text-anchor="middle">（诊断/药物调整/指标解读）</text>

    <rect x="490" y="365" width="220" height="60" rx="8" ry="8" fill="#E0F5F5" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="600" y="385" font-size="14" font-weight="bold" fill="#0B5345" text-anchor="middle">专科护士</text>
    <text x="600" y="405" font-size="12" fill="#2C3E50" text-anchor="middle">（心理筛查/宣教随访/监测）</text>

    <rect x="830" y="365" width="220" height="60" rx="8" ry="8" fill="#E0F5F5" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="940" y="385" font-size="14" font-weight="bold" fill="#0B5345" text-anchor="middle">康复治疗师</text>
    <text x="940" y="405" font-size="12" fill="#2C3E50" text-anchor="middle">（认知/运动综合训练方案）</text>

    <!-- 时间线节点 -->
    <rect x="150" y="440" width="130" height="40" rx="8" ry="8" fill="#FFFFFF" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="215" y="465" font-size="14" font-weight="bold" fill="#006666" text-anchor="middle">T1（第1周）</text>

    <rect x="310" y="440" width="130" height="40" rx="8" ry="8" fill="#FFFFFF" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="375" y="465" font-size="14" font-weight="bold" fill="#006666" text-anchor="middle">T2（1个月）</text>

    <rect x="470" y="440" width="130" height="40" rx="8" ry="8" fill="#FFFFFF" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="535" y="465" font-size="14" font-weight="bold" fill="#006666" text-anchor="middle">T3（3个月）</text>

    <rect x="630" y="440" width="130" height="40" rx="8" ry="8" fill="#FFFFFF" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="695" y="465" font-size="14" font-weight="bold" fill="#006666" text-anchor="middle">T4（6个月）</text>

    <rect x="790" y="440" width="130" height="40" rx="8" ry="8" fill="#FFFFFF" stroke="#1ABC9C" stroke-width="1.5" filter="url(#shadow2)"/>
    <text x="855" y="465" font-size="14" font-weight="bold" fill="#006666" text-anchor="middle">T5（12个月）</text>

    <!-- 向下箭头 -->
    <path d="M600,490 C600,515 600,515 600,540" stroke="#1ABC9C" stroke-width="2" fill="none" marker-end="url(#arrow2)"/>
  </g>

  <!-- ==================== 模块3：评估维度与数据采集 ==================== -->
  <g id="module-3">
    <!-- 背景 -->
    <rect x="50" y="550" width="1100" height="170" rx="12" ry="12" fill="#F8F0FF" stroke="#9370DB" stroke-width="2" filter="url(#shadow3)"/>
    <text x="600" y="575" font-size="15" font-weight="bold" fill="#4A235A" text-anchor="middle">第三阶段：评估维度与数据采集（两大评估维度双轨并行）</text>

    <!-- 影像学节点 -->
    <rect x="150" y="600" width="380" height="90" rx="8" ry="8" fill="#F3EEF9" stroke="#8E44AD" stroke-width="1.5" filter="url(#shadow3)"/>
    <text x="340" y="625" font-size="14" font-weight="bold" fill="#4A235A" text-anchor="middle">影像学评估</text>
    <text x="340" y="645" font-size="12" fill="#2C3E50" text-anchor="middle">静息态fMRI（ALFF/dALFF） / 结构像 / DWI</text>
    <text x="340" y="665" font-size="12" fill="#2C3E50" text-anchor="middle">动态脑功能网络重塑与灰质保护效应</text>

    <!-- 实验室节点 -->
    <rect x="670" y="600" width="380" height="90" rx="8" ry="8" fill="#F3EEF9" stroke="#8E44AD" stroke-width="1.5" filter="url(#shadow3)"/>
    <text x="860" y="625" font-size="14" font-weight="bold" fill="#4A235A" text-anchor="middle">实验室评估</text>
    <text x="860" y="645" font-size="12" fill="#2C3E50" text-anchor="middle">多靶点炎症因子（IL-6/TNF-α等） / Hcy / 甲状腺功能</text>
    <text x="860" y="665" font-size="12" fill="#2C3E50" text-anchor="middle">HPA轴激素与神经-内分泌-免疫轴动态变化</text>

    <!-- 向下箭头 -->
    <path d="M600,720 C600,745 600,745 600,770" stroke="#8E44AD" stroke-width="2" fill="none" marker-end="url(#arrow3)"/>
  </g>

  <!-- ==================== 模块4：数据分析与预期目标 ==================== -->
  <g id="module-4">
    <!-- 背景 -->
    <rect x="50" y="780" width="1100" height="170" rx="12" ry="12" fill="#FFF5F0" stroke="#FF8C00" stroke-width="2" filter="url(#shadow4)"/>
    <text x="600" y="805" font-size="15" font-weight="bold" fill="#7E5109" text-anchor="middle">第四阶段：数据整合分析与研究目标</text>

    <!-- 统计方法节点 -->
    <rect x="150" y="825" width="900" height="45" rx="8" ry="8" fill="#FDEBD0" stroke="#E67E22" stroke-width="1.5" filter="url(#shadow4)"/>
    <text x="600" y="850" font-size="14" font-weight="bold" fill="#7E5109" text-anchor="middle">统计分析方法：方差分析 / Kruskal-Wallis检验 / Spearman相关性分析 / 岭回归分析</text>

    <!-- 目标节点 -->
    <rect x="150" y="880" width="900" height="45" rx="8" ry="8" fill="#FDEBD0" stroke="#E67E22" stroke-width="1.5" filter="url(#shadow4)"/>
    <text x="600" y="905" font-size="14" font-weight="bold" fill="#7E5109" text-anchor="middle">三大核心目标：干预效果评估 / 影像-实验室标志物动态关联分析 / 临床实践规范化（SOP）</text>

    <!-- 向下箭头 -->
    <path d="M600,950 C600,975 600,975 600,1000" stroke="#E67E22" stroke-width="2" fill="none" marker-end="url(#arrow4)"/>
  </g>

  <!-- ==================== 模块5：预期成果 ==================== -->
  <g id="module-5">
    <!-- 背景 -->
    <rect x="50" y="1010" width="1100" height="120" rx="12" ry="12" fill="#F0FFF0" stroke="#32CD32" stroke-width="2" filter="url(#shadow5)"/>
    <text x="600" y="1035" font-size="15" font-weight="bold" fill="#1E8449" text-anchor="middle">第五阶段：预期成果与效益</text>

    <!-- 成果1 -->
    <rect x="140" y="1055" width="280" height="55" rx="8" ry="8" fill="#E8F5E9" stroke="#2ECC71" stroke-width="1.5" filter="url(#shadow5)"/>
    <text x="280" y="1075" font-size="14" font-weight="bold" fill="#1E8449" text-anchor="middle">学术论文</text>
    <text x="280" y="1095" font-size="12" fill="#2C3E50" text-anchor="middle">发表高水平论文2篇</text>

    <!-- 成果2 -->
    <rect x="460" y="1055" width="280" height="55" rx="8" ry="8" fill="#E8F5E9" stroke="#2ECC71" stroke-width="1.5" filter="url(#shadow5)"/>
    <text x="600" y="1075" font-size="14" font-weight="bold" fill="#1E8449" text-anchor="middle">人才培养</text>
    <text x="600" y="1095" font-size="12" fill="#2C3E50" text-anchor="middle">培养硕研2名 / 培训医护≥20人</text>

    <!-- 成果3 -->
    <rect x="780" y="1055" width="280" height="55" rx="8" ry="8" fill="#E8F5E9" stroke="#2ECC71" stroke-width="1.5" filter="url(#shadow5)"/>
    <text x="920" y="1075" font-size="14" font-weight="bold" fill="#1E8449" text-anchor="middle">社会效益</text>
    <text x="920" y="1095" font-size="12" fill="#2C3E50" text-anchor="middle">提升卒中患者心理健康 / 降低复发率</text>
  </g>
</svg>
