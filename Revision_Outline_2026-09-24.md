# 导师稿后续完善：逐段检查与修改 outline

建立日期：2026-09-24；Figure 4 执行记录更新：2026-09-29。用途：逐段修改时使用的工作清单，不是另一版论文，也不是投稿前格式审查。Figure 4 的后续用户决定优先于本文件原有待办，见操作批次 05。

## 0. Overview：总体判断与执行边界

导师这轮修改的主要价值在于明确了全文的问题：资源持有量影响 earning–spending 的权衡，选择又改变随后决策所处的资源状态。后续工作以导师稿为基准，补齐这一叙事所需的统计、引文和方法对应关系；不重新设计故事，不因个人措辞偏好改写导师的文字。

当前最重要的工作有三项：

1. 主结果第一次在 Results 中出现时有对应的关键统计，且读者能追溯到正确的图、表和方法。
2. 删减正文中的技术枝节时，保留的补充证据仍在 SI 中可找到、可理解；Figure 4 的 coefficient-sign 分析已按后续决定删除。
3. 修复真正影响含义的错误：时间窗、拟合层级、pooled 与个体结果、图表指向、任务条件与方法实现的对应关系。

### 0.1 本清单依据的版本

- **导师稿（主要编辑基准）**：`/Users/arthurwang/.codex/attachments/6ecd9e70-15cf-4505-b5c7-7a0bfc6b2147/Pasted text.txt`。
- **此前英文稿及现有方法、表格**：`sn-article.tex`。截至 2026-09-29，Figure 4 相关部分已按用户逐项确认的取舍修改；其余部分不能据此视为已合并导师附件。
- **参考文献库**：`sn-bibliography.bib`。
- **此前讨论**：“Overall check” 最后确认并实施的方案；其早期、后来被否决的建议不重新列为任务。
- 本轮已核查文本与现有表格，未复算原始数据、未审计分析代码，也未重新逐面板核验所有 PDF。凡需这些证据的项目均列为待核对。
- 以下定位优先使用章节、段落首句、图名和 LaTeX label，避免修改后行号漂移。

### 0.2 已确定的边界

- 尽量保留导师修改；只处理明显错误、证据对应和必要补充。
- 这是 bioRxiv 草稿，不设摘要或正文长度目标，不按期刊投稿字数压缩。
- **Discussion 整体留给导师继续处理；2026-09-29 仅同步删除 Figure 4 已取消的 sign 与 offer-onset 图相关句子。**
- 保留进化意义作为动机与解释性升华。现有 `may rely on`、`suggesting` 不需要仅因推断性质而删除或弱化。
- 不添加此前已排除的 sensitivity 支线、行为竞争模型、no-bias model、后续切换预测或新实验。
- 保留现有重采样分析框架；方法中如实说明重复使用数据与推断范围，不以此要求重做整个统计体系。
- Figure 4 的 coefficient-sign 正文分析、SI 面板和对应方法已按用户决定删除；不要恢复。
- Hernádi 2015 若引用，必须明确其 spend 一次性兑现累积奖励、结束积累序列，与本任务可部分消费和保留余额不同。不得写成两者提供相同的自由 spending 能力。

### 0.3 项目标记与使用方式

- **[A 直接处理]**：我可以依据现有材料完成，不需你重新做科学判断。
- **[B 核对事实]**：需要你确认实际实验或代码实现；若后续提供代码路径，可交由我检查，不必由你手工整理。
- **[C 修改/决定]**：需要你决定呈现方式、组织图件或补充已有结果；不是默认要求新增分析。
- **[D 暂缓]**：本轮不处理，留待导师或后续阶段。

复选框表示“已实际完成并核验”，不是“已经提出方案”。除操作批次记录的工作外，原待办不能视为已执行到论文中。逐段工作时先完成 A，集中解决该段必要的 B，再处理 C；不要为等待一个未知 p 值阻塞全部文字和引用修正。

---

## 1. Title、作者信息与 Abstract

### 1.1 Title 与作者信息

**保留**：现有标题及导师新增的 Lusha Zhu 与相关单位。

- [ ] **AUTH-01 [A]** 检查作者上标与单位编号一一对应；通讯作者标识、email 和单位标识没有因 `affil*` 改动而错位。
- [ ] **AUTH-02 [B]** 最终姓名拼写、作者顺序、单位正式英文名称由作者确认。
- [ ] **AUTH-03 [C]** 在作者贡献中补上新增作者；不自行推断任何人的贡献。

**完成标准**：作者、单位和贡献信息一致；没有擅自调整署名。

### 1.2 Abstract

**该段作用**：从 money／wealth 引出一般性的资源依赖决策问题，概括任务与主要神经结果，并保留进化意义的收束。

**保留**：导师的开头、总体推进和结尾；不设置字数目标，不要求恢复旧摘要。

- [ ] **ABS-01 [A]** 只修明显语言错误，例如 `relative values of the earning and spending` 中多余的 `the`。
- [ ] **ABS-02 [A]** 核对摘要中的核心术语与 Results 定义一致：resource state 是 token holdings；relative chosen value 不是传统所选奖励的绝对价值。
- [ ] **ABS-03 [A]** 检查 `across all three regions` 的对应结果是否确实覆盖三脑区；不把某脑区更强或某个体特例改写成同等强度的普遍规律。此处先核对，不能仅凭担忧改措辞。
- [ ] **ABS-04 [A]** 摘要不添加主结果 p 值串；统计首次完整报告位置是 Results 对应段落。
- [ ] **ABS-05 [D]** 不对进化意义做额外“降调”，不引入跨物种验证作为本稿待办。

**完成标准**：保持导师摘要的故事和声音，修复语言和事实对应即可。

## 2. Introduction：按导师的四段结构检查

### 2.1 第一段：Money、wealth 与 resource state

定位：`Money is an important intermediary in our everyday economic behavior.`

**作用与保留**：用日常 earning–spending 说明为何当前持有量可能影响选择。

- [ ] **INT-01 [A]** 区分一般背景、理论预期和本文发现；保持 `may` 等已有条件性表达，不把边际效用解释改成新的实证结论。
- [ ] **INT-02 [A]** 如为边际效用论断补理论引文，从现有 `bernoulli1954exposition` 等条目选取直接相关来源；不要求常识性开头每句话都有引文。
- [ ] **INT-03 [A]** 不为了缩短而重写整段，不追加 fixation cost、动态库存等模型解释支线。

### 2.2 第二段：持续的资源—选择循环

定位：`This dependence creates a recurring computational problem.`

**作用与保留**：明确持有量影响估值和选择，而 earning／spending 又更新持有量。

- [ ] **INT-04 [A]** 保留循环作为研究问题；不把提出这一问题等同于 Results 已建立全部因果连接。
- [ ] **INT-05 [A]** 只检查与后文问题对应：状态表征、状态更新、价值表征、选择格式都有结果承接。

### 2.3 第三段：已有研究与缺口

定位：`Examining how the primate brain represents token holdings...`，包含两个 `(ref)`。

**作用与保留**：保留导师的神经研究背景和进化动机，补足论断与文献对应。

- [ ] **INT-06 [A]** 第一个 `(ref)` 按具体论断补引文：OFC offer/chosen/good-based signals 优先 Padoa-Schioppa & Assad 2006；lateral PFC/good-to-action 可核对 Cai 2014、Lin 2021；若明确保留 ACC 的特定编码主张，另配实际研究 ACC 的原始来源。不要用一篇 OFC 论文支撑所有区域。
- [ ] **INT-07 [A]** 第二个 `(ref)` 分清“持有量影响行为偏好”与“神经活动表征持有量／reference state”。Yang、Ferro 对应 gain/loss/risk 与 token-dependent signals；Nguyen 对应 reference-related encoding，不承担自由 earning–spending 行为的证据。
- [ ] **INT-08 [A]** 文献只需支撑句子实际声称的内容；先核对原文再放入 cite key，不按标题匹配后直接视为确认。
- [ ] **INT-09 [A]** 核对缺口表述是否指向本任务的 earning／partial spending 与联合价值表征，而不是误称从未发现任何资源依赖神经价值信号。仅在出现后者时做最小修正。
- [ ] **INT-10 [C]** Hernádi 2015 不强制插入 Introduction。如确需在此交代先例，引用与差别必须放在一起：一次性兑现并结束序列，与本任务部分消费、保留余额、返回 earning 不同；也不要将其奖励积累装置未经核实地写成与本任务相同的 token wallet。
- [ ] **INT-11 [A]** 不把所有既有范式统一称为固定 token threshold。Nguyen 是 instructed response task，固定 trial block 后交付奖励；具体范式分别描述。

### 2.4 第四段：本任务与研究问题

定位：`Here we developed a new earning–spending task...`

- [ ] **INT-12 [A]** 保留跨 trial 持有、可部分 earning／spending、自主停止及无固定兑换阈值的描述。
- [ ] **INT-13 [A]** 核对 `continuous` 指持续演化的资源状态，而非 token 数值在数学上连续；通常无需专门改写，避免引入无意义的术语争论。
- [ ] **INT-14 [A]** 保留问题式的 `how ... transformed`，不因提出机制问题本身而削弱引言；只确保结尾摘要性陈述与实际结果一致。
- [ ] **INT-15 [A]** 修空格、标点和引用格式，不恢复旧版大段脑区功能罗列。

**本章完成标准**：两个 `(ref)` 已解决，先例与本任务区别明确，导师四段叙事基本不变。

## 3. Results 2.1：Resource state shifts earning–spending preferences（Fig. 1）

### 3.1 第一段：任务简述

**保留**：fixation earning、不同 earning rate／water amount、跨 trial token holdings。

- [ ] **BHV-01 [A]** 统一单位为 `tokens s^{-1}` 或全文一致的形式；客观 \(V_{Earn},V_{Spend}\) 与主观 \(V_E,V_S\) 不混用。
- [ ] **BHV-02 [B]** 核对最低 spending 档位：W/U 与 T 实际水量不同，图上 `0,1,2,4` 是档位、归一化值还是实际定量尺度？正文、Fig. 1B 和 Methods 必须能互相解释。
- [ ] **BHV-03 [A]** 原稿中已定义 initial successful choice、边界排除等；确认 Results 简述不与其冲突，不把 Methods 全搬进正文。

### 3.2 第二段：offer 与 holdings 对选择的影响

定位：`The initial choice on each trial revealed two consistent behavioral patterns...`

- [ ] **BHV-04 [A]** 保留两个主要观察：offer 条件效应，以及相同 offer 下 holdings 增加时 earning 倾向降低。
- [ ] **BHV-05 [B]** 查明该核心行为效应是否有现成的对应检验、效应量和分析输出。若有，首次陈述处补报；若仅为曲线描述，列出统计缺口，不拿模型参数检验替代行为效应检验。
- [ ] **BHV-06 [A]** Figure 1B/C 颜色排序保留 illustrative 性质，不升级为计算出来的价值比例或每个条件严格排序。

### 3.3 第三段：非参数权重

定位：`This state-dependent shift in choice is consistent with diminishing marginal utility...`

- [ ] **BHV-07 [A]** 保留 `consistent with`；拟合权重的变化用于描述相对 earning/spending 倾向，不写成行为已唯一确定两类绝对效用各自的变化。
- [ ] **BHV-08 [A]** 不给非参数模型强加独立 bias 或新 baseline，不新增 sensitivity 结果。
- [ ] **BHV-09 [A]** 图注准确说明非参数权重；不以正文需要“统计”之名给每条拟合曲线都加检验。

### 3.4 第四段：参数模型、泛化与 RT

- [ ] **BHV-10 [A]** 保持 \(\Delta V\) 的统一含义：\(\Delta V=V_E-V_S\)；进入 sigmoid 的量是 \((\Delta V-b)/\gamma\)。实际排版使用 LaTeX 符号，见文末统一表。
- [ ] **BHV-11 [B]** 确认 held-out session 的预测指标、比较对象和已有统计；sigmoid 是模型定义，不能仅用“呈 sigmoid”作为独立验证。
- [ ] **BHV-12 [B]** 核对 session-wise alpha 的统计。现稿 alpha 上界为 1，已有 TODO 指出对边界值直接作 signed-rank test 的问题。确认后再决定报告描述性分布还是保留有依据的推断；不自行重启整套模型比较。
- [ ] **BHV-13 [B]** RT 起止事件必须确认：是否包含获得首个 token／water 所需 fixation 时间？若包含，不可直接称为纯决策时间。核对排除规则、median ties、统计单位及现有检验。
- [ ] **BHV-14 [C]** 将模型泛化／RT 中实际用于主结论的关键指标和 p 值补在首次陈述处；辅助结果留 SI。
- [ ] **BHV-15 [C]** 修改 Fig. 1E 实际 artwork 横轴为 \((\Delta V-b)/\gamma\)，现有 TODO 不能仅靠改图注解决。

**完成标准**：行为发现、拟合解释和验证证据分得清；所有关键数值有来源，图示与实际任务条件一致。

## 4. Results 2.2：Distributed prefrontal tuning（Fig. 2）

### 4.1 第一段：从行为到状态表征、五组划分

- [ ] **TUN-01 [A]** 保留对数式分组及其已有 numerical magnitude 引文；五组边界在正文、图注和 Methods 一致。
- [ ] **TUN-02 [B]** 若保留“keeping trial counts more comparable”，核实这是分组依据或实际结果；不凭对数分组本身推断 trial counts 均衡。

### 4.2 第二段：选择性与代表单元

- [ ] **TUN-03 [A]** 修 `We observed a significant proportion of neurons ... encoded`、`firing in when`、`preferred number ... were` 等明确语法问题。
- [ ] **TUN-04 [B]** 补各脑区 selective units 数量、有效分母、比例和检验。“每个 neuron 的回归显著”不等于“选择性比例显著高于机会水平”；确认导师这句实际指哪种结论。
- [ ] **TUN-05 [A]** 若只有单元选择性检验，改成准确报告选择性数量／比例，而非无依据地写 population proportion 显著；无需另加检验才能保留本段。
- [ ] **TUN-06 [A]** 示例与 Fig. 2A–D 对齐，preferred-state distribution 对应 E。

### 4.3 第三段：调谐形状

- [ ] **TUN-07 [A]** 修 `neurons tuning functions`；保留 recentering 的解释及 shuffle control。
- [ ] **TUN-08 [A]** 将支持主文调谐形状主张的关键统计从图注整理到 Results 首次报告处，保留正确比较：相对距离 ±1 与 ±2，而非 Gaussian fit 的显著性。
- [ ] **TUN-09 [B]** 当前图注的 p 值为 ACC 3.31×10^-41、DLPFC 2.50×10^-36、OFC 2.32×10^-36；使用前核对其样本单位、合并方式与实际检验。数值已见于稿件，不代表代码已验证。
- [ ] **TUN-10 [A]** `Gaussian-like` 作为形状描述保留，不写成已进行 Gaussian 模型选择；`homogeneous tuning profiles` 若仅指对齐后的形状相似，不让它误指所有神经元具有相同偏好。

**完成标准**：比例、调谐形状与 shuffle 的统计分别对应各自结论。

## 5. Results 2.3：Temporal dynamics and updating（Fig. 3）

### 5.1 第一段：cross-temporal decoding

- [ ] **UPD-01 [A]** 保留导师对不断 earning/spending 所需状态跟踪的引入。
- [ ] **UPD-02 [A]** 给 ACC 区域优势恢复明确的 offer-onset epoch 限定。导师移动句子后，两个 p 值容易被误解为专指 offer 前活动。
- [ ] **UPD-03 [B]** 核对 ACC–DLPFC 6.60×10^-34 与 ACC–OFC 7.20×10^-34 的具体来源：矩阵哪些 entries、汇总方法、观察单位、配对、单双侧、校正。三处重复 TODO 合并成一个源头说明，再同步回引用处。
- [ ] **UPD-04 [A]** `stable` 指跨时间泛化的编码关系，不指 holdings 或群体活动数值不变化；只有读者可能误解时补一个短限定，不扩展解释。
- [ ] **UPD-05 [A]** pre-offer 可解码与 wallet 在 ITI 可见不矛盾，不将其单独解释为纯内部记忆证据。

### 5.2 第二段：update trajectories、双向标准及个体

- [ ] **UPD-06 [A]** 保留 earning 正向／spending 负向的联合标准，不将单方向显著等同于双向 updating。
- [ ] **UPD-07 [A]** 首次报告 ACC／OFC 满足标准时补关键统计。现有 `tab:supp_state_updating` 提供 pooled p 值：ACC earning 1.70×10^-15、spending 1.10×10^-6；OFC earning 2.00×10^-18、spending 6.50×10^-13。正式落稿仍需 UPD-09 的检验配置对应。
- [ ] **UPD-08 [A]** 修复笼统的个体一致性：ACC 的 W/T、OFC 的 W/U/T 满足双向标准；DLPFC pooled 不满足，但 U 满足。建议只明确 ACC/OFC 在相应个体中重复，DLPFC 个体差异引用表格。
- [ ] **UPD-09 [B]** 核对 updating regression 中 W 是 pre-update 还是 post-update、准确 QR 顺序、p 值推断单位及 correction。
- [ ] **UPD-10 [A]** shuffle 结果准确写为“不满足双向标准”；不能写成所有 shuffle 条件、所有方向均不显著，现有表中有孤立单方向显著。
- [ ] **UPD-11 [A]** 保留 `could influence subsequent value coding and decision making` 的可能性表述，不要求为这句话增加后续行为预测分析。

**完成标准**：时间范围与 pooled/individual/shuffle 三个层次不混淆。

## 6. Results 2.4：Resource-state modulation of offer value（Fig. 4）

**本节是核心结果；完善重点是证据对应，不是增加分析数量。**
**2026-09-29 后续决定覆盖本节旧待办**：不恢复 coefficient-sign 分析；nested-model 只呈现 wallet update，不加 offer-onset 附图；geometry 句删除 `monotonically` 与 `non-monotonic`。已执行内容和未完成核验见操作批次 05。

### 6.1 第一段：问题、模型预测与代表单元

- [ ] **VAL-01 [A]** 保留导师的开头和 model→neuron 组织，仅将容易混成因果事实的 `model suggested that ... caused` 改为清晰的模型预测表达。
- [ ] **VAL-02 [A]** Fig. 4A/B 明确 model-derived；不要求行为图必须已经证明所有预测几何性质。
- [ ] **VAL-03 [A]** 代表单元句旁增加一句中性 SI 引用，覆盖 coefficient-sign 面板，不恢复已被导师删除的整段分析。
- [ ] **VAL-04 [A]** 可用的桥接草案：`Representative neurons and complementary analyses of joint tuning characterized how offer attributes and resource state were represented by individual neurons (Supplementary Fig. X).` 使用前按最终面板范围替换 X；这句不声称所有结果均符合预测。
- [ ] **VAL-05 [C]** SI 中新增短补充结果，具体安排见第 11 节；保留图及正负结果。

### 6.2 第二段：nested-model comparison

- [ ] **VAL-06 [A]** 修 `representatioin`、`DLFPC`。
- [ ] **VAL-07 [A]** 修分析层级：Methods 是逐 unit 拟合 M1/M2，再汇总 per-unit 增量。导师句子的 `at the population level` 改为 `across neurons` 等准确短语；与下一段 population geometry 分开。
- [ ] **VAL-08 [A]** 将统计主张精确写为 observed ΔR²adj 相对 value-label-shuffled increment 的比较，而非含糊地称 M2 显著优于 M1。
- [ ] **VAL-09 [A]** 删除错误的 `tab:supp_choice_conditioned` 指向：它是 choice-conditioned TDR 表，不含本分析统计。
- [ ] **VAL-10 [B]** 查找真实 nested-model 输出：各脑区有效 units、检验时间窗、增量汇总值、p 值、shuffle 次数/范围、跨时间校正。不能从曲线星号反推数值，也不能拿 choice-conditioned 表的 p 值填入。
- [ ] **VAL-11 [C]** 根据已有输出决定正确统计载体：现成附图/表可容纳则使用；否则补一张紧凑统计表。主文仅报支持核心主张的关键结果，不把全部 windows 搬入段落。
- [ ] **VAL-12 [A]** 保留 VS 不能做同类增量检验的简短说明：它的状态成分被 baseline state terms 吸收。详细共线性解释留 Methods。
- [ ] **VAL-13 [A]** 不将这个检验概括为已证明某种唯一乘性机制，也不因此削弱“非加性 earning-offer/state 成分”的对应结论。

### 6.3 第三段：TDR geometry

- [ ] **VAL-14 [A]** 修复 `how this state dependence neural geometry` 缺谓语、`state-dependence structure` 等明确语言错误。
- [ ] **VAL-15 [A]** 保留模型预测与 aspect ratio 的解释，但不把 ratio 增大自动等同于 earning-axis compression；两轴分量在 SI 中支持具体解释。
- [ ] **VAL-16 [B]** 核对三脑区实际曲线及已有定量比较。此前正文写 ACC 单调、DLPFC/OFC 较弱且非单调；导师写 `also evident`。若图仍是前者，仅补一个最小的区域强度/形态限定，不恢复长篇讨论。
- [ ] **VAL-17 [B]** 确认 geometry 是否有正式 state-trend 或 real-versus-shuffle 检验。没有就保持描述性结论，不为了“每段有 p 值”临时制造显著性主张。
- [ ] **VAL-18 [B]** 核对 representative/best-bootstrap 图的选择规则，确保图注说明展示与统计汇总的关系；不能让单次展示代替跨迭代结果。
- [ ] **VAL-19 [B]** 核对最低 spending 档位排除规则，尤其 monkey T 不是字面上的 zero water；统一到真实筛选条件。
- [ ] **VAL-20 [A]** 保留本节围绕 wallet update。offer-onset 对照留 SI，不将本节改成两个阶段并重的故事。

**完成标准**：模型、单元增量、群体 geometry 各有清楚角色；核心增量统计可追溯，SI 单元证据有入口。

## 7. Results 2.5：Decision-related value representations（Fig. 5）

### 7.1 第一段：从 offer value 到选择相关表示

- [ ] **CHV-01 [A]** 修 `a mechanism that how...`，并用短语明确此处转向 offer-aligned evaluation；避免把上一节 wallet-update 信号直接当成本次初始选择的已证实输入。
- [ ] **CHV-02 [A]** 保留 ΔV 系数符号分析作为 single-unit encoding 的检验。结论限定为未支持占主导的相反方向联合调谐，不扩展为“PFC 无法比较价值”。

### 7.2 第二段：choice-conditioned encoding

- [ ] **CHV-03 [A]** 修 `example neuron show`；example A/B、population C 对应正确。
- [ ] **CHV-04 [A]** 保留“在可辨认该信号的条件下更强”等已有限定，不强制三脑区对所有变量都有同样结果。
- [ ] **CHV-05 [B]** 从 `tab:supp_choice_conditioned` 提取支持主句的 ΔR²、检验和 p 值；区分 matched-choice advantage 的检验与相对 choice-shuffle 的检验，两者不互相代替。
- [ ] **CHV-06 [C]** 主文选最必要比较；全部脑区、猴及 shuffle 继续放表。

### 7.3 第三段：relative chosen value 定义、编码与区域分布

- [ ] **CHV-07 [A]** 保留 task-specific, bias-adjusted relative chosen-value 定义，公式 \(V_{Chosen}=c(\Delta V-b)\)，允许为负。
- [ ] **CHV-08 [A]** 不改名、不新增 no-bias comparison；2006 研究是相关编码先例，不声称两项研究变量定义相同。
- [ ] **CHV-09 [A]** 修 `These strength of representation` 等语法。
- [ ] **CHV-10 [A]** 保留 `ACC showed little VE encoding during offer evaluation` 的阶段限定，不能误扩展到 wallet update。
- [ ] **CHV-11 [B]** 若保留三脑区 pooled `VS > VChosen > VE`，核对每个不等号的实际比较；主文给必要统计或清楚的范围摘要，完整表保留。
- [ ] **CHV-12 [B]** 区域间强弱比较使用 `tab:supp_r2_by_variable`，区域内变量比较使用 `tab:supp_r2_by_area`，不得对调。

### 7.4 第四段：时间顺序

- [ ] **CHV-13 [A]** 修 `For signals that we could estimate latencies`；保留“可估计的信号”限定。
- [ ] **CHV-14 [B]** 核对 onset 与 t50 各自支持哪些比较；选实际支持核心陈述的结果，不把两指标混成单一一致排序。
- [ ] **CHV-15 [A]** 对完整排序未同样清楚的脑区加一个短限定，尤其 ACC offer-onset VE；不恢复不必要的长篇防御性文字。
- [ ] **CHV-16 [A]** 保留 `consistent with` 和 `potential intermediate` 的解释，不要求新增因果实验。

**完成标准**：variable definition、choice conditioning、编码强度与时间关系不混为一项证据。

## 8. Results 2.6：Good-based and action-based choice（Fig. 6）

### 8.1 第一段：任务选择与眼动坐标

- [ ] **CHO-01 [A]** 保留导师的动作切入与 DLPFC/OFC 示例。
- [ ] **CHO-02 [B]** 核对 left/right 是屏幕坐标、相对于 trial 初始 gaze 的相对方向，还是分析中另有定义；Methods 中目标相对 gaze 布置，术语应与实际编码一致。

### 8.2 第二段：群体坐标与编码强度

- [ ] **CHO-03 [A]** 修 `right)and`。
- [ ] **CHO-04 [A]** 轨迹指向 C，encoding trajectories/strength 指向 D；导师新增的 C,left 不能替代 D 的编码强度证据。
- [ ] **CHO-05 [A]** 首次报告 OFC ES 优势、DLPFC LR 优势时补关键强度和 p 值，完整数据引用 `tab:supp_choice_strength`。
- [ ] **CHO-06 [B]** 当前 pooled 表中 OFC ES-vs-LR p=2.64×10^-34，DLPFC p=1.37×10^-33；核对统计配置及效应量后使用，不将这些重采样分布 p 值解释成独立动物层面的检验。
- [ ] **CHO-07 [A]** 分清区域内 ES/LR 偏好与某信号跨区域最强两类比较。`strongest in OFC/DLPFC` 若保留，应有对应跨区域证据，不直接用区域内比较替代。

### 8.3 第三段：是否有稳定时间优势

- [ ] **CHO-08 [A]** 保留无一致时间优先级的结论；不将不显著写成等效或同时发生。
- [ ] **CHO-09 [A]** 各种时序 p 值继续放表；正文无需为一个“未见稳定排序”的概括列出所有两两检验。

### 8.4 结尾

- [ ] **CHO-10 [C]** 导师已经压缩的总结可保留；若逐段改后与上一段重复，再决定删或并，不预先要求改动。

## 9. Discussion

- [ ] **DIS-01 [D]** 整体讨论仍留给导师；Figure 4 对应段落已因删除 sign 分析和取消 offer-onset 图而做最小同步修正，见操作批次 05。
- [ ] **DIS-02 [D]** 本清单完成后，可把“新增 SI 引用位置、图号变化”等信息交给导师；不现在改其段落。

## 10. Methods：按实际方法顺序核对

**原则**：保留读者理解主结论必需的变量、模型、窗口、统计单位和训练/测试关系；实现细节留 SI。不是按主图/附图机械划分，也不为字数进行大规模搬移。

### 10.1 Subjects、装置、任务、training、recording

- [ ] **MET-01 [B]** 伦理委员会正式英文名称及 protocol number；与 declarations 一致。
- [ ] **MET-02 [B]** 实际 reward 档位、每猴水量、token 边界、earning/spending 时间、initial successful choice 定义、trial-end 规则与图示一致。
- [ ] **MET-03 [A]** 核对记录数与样本覆盖：ACC 仅 W/T；DLPFC/OFC W/U/T。每项分析实际纳入数与总 recorded units 区分。
- [ ] **MET-04 [B]** 如称 single units，核对现有 spike sorting/质量筛选文字是否如实反映使用标准；只补已有事实，不预设需要重新 spike-sort。

### 10.2 Behavioral modeling

- [ ] **MET-05 [A]** 非参数与参数模型分开：非参数无独立 bias；参数模型中的 b、gamma、alpha 等定义保持一致。
- [ ] **MET-06 [A]** fixed-alpha=1 对应 linear utility/constant marginal utility，不写 linear marginal utility。
- [ ] **MET-07 [B]** 拟合约束、reward normalization、LOSO 留出单位、优化目标与代码一致；alpha 边界问题见 BHV-12。
- [ ] **MET-08 [B]** RT 的事件与统计配置见 BHV-13；Methods 给精确定义，Results 再选择正确名称。

### 10.3 Preprocessing 与通用 TDR

- [ ] **MET-09 [B]** 核对单位筛选、active epochs、平滑核与时间对齐，尤其 causal kernel 的使用与 latency 定义一致。
- [ ] **MET-10 [B]** 分别核对 unit sampling、train/test trial partition、test-trial resampling 是否 replacement，及分析专属例外；不能一个 with/without 统管所有步骤。
- [ ] **MET-11 [A]** 保留 pseudo-population 与迭代复用原始数据的说明，不将 iteration 数当动物/session 数。
- [ ] **MET-12 [B]** 若重复 update 来自同一 trial，确认实际分割单位及窗口重叠情况，并如实描述；重叠本身不被列为推翻结果的理由，也不默认要求重分析。
- [ ] **MET-13 [B]** 各模型的回归变量、ridge 使用、QR 顺序以及 target placed last 的实施与文字一致。
- [ ] **MET-14 [A]** 通用算法只定义一次，特定分析只写差别；避免重复叙述出现不一致。

### 10.4 Cross-temporal、updating、latency

- [ ] **MET-15 [B]** cross-temporal 区域比较配置与 UPD-03 共同核对；用同一记录解决所有重复 TODO。
- [ ] **MET-16 [B]** 更新 W 时点、QR、单方向检验和双向标准与 UPD-09 共同核对。
- [ ] **MET-17 [B]** latency 五个连续 samples 实际对应多少 ms；起始阈值、有效估计比例、无效迭代处理、onset 与 t50 的计算明确。

### 10.5 Nested model、geometry、joint encoding

- [ ] **MET-18 [B]** nested shuffle 在 unit 内如何置换、保留何种 strata、次数与 time-window correction；与 VAL-10 的统计记录统一。
- [ ] **MET-19 [A]** M1 state-independent predictors 与 M2 新增 VE 的定义不混；state indicators、choice covariate 的含义写清。
- [ ] **MET-20 [B]** geometry 九条件、三 state groups、回归/投影/平均窗口、截尾 range、ratio 及 representative bootstrap 规则与实现一致。
- [ ] **MET-21 [B]** coefficient-sign 分析究竟使用哪些 value predictors、时间窗、unit 筛选和检验；SI 结果描述不能自行切换到另一组系数。

### 10.6 Relative chosen value 与 choice format

- [ ] **MET-22 [B]** VChosen 单元选择性 shuffle 哪些 labels、是否联合置换、在何种 strata 内执行；保留真实次数。
- [ ] **MET-23 [A]** choice-conditioned TDR 对应 Fig. 5C，joint dynamics 对应 D–F；检查是否还有旧引用残留。
- [ ] **MET-24 [B]** choice strength/latency 的单位、配对、单双侧、校正如实报告。若与当前图注不同，先查代码再统一，而非凭方法偏好改检验。

**完成标准**：每项主结果都能找到其变量、数据单位、窗口、检验和图表；未知处有明确待核对项，不以猜测填平 TODO。

## 11. Supplementary Information：跟随主文的补充证据链

**2026-09-29 更新**：Figure 4 的 coefficient-sign 图和补充结果已取消；该图的 SI 保留代表单元、wallet-update nested-model 个体曲线，以及 geometry 的分量、shuffles 和个体结果。下表和 11.2--11.3 中与此冲突的旧条目以操作批次 05 记录为准。

### 11.1 推荐组织顺序

| SI 内容组 | 对应主文 | 承担的任务 | 文字需求 |
|---|---|---|---|
| Behavioral-model controls | Fig. 1 | 泛化、session 参数、RT | 简述比较目的与主要结果，完整算法留 SI Methods |
| Recording coverage and resource tuning controls | Fig. 2 | 记录覆盖、调谐 shuffle | 图注足以解释的部分不再重复 |
| Individual resource dynamics and update tests | Fig. 3 | 个体结果与方向性 control | 简短指出 pooled 与个体的关系和例外 |
| Representative units and nested-model individuals | Fig. 4 | OFC 代表单元及 wallet-update 个体曲线 | 图注说明 A--C；不再包含 coefficient-sign 面板 |
| Geometry components, shuffles and individuals | Fig. 4 | 两轴分量、ratio、controls | 解释 ratio 来源和区域差异，避免罗列每条曲线 |
| Value-difference / relative chosen-value controls | Fig. 5 | 单元结果、choice conditioning、详细强度与时序 | 给读者需要的定义与适用范围 |
| Choice-format comparisons | Fig. 6 | 区域内/跨区域、个体与不同 latency 指标 | 一句概括无稳定时序，其余表格承载 |

### 11.2 Coefficient-sign 图与短补充结果

**已取消**：用户决定删除 Figure 4 coefficient-sign 分析，不再执行 SI-01--07；SI 图原 D 已改为 C。

- [ ] **SI-01 [A]** 保留现有 sign panels，正文入口按 VAL-03/04 设置。
- [ ] **SI-02 [A]** 小节标题可用 `Joint tuning to offer attributes and resource state`。
- [ ] **SI-03 [B]** 写目的前核对模型与 coefficient 定义；明确它检验 tuning signs 的关联，而不是直接测量 sensitivity 随 holdings 的变化。
- [ ] **SI-04 [A]** 结果完整交代 spending 的预期同号关联，以及 earning 的预期异号关联未达到显著；使用实际 p 值和 unit counts，不用一句“符合模型”包办。
- [ ] **SI-05 [A]** 保留可能的敏感性解释：earning-value neurons 较少可能限制该 sign-based analysis；使用 `may`，不当成确定原因。
- [ ] **SI-06 [A]** 用一两句说明 sign association 与 nested-model increment 检验不同性质，前者的 earning 阴性不直接否定后者；不声称 nested model 修复或验证了 sign 结果。
- [ ] **SI-07 [A]** 图注说明面板、系数、n、检验及标记；解释放补充结果，完整实现放 SI Methods，避免三处复制同一段。

### 11.3 两阶段与 geometry 附图

**已取消 SI-08**：不恢复 offer-onset 并列面板；仅展示 wallet update。geometry 已改用 Choice FR 重跑。

- [ ] **SI-08 [C]** 从绘图源码恢复 offer-onset 和 wallet-update 并列 nested-model 面板，保留 matched-event control。
- [ ] **SI-09 [C]** 核心 nested/geometry 个体结果覆盖所有有记录动物：ACC W/T，其余 W/U/T。不要求所有辅助分析都逐猴复制。
- [ ] **SI-10 [A]** 图件更新之后才定 panel letters、caption 与引用，不用文字宣称尚未出现在图里的 panels 已完成。
- [ ] **SI-11 [A]** 保留 component ranges，不能仅凭 aspect ratio 为某一轴的变化归因。
- [ ] **SI-12 [A]** 所有保留附图/表都应至少有明确正文或 SI 文字入口；检查“孤立图”和指向已删除面板的引用。

### 11.4 SI Methods 与现有表

- [ ] **SI-13 [A]** 保留实施参数、优化细节、专属 controls 和完整比较；主 Methods 保留决定主结论如何产生的核心定义。
- [ ] **SI-14 [A]** 建立一次性 analysis configuration 表，至少列 event alignment、fit/projection/statistics window、sample unit、resampling 数、QR 顺序和 shuffle。各值先从稿件整理，未知标待代码确认。
- [ ] **SI-15 [A]** 表中 `<`、`>`、`~` 的含义保持准确：非显著不是等效，均值排序不是所有相邻/非相邻比较都显著。
- [ ] **SI-16 [A]** mean±SD across resamples 与 SEM/CI 分开；不把 SD 改名为 confidence interval。

**完成标准**：主文每项核心结果有紧凑的 SI 支撑路径；sign 分析不孤立，也不重新占据主文。

## 12. 参考文献、图注与全文一致性

### 12.1 可以直接修的 bibliographic 项目

- [ ] **REF-01 [A]** Ferro 条目从预印本更新为正式发表：Nature Communications 17, 7554 (2026)，DOI `10.1038/s41467-026-70423-1`。cite key 可以暂时保留原 key，以免产生无意义的全篇替换。
- [ ] **REF-02 [A]** Nguyen DOI 更正为 `10.1073/pnas.2514110122`，文章号 `e2514110122`；补全正式作者列表并核对卷期。
- [ ] **REF-03 [A]** 检查新增 cite keys 全部存在；导师注释保留的旧段落里的引用不算活跃正文已引用。
- [ ] **REF-04 [A]** Hernádi 的文献论断按 INT-10 执行，不以“首次自由 spend”之类宽泛表述取代任务差别。

本轮对照过的原始来源入口：

- Ferro 正式版：https://www.nature.com/articles/s41467-026-70423-1
- Nguyen 正式全文：https://pmc.ncbi.nlm.nih.gov/articles/PMC12685095/
- Padoa-Schioppa & Assad 2006：https://www.nature.com/articles/nature04676
- Yang 2022：https://www.nature.com/articles/s41467-022-28278-9
- Hernádi 2015 原研究记录：https://pubmed.ncbi.nlm.nih.gov/25622146/

这些入口不代表本清单中的每个候选论断都已逐句验证；正式插入引用时仍按 INT-08 对齐。

### 12.2 图注处理原则

- [ ] **CAP-01 [A]** 主结果首次在 Results 报关键统计，图注保留理解图必需的 n、误差条、检验、单双侧、校正与标记说明。
- [ ] **CAP-02 [A]** 完整 p 值可留补充表，不要求每个 p 值都写进图注，也不机械删除图注中仍有用的数值。
- [ ] **CAP-03 [A]** 核对图中指标与措辞：本文某些 TDR 指标是 squared Pearson correlation，不自动等同于一般意义的 out-of-sample explained variance；与 nested-model adjusted R² 区分。
- [ ] **CAP-04 [A]** W/U/T 命名、颜色、单位、时间零点、面板号、窗口与正文及 Methods 一致。
- [ ] **CAP-05 [C]** 图件实际更新后重新编译并目视核验，尤其 Fig. 1E 和两阶段附图。本次只创建 outline，尚未进行该步骤。

### 12.3 统一符号表

| 量 | 定义/使用原则 |
|---|---|
| Token holdings / resource state | 任务中当前 token 数；方法明确各 event 取值时点 |
| \(V_{Earn}\) | 客观 earning rate |
| \(V_{Spend}\) | 客观 spending reward 属性，需说明档位与实际给水映射 |
| \(V_E,V_S\) | 模型主观 earning/spending values |
| \(\Delta V\) | \(V_E-V_S\) |
| 选择概率的输入 / Fig. 1E 横轴 | \((\Delta V-b)/\gamma\) |
| \(V_{Chosen}\) | \(c(\Delta V-b)\)，c=+1 earn、−1 spend |
| RT difficulty proxy | \(\left|(\Delta V-b)/\gamma\right|\) |
| Nested increment | \(\Delta R^2_{adj}\)，M2−M1 |
| TDR encoding metric | 按实际定义注明 squared Pearson correlation，避免与 nested metric 混用 |

## 13. 容易遗漏但重要的收尾

- [ ] **END-01 [A]** 开始实改时先明确编辑基准，避免只修改旧 `sn-article.tex` 而漏合并导师稿；合并时保留导师措辞，不把注释掉的旧段落当活跃正文。
- [ ] **END-02 [A]** 引文/交叉引用自动检查只能发现 label 缺失，不能发现“引用存在但内容不对”；必须保留本清单中语义核对。
- [ ] **END-03 [B]** 发出 bioRxiv 版本前确认伦理、Funding、Acknowledgements、Competing interests、作者贡献及 Data/Code availability 的真实内容。可延后填写，但不能发布 `Please provide...` 占位。
- [ ] **END-04 [C]** 数据/代码何时公开、放何处由你和合作者决定，不自动上传或公开。
- [ ] **END-05 [A]** 编译后核对 figure/table 编号与 SI 独立编号；源文件更改不意味着现有 PDF 已同步。
- [ ] **END-06 [D]** 不新增字数、期刊模板、投稿 display item 数或强制拆 SI 等要求。是否拆文件按草稿管理需要决定。

## 14. 首批可执行项与待你核对的信息包

### 14.1 我可以先完成，不依赖代码的项目

1. 导师文字的明确拼写/语法修复清单与逐句替换稿。
2. Introduction 两处 `(ref)` 的论断—来源映射，bib 元数据修正。
3. 两处已确定的图表引用错误，及其余交叉引用语义核对。
4. 从现有图注/表提取主结果统计并标明来源，不推断缺失数字。
5. coefficient-sign 的正文桥接与 SI 补充结果框架，待真实统计填入。
6. 将重复 Methods TODO 汇总成一份实际配置核对表。

### 14.2 优先需要你提供或允许从代码定位的信息

| 优先顺序 | 所需信息 | 解决哪些条目 |
|---|---|---|
| 1 | Nested-model 统计输出与绘图源码位置 | VAL-09–11、MET-18、SI-08 |
| 2 | Cross-temporal 区域比较的计算位置 | UPD-02/03、MET-15 |
| 3 | 各 TDR 的抽样、分割、QR、W 时点及 latency 实现 | UPD-09、MET-10/12/13/16/17 |
| 4 | 行为主要效应、LOSO、alpha session 图及 RT 的输出/代码 | BHV-05/11–14 |
| 5 | Sign 分析的系数定义、计数和检验输出 | MET-21、SI-03/04 |
| 6 | 最低 spending 档位与 geometry 条件筛选 | BHV-02、VAL-19 |

无需一次性整理所有信息。逐段修改时，只处理对应条目的依赖；代码路径比口头回忆更适合解决实现问题。

### 14.3 每段完成后的固定核验

- [ ] 导师原意是否保留？改动是否只为纠错或必要完善？
- [ ] 主张对应的是观察、模型预测还是解释？
- [ ] 主结果首次出现的统计是否有真实来源？
- [ ] 图、表、面板和方法是否指向同一分析？
- [ ] 时间阶段、脑区、pooled/个体和分析单位是否一致？
- [ ] 被移入 SI 的内容是否仍可找到、可理解？
- [ ] 是否误引入已排除的新分析或 Discussion 改写？

完成上述检查即可推进下一段；不为追求“所有问题一次解决”反复改写导师已经定下的叙事。


---

# 第二部分：已执行的具体修改操作

> 前面的第 0–14 节保留为原始 outline；其未勾选框表示原始计划状态。本部分按实际执行批次记录完成内容，后续修改继续追加，不能将原始 outline 中的所有项目视为已完成。

## 操作批次 01｜2026-09-24｜Introduction 引用补充

### 1. 本轮依据、文件及边界

- 授权依据：用户确认 Cesarini、Vanags 放在第一段最后一句；核查 Harvey 后决定是否同处加入；确认 Bernoulli、Mangel–Clark、DLPFC 组合；OFC 三篇均引；ACC 采用 Cai 2012＋Kennerley 2009；拒绝三篇 scarcity/poverty 综述；要求保留导师措辞并记录具体修改。
- 导师措辞来源：`/Users/arthurwang/.codex/attachments/6ecd9e70-15cf-4505-b5c7-7a0bfc6b2147/Pasted text.txt` 中未注释的四段 Introduction。
- 对照材料：`/Users/arthurwang/Downloads/PhD_Thesis/Tex/Chap_1_Intro.tex`、`/Users/arthurwang/Downloads/PhD_Thesis/Biblio/ref.bib`，以及核查过的原始出版来源。
- 修改文件：`sn-article.tex`、`sn-bibliography.bib`、本操作记录；重新编译生成 `sn-article.pdf` 及其辅助文件。
- 编辑开始时，主文件仍为旧版三段 Introduction，因此先仅合入导师的四段引言，再添加本轮确认的引用。没有将导师附件的 Abstract、作者信息、Results 或 Discussion 等其他部分合入。
- 两份 PhD_Thesis 附件和导师附件均未修改。

### 2. 第一步：核查 Harvey 2022，并决定加入第一段末句

核查来源：[Harvey & Blake, 2022，原始论文](https://pmc.ncbi.nlm.nih.gov/articles/PMC9515640/)，DOI `10.1098/rspb.2022.0712`。

- 正确书目信息：Teresa Harvey、Peter R. Blake；*Proceedings of the Royal Society B: Biological Sciences*，289(1983)，20220712。
- 研究包括 194 名 4–10 岁儿童，比较收益／损失及不同奖励规模下的风险选择，并测量家庭 SES 和主观社会地位。
- 收益情境中的 SES 差异支持 developmental risk sensitivity theory：低 SES 儿童更区分高低奖励，并在高奖励条件下比高 SES 儿童更倾向风险选项；损失情境未完全符合任一理论。
- 判断：可以作为资源背景与决策偏好相关的补充证据，同 Cesarini、Vanags 放在第一段总括句末。它不是对当前持有量的直接操纵，也不直接检验 earning–spending；这些边界记录于此，不为此增加或改写导师正文。

### 3. 第二步：仅合入导师四段 Introduction

在 `sn-article.tex` 的 `\section{Introduction}\label{sec1}` 与 `\section{Results}\label{sec2}` 之间，以导师四段原文替换旧版三段正文。

- 保留 money／wealth 开头、资源—选择循环、进化动机、已有研究与研究问题，以及第四段任务概述。
- 不恢复附件中以 `%%` 注释的旧稿段落。
- 除下表的引用插入、删除两个 `(ref)` 占位、清除行末空格，以及将第四段 `actions.   Together` 之间的三个空格统一为一个外，不更改导师词句。
- 用自动文本对照确认：去除新增 `\cite{...}` 和导师原文的 `(ref)`，归一化空白后，四段文字与导师原文完全一致。

### 4. 第三步：逐处插入引用

本轮共设置 **7 处引用、17 篇不同文献**。

| 操作 | 精确位置（导师原文） | 加入的文献与 cite key | 对应内容 |
|---|---|---|---|
| 4.1 | 第一段 `...less valuable when they are abundant` 后、逗号前 | Bernoulli 1738/1954：`bernoulli1954exposition` | 边际效用递减的理论来源；仅对应这一分句 |
| 4.2 | 第一段最后一句 `...the resource state in which those opportunities are evaluated` 后、句号前 | Cesarini 2017：`cesarini2017effect`；Vanags 2025：`vanags2025greater`；Harvey & Blake 2022：`harvey2022developmental` | 财富冲击与劳动供给、收入／财务状况与亲社会偏好、儿童 SES 与风险选择；三篇均放在同一句末 |
| 4.3 | 第二段 `Resource state thus influences valuation and choice, while earning and spending update the resource state itself` 后、句号前 | Mangel & Clark 1986：`mangel1986unified`；Mangel & Clark 1988：`mangel1988dynamic` | state-dependent decision framework；不将本文说成检验了长期最优策略或多步规划 |
| 4.4 | 第三段已有神经信号句中的 `orbitofrontal cortex (OFC)` 后 | Padoa-Schioppa & Assad 2006：`padoa-schioppaNeuronsOrbitofrontalCortex2006b`；Padoa-Schioppa & Conen 2017：`padoa-schioppaOrbitofrontalCortexNeural2017`；Ballesta 2020：`ballestaValuesEncodedOrbitofrontal2020a` | OFC offer/chosen value、所选物品；综述；价值与选择的因果证据 |
| 4.5 | 同一句中的 `dorsolateral prefrontal cortex (DLPFC)` 后 | Cai & Padoa-Schioppa 2014：`cai2014contributions`；Lin 2020：`lin2021evidence` | 物品域选择结果与动作计划、动作域奖励概率／价值计算 |
| 4.6 | 同一句中的 `anterior cingulate cortex (ACC)` 后 | Cai & Padoa-Schioppa 2012：`caiNeuronalEncodingSubjective2012`；Kennerley 2009：`kennerleyNeuronsFrontalLobe2009b` | ACC chosen value／chosen juice／运动方向，以及多决策变量相关价值编码；移除该句原有 `(ref)` |
| 4.7 | 第三段 `...token holdings and other wealth-like reference states` 后、句号前 | Yang 2022：`yangPrimateAnteriorInsular2022c`；Ferro 2026：`ferroAccumulationVirtualTokens2025a`；Nguyen 2025：`nguyenNeuralRepresentationDecisional2025a`；Seo & Lee 2009：`seo2009behavioral` | token-dependent behavior 和神经 holdings/reference-state 表征；替换第二个 `(ref)` |

补充解释，仅用于记录引用范围：

- Cesarini 提供彩票财富冲击对 earnings 的证据；Vanags 是 80,337 人、76 国的收入／financial well-being 与亲社会偏好及行为关联研究；Harvey 是儿童 SES 相关研究。三者不是同一种测量或因果设计。
- Cai 2012 支持 ACC 的 chosen value／choice，不据此声称该实验观察到了 individual offer-value 编码。
- Cai 2014 的时序为 offer 已呈现、动作目标尚未呈现时的物品域选择结果，随后出现空间／动作信号；不沿用中文附件中“选项尚未呈现”的概括。
- Nguyen 支持 reference-related 神经表征，不承担自主 earning–spending 行为的证据。
- 第四段不加外部引用；conserved 句不加 Chen 2006。
- 未加入 Haushofer & Fehr 2014、Haushofer & Salicath 2023、de Bruijn & Antonides 2022；未加入 Balewski 2023、Hernádi 2015 等未获本轮选用的补充引用。现有 bibliography 中不再用于引言的条目未批量删除。

### 5. 第四步：修正已有 bibliography 条目

保留已有 cite key，避免破坏 Results／Discussion 中对同一文献的引用；年份以条目内部 `year` 字段为准，key 中的旧年份不影响排版。

| 条目 | 实际修改 | 核查来源 |
|---|---|---|
| `cesarini2017effect` | 标题由 `...Evidence from swedish lottery winners` 改为正式标题 `...Evidence from Swedish Lotteries`；期号 6→12；页码 1298–1331→3917–3946；补 DOI `10.1257/aer.20151589`；统一作者缩写标点 | [AER](https://doi.org/10.1257/aer.20151589) |
| `vanags2025greater` | 作者由 Edgars Vanags、Jennifer Cutler、Fabian Kosse、Paul Lockwood 修正为 Paul Vanags、Jo Cutler、Fabian Kosse、Patricia L. Lockwood；期号 1→2；文章号 pgae003→pgae582；补 DOI `10.1093/pnasnexus/pgae582` | [PNAS Nexus](https://doi.org/10.1093/pnasnexus/pgae582) |
| `harvey2022developmental` | 第一作者 Hannah J. Harvey→Teresa Harvey；期号 1976→1983；期刊名补全 `: Biological Sciences`；补 DOI `10.1098/rspb.2022.0712`；文章号保留 20220712 | [原文](https://pmc.ncbi.nlm.nih.gov/articles/PMC9515640/) |
| `seo2009behavioral` | 错误 DOI `10.1523/JNEUROSCI.4157-08.2009`→`10.1523/JNEUROSCI.4726-08.2009` | [原文](https://pubmed.ncbi.nlm.nih.gov/19295166/) |
| `ferroAccumulationVirtualTokens2025a` | `@misc`→`@article`；2025 bioRxiv 更新为 2026 *Nature Communications* 17:7554；预印本 DOI／URL 换成正式版 `10.1038/s41467-026-70423-1`；移除原 `publisher = Neuroscience`；Hayden 补中间名缩写 Y.；保留 key | [正式出版页](https://www.nature.com/articles/s41467-026-70423-1) |
| `nguyenNeuralRepresentationDecisional2025a` | DOI `10.1073/pnas.2414538122`→`10.1073/pnas.2514110122`；文章号 e2414538122→e2514110122；补期号 48；将 `Nguyen, D. and others` 补全为 Duc Nguyen、Erin L. Rich、Joni D. Wallis、Kenway Louie、Paul W. Glimcher | [PubMed](https://pubmed.ncbi.nlm.nih.gov/41284894/) |
| `cai2014contributions` | 补 DOI `10.1016/j.neuron.2014.01.008`，其余信息不变 | [Neuron 原文](https://pmc.ncbi.nlm.nih.gov/articles/PMC3951647/) |

`lin2021evidence` 的 `year` 原本已是 2020，因此没有改成 2021，也未仅为统一命名而更换 key。Bernoulli、OFC 三篇、ACC 两篇和 Yang 的条目本轮未改写。

### 6. 第五步：新增两条 Mangel–Clark 文献

- `mangel1986unified`：Mangel, Marc & Clark, Colin W. (1986). *Towards a Unified Foraging Theory*. **Ecology 67(5):1127–1138**. DOI [10.2307/1938669](https://doi.org/10.2307/1938669)。标题依据原论文 PDF；出版社网页题名存在 `Unifield` 拼写，不照搬该网页错误。
- `mangel1988dynamic`：Mangel, Marc & Clark, Colin W. (1988). *Dynamic Modeling in Behavioral Ecology*. **Princeton University Press, Princeton, NJ**. DOI [10.2307/j.ctvs32s5v](https://www.jstor.org/stable/j.ctvs32s5v)。使用 `@book` 条目。

### 7. 第六步：核验与编译

已执行并通过：

1. 导师文本对照：移除 citation 命令和占位、归一化空白后，四段导师原文一致。
2. 修改范围对照：`sn-article.tex` 中 Introduction 之前及 Results 标题之后的源文本与修改前完全一致。
3. 引言结构与引用：4 段、7 处 citation、17 个不同 cite key；两个 `(ref)` 均已移除；所有 key 均存在，无重复 bibliography key。
4. 通过 `latexmk -pdf -interaction=nonstopmode -halt-on-error sn-article.tex` 完成 BibTeX 与 LaTeX 多轮编译；返回成功，输出 **41 页 `sn-article.pdf`**。
5. 最终编译日志无 undefined citation／reference；BibTeX 无警告或错误。
6. 仍有字体替换、underfull box、PDF 书签及 Results 图件略高于页面的排版警告（图件超高 0.77106 pt）；本轮未改相关章节或图件。没有宣称完成全文视觉审校或数据／统计复核。

本批次完成的是 Introduction 引用落实和相关书目信息修正。前半部分 outline 中的 Results、Methods、SI、作者信息及其他待办均不因本次编译而视为已完成。

---

## 操作批次 02｜2026-09-25｜Fig. 1 相关 Results、图注与 SI

### 1. 编辑范围与依据

- 本轮实际修改 `sn-article.tex`；此前已完成的 Introduction 和 bibliography 修改保留。
- Results 第一节此前仍是旧版文字。本轮先合入导师附件中 `Resource state shifts earning--spending preferences` 的四段正文，再落实下面的已讨论修改；不合入其他 Results 小节或 Discussion。
- 核对依据：导师稿、现有图注，以及用户提供的 `bhv_summary_first_choice.m`、`bhv_model_validation_first_choice.m`、`extract_rt_deltaV_stats.m`，并追读其调用的 `mdl_full_param.m`、`mdl_obj_val_diff.m`。本轮未执行 MATLAB、未重拟合、未复算 p 值。
- 用户确认：图中 0/1/2/4 仅为示意；真实 reward 按第二小 reward amount 归一化。RT 为 offer onset 至 target fixation onset 的时间，覆盖所有 recording sessions。
- 用户已更新 `BHV.pdf` 和 `SM_BHVSummary.pdf`，并确认不再修改 artwork。已目视核查两张独立图件；剩余表述通过图注与 SI 同步，最终处理见第 5 节。

### 2. 已完成：正文与符号

| 状态 | 位置／原文 | 实际修改 |
|---|---|---|
| [x] | Fig. 1E 与 Results 的 `(Delta V-b)/gamma` | 引入简写 `\widetilde{\Delta V}=(\Delta V-b)/\gamma`；原始 `\Delta V=V_E-V_S` 定义保留。RT 使用绝对值 `|\widetilde{\Delta V}|` |
| [x] | earning/spending rate 单位 | 统一为 `tokens/s`，包括 Fig. 1、行为 Methods 及 Fig. 4 图注的同一单位；Fig. 4 其余内容不变 |
| [x] | `weights of earning options decreased ... spending options increased` | 两处趋势各加 `generally`；不展开曲线例外 |
| [x] | `This account generalized to held-out sessions...` | 明确 free-alpha 相比 fixed-alpha 的 held-out loss 较低，加入 W/U/T 的 n=52/63/64、p=4.20e-10/7.20e-12/3.50e-12 及双侧 Wilcoxon signed-rank 检验 |
| [x] | 同句的 session-wise fits | 单列一句说明跨 session 的 fitted utility curvature 稳定性，报告 median alpha=0.73/0.81/0.79，指向补图 B |
| [x] | 行为正文及补图标题中的 `decision time` | 统一为 `reaction time` |

### 3. 已完成：Fig. 1 图注

| 状态 | 面板 | 实际修改 |
|---|---|---|
| [x] | B | 不再将 0/1/2/4 写成实际实验水量；明确 schematic labels，并指向 Methods 的实际设置及归一化 |
| [x] | C | 明确 initial successful choice、holdings 1--24；补充颜色越浅表示 holdings 越高 |
| [x] | E | 定义 `\widetilde{\Delta V}`；补充每个显示的 condition-state 组合至少 5 observations；沿用 C 的条件与 holdings 配色 |
| [x] | E | `Dashed curves are logistic fits` 改为 `Dashed curves show the model-predicted choice probabilities`，与代码直接绘制 sigmoid 的实现一致 |

### 4. 已完成：Supplementary Methods 与行为补图图注

- [x] Session-wise alpha：明确展示 across-session stability，保留拟合范围 [0,1]、bin width=0.05 与中位数说明；删除要求另作／解释对 1 检验的 TODO。
- [x] 补图 B：明确稳定性目的；删去末句 `Estimates below 1 correspond to diminishing marginal utility`，保留分布与中位数。根据更新后的 Density 纵轴，将图注及 Supplementary Methods 同步为 `probability-density histograms`。
- [x] RT 定义：offer onset 到 initially selected target 的 fixation onset；不将 token event 当 RT 终点，不写入减 50 ms 的实现细节。
- [x] RT 范围：所有 recording sessions、有效 initial choices、holdings 1--24。
- [x] RT 分组：每只猴独立取 difficulty 中位数，hard 为 at or below median，easy 为 above median；补充固定正 gamma 下使用 `|Delta V-b|` 与标准化绝对值分组等价。
- [x] RT 筛选：分组后排除 RT >700 ms；区分统计筛选范围与显示范围 100--500 ms。
- [x] RT 检验：明确每只猴合并 trials 的双侧 Wilcoxon rank-sum，SI 简述没有显式建模 within-session dependence；删除原待核对 TODO，不要求本轮新增分析。
- [x] 补图 C：补充颜色变浅代表更高 holdings；保留现图 `% Earning` 标签，图注明确其显示 0--1 proportions，1 对应 100%。
- [x] 补图 D：同步 RT 定义、分组边界、筛选／显示范围和检验单位；保留已有 p 值，U 写为 below numerical precision。

### 5. 已完成：更新后图件核查与最终处理

- [x] Fig. 1E 已使用 `\widetilde{\Delta V}`，未加绝对值，与图注一致；移除源文件中等待修改横轴的 TODO。
- [x] Fig. 1B 保留 `Value ratio`；图注已说明 illustrative 性质，不再要求增加图内标签。
- [x] Fig. 1B 保留 `token/s`；与图注、正文中的 `tokens/s` 含义相同，不要求为单复数重做图件，也不额外添加解释性图注。
- [x] 行为补图 A/B 已统一为 Monkey W/U/T，样本数分别为 52/63/64。
- [x] 行为补图 B 已去掉 alpha 检验的 p 值，保留样本数、分布及中位线；median 数值由图注提供。图注和 SI 已同步 density 表述。
- [x] 行为补图 C 不再要求修改 `% Earning` artwork；图注明确：`Ordinates labeled “% Earning” display proportions on a 0–1 scale (1 corresponds to 100%).`
- [x] 行为补图 D 已有 `RT (ms)`，原 `p=0.0e+00` 已删除；统计结果仅在图注报告即可。补图 A 图内 p 值也已移除，对应数值仍在正文／图注保留。
- [x] 两张独立 PDF 已完成目视核查，未见明显文字遮挡或裁切。本批次不再保留要求用户继续修改 artwork 的待办。
- [ ] 合入整篇论文后的最终页面排版检查尚未执行；这与独立图件内容核查分开记录。

### 6. 核验与完成边界

1. 已按修改前源文件逐段检查 diff；正文改动局限于 Results 第一节、Fig. 1 图注、行为 SI 与单位同步。其余 Results 正文、Introduction、Discussion、bibliography 未在本轮改写。
2. 已运行 `pdflatex -draftmode -interaction=nonstopmode -halt-on-error`，在临时目录完成源文件编译检查，返回成功；没有更新工作区 `sn-article.pdf` 或其编译辅助文件。
3. 已完成用户更新后两张独立图件的视觉核查及最终图注／SI 同步；未重新生成工作区论文 PDF，整篇页面排版尚未核查。
4. 本批次记录覆盖前文行为条目中的旧待办：不再要求为 Fig. 1C 的描述性趋势另加检验、不要求新增 alpha 显著性检验、不继续追问用户已确认的 RT 起止／session 范围，也不新增绝对效用或曲线例外讨论。


---

## 操作批次 03｜2026-09-25｜Fig. 2 正文、图注与 resource-state SI

### 1. 编辑依据与边界

- 本轮修改 `sn-article.tex` 和本日志。Results 2.2 此前仍为旧版；先合入导师附件中 `Distributed prefrontal tuning represents current resource state` 的三段正文，再落实用户确认的四项文字修改。
- 核对代码：`/Users/arthurwang/Downloads/Project code/src/tuningCurve/analyzeTokenEncoding.m`。仅阅读实现；未运行 MATLAB、未复算统计、未改代码或 artwork。
- 用户决定：不新增分析，不要求补 trial counts 或真实与 shuffle 的比例比较；保留导师的分组理由、Gaussian-like 和现有图件布局。
- shuffle 汇总和沿用原始 preferred group 的细节放 Supplementary Methods；主图和 SI 图注只保留 `dark bars show shuffle estimates`。

### 2. 已完成：正文

| 状态 | 原文／位置 | 实际修改 |
|---|---|---|
| [x] | `We observed a significant proportion of neurons across all three regions encoded token number.` | 改为 `Neurons in all three regions showed significant selectivity for token holdings.`，对应逐单元选择性检验，不声称 population proportion 经过显著性比较 |
| [x] | `maximal firing in when`、`preferred number of tokens were distributed`、`neurons tuning functions` | 修正为 `maximal firing when`、`preferred token-holding levels were distributed`、`neurons' tuning functions` |
| [x] | `This graded decline disappeared ... indicating that it did not arise solely from selecting and aligning response peaks` | 改为分别报告真实数据与 shuffle 内部的 ±1 vs ±2 比较，不声称两者差异经过直接检验 |
| [x] | 真实数据统计 | 正文加入 ACC p=3.31e-41、DLPFC p=2.50e-36、OFC p=2.32e-36，Wilcoxon rank-sum tests |
| [x] | 非显著 shuffle 统计 | 按用户要求在正文同样报告 ACC p=0.934、DLPFC p=0.792、OFC p=0.816，保留 Supplementary Figure 的自动引用 |

### 3. 已完成：图注与 Supplementary Methods

- [x] Fig. 2E 和 SI 图 A：百分比明确为 analyzed units 中具有 resource-state selectivity 并归入相应 preferred group 的比例；不写成 selective units 内部百分比。
- [x] Fig. 2F–H：补充负向调谐先翻转、再 min–max normalization、最后按 preferred group 平均。
- [x] 主图与 SI 图注同步将 shuffle 结论写为对应距离比较不显著；保留三个已有 p 值。
- [x] Supplementary Methods：纠正 `their mean selective proportion and peak-aligned curves defined the null estimates`；明确比例平均十次 permutations，群体调谐曲线及对应检验使用第一次 permutation。
- [x] Supplementary Methods：记录 shuffle 柱按真实数据中的 preferred group 汇总各 unit 的十次显著频率，分母为对应脑区全部 analyzed units。图注不展开此细节。

### 4. 核验与完成边界

1. 已核对修改前后 diff；改动仅涉及 Fig. 2 对应 Results、主图注、resource-state Supplementary Methods 和对应 SI 图注。其他 Results、Introduction、Discussion 与 bibliography 未修改。
2. 已在临时目录运行 `pdflatex -draftmode -interaction=nonstopmode -halt-on-error`，成功完成编译检查。仍有字体替代及 underfull 排版警告；本轮未进行最终页面视觉验收。
3. 未更新工作区 `sn-article.pdf`、独立图件及编译辅助文件。
4. 本批次落实已确认的文字方案，不将此前建议的新增比例检验、trial-count 报告、单猴面板扩充或代码修改列为必做事项。
5. 数值沿用现稿，未重新核算；先前发现的 SI artwork OFC shuffle 标注 0.815 与文字 0.816 的差异，本轮未擅自改图或改数值。现有 ±1/±2 检验仍为代码中的响应点合并比较；本轮文字修改不代表重新验证其推断假设。


---

## 操作批次 04｜2026-09-28｜Fig. 3 区域比较表与 resource-state dynamics

### 1. 新增统计表与来源

- [x] 在 Supplementary Fig. 4（个体 cross-temporal 矩阵）之后、原 Supplementary Table 1（updating tests）之前插入 `tab:supp_state_decoding_regions`。新表为 Supplementary Table 1，原 updating 表及其后续表格顺延；正文均用自动引用。
- [x] 按 Supplementary Table 4 的九列布局整理 Offer onset、Wallet update 两个同 epoch 象限及 Pooled/W/U/T。每个脑区报告矩阵位置的 $R^2$ mean±SD；三组比较报告 p 值，并按胜出脑区着色，显著值加粗，非显著值用浅色；ordering 按均值排序，以 `>` 表示相邻比较显著，以 `~` 表示不显著。ACC 在 U 无记录，留空。
- [x] 数值逐项取自 `figures/SM4-Token/CrossDecoding_QuadrantSummary.svg`；核对生成代码 `Downloads/Project code/src/dynamics_TDR/TDR_CrossDecoding_Token.m` 的 `plotQuadrantSummaryTable`：先按十次 resampling 对各矩阵位置取均值，再对 offer 14×14 或 wallet 10×10 个位置计算 mean±SD；脑区间对应位置做双侧 Wilcoxon signed-rank，未做多重比较校正。表注说明时间位置共享数据和相邻时间窗，不能当成独立动物或 session。
- [x] 保留主图与 SI 矩阵图；quadrant summary SVG 仅作为新表数据来源，不另插入论文。

### 2. Fig. 3 对应文字同步

- [x] Results 2.3 合入导师对持续 earning/spending 的引入，删去非重点的 pre-offer decodability 句；将 `significant decoding was concentrated near the temporal diagonal` 改为强度沿对角线最强的描述。ACC 对比值及其准确范围指向新表。
- [x] 更新结果正文补 ACC/OFC pooled 的两个方向 p 值；删去笼统的个体一致性断言，个体与 shuffle 细节交给 Supplementary Table；shuffle 仅声称没有一个 control 满足双向标准。
- [x] Fig. 3A 图注增加区域比较表入口；Fig. 3C 图注增加个体与 shuffle 表入口，符号与现有 artwork 一致改用 $\beta$；SI 个体矩阵图注不再称 independently resampled real/shuffle iterations 为 matched samples；updating 表注简短交代 ACC W/T、OFC W/U/T 与 DLPFC U。
- [x] Methods 增加 within-epoch 区域比较的观察单位、矩阵范围、配对和未校正信息；区分 token 五组与 value tertiles；按代码补 updating 的 pre-update token、`[V_E,V_S,Choice,Token]` QR 顺序、五组时间斜率及 resampling 检验单位。

### 3. 核验边界

- 表中数值来自现成 SVG 与生成代码，未重跑 MATLAB 或原始神经数据。跨脑区 p 值的观测单位是相关的矩阵时间位置，保留其描述范围，不将其解释为跨独立动物或 session 的推断。
- 本批次不修改 Fig. 3 或 SI Fig. 4 的 artwork，不新增跨 epoch 的比较，也不新增独立的 SI Results 段落。
- 已在临时目录完成 `pdflatex` 编译及新表所在页面的视觉检查：新表无溢出、无裁切，自动编号为 Supplementary Table 1；原 updating 表顺延为 Supplementary Table 2。工作区既有 `sn-article.pdf` 未更新。
- 按用户后续版式要求，Supplementary Table 1 的 epoch 名称在第一列分别拆为 `Offer / onset` 与 `Token / update` 两行；三个均值列只显示脑区名，$R^2$ 的定义留在表注；非显著 p 值统一为黑色，不再使用浅色。

## 操作批次 05｜2026-09-29｜Fig. 4 正文、图注、SI 与图件同步

### 1. 用户确定的呈现边界

- 保留导师稿 model→代表单元→nested model→population geometry 的推进；开头不强调 earning values `converge` 或 spending values `increase`。
- 删除 Fig. 4 的 coefficient-sign 正文分析、SI 面板与对应方法；不恢复 sign 分析的 SI Results。此决定覆盖原 VAL-03--05 和 SI-01--07。
- nested-model 引入不用 `heterogeneous`、`at the population level` 或 `in each neuron`；正文称 shuffled-$V_E$ control，图注和 Methods 说明新增 $V_E$ predictor 如何打乱。
- 只展示 wallet-update nested-model 及 geometry，不增加 offer-onset 并列面板；此决定覆盖原 SI-08。geometry 使用用户重跑的 Choice FR 图件，并按用户的事件定义称 wallet update。
- geometry 结果句不使用 `monotonically` 或 `non-monotonic`；结论保留资源状态对 ACC、DLPFC、OFC 的广泛、分布式影响。

### 2. 已执行到 `sn-article.tex`

- [x] Results 2.4 首段合入导师的简短模型预测与代表单元结构，移除 coefficient-sign 分析；nested-model 句直接引出分析，并将统计主张写为观测增量相对 shuffled-$V_E$ control 的比较。
- [x] geometry 句改为 `The aspect ratio increased with resource state in ACC and showed a weaker tendency to increase in DLPFC and OFC.`；收束句点名 ACC、DLPFC、OFC 的 distributed influence，不添加区域连接的机制主张。
- [x] 主图及 SI 图注将最低水量档位写为 `the lowest spending-reward condition`，不再泛称 zero reward；Fig. 4C 的个体结果引用从 SI 图 D 改为 C。
- [x] SI 单元图注与新 artwork 对齐：A/B 为代表单元，C 为 wallet-update 个体 nested-model 曲线；删除已不存在的 sign 面板描述及恢复两阶段图的旧 TODO。
- [x] 删除仅服务于 Fig. 4 offer-value/token coefficient-sign 分析的 `Joint-encoding analysis` Methods 小节；保留 Fig. 5 的 $V_E$/$V_S$ joint encoding 分析。
- [x] Nested-model Methods 按提供的 `modelComparison_time.m` 说明：逐 unit 将新增 $V_E$ predictor 在所有有效事件间置换一次，baseline predictors 和 firing rates 不变；逐 100-ms bin 比较观测与打乱的 per-unit $\Delta R^2_{adj}$，未做跨 bin 校正。图注相应写明 paired two-sided Wilcoxon signed-rank test across units。
- [x] Discussion 中仅删除已取消的 sign 证据、offer-onset 比较及其旧 TODO；其余 Discussion 留待导师处理。

### 3. 图件与核验

- [x] 用户更新的 `SM_OfferValueSingleUnit.pdf` 已无 sign 面板；用户再次更新后，图上的 `Monkey W` 已核实正确。`ValueModulation.pdf`、`SM_OfferValueGeometry.pdf` 已替换为 Choice FR 重跑版本。上述 PDF 由用户提供，本批次未改绘图数据。
- [x] 在临时目录编译 `sn-article.tex` 成功，目视检查论文第 7、32、33 页：主图与 SI 图完整，Supplementary Fig. 5 的 A/B/C、Figure 4C 到 SI C 的引用、Supplementary Fig. 6 均对应。编译没有 undefined reference/citation；既有 Fig. 3 浮动体过高警告与本批次无关。已将核验后的编译结果同步至工作区 `sn-article.pdf`。
- [ ] 新版图中的 geometry 数值与显著性尚未从重跑输出逐项核对；当前 Results 保持描述性，不新增具体 p 值。nested-model 各区有效 unit 数、窗口汇总值与 p 值仍需从输出记录，不能从曲线标记反推。
- [ ] `Downloads/Project code/src/regression/modelComparison_time.m` 的绘图标题仍有 `Money W` 字符串；用户交付的 SI PDF 已修为 `Monkey W`，以后从该源码重新导图前需同步改源标签。

## 操作批次 06｜2026-09-29｜Fig. 5 正文与 SI 图注

### 1. 用户确定的呈现方式

- 以导师稿的四段叙事为基准：从 offer-value representations 转向决策，随后讨论 choice-conditioned encoding、相对 chosen value 与时间顺序；只修明确语法和证据对应。
- $\Delta V$ 系数符号结果限定为 single-unit tuning 未支持占主导的相反方向联合调谐；不推断 PFC 不能比较价值，也不否认 population 层面可能存在 value-difference 表示。
- 正文报告 pooled 与 choice-label-shuffle 的关键结果，用跨区范围和最大/最小 $p$ 值压缩呈现；个体结果及全部精确数值留 Supplementary Table。不能把表内各自对零的检验解释成 real-versus-shuffle 直接检验。
- 保留 pooled $V_S>V_{Chosen}>V_E$，个体例外交给表格。时间顺序保留导师的 overall-consistent 判断，以 stable latency estimates 作短限定；具体反例放 onset 补表表注。

### 2. 已执行到 `sn-article.tex`

- [x] Figure 5 Results 四段合入导师的开头、choice 引入、代表单元 A/B 分开引用、relative chosen-value 引入、pooled 强度与区域描述、时间顺序框架；修 `a mechanism that how`、`example neuron show`、`These strength of representation` 等语法。
- [x] Choice-conditioned 段补 pooled $V_E$ 的 $\Delta R^2=0.037$--$0.209$（all $p\leq1.18\times10^{-11}$）及 $V_S$ 的 $0.123$--$0.299$（all $p\leq2.67\times10^{-18}$），说明对 100 次 resamples 的单侧 Wilcoxon signed-rank 检验。
- [x] 同段写明 choice-label shuffle 后 $V_E$ 优势不再显著（all $p\geq0.091$），$V_S$ 优势仍显著但观测 $\Delta R^2$ 较小（$0.041$--$0.070$，all $p\leq3.18\times10^{-12}$）。较小仅是表值的描述性比较；未声称 real-versus-shuffle 差异显著。
- [x] 保留 $V_{Chosen}=c(\Delta V-b)$、可为负的相对优势定义。pooled 强度排序指向区域内比较表，区域分布指向跨区域比较表，并明确个体结果在同一补表中。
- [x] 时间句采用 `For signals with stable latency estimates` 和 `overall consistent`；onset 补表表注列出 pooled ACC $V_E$ 的例外（79% valid，$168.7\pm119.8$ ms，晚于 $V_{Chosen}$ 的 $118.4\pm60.2$ ms，$p=7.65\times10^{-3}$）。
- [x] Supplementary Fig. 中 panel A 保留 offer onset 与 wallet update 两列；panel B 图注明确为 offer evaluation、offer onset 后 0--500 ms。依据 `VE_VS_interaction.m` 与 `analyzeVChosenEncoding.m` 的数据读取和分析窗口核对。

### 3. 核验边界

- 数字逐项对照现有 Supplementary Tables 与提供的三个 MATLAB 脚本；未运行 MATLAB、未复算数据或重新生成 Figure 5／SI PDF。
- Choice-conditioned 检验在各自 real/shuffle 数据中比较 $\Delta R^2$ 与零；shuffle 后 $V_S$ 仍显著，不把 choice-label shuffling 写成完全消除 choice dependence。
- 脚本中的 latency 过滤允许有估计值但波动较大；`stable` 是解释结果适用范围的文字限定，并非新增数值阈值。
- 已在临时目录通过 `pdflatex -draftmode -interaction=nonstopmode -halt-on-error` 源文件编译检查，未更新工作区 PDF。`git diff --check` 仅报告此前 Fig. 1、Fig. 2 两行已有的行尾空格；本批次编辑的 Figure 5 行未引入新的空格问题。

---

## 操作批次 07｜2026-09-29｜Fig. 6 正文、主图图注与 choice-format 方法

### 1. 用户确定的呈现边界

- 保留导师稿 Figure 6 正文的动作切入、DLPFC/OFC 代表单元、TDR 群体轨迹、无一致时序优先级的推进；根据用户再次检查的证据，仅调整结尾的跨脑区 `strongest in OFC/DLPFC`：不再声称同一 choice coordinate 在某脑区跨动物最强。
- 保留脑区内偏好：DLPFC 的 left/right action 相对 earning/spending choice 更强，OFC 的 earning/spending choice 相对 left/right action 更强。OFC Monkey W 的两类信号均弱、脑区内比较不显著；由现有 Supplementary Table `tab:supp_choice_strength` 如实呈现，不在正文显眼处单列例外。
- ACC 的较弱 choice signals 和相对 earning/spending 偏好留在结果段；`In summary` 只总结 OFC 与 DLPFC 的阳性坐标偏好，不提 ACC。
- 用户更新后的 `Choice.pdf` 仅有 A--C；导师决定删除原 Fig. 6D 的 $R^2(t)$ 曲线。主图展示代表单元和二维轨迹；编码强度的定量证据由现有 SI 强度表承载。新提供的跨脑区强度 SVG 不加入论文，也不新增 Figure 6 专属 SI 图。

### 2. 已执行到 `sn-article.tex`

- [x] Results 最后一节合入导师动作切入及两段主体措辞；修 `right)and`，C 面板分别指向 OFC 右、DLPFC 中、ACC 左。将 `encoding trajectories` 补为 `encoding trajectories and strength comparisons`，并以一句简短的 Supplementary Table 引用承接强度证据；不再引用已删除的 D。
- [x] 保留导师关于没有一致时序优先级的完整段落与四张 SI 时序表的自动引用。结尾改为 `In summary, these results identify a regional difference of choice representation, with OFC preferentially representing earning/spending choice and DLPFC preferentially representing left/right action.`
- [x] Figure 6 图注删除 `(D) Temporal encoding strength`，保留与新版 A--C 图件对应的代表单元和轨迹说明；没有改 `Choice.pdf` 图件。
- [x] 对照用户提供的 `TDR_VL_VR_VE_VS_token_choiceLR_choiceES.m` 实际赋值与执行代码，而非过时注释：choice-format TDR ridge $\lambda=1$，100 次 resampling，每个 choice-label group 每次抽取 75 个 held-out trials。主 Methods 两处原 $\lambda=5$ 同步为 1，并给通用 300-trial 描述补 Figure 6 例外。
- [x] Choice-format Methods 补 QR 顺序 `$[V_L,V_R,V_E,V_S,W,Choice_{LR},Choice_{ES}]$`、left/right 为被选选项屏幕侧、0--500 ms 平均 $R^2$、强度及有效时序分布的双侧 Wilcoxon rank-sum、重采样迭代作为检验单位。保留并收窄 TODO，后续 Methods 专项仍需核对完整配置、生成输出与多重比较处理；本轮不宣称完成方法审计。

### 3. 证据边界与后续核对

- 新跨脑区 SVG 的 pooled 行显示 ES 的 OFC 与 LR 的 DLPFC 优势，但个体排序不稳定（ES：Monkey W 的 ACC 高于 OFC；LR：Monkey W 的 ACC、Monkey U 的 OFC 高于 DLPFC）。因此不以 pooled 排序维持旧的跨脑区 `strongest` 结论。
- 脑区内表 `tab:supp_choice_strength` 支持 pooled DLPFC LR>ES 和 pooled OFC ES>LR；OFC Monkey W 的 ES/LR 比较不显著。表仍在 SI，未新增跨脑区表。
- 用户提供的 MATLAB 脚本默认可加载缓存；本轮读取代码但未运行 MATLAB，也未逐项核对当前 `Choice.pdf` 和 SI 数值表的生成缓存。保留 Methods TODO 供后续专项检查。
- 已目视核查用户更新的独立 `Choice.pdf`：A/B 代表单元、C 三脑区轨迹，未见 D 面板；未修改该 PDF。`sn-article.tex` 在临时目录通过 `pdflatex -draftmode -interaction=nonstopmode -halt-on-error` 源文件编译检查；未重编工作区正式 PDF 或完成合入后的整篇页面视觉验收。

---

## 操作批次 08｜2026-09-30｜Abstract

- [x] 将导师稿 Abstract 合入 `sn-article.tex`，取代此前仍在主文件中的旧摘要；保留导师稿的开头、结果推进和结尾。
- [x] 仅修正一处语法：`the relative values of the earning and spending` → `the relative values of earning and spending`。
- 用户决定其余建议均不修改：保留导师稿的术语与 `across all three regions` 表述，不在摘要加入术语解释、统计数字或额外限定，也不调整进化意义的结尾。
