# 新能源汽车电驱动产品行业每日资讯 - 2026年10月06日

> 收集时间：2026-10-06 02:35（北京时间）
> 资讯数量：9条 | 国内2条 | 国外5条 | 学术2条
> 说明：本期经8轮定向检索（中文产业综合、中文企业动态、英文产业综合、英文企业动态、中文学术、英文学术、中文功率器件专项、英文技术方案专项，实际执行30+轮含时效补充检索）并逐条抓取原文核实。**时效说明**：截至执行时点（10/6凌晨，中国国庆假期第6日、周末结束、IEEE ECCE 2026会期第3日），全球电驱动领域**近24小时（10/5–10/6）纯新增"电驱本体"硬资讯仍极为稀少**：国内处于国庆假期（10/1–10/7）静默窗口，头部主机厂/电驱企业无新发布；海外产业侧仅见少量非电驱核心的功率器件新闻。本期以 **10/5 新发生事件**为骨架（Equipmake为Perkins氢混动力单元提供重载辐条电机+SiC逆变器进入实机测试、欧盟委员会批准塔塔AutoComp与博世合资电驱桥、FEV亚琛年会相关线索），纳入 **10/4 起 ECCE 2026 会期**的 Hillcrest ZVS 牵引逆变器论文，并补遗 **9/30 DeepDrive轮毂电驱**、**9/23 广汽非晶合金电驱产业化量产**、**9/18 Ricardo ALUMOTOR**、**9/17 潍柴Vectopower Evo逆变器**，以及 **10/1 IEEE TPEL 物理信息RNN无模型预测控制**、**9/22 arXiv CSI高速PMSM无位置传感器控制**两篇论文（部分为48小时窗口外、此前日报未收录，均已如实标注）。已与近期日报逐项去重核对：**10/5日报已覆盖**BEM无稀土双绕组电机声明、ECCE 2026议程、IEEE TTE弱磁自适应过调制、CSI双内模解耦、不变流形无模型预测控制、英飞凌XENSIV角度传感器、尼得科出售车用电机业务，本期不重复收录；**10/2日报已覆盖**东芝沟槽栅SiC MOSFET、通用汽车+普渡大学ECCE GaN多电平+双三相PMSRm、IEEE TTE 250kW双三相IPM、扁线端部绕组喷油冷却、WBG轴承电压灰箱模型、港科大（广州）IPMSM无位置传感器控制、博世SiC S-Cell，本期不重复收录；**10/1日报已覆盖**尼得科减值、小鹏第三代HySiC混碳模块、峰岹收购Sciosense、蔚然扁线波绕专利、Tau Motors软件定义电驱、Wolfspeed 200mm衬底、东芝3300V SiC模块，本期不重复收录。已严格剔除：整车发布/上市/销量（领克20、AION/埃安全系整车宣传、BMW/Mercedes等整车稿）、动力电池与充放电、智能驾驶与域控制器、机器人/低空经济非车用电机、泛财经与无实质电驱参数的营销通稿。**另经时效性核验剔除**：onsemi EPP斯巴鲁评估（原始发布2026-09-16，属旧闻重发）、L&T Semiconductor 1200V SiC平台（2026-09-18/10-01）、TDK HAL 13xy电机位置传感器（2026-05-28）、FEV+RWTH无稀土模块化转子（2025-10）、芯聚能/芯粤能1400V SiC量产（2026-09-14事件）等超出48小时窗口且不属本次补遗范围。**另经严格核实、按SOP不作定性结论**：ECCE 2026会议论文（如Hillcrest ZVS）的量化指标为**作者论文与厂商测试结果**，部分基于特定台架条件，已如实标注测试工况，不代表已量产整车实测。

---

## 1. Equipmake为Perkins "Project Coeus"氢/多燃料混合动力单元提供重载辐条式（spoke）电机+自研碳化硅逆变器：整机397kW/1938N·m，已装车Terex撕碎机实地测试

**分类**：产品发布/技术发布
**摘要**：Perkins（卡特彼勒全资子公司）正将型号为1206的多燃料混合动力工业动力单元（IOPU）安装于Terex Ecotec TDS 820撕碎机进行实地测试；该单元由Perkins与英国电气化厂商Equipmake在"Project Coeus"项目下联合开发，Equipmake提供了新设计的**辐条式（spoke）重载电机**及其自研**碳化硅（SiC）逆变器**，整机输出**397kW（508hp）、1938N·m**。
**来源**：[Electric & Hybrid Vehicle Technology International（2026-10-05）· Equipmake spoke-architecture e-motor powers Perkins fuel-flexible hybrid in machine tests](https://www.electrichybridvehicletechnology.com/news/equipmake-spoke-architecture-e-motor-powers-perkins-fuel-flexible-hybrid-in-machine-tests.html)
**发布时间**：2026-10-05
**相关企业/机构**：Perkins Engines（英国，Caterpillar Inc. 全资子公司）；Equipmake（英国Snetterton）；Loughborough University（Wolfson School）；英国先进推进中心（APC）资助
**技术亮点**：
- **产品本质**：面向非道路重载工况的**电机-发动机一体化混合动力单元（MGU）**——Equipmake在Snetterton工厂设计并制造**辐条式（spoke-type）重载驱动电机**，与其**自研SiC逆变器**及配套功率电子组合为MGU，再与Perkins的可配置火花点火发动机集成，作为**柴油动力单元的"直接替换件"（drop-in replacement）**
- **量化指标**：整机综合输出**397kW（508hp）**、**1938N·m**，峰值转矩区间**1200–1500rpm**；可配置运行于**氢气、甲醇、乙醇、生物甲烷**四种燃料（均为火花点火）
- **应用与测试**：首台示范应用为**Terex Ecotec TDS 820撕碎机**，由Perkins客户机械工程团队在英国Peterborough研发中心集成，随后在Perkins试验场验证**峰值负载能力与瞬态响应**；该动力单元曾在CONEXPO-CON/AGG首次公开亮相
- **技术阶段**：**工程验证/实机测试阶段**（自试验台转入整机实机测试，非量产定型）
- **项目背景**：Project Coeus为2023年启动的三年期项目，由Perkins牵头，Equipmake与Loughborough University参与，经APC获英国政府**1114万英镑**资助，其中Equipmake获**324万英镑**
- **相对主流方案**：面向非道路重载设备的"多燃料混合动力+电驱"路线，强调**无需整机重新设计**即可由柴油向低碳燃料与电气化过渡，与乘用车三合一体积/功率密度导向不同

---

## 2. Hillcrest零电压开关（ZVS）牵引逆变器IEEE ECCE 2026论文：电机端电压过冲降低逾90%（1.5→1.04 p.u.）、dv/dt由约16降至1.4 V/ns、5MHz以上EMI降约25dB

**分类**：技术突破/学术成果
**摘要**：Hillcrest Energy Technologies在**IEEE ECCE 2026（2026-10-04至10-08，温哥华）**发表的同行评审论文《High-Performance ZVS Inverter for Traction Systems Under Reflected Wave Conditions》给出对比测试结果：相较常规硬开关SiC逆变器，其**零电压开关（ZVS）**方案将**电机端电压过冲降低逾90%**（由1.5 p.u.降至1.04 p.u.），并将**电压变化率（dv/dt）由约16 V/ns降至约1.4 V/ns**、5MHz以上高频EMI降低约**25dB**。
**来源**：[Hillcrest Energy Technologies（2026-09-29）· Hillcrest ZVS Technology Demonstrates More Than 90% Reduction in Motor Voltage Spikes](https://hillcrestenergy.tech/news/2026/09/hillcrest-zvs-technology-demonstrates-more-than-90-reduction-in-motor-voltage-spikes/)；论文：E. Serban, J. Amini, M. Kroesser, C. Lascu, "High-Performance ZVS Inverter for Traction Systems Under Reflected Wave Conditions," Proc. IEEE ECCE 2026
**发布时间**：2026-09-29（企业发布）/ 2026-10-04至10-08（ECCE 2026会议报告）
**相关企业/机构**：Hillcrest Energy Technologies Ltd.（加拿大）；Systematec GmbH（德国）；Politehnica University of Timișoara（罗马尼亚）
**技术亮点**：
- **问题本质**：SiC器件开关速度远高于硅，逆变器-电缆-电机之间的阻抗失配引发**电压反射（reflected wave）**，即使电缆仅数米，电机端电压也可达直流母线电压的**2倍**，加速绕组绝缘老化、诱发局部放电并导致逆变器馈电电机绕组早期失效
- **创新本质**：ZVS在**开关时刻**（而非下游）治理问题——在器件两端电压接近零时换流，将电压过渡时间延长约**10倍**，同时保持高效率（区别于用缓冲电路降slew rate会增加开关损耗）
- **量化指标（对比常规硬开关SiC逆变器）**：
  - 电机端过冲：**1.5 p.u.（+50%）→ 1.04 p.u.（+4%）**（测试条件：80kW电机、2m屏蔽电缆、400V DC、20kHz）
  - 电压变化率dv/dt：**约16 V/ns → 约1.4 V/ns**（470V DC、40kHz、调制比0.4）；对应开关电压上升时间**约30ns → 约335ns**
  - 高频EMI：**1–5MHz降低5–25dB；5MHz以上降低约25dB**
  - 长电缆：在**50m电缆**最恶劣双脉冲条件下，峰值负载电压**约920V（<2 p.u.）**；论文称同类工况下硬开关逆变器文献报道超过**2–3 p.u.**；本方案将临界电缆长度扩展至约**18m**
- **测试平台**：三相逆变器采用**1200V SiC MOSFET**，驱动80kW电机，电缆为35mm²四芯屏蔽电缆（0.3µH/m、130pF/m、特性阻抗约48Ω、传播速度约160m/µs）
- **平台既有结果**：公司称此前在多家整车厂/Tier1设施测试中实现**峰值逆变器效率最高99.7%**，并显著降低EMI、减小直流母线电容
- **技术阶段**：**同行评审论文/台架测试阶段**（论文将收录于ECCE 2026 Proceedings并后续上线IEEE Xplore；非量产整车实测）
- **相对主流方案**：传统以**电机端或逆变器柜被动滤波**抑制反射波，但增加成本、体积与功率损耗，抵消宽禁带器件的固有优势；ZVS以"在开关事件处消除成因"替代"下游治理"

---

## 3. 欧盟委员会批准塔塔AutoComp（Tata Sons旗下）与博世（Bosch）合资电驱桥（e-axle）企业：面向印度市场本地化生产电动车桥

**分类**：产品发布/商业动态
**摘要**：据MarkLines 10月5日报道，**欧盟委员会于10月2日批准**塔塔集团旗下**Tata AutoComp Systems Limited**与德国**Robert Bosch GmbH（博世）**设立合资企业；该合资公司将主要面向**印度汽车产业制造并供应电驱桥（electric axles）**。
**来源**：[MarkLines（2026-10-05）· European Commission clears India's Tata Sons and Bosch electric axle joint venture](https://www.marklines.com/en/news/351933)；[Bosch Limited 公告 · Bosch Limited and Tata AutoComp Systems announce a joint venture](https://us.bosch-press.com/pressportal/in/en/press-release-7616.html)；[Global Auto Insight · Tata AutoComp Bosch JV Cleared by EU Commission](https://www.globalautoinsight.com/news/tata-autocomp-bosch-joint-venture-eu-commission-approval)
**发布时间**：2026-10-02（欧盟委员会批准）/ 2026-10-05（行业报道）
**相关企业/机构**：Tata AutoComp Systems Limited（Tata Sons Private Limited 控股，印度）；Robert Bosch GmbH（德国）；股权结构为双方**各持50%**
**技术亮点**（商业动态，技术参数从略）：
- **事件性质**：**电驱桥（e-axle）**合资企业获欧盟监管放行，聚焦**印度本地化生产与供应**，是电驱供应链在地化（localization）的又一案例
- **事件脉络**：该项目此前由博世印度（Bosch Limited）与Tata AutoComp于**2026年3月**宣布，计划**2026年年中**开始运营，尚待全部监管批准；本次欧盟委员会批准为其**里程碑式监管进展**（下一步为印度等辖区的最终落地）
- **产业影响**：在整车价格战与电驱高度自研背景下，**Tier1以合资/本地化方式切入新兴市场电驱桥供应**，绑定Tata集团在印度的整车资源，反映电驱供应链"区域化+成本导向"趋势

---

## 4. 广汽集团携手中科院东莞材料所实现非晶合金电驱产业化量产：铁芯损耗降75%、电机峰值效率99%、SiC电控损耗较硅基IGBT降71.6%

**分类**：技术突破/产品发布
**摘要**：广汽集团与中国科学院东莞材料科学与技术研究所（东莞材料所，汪卫华院士领衔）于9月23日在东莞联合举办"非晶电驱两创融合论坛及合作成果发布会"，宣布**非晶合金电驱实现车规级规模化量产**，广汽埃安**三款量产车型**（2027款埃安RT、埃安N60、2027款埃安i60）集中亮相并搭载该电驱。
**来源**：[中国科学院广州分院（2026-09-29）· 东莞材料所携手广汽实现非晶电驱产业化落地](http://www.gzb.ac.cn/kjh/202609/t20260929_8287641.html)；[新华网广东（2026-09-23）· 广汽携手中国科学院东莞材料所攻坚非晶电驱产业化](http://www.gd.xinhuanet.com/20260924/3f384d9d460543dd8ad3bbf81903194b/c.html)；[南方+（2026-09-24）· 非晶电驱量产落地](https://m.mp.oeeee.com/a/BAAFRD0000202609241672364.html)
**发布时间**：2026-09-23（成果发布）/ 2026-09-24至09-29（媒体报道）
**相关企业/机构**：广汽集团（广汽埃安、锐湃动力科技）；中国科学院东莞材料科学与技术研究所（汪卫华院士团队）；华南理工大学（杨超教授）
**技术亮点**：
- **材料本质**：**非晶合金（"金属玻璃"/"手撕钢"）**，成品带材厚度仅**0.025毫米（约头发丝1/5）**；凭借无序原子排布实现**极低矫顽力与超高电阻率**，可大幅抑制电机涡流损耗与磁滞损耗，但材料"薄而脆"给车规级大批量制造带来极高门槛
- **制造工艺突破（量化）**：非晶带材无法直接复用传统硅钢冲压工艺，广汽与东莞材料所从零搭建**激光切割+精密叠压+专属热处理**非标产线，将**非晶铁芯叠压层数提升至3800层，达传统硅钢电机的10倍**；"基于超薄非晶材料的低损耗定子铁芯精密制造关键技术和应用"项目获**第51届日内瓦国际发明展最高奖"评审团特别金奖"**，并获**2025年度"全球新能源汽车唯一动力系统创新技术"**
- **性能量化（以2027款埃安RT为例）**：非晶合金铁芯搭配**碳纤维转子**，**电机铁芯损耗下降75%**，实现**99%电机峰值效率**；配套**碳化硅电控**较传统硅基IGBT电控**损耗降低71.6%**
- **能效实证**：在海南环岛高速真实家庭出游工况，测得**8.571 kWh/100km**，创"驾驶量产纯电轿车通过海南环岛高速电耗最低"**吉尼斯世界纪录**；动力组合为"非晶合金电驱+碳化硅电控+宁德时代电池"，下探至**9.98万–12.38万元**价格带
- **产品沿革**：以非晶合金量产为核心的**广汽埃安夸克电驱2.0**已于**2026-08-23在锐湃动力科技量产下线**，当时公布**98.5%量产电机效率、13kW/kg功率密度、30000rpm最高转速**三项指标
- **技术阶段**：**已量产**（车规级规模化量产并装车）

---

## 5. DeepDrive双转子径向磁通轮毂电驱+一体化SiC逆变器：IW 2500（19英寸）峰值220kW/2500N·m、峰值效率96.5%、含逆变器仅36kg

**分类**：技术发布
**摘要**：德国DeepDrive正在开发一种**轮毂电驱（in-wheel drive）**方案，将其**专利双转子径向磁通电机**与**一体化SiC MOSFET逆变器**集成于轮端；其最新**IW 2500（19英寸）**支持**300–850V DC**供电，峰值**220kW/2500N·m**（持续30秒），峰值效率**96.5%**，含逆变器整重**36kg**。
**来源**：[everything PE（2026-09-30）· Dual-Rotor Motor and Integrated SiC Inverter Target High-Density In-Wheel EV Propulsion](https://www.everythingpe.com/news/details/12118-dual-rotor-motor-and-integrated-sic-inverter-target-high-density-in-wheel-ev-propulsion)；[DeepDrive 技术页](https://www.deepdrive.tech/technology/)；[DeepDrive 轮毂驱动页](https://www.deepdrive.tech/in-wheel-drive)
**发布时间**：2026-09-30
**相关企业/机构**：DeepDrive（德国，2021年成立，团队含博世、奥迪、英飞凌背景）
**技术亮点**：
- **架构创新**：**双转子径向磁通（Dual Rotor, Radial-Flux）**电机——定子置于两转子之间，单个定子磁场同时与两转子作用，提升转矩密度并降低铁耗；采用**分布式条式绕组（distributed bar winding）**，**槽满率>80%**，降低转矩脉动与噪声
- **一体化电控**：与电机集成的**SiC MOSFET逆变器**采用专利拓扑以降损降本，并保持紧凑
- **量化指标（IW 2500，19英寸）**：供电范围**300–850V DC**；峰值功率**220kW**、峰值转矩**2500N·m**（持续30秒）；峰值效率**96.5%**；含逆变器重量**36kg**（不含轴承）；最高转速**1800rpm**
- **材料与冷却**：相较传统方案可**减少50%磁体材料、减少80%铁**，且磁体**不含重稀土**；采用**水-乙二醇冷却**，热管理系统兼顾电机与集成逆变器散热；支持控制器集成式打滑控制与CAN接口
- **技术阶段**：**产品/技术发布（开发中）**，面向轮毂直驱或作为按需AWD/PHEV的补充驱动
- **相对主流方案**：**取消电机-车轮之间的减速器**，直接向车轮输出转矩，减少机械件与传动损耗；但轮端集成对**簧下质量**提出更高要求，是轮毂电驱的共性挑战

---

## 6. 【补遗】潍柴（Weichai）发布Vectopower Evo牵引逆变器与WMC多合一控制器：ARM+FPGA架构控制周期2μs、峰值效率>99%、CHTC工况能耗低1.65%

**分类**：技术发布（48小时窗口外补遗，此前日报未收录）
**摘要**：潍柴（Weichai）在**IAA Transportation 2026**展出其新款**Vectopower Evo牵引逆变器**与**WMC多合一集成控制器**，面向重型卡车与工程机械；逆变器采用**ARM+FPGA架构**，控制周期达**2μs**、峰值效率**>99%**，在中国重型商用车测试循环（CHTC）下能耗较同类产品低**1.65%**。
**来源**：[Power Progress（2026-09-17）· Weichai shows new inverter and controller units at IAA Transportation](https://www.powerprogress.com/news/weichei-shows-new-inverter-and-controller-units-at-iaa-transportation/8131541.article)
**发布时间**：2026-09-17（IAA Transportation 2026 展出）
**相关企业/机构**：潍柴动力（Weichai Power，中国）
**技术亮点**：
- **逆变器（Vectopower Evo）**：**ARM+FPGA架构**实现**2μs控制周期**、峰值效率**>99%**；转矩响应时间**<10ms**、控制精度约**2.0%**；支持CAN、CANopen、RS-232通信接口；面向重卡与工程机械，强调高精度、快响应与成本效益
- **多合一控制器（WMC-L/H/B）**：**多核芯片**将**MCU、PDU、BDU集成于单一单元**；主功率模块集成驱动板、功率模块（**兼容IGBT与SiC**）与母线电容，并进一步整合**两路DC/AC变换器+一路DC/DC变换器**；标配安全与网络安全系统，面向轻/重型卡车
- **量化对比**：CHTC工况能耗较同类产品**低1.65%**（企业自测）
- **技术阶段**：**产品发布**（IAA Transportation 2026展出，配套电池包一同亮相）

---

## 7. 【补遗】Ricardo发布ALUMOTOR无永磁、少铜800V车用电机：铝绕组+油冷喷油+扁线，峰值195kW、功率密度3kW/kg、最高14000rpm

**分类**：技术突破（48小时窗口外补遗，此前日报未收录）
**摘要**：Ricardo开发出**ALUMOTOR**——一种**不含永磁体、少铜**的车用电驱动电机，采用**铝绕组**并兼容**标准800V功率电子**；峰值功率**195kW（6000rpm）**、功率密度**3kW/kg**、最高转速**14000rpm**、效率图内**92%**，面向轻型商用车、非道路设备与专用车辆。
**来源**：[everything PE（2026-09-18）· Ricardo Develops Critical-Mineral-Free 800 V EV Motor](https://www.everythingpe.com/news/details/12053-ricardo-develops-critical-mineral-free-800-v-ev-motor)
**发布时间**：2026-09-18
**相关企业/机构**：Ricardo plc（英国）
**技术亮点**：
- **材料创新**：以**铝绕组**替代传统"永磁体+高铜"结构，实现**无永磁、少铜**架构，降低对关键矿产（稀土、铜）供应链的依赖；公司称相较标准电机**最高可降低约60%成本**（视对比基准）
- **量化指标**：**800Vdc**工作电压，兼容标准功率电子（无需专用功率变换架构）；**峰值功率195kW@6000rpm**、**额定功率131kW**；**功率密度3kW/kg**；**峰值转矩400N·m@3500rpm**、**额定转矩250N·m@5000rpm**；最高转速**14000rpm**（以最终验证测试为准）；效率图大范围内**92%**
- **冷却与绕组**：**油冷架构（含喷油油道）**+**扁线（hairpin）绕组**，兼顾效率与成本控制
- **应用定位**：轻型商用车、非道路设备与专用车辆
- **技术阶段**：**研发/设计阶段**（最高转速等指标"subject to final validation testing"，即待最终验证测试）
- **相对主流方案**：在**800V高压平台**下以"铝绕组+无永磁"实现低成本、供应链韧性，与当前以稀土PMSM为主流、无稀土路线（EESM/WRSM/铁氧体）并起的趋势一致

---

## 8. 【补遗】IEEE TPEL（2026-10-01）：基于物理信息循环神经网络（PIRNN）的PMSM无模型预测电流控制——以RNN替代传统观测器在线估计集总扰动

**分类**：技术突破/学术成果
**摘要**：《IEEE Transactions on Power Electronics》（2026-10-01）刊文提出一种基于**物理信息循环神经网络（PIRNN）**的**无模型预测电流控制（MFPCC）**策略，利用具备时序学习能力的**循环神经网络（RNN）**替代传统观测器，在线估计**超局部模型（ultra-local model）**中的**集总扰动项**，并通过物理信息学习机制将RNN输出与实测电流显式关联。
**来源**：[Semantic Scholar · Model-Free Predictive Current Control for PMSMs Based on a Physics-Informed Recurrent Neural Network（DOI:10.1109/TPEL.2026.3690904，2026-10-01）](https://www.semanticscholar.org/paper/Model-Free-Predictive-Current-Control-for-PMSMs-on-Zang-Zhou/612ce9a6586a8c92bb2bb4ff1f80edc85fe01080)；[ORCID记录（DOI:10.1109/TPEL.2026.3690904）](https://orcid.org/0009-0003-0177-0146)
**发布时间**：2026-10-01
**相关企业/机构**：作者 Yonghang Zang、Fobao Zhou、Zhenxiao Yin、Yang Shen、Maohui Lin、Hang Zhao（具体单位以原文为准）
**技术亮点**：
- **问题**：无模型预测电流控制（MFPCC）依赖超局部模型对集总扰动的估计，传统方法需观测器且对参数失配敏感；同时神经网络类方法普遍缺乏"真值（ground truth）"监督信号
- **创新本质**：以**PIRNN**取代传统观测器在线估计集总扰动项；引入**物理信息学习机制**，将RNN输出与实测电流显式建立联系，以缓解标注缺失问题，提升参数失配下的控制精度
- **量化指标**：电流脉动、动态响应、参数鲁棒性等具体数值**暂未公开**（IEEE Xplore摘要受限），本条不作推测，以原文图表为准
- **技术阶段**：**建模/方法研究阶段**（同行评审期刊论文），面向车用PMSM驱动控制的"免模型/免观测器+AI"方向
- **相对主流方案**：相较依赖精确模型或额外观测器的预测控制，本方法以"RNN+物理信息约束"降低对模型与观测器的依赖，指向控制算法的数据驱动简化路径

---

## 9. 【补遗】arXiv（2026-09-22）/ICEM 2026：电流源逆变器（CSI）馈电高速PMSM高性能无位置传感器控制——弱谐振近似重构定子电流，100krpm下位置误差<5°

**分类**：技术突破/学术成果
**摘要**：一篇被**ICEM 2026**录用并报告的论文提出面向**电流源逆变器（CSI）馈电高速永磁同步电机（PMSM）**的**无位置传感器控制**方法：以**弱谐振近似（weak-resonance-based approximation）**由逆变器调制指令与前馈电容电流估计**重构定子电流**，将传感需求降至**直流母线电流+两路端电压**；在**100W、100krpm**的**GaN基两级CSI（Buck+CSI）**样机上实现转子位置估计误差**<5°**。
**来源**：[arXiv:2609.25878（2026-09-22）· High-Performance Sensorless Control for High-Speed PMSM with Current Source Inverters](https://arxiv.org/abs/2609.25878)（Comments: Accepted, and presented at ICEM 2026）
**发布时间**：2026-09-22
**相关企业/机构**：作者 Nail Tosun、Devinda Molligoda、Xu Deng、Barrie Mecrow（Nail Tosun为剑桥大学相关研究者，具体单位以原文为准）
**技术亮点**：
- **对象与优势**：**CSI**相较电压源逆变器（VSI）用于高速电机驱动具**固有抑制谐波电流、输出电压升压、降低电机侧电磁干扰**等优势，但CSI馈电PMSM的无位置传感器控制成熟度低于VSI（传统实现需测量全部电路状态变量）
- **创新本质**：提出**弱谐振近似**，由**逆变器调制指令+前馈电容电流估计**重构定子电流，将传感需求降低为**直流母线电流+两路端电压**；给出**观测器–PLL**结构并分析其计算复杂度
- **量化指标**：在**100W、100krpm**的**GaN基两级CSI原型（Buck+CSI）**上，仿真与实验均实现转子位置精确跟踪与高带宽运行，**100krpm下位置估计误差<5°**
- **技术阶段**：**实验样机验证/学术报告阶段**（ICEM 2026录用并报告）
- **相对主流方案**：相较需完整状态测量的CSI无位置传感器方案，本方法以"弱谐振近似+前馈"减少传感器数量，指向**高速电驱（GaN+CSI）**的传感精简方向

---

## 简要总结

- **当日（10/5–10/6）"电驱本体"新增硬资讯仍处假期+会期叠加的低谷，全球范围无重大定点/量产公告**：中国国庆假期（10/1–10/7）使国内头部主机厂/电驱企业集体静默；海外仅见少量**非道路重载**与**电驱供应链**动态（Equipmake+Perkins重载电机+SiC逆变器进入实机测试、欧盟批准塔塔AutoComp与博世合资电驱桥）。本期国内企业动态偏少（2条，且均为近期补遗），已如实标注。
- **最具技术价值的当期为"宽禁带器件的系统级副作用治理"**：Hillcrest的**ZVS牵引逆变器**论文直面SiC快速开关引发的**电压反射/电机端过冲**问题，以"在开关时刻降低dv/dt"实现**过冲-90%、dv/dt 16→1.4 V/ns、5MHz以上EMI-25dB**，为"用SiC又不想加被动滤波"的行业痛点提供了可量化的替代路径（ECCE 2026会期报告）。
- **器件与拓扑两条主线之外，"底层材料"成为国产电驱差异化的新焦点**：广汽携手中科院东莞材料所的**非晶合金电驱**以**铁芯损耗-75%、电机峰值效率99%、SiC电控损耗-71.6%**实现车规级量产并下探10万元级市场，代表"从材料到整车"的根技术竞争；同时**无稀土/去永磁路线**（Ricardo铝绕组ALUMOTOR、DeepDrive双转子轮毂电驱）持续活跃，但多处于研发或设计验证阶段。
- **电驱控制算法向"免模型、免观测器、数据驱动"演进**：本期两篇论文（IEEE TPEL物理信息RNN无模型预测电流控制、arXiv/ICEM CSI高速PMSM无位置传感器控制）分别指向**AI替代观测器**与**传感精简**，共同反映电驱控制在高带宽与低成本间的工程化取舍。
- **总体特征：时效稀缺、以补遗为主、零杜撰**。本期9条中，仅第1–3条接近48小时窗口（10/2–10/5），其余为9/17–10/1的**优质补遗**（此前日报均未收录，已逐条标注）；所有条目均抓取原文核实并明确技术阶段（量产/样机/研发），ECCE 2026论文指标已标注测试工况、企业自测数据已注明来源，未核实参数一律不填。
