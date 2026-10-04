# 新能源汽车电驱动产品行业每日资讯 - 2026年10月05日

> 收集时间：2026-10-05 02:43（北京时间）
> 资讯数量：7条 | 国内0条 | 国外3条 | 学术4条
> 说明：本期经8轮定向检索（中文产业综合、中文企业动态、英文产业综合、英文企业动态、中文学术、英文学术、中文功率器件专项、英文技术方案专项，实际执行30+轮含时效补充检索）并逐条抓取原文核实。**时效说明**：截至执行时点（10/5凌晨，中国国庆假期第5日、周末叠加以IEEE ECCE 2026会期首日），全球电驱动领域**近24小时（10/4–10/5）纯新增"电驱本体"硬资讯极为稀少**：国内处于国庆假期静默窗口，头部企业无新发布；产业链媒体（everything PE 汽车栏目、Power Semiconductors Weekly 等）更新停滞在10/1；海外无重大定点/量产公告。本期以 **10/3–10/4 新发生事件**为骨架（BEM无稀土双绕组电机性能声明被第三方分析解读、IEEE ECCE 2026开幕），纳入 **10/2 尼得科车用电机业务出售动向**，并补遗 **10/1 见刊的三篇IEEE电驱/电机控制论文**与 **9/28 英飞凌电机控制用自校准角度传感器**（48小时窗口外、此前日报未收录，如实标注）。已与近期日报逐项去重核对：**10/2日报已覆盖**东芝沟槽栅SiC MOSFET阈值电压漂移抑制、通用汽车+普渡大学ECCE GaN多电平+双三相PMSRm电驱、250kW双三相IPM可变幅值中间矢量调制、扁线端部绕组定子–转子集成喷油冷却、WBG逆变器轴承电压"灰箱"模型、港科大（广州）IPMSM参数鲁棒无位置传感器控制、博世SiC S-Cell，本期不重复收录；**10/1日报已覆盖**日本电产（Nidec）6,320亿日元减值、Tau Motors软件定义电驱-Tau Gamma无稀土WRSM电机、小鹏第三代HySiC混碳功率模块、峰岹科技收购Sciosense、Wolfspeed 200mm Premium SiC衬底、东芝3300V SiC模块，本期不重复收录（**尼得科出售车用电机业务**为同一公司事件线的**后续新进展**，与10/1日报所载减值事项区分，见第7条）。已严格剔除：整车发布/上市/交付量（法拉利Luce、小米Vision GT、领克/零跑、Leapmotor等）、动力电池与充换电（宁德时代匈牙利工厂试产、Gentherm电池热管理、StoreDot极速充电）、智能驾驶与域控制器（Delta+NVIDIA Hyperion）、低空经济与机器人、泛财经与无实质电驱参数的营销通稿。**另经时效性核验剔除**：Fraunhofer IZM 500kW/1L/99% SiC逆变器（2026-05）、L&T Semiconductor 1200V SiC平台（2026-09-18/23）、onsemi Embedded Power Platform及斯巴鲁评估（原始发布2026-09-16，10/2报道属**旧闻重发**）、ZF AxTrax 2电驱桥（嘉兴产线2026年6月投产）、Hyundai Mobis 160kW PE系统（2026-05-07）、Geely 16合1电驱（2026年7–8月）等**均超出48小时窗口且不属本次补遗范围**。**另经严格核实、按SOP不作定性结论**：第1条BEM性能数据为**企业自述、未经独立验证**，已如实标注，不与已核实的量产参数混同。

---

## 1. 美国初创Best Electric Machine（BEM）发布无稀土双绕组"双主动"电机性能声明：自称标称功率2×、峰值转矩最高8×，第三方分析指其未经独立验证

**分类**：技术突破/学术前沿（企业自述性能，未经独立验证）
**摘要**：美国初创Best Electric Machine（BEM）于9月30日发布其SYNCHRO-SYM架构性能声明，宣称在**完全不含永磁体**条件下，标称功率达传统"被动转子"电机**2倍**、峰值转矩最高**8倍**、恒转矩区延伸至**2倍同步速**；第三方分析机构Discovery Alert于10月3日发文对该声明的可信度与量产可行性进行了审慎解读。
**来源**：[Discovery Alert（2026-10-03）· US Startup Claims Rare-Earth-Free Motor Beats Magnets on Torque](https://discoveryalert.com/news/rare-earth-free-motors-october-2026/)（原始声明：BEM于2026-09-30发布的性能客座文章，发布方声明未独立验证）
**发布时间**：2026-09-30（企业声明）/ 2026-10-03（第三方分析）
**相关企业/机构**：Best Electric Machine（BEM，美国，CTO Frederick Klatt）；分析方 Discovery Alert；引用市场数据机构 Persistence Market Research、S&P Global Automotive Insights
**技术亮点**：
- **架构创新本质**：SYNCHRO-SYM将传统的"主动定子+被动转子"改为**定子与转子均具独立受控电磁角色**（转子侧无刷、主动励磁）；配套**BRTEC**（无刷+无位置传感器实时仿真控制）系统，据公司称可在同步速下/上/下全程稳定运行，无需滑差感应、电刷或滑环，并支持**无大容量直流母线的直接AC-AC变换**
- **量化声明（企业自述、未经独立验证）**：标称功率**2×**、峰值转矩**最高8×**（对比同封装被动转子电机）；恒转矩区**延伸至2×同步速**；公司以改装自量产标准机座的感应电机进行样机验证
- **技术阶段**：**概念验证/样机阶段**（改装现成机座验证，非专用量产设计；截至2026年10月未检索到SYNCHRO-SYM/BRTEC相关专利公开，亦无第三方或整车厂独立验证）
- **存疑提示（按SOP如实标注）**：上述倍数为公司CTO在其客座文章中发布，刊载方声明**未独立验证**；第三方分析指出主动转子路线面临**转子侧铜耗散热（旋转体内部散热难）**、**多端口控制与转子侧功率传输的额外电力电子复杂度**、**从改装感应电机到专用量产的可扩展性未证实**等风险——**本条不作"突破性结论"，仅作趋势线索记录**
- **可核实的产业背景**：无稀土EV电机市场预计由**2026年29亿美元增至2033年70亿美元（CAGR 13.4%）**；S&P Global Automotive Insights（2025-11）将**EESM（电励磁同步电机）**列为最具前景的近期替代路线；铁氧体混合与铜转子方案已实现相对参照电机**15–35%成本下降**

---

## 2. IEEE ECCE 2026在温哥华开幕（10/4–8）：电驱动议程密集覆盖高速/无轴承电机、无位置传感器控制、GaN器件、牵引逆变器优化、多相驱动与轴向磁通

**分类**：技术突破/学术成果（学术会议）
**摘要**：IEEE能源转换大会与博览会（ECCE 2026）于10月4–8日在加拿大温哥华举行；官方议程显示电驱动与电机相关专场高度密集，反映行业前沿当期聚焦**高压宽禁带、多相化、高转速、轴向磁通与热管理**等方向。
**来源**：[IEEE ECCE 2026 官方议程 Session Index](https://epapers2.org/ecce2026/ESR/session_index.php)；[ECCE 2026 About](https://www.ieee-ecce.org/2026/about-ecce/)
**发布时间**：2026-10-04（会期2026-10-04至10-08）
**相关企业/机构**：IEEE PELS/IAS；举办地温哥华会展中心（Vancouver Convention Centre）；分会主席含GM、Schaeffler、Politecnico di Torino、University of Nottingham、华中科技大学、KAIST、University of Minnesota等机构专家
**技术亮点**：
- **10月5日（会期首日）电驱动相关专场**：High-Speed and Bearingless Machines（高速与无轴承电机）、Sensorless Controls for Electric Drives（电驱动无位置传感器控制）、GaN Power Devices and Applications（GaN功率器件与应用）、AI-Enabled Modelling/Co-Simulation for Electric Machines、Battery Management System and Electric Powertrains
- **10月6–7日**：Electric Machines for Transportation and Mobility（交通与出行用电机）、NVH/Reliability and Condition Monitoring in Electric Machines、Performance Optimization of AC Drives in High Speed Operation（高速运行交流驱动性能优化）、Analysis and Optimization of Traction Inverters（牵引逆变器分析与优化）、WBG Power Devices、Control of Multi-Phase Motor Drives（多相电机驱动控制）、Axial-Flux Machines for High Power Density（高功率密度轴向磁通电机）、Wound-Field and Hybrid-Excited Synchronous Machines（绕线励磁与混合励磁同步电机）、Electric Machine Thermal Management and Cooling Technologies
- **说明**：本条为**会议议程层面**资讯（非单篇成果）；具体论文的量化指标以后续见刊/收录为准，本条不作推测

---

## 3. IEEE TTE（2026-10-01）：PMSM弱磁"自适应分频系数+参考电压"过调制策略，提升直流母线电压利用率、扩展弱磁转速–转矩包络

**分类**：技术突破/学术成果
**摘要**：《IEEE Transactions on Transportation Electrification》（2026-10-01出版）刊文提出面向**永磁同步电机（PMSM）弱磁（FW）运行**的**过调制（OVM）**策略，以"自适应分频系数（adaptive dividing factor）+参考电压过调制"提升**直流母线电压利用率**，从而扩展电机弱磁区的**转速–转矩包络**。
**来源**：[IEEE Transactions on Transportation Electrification（DOI:10.1109/TTE.2026.3692185，2026-10-01）· Adaptive Dividing Factor and Reference Voltage Overmodulation Strategy for PMSM Field-Weakening Control](https://doi.org/10.1109/TTE.2026.3692185)；[Semantic Scholar 条目](https://www.semanticscholar.org/paper/Adaptive-Dividing-Factor-and-Reference-Voltage-for-Wang-Wang/23cf23f91a23b73581a18d665cc4f85a1df1a89d)
**发布时间**：2026-10-01
**相关企业/机构**：作者 Zi-Yuan Wang、Xiao-Lin Wang、Xu-Cong Bao（具体单位以原文为准）
**技术亮点**：
- **对象与痛点**：PMSM弱磁运行时受**直流母线电压上限**约束，转速–转矩能力受限；过调制技术可提高母线电压利用率而扩展弱磁工作区
- **创新本质**：以**自适应分频系数**配合**参考电压过调制**，在弱磁工况下动态优化调制策略（相较固定参数过调制更适配母线与工况变化）
- **量化指标**：电压利用率提升具体数值、电流THD、转速/转矩包络扩展幅度等**暂未公开**（IEEE Xplore摘要受限），本条不作推测，以原文图表为准
- **技术阶段**：**建模/方法研究阶段**（同行评审期刊论文），面向车用PMSM驱动的高转速弱磁效率与出力优化
- **相对主流方案**：传统过调制多采用固定调制参数，在母线电压与负载波动时难以兼顾电压利用率与谐波；本方法以"自适应参数+参考电压调制"提升弱磁区电压利用率与边界扩展能力

---

## 4. IEEE TTE（2026-10-01）：CSI馈电PMSM系统"离散时间复数矢量双内模解耦控制（含延时补偿）"——电压环与电流环同施内模原理

**分类**：技术突破/学术成果
**摘要**：《IEEE Transactions on Transportation Electrification》（2026-10-01出版）刊文提出一种**带延时补偿的双内模（DIM）解耦控制**方法，将**内模原理同时应用于电压环与电流环**，用于**电流源逆变器（CSI）馈电的PMSM系统**，以发挥CSI固有的升压能力、友好输出电压波形与高可靠性。
**来源**：[IEEE Transactions on Transportation Electrification（DOI:10.1109/TTE.2026.3693343，2026-10-01）· Discrete-Time Complex Vector Dual Internal Mode Decoupling Control Method With Delay Compensation for CSI-Fed PMSM System](https://doi.org/10.1109/TTE.2026.3693343)；[Semantic Scholar 条目](https://www.semanticscholar.org/paper/Discrete-Time-Complex-Vector-Dual-Internal-Mode-for-An-Lu/7aaaf483fabdb1affb6ea333b594df02520d03d1)
**发布时间**：2026-10-01
**相关企业/机构**：作者 Qun-Tao An、Yu-Zhuo Lu、Xiao-Guang Zhang（具体单位以原文为准）
**技术亮点**：
- **对象与优势**：**CSI（电流源逆变器）馈电PMSM驱动**——CSI相较VSI具**固有升压能力、输出电压波形友好、可靠性高**等优势，但控制上存在耦合与延时带来的动态/稳态性能折衷
- **创新本质**：**离散时间复数矢量**框架下，将**内模原理同时施加于电压环与电流环（DIM双内模）**以实现解耦，并引入**延时补偿**改善数字控制延时对动态性能的影响
- **量化指标**：动态响应时间、电流谐波、鲁棒性边界等具体数值**暂未公开**（IEEE Xplore摘要受限），本条不作推测
- **技术阶段**：**建模/方法研究阶段**（同行评审期刊论文），面向CSI架构在车用/牵引电驱中的应用探索
- **相对主流方案**：常规VSI（电压源逆变器）驱动为主流，本方法面向CSI架构的耦合与延时问题给出"双内模+复数矢量+延时补偿"的离散化解耦控制路径

---

## 5. IEEE TPEL（2026-10-01）：基于不变流形的PMSM"无观测器"无模型预测控制——低通滤波构造约束、自适应时间常数

**分类**：技术突破/学术成果
**摘要**：《IEEE Transactions on Power Electronics》（2026-10-01出版）刊文提出一种基于**不变流形（invariant manifold）约束**、适用于**PMSM**的**无观测器有限控制集无模型预测控制（FCS-MFPC）**方案：以**低通滤波器构造约束**定义不变流形，从而规避传统超局部模型方法中复杂函数结构与多超参数的缺陷。
**来源**：[IEEE Transactions on Power Electronics（DOI:10.1109/TPEL.2026.3695904，2026-10-01）· Invariant Manifold Based Model-Free Predictive Control for PMSM Motor With Adaptive Time Constant](https://doi.org/10.1109/TPEL.2026.3695904)；[Semantic Scholar 条目](https://www.semanticscholar.org/paper/Invariant-Manifold-Based-Model-Free-Predictive-for-Luo-Luo/f49567a5f06a929384c5588c8cd6caeb6be14df2)
**发布时间**：2026-10-01
**相关企业/机构**：作者 Yi-Xiao Luo、Junqiang Luo、Jin-Cheng Yu 等（具体单位以原文为准）
**技术亮点**：
- **问题**：现有基于**超局部模型（ultra-local model）**的FCS-MFPC方法**函数结构复杂、超参数多**，且通常需要观测器，增加了系统复杂度与整定难度
- **创新本质**：提出**无观测器**的FCS-MFPC方案——利用**低通滤波器构造约束**以定义**不变流形**，并以**自适应时间常数**提高对参数/工况变化的适应性，从而简化结构、减少超参数
- **量化指标**：电流脉动、参数鲁棒性、动态响应等具体数值**暂未公开**（IEEE Xplore摘要受限），本条不作推测
- **技术阶段**：**建模/方法研究阶段**（同行评审期刊论文），面向PMSM驱动控制器的"免参数/免观测器"简化方向
- **相对主流方案**：相较依赖精确模型或多超参数的模型预测控制，本方法以"不变流形约束+自适应时间常数"降低控制器复杂度与参数敏感性，指向电驱控制算法工程化落地的简化路径

---

## 6. 【补遗】英飞凌推出XENSIV TLx49012系列自校准数字角度传感器：精度<0.1°、延迟1.5µs、ASIL B，面向汽车/工业电机控制

**分类**：技术发布（电机控制用角度/位置传感器）
**摘要**：英飞凌（Infineon）推出**XENSIV TLx49012**系列**四款基于霍尔技术的数字角度传感器**，面向汽车与工业**电机控制**应用，具备**系统级自校准**功能，可免除客户自研标定程序与外部参考编码器，直接服务无刷直流电机（BLDC）的转子位置反馈需求。
**来源**：[everything PE（2026-10-01）· Infineon Launches Self-Calibrating XENSIV Angle Sensors for Motor Control](https://www.everythingpe.com/news/details/12129-infineon-launches-self-calibrating-xensiv-angle-sensors-for-motor-control)；[MarkLines（2026-09-29）· Infineon presents XENSIV TLx49012 digital angle sensors](https://www.marklines.com/en/news/351652)；原始来源：[Infineon XENSIV TLx49012](https://www.infineon.com/part/TLE49012-S0001)
**发布时间**：2026-09-28（官方发布，**48小时窗口外补遗**，此前日报未收录）
**相关企业/机构**：Infineon Technologies AG（英飞凌）
**技术亮点**：
- **精度与延迟（量化）**：角度精度**优于0.1°**，延迟低至**1.5 µs**，适配高速、高动态电机系统的实时转子位置反馈
- **磁场与接口**：支持磁场范围**20 mT–120 mT**，兼容标准磁体配置；接口支持**SPI、ABZ、UVW、PWM**，便于集成入多种电机控制器架构
- **自校准**：**全自动初始标定+片上连续补偿**，免除客户自研标定与外部参考编码器，支持**同轴（on-axis）与离轴（off-axis）**安装，降低全生命周期（系统设计到产线EOL测试）开发成本
- **车规等级**：汽车级变体**TLE49012**符合**ISO 26262**、达**ASIL B**，满足现代汽车（含机器人）电机控制的**功能安全**要求
- **技术阶段**：**产品发布**（车规级量产级器件），面向汽车电动化提速与机器人/自动化扩张带来的BLDC位置传感需求

---

## 7. 尼得科（Nidec）寻求出售车用电机（EV motor）业务单元：涉Stellantis法国合资eMotors、欧洲约700人

**分类**：产品发布/商业动态（业务重组/退出）
**摘要**：据《Automotive News》10月2日报道，因**会计问题**及电动汽车电机业务盈利持续恶化，日本电产（Nidec）正寻求**出售其汽车电机（automotive electric motors）业务单元**；该业务与**Stellantis**在法国设有合资公司**eMotors（双方各持50%）**，生产电机、逆变器与减速器，供货BMW、Stellantis、Volkswagen等，欧洲制造基地含波兰工厂及新建塞尔维亚工厂，该业务单元**约700人**。
**来源**：[Automotive News（2026-10-02）· Stellantis, VW, BMW supplier Nidec to divest EV motor unit](https://www.autonews.com/manufacturing/suppliers/ane-stellantis-nidec-1002/)；[Automotive News Europe · Focus on Electrification](https://www.autonews.com/europe/focus-electrification/)
**发布时间**：2026-10-02（**接近48小时窗口边缘**，因当日电驱产业硬资讯稀缺、且系重大第三方电驱供应商重组事件，作宽限收录并如实标注）
**相关企业/机构**：Nidec Corporation（尼得科/日本电产，TSE:6594）；Stellantis（法国合资eMotors，50%/50%）；BMW、Volkswagen Group（客户）
**技术亮点**（商业动态，技术参数从略）：
- **事件性质**：第三方电驱供应商**业务退出/出售**；与该合资体系在法国**Tremery工厂**生产EV电机的产能布局相关
- **事件脉络**：据**10/1日报**，尼得科已于9月30日计提约**6,320亿日元**资产减值、2025财年净亏**5,646.2亿日元**（约35.9亿美元），并将EV驱动装置"E-Axle"业务由扩张转为收缩（含与中国广汽合资业务磋商撤资）；**本条为其"出售车用电机业务"的后续新进展**，与已收录的减值事项区分，非重复
- **产业影响**：在整车价格战与电驱高度自研背景下，**外资第三方电机/电驱供应商的规模经济与利润空间持续承压**，短期或加速行业资产重组、业务出售与产能整合

---

## 简要总结

- **当日最具"时效性"的新增线索是"无稀土/去永磁电机"路线的持续发酵，但需强审慎**：美国BEM的SYNCHRO-SYM"双主动"电机宣称标称功率2×、峰值转矩最高8×且完全无永磁，属**企业自述、未经独立验证**（第三方分析明确提示转子侧散热、多端口控制复杂度与量产可扩展性风险）。按SOP如实标注为"趋势线索"，**不得与已核实的量产参数混同**；可核实的产业背景是无稀土EV电机市场规模预期（2026年29亿美元→2033年70亿美元，CAGR 13.4%）与EESM被S&P Global列为最具前景近期替代路线。
- **学术前沿本期聚焦"高压高频下的调制、控制与器件"**：ECCE 2026（10/4–8，温哥华）议程密集覆盖**高速/无轴承电机、无位置传感器控制、GaN功率器件、牵引逆变器优化、多相电机驱动控制、高功率密度轴向磁通电机与电机热管理**；同期IEEE TTE/TPEL（10/1）三篇论文分别指向**弱磁区自适应过调制**（提升母线电压利用率、扩展弱磁包络）、**CSI馈电PMSM的离散复数矢量双内模解耦+延时补偿**、以及**基于不变流形的无观测器无模型预测控制**（免参数/降复杂度），共同反映电驱控制向"高压宽禁带+多相化+低复杂度免参数算法"演进。
- **器件与传感侧，电机控制链的"系统级简化"仍是主线**：英飞凌XENSIV TLx49012以**<0.1°精度、1.5µs延迟、ISO 26262/ASIL B**与**系统级自校准**，尝试免除客户标定与外部编码器，降低电机控制系统的设计-量产成本——是电驱电控"降本减复杂度"在传感器环节的体现。
- **产业动态核心特征：假期/会期叠加导致的"资讯真空"，第三方电驱供应商承压显性化**。本期7条中，国内企业动态**全部缺位（0条）**——中国国庆假期（10/1–10/7）叠加周末，头部主机厂/电驱企业无新发布，产业链媒体更新停滞于10/1；海外产业侧仅**尼得科出售车用电机业务**一条硬动态，且为10/1日报所载"减值收缩"事件的后续。已如实标注实际数量（7条）、国内0条，并明确剔除onsemi EPP斯巴鲁等**旧闻重发**与超窗条目，确保零杜撰。