# Revision summary

> **比较基准**：导师稿 `sn-article_20260921.pdf` 与本地合并稿 `sn-article.tex`。页码和行号均指导师稿 PDF 边栏的连续行号；图注没有印刷行号时，以图号和面板定位。以下只列导师稿之后的修改；英文句子中的引用用 LaTeX `\cite{...}` 表示本地稿中的确切插入位置，编译后的论文会显示文献编号。

## Overall revision

1. 保留导师稿提出的核心问题：当前 token holdings 影响 earning–spending 的估值与选择，而选择又更新后续决策的资源状态。
2. 为主要论断补齐文献和统计，明确检验比较什么、以什么为观察单位。
3. 对齐 Results、主图、图注、Methods 和 Supplementary Information 中的条件、时间窗、图表引用及术语。
4. 收窄个别超出证据的表述，尤其区分模型预测与数据结果、pooled 与个体结果、单神经元分析与群体表示。

## Abstract

### A1｜模型结果句：删除多余冠词

**位置**：Abstract，第 1 页第 20–21 行。

**原文**：“A state-dependent utility model explained this shift through opposing changes in the relative values of the earning and spending.”

**改动后**：“A state-dependent utility model explained this shift through opposing changes in the relative values of earning and spending.”

**理由**：`earning` 和 `spending` 在这里指两类行为或选项，删除 `the` 修正语法，不改变模型结论。

**补充**：摘要其余叙事沿用导师稿，未因进化意义是解释性推断而删去结尾。

## Introduction

### I1｜第一段：边际效用论断加入理论引文

**位置**：问题引入；第 1 页第 34–35 行。

**原文**：“Earning an additional unit may be especially valuable when holdings are low but less valuable when they are abundant, whereas spending may become more attractive as resources accumulate.”

**改动后**：“Earning an additional unit may be especially valuable when holdings are low but less valuable when they are abundant `\cite{bernoulli1954exposition}`, whereas spending may become more attractive as resources accumulate.”

**理由**：Bernoulli 为资源增量的边际价值可能随持有量改变提供理论背景。

**补充**：保留导师稿的 `may`，没有将该理论预期表述为本文直接证明的普遍规律。

### I2｜第一段：资源背景与行为偏好的证据

**位置**：问题引入的段末总结句；第 1 页第 35–37 行。

**原文**：“Economic decisions therefore depend not only on the opportunities currently available, but also on the resource state in which those opportunities are evaluated.”

**改动后**：“Economic decisions therefore depend not only on the opportunities currently available, but also on the resource state in which those opportunities are evaluated `\cite{cesarini2017effect,vanags2025greater,harvey2022developmental}`.”

**理由**：三篇文献分别涉及财富冲击与劳动供给、收入及财务状况与亲社会偏好、儿童社会经济背景与风险选择，为“资源背景与行为偏好有关”提供不同类型的证据。

**补充**：这些研究的设计和测量不同，均不被写成对本任务中自主 earning–spending 的直接检验。

### I3｜第二段：资源—选择循环加入理论框架

**位置**：提出持续反馈问题；第 2 页第 40–41 行。

**原文**：“Resource state thus influences valuation and choice, while earning and spending update the resource state itself.”

**改动后**：“Resource state thus influences valuation and choice, while earning and spending update the resource state itself `\cite{mangel1986unified,mangel1988dynamic}`.”

**理由**：Mangel and Clark 的 state-dependent decision 框架支持把当前状态、选择和后续状态更新放在同一问题中考察。

**补充**：本文没有因此声称检验了长期最优策略或多步规划。

### I4｜第三段：按脑区补齐已有神经证据

**位置**：background on neural evidence；第 2 页第 47–50 行。

**原文**：“Previously, neural signals related to offer value, chosen value, and categorical choice have been demonstrated across prefrontal cortex, including the orbitofrontal cortex (OFC), the dorsolateral prefrontal cortex (DLPFC), and the anterior cingulate cortex (ACC) (ref).”

**改动后**：“Previously, neural signals related to offer value, chosen value, and categorical choice have been demonstrated across prefrontal cortex, including the orbitofrontal cortex (OFC) `\cite{padoa-schioppaNeuronsOrbitofrontalCortex2006b,padoa-schioppaOrbitofrontalCortexNeural2017,ballestaValuesEncodedOrbitofrontal2020a}`, the dorsolateral prefrontal cortex (DLPFC) `\cite{cai2014contributions,lin2021evidence}`, and the anterior cingulate cortex (ACC) `\cite{caiNeuronalEncodingSubjective2012,kennerleyNeuronsFrontalLobe2009b}`.”

**理由**：把 OFC、DLPFC 和 ACC 的文献分别放在对应脑区之后，并去掉未完成的 `(ref)`；读者可以看出各脑区陈述的来源，而不会误以为一组文献共同证明三个脑区均编码全部三类变量。

**补充**：Cai 2012 支持 ACC 的 chosen value 等选择相关信号；此处没有据此声称该研究观察到了独立的 offer-value 编码。

### I5｜第三段：补齐 token holdings 与 reference-state 文献

**位置**：已有 token 研究及本文缺口；第 2 页第 50–52 行。

**原文**：“Token-based studies have also shown that accumulated holdings influence preferences, including decisions involving gains, losses, and risk, and that neural activity can represent token holdings and other wealth-like reference states (ref).”

**改动后**：“Token-based studies have also shown that accumulated holdings influence preferences, including decisions involving gains, losses, and risk, and that neural activity can represent token holdings and other wealth-like reference states `\cite{yangPrimateAnteriorInsular2022c,ferroAccumulationVirtualTokens2025a,nguyenNeuralRepresentationDecisional2025a,seo2009behavioral}`.”

**理由**：现有研究分别支持 token-dependent behavior、holdings 编码及 reference-related 神经表征；替换未完成的 `(ref)`。

**补充**：Nguyen 的研究支持 reference-state 相关神经编码，不作为动物可自主部分消费并保留余额的行为证据。

### I6｜References：修正新增引用涉及的书目记录

**位置**：References；无正文边栏行号。Introduction 第四段的研究问题及结果概括未改写。

| 文献 | 原记录中的问题 | 改动后 |
|---|---|---|
| Cesarini 2017 | 标题误作 “Swedish lottery winners”；期号 6、页码 1298–1331 | 正式标题 “Evidence from Swedish Lotteries”；期号 12、页码 3917–3946；补 DOI `10.1257/aer.20151589` |
| Vanags 2025 | 作者姓名、期号 1、文章号 `pgae003` 有误 | 改为 Paul Vanags、Jo Cutler、Fabian Kosse、Patricia L. Lockwood；期号 2、文章号 `pgae582`；补 DOI |
| Harvey and Blake 2022 | 第一作者、期号及期刊全名有误 | 改为 Teresa Harvey、Peter R. Blake；289(1983):20220712；补 DOI `10.1098/rspb.2022.0712` |
| Seo and Lee 2009 | DOI 末段为 `4157-08.2009` | 改为 `4726-08.2009` |
| Ferro 2026 | 仍列为 2025 bioRxiv 预印本 | 更新为 2026 *Nature Communications* 17:7554，DOI `10.1038/s41467-026-70423-1` |
| Nguyen 2025 | DOI、文章号及作者列表有误 | DOI 改为 `10.1073/pnas.2514110122`，文章号 `e2514110122`，补正式作者列表及期号 |
| Cai and Padoa-Schioppa 2014 | 缺 DOI | 补 `10.1016/j.neuron.2014.01.008` |
| Mangel and Clark 1986、1988 | 原书目库无条目 | 新增 *Towards a Unified Foraging Theory* 及 *Dynamic Modeling in Behavioral Ecology* |

**理由**：让新增的七处 Introduction 引用指向正确出版信息。已有 cite key 保留，避免破坏 Results 和 Discussion 的交叉引用。

**补充**：第四段仅统一了 `actions.` 与 `Together` 之间的多余空格，没有改变英文句子。

## Figure 1 — Resource state shifts earning–spending preferences

### F1-1｜第一段：earning rate 的单位

**位置**：Results 2.1，任务条件介绍；第 2 页第 69–73 行。

**原文**：“Each trial paired one of three earning options, distinguished by earning rate ($V_\text{Earn}$, token/sec), with one of four spending options, distinguished by water amount ($V_\text{Spend}$) (Fig. 1B).”

**改动后**：“Each trial paired one of three earning options, distinguished by earning rate ($V_\text{Earn}$, tokens/s), with one of four spending options, distinguished by water amount ($V_\text{Spend}$) (Fig. 1B).”

**理由**：统一全文的 earning-rate 单位写法；Figure 1 和行为 Methods 中相同量也使用 `tokens/s`。

**补充（2026-10-09 核对）**：全文速率单位采用 `tokens/s`。当前 Overleaf 导出稿的 Figure 1B、Figure 4A–B 图注及行为 Methods 仍有 `tokens s⁻¹`，Results 2.1 还有 `token/sec`；本地这些位置及行为模型中的 earning/spending speed 定义已使用 `tokens/s`。两种写法表示同一单位，此次确认采用本地的统一写法。

### F1-2｜Figure 1B：图中 spending 数值是示意标签

**位置**：Figure 1B 图注，导师稿第 3 页；图注无边栏行号。

**原文**：“Twelve offer conditions were generated by crossing three earning rates ($V_\text{Earn}=4, 5$ or $10$ tokens s$^{-1}$) with four spending reward magnitudes ($V_\text{Spend}=0, 1, 2$ or $4$ arbitrary units).”

**改动后**：“Twelve offer conditions were generated by crossing three earning rates ($V_\text{Earn}=4, 5$ or $10$ tokens/s) with four spending reward magnitudes ($V_\text{Spend}$). The spending-reward labels 0, 1, 2 and 4 are schematic; actual reward settings and normalization to the second-smallest reward magnitude are described in Methods.”

**理由**：Figure 1B 中的 0/1/2/4 是图示档位，不是各猴实际给水量；新句将示意标记与 Methods 中的真实设置区分开。

### F1-3｜Figure 1C：明确选择样本与颜色含义

**位置**：Figure 1C 图注，导师稿第 3 页；图注无边栏行号。

**原文**：“Line colors follow the illustrative offer-condition gradient in B. Only the initial choice on each trial was included.”

**改动后**：“Line colors follow the illustrative offer-condition gradient in B, with lighter shades indicating larger token holdings. Only the initial successful choice on each trial was included, at holdings of 1–24 tokens.”

**理由**：补出图中颜色与 token holdings 的映射，且让图注与行为模型实际使用的有效首次选择及 1–24 token 范围一致。

### F1-4｜第三段：非参数权重表述为总体趋势

**位置**：Results 2.1，非参数权重；第 2 页第 80–85 行。

**原文**：“In all three monkeys, the subjective weights of earning options decreased, whereas those of spending options increased, as tokens accumulated, showing a state-dependent shift in the relative weights favoring spending over earning.”

**改动后**：“In all three monkeys, the subjective weights of earning options generally decreased, whereas those of spending options generally increased, as tokens accumulated, showing a state-dependent shift in the relative weights favoring spending over earning.”

**理由**：图中呈现的是总体方向；加 `generally` 避免暗示每条条件曲线在每个 token level 都严格单调。

### F1-5｜第四段及 Figure 1E：区分原始与缩放后的 value difference

**位置**：Results 2.1 第四段，第 2 页第 86–89 行；Figure 1E 图注，导师稿第 3 页。

**原文**：“Probability of choosing to earn was a sigmoid function of the bias-adjusted, scaled value difference, $(\Delta V-b)/\gamma$, where $\Delta V=V_E-V_S$, in all three monkeys (Fig. 1E and Supplementary Fig. 1C).”

**改动后**：“Probability of choosing to earn was a sigmoid function of the bias-adjusted, scaled value difference, $\widetilde{\Delta V}=(\Delta V-b)/\gamma$, where $\Delta V=V_E-V_S$, in all three monkeys (Fig. 1E and Supplementary Fig. 1C).”

**理由**：`\Delta V` 始终表示主观 earning value 减 spending value；新增符号专指经过 choice bias 与 noise scale 变换后进入 sigmoid 的量。Figure 1E 的实际横轴及图注同步使用这一符号。

### F1-6｜第四段：将 held-out 泛化写成具体模型比较

**位置**：Results 2.1 第四段；第 2 页第 89–91 行。

**原文**：“This account generalized to held-out sessions and was consistently recovered in session-wise fits across all three subjects (Supplementary Fig. 1A,B).”

**改动后**：“The free-$\alpha$ model yielded lower held-out loss than the fixed-$\alpha$ model in all three subjects (W: $n=52$ sessions, $p=4.20\times10^{-10}$; U: $n=63$, $p=7.20\times10^{-12}$; T: $n=64$, $p=3.50\times10^{-12}$; two-sided Wilcoxon signed-rank tests; Supplementary Fig. 1A). Independent session-wise fits further illustrated the stability of fitted utility curvature across recording sessions (median $\alpha$: W, 0.73; U, 0.81; T, 0.79; Supplementary Fig. 1B).”

**理由**：原句把 held-out 预测与 session-wise 拟合合在一个概括中；修订后分别交代比较对象、样本数、检验和曲率参数的描述性结果。

### F1-7｜第四段及 SI：将时间量准确称为 reaction time

**位置**：Results 2.1 第四段，第 2 页第 91–92 行；Supplementary Fig. 1D 和 behavioral-model controls。

**原文**：“Moreover, the resulting decision variable predicted decision time: responses were slower near the fitted behavioral indifference point (Supplementary Fig. 1D).”

**改动后**：“Moreover, the resulting decision variable predicted reaction time: responses were slower near the fitted behavioral indifference point (Supplementary Fig. 1D).”

**理由**：分析量由 offer onset 测至最初选中目标的 fixation onset，称 `reaction time` 更符合事件定义。SI 另说明每猴的难度中位数分组、RT >700 ms 的排除、图中 100–500 ms 的显示范围，以及基于 pooled trials 的双侧 Wilcoxon rank-sum 检验。

### F1-8｜Figure 1E 图注：说明虚线是模型预测

**位置**：Figure 1E 图注；导师稿第 3 页，图注无边栏行号。

**原文**：“Dashed curves are logistic fits.”

**改动后**：“Dashed curves show the model-predicted choice probabilities.”

**理由**：虚线由已经拟合的行为模型给出选择概率。新句直接说明图中虚线代表什么，避免将其误解为另一次独立的 logistic 曲线拟合。

## Figure 2 — Distributed prefrontal tuning

### F2-1｜第二段：把选择性结论限定为单元检验

**位置**：Results 2.2 第二段，第 4 页第 101–103 行。

**原文**：“We observed a significant proportion of neurons across all three regions encoded token number.”

**改动后**：“Neurons in all three regions showed significant selectivity for token holdings.”

**理由**：现有分析检验的是单个 neuron 是否对 token holdings 有选择性。原文的 `significant proportion` 容易被理解为另做了总体比例是否高于机会水平的检验。

### F2-2｜第二段：修正代表单元和 preferred-state 句的语法

**位置**：Results 2.2 第二段，第 4 页第 102–103 行，续第 5 页第 104–105 行。

**原文**：“Fig. 2C,D shows an OFC neuron that showed maximal firing in when the saved tokens were at the intermediate level [8–15]. Across ACC, DLPFC and OFC, preferred number of tokens were distributed across all five groups (Fig. 2E).”

**改动后**：“Fig. 2C,D shows an OFC neuron that showed maximal firing when the saved tokens were at the intermediate level [8–15]. Across ACC, DLPFC and OFC, preferred token-holding levels were distributed across all five groups (Fig. 2E).”

**理由**：删除多余的 `in`，并使复数主语与谓语、token-holding 概念一致。

### F2-3｜第三段：区分真实数据与 shuffle 各自的距离比较

**位置**：Results 2.2 第三段，第 5 页第 105–113 行。

**原文**：“This graded decline disappeared when resource-state-group labels were shuffled and the complete analysis was repeated, indicating that it did not arise solely from selecting and aligning response peaks (Supplementary Fig. 3).”

**改动后**：“Normalized responses were higher at relative distances of $\pm1$ than at $\pm2$ from the preferred group in all three regions (ACC, $p=3.31\times10^{-41}$; DLPFC, $p=2.50\times10^{-36}$; OFC, $p=2.32\times10^{-36}$; Wilcoxon rank-sum tests). The corresponding comparison was not significant after resource-state-group labels were shuffled and the analysis was repeated (ACC, $p=0.934$; DLPFC, $p=0.792$; OFC, $p=0.816$; Wilcoxon rank-sum tests; Supplementary Fig. 3).”

**理由**：这六个 p 值分别来自真实数据和 shuffle 数据内部的 `±1` 对 `±2` 比较。原文可被误读为已直接检验真实曲线与 shuffle 曲线之间的差异；修订后明确每个 p 值实际支持的结论。

### F2-4｜Figure 2E 图注：明确百分比的分母

**位置**：Figure 2E 图注；导师稿第 4 页，图注无边栏行号。

**原文**：“Bars show the percentage of selective neurons preferring each resource-state group in ACC (red), DLPFC (green) and OFC (blue); dark bars show shuffle estimates.”

**改动后**：“Bars show the percentage of analyzed units that were resource-state selective and assigned to each preferred group in ACC (red), DLPFC (green) and OFC (blue); dark bars show shuffle estimates.”

**理由**：明确柱高的分母是脑区内所有 analyzed units，而非只在显著选择性的神经元中计算比例。

### F2-5｜Figure 2F–H 图注：写出群体调谐曲线的处理步骤

**位置**：Figure 2F–H 图注；导师稿第 4 页，图注无边栏行号。

**原文**：“Selective neurons were grouped according to their preferred resource-state group, and their normalized tuning curves were averaged within each group for ACC (F), DLPFC (G) and OFC (H).”

**改动后**：“Selective neurons were grouped according to their preferred resource-state group. Negatively tuned curves were inverted before min–max normalization, and normalized curves were averaged within each group for ACC (F), DLPFC (G) and OFC (H).”

**理由**：补出负向曲线反转、归一化和按 preferred group 平均的次序，使图注足以解释曲线如何得到。

**补充**：Supplementary Methods 另写明 shuffle 柱汇总 10 次 permutation，而群体调谐曲线及其检验使用其中一次。正文的 `Gaussian-like` 只是形状描述，不表示进行了 Gaussian 模型选择。

## Figure 3 — Temporal dynamics and updating

### F3-1｜第一段：限定 ACC 区域比较的时间范围

**位置**：Results 2.3 第一段，第 5 页第 119–126 行。

**原文**：“Token number was decodable even before offer onset in all three regions. The decoding was significantly stronger in ACC than in DLPFC ($p=6.60\mathrm{e}{-34}$) or OFC ($p=7.20\mathrm{e}{-34}$).”

**改动后**：“During the offer-onset epoch, decoding was strongest near the temporal diagonal, suggesting a dynamic representation of token number. By contrast, decoding generalized broadly across the wallet-update epoch, demonstrating a stable resource-state representation during this period. ACC showed higher offer-onset decoding accuracy across paired matrix locations than DLPFC ($p=6.6\mathrm{e}{-34}$) or OFC ($p=7.2\mathrm{e}{-34}$; Supplementary Table 1).”

**理由**：删去不承担本段主结论的 pre-offer 句，并将两个区域比较明确限定于 offer-onset epoch；导师稿中相邻句的位置可能使读者把 p 值误解为 pre-offer 专属比较。

**补充**：Figure 3A 是 cross-temporal decoding 矩阵，横纵轴分别为训练和测试时间。新增 Supplementary Table 1 汇总 offer-onset 与 wallet-update 两个 epoch 的矩阵位置统计；Methods 说明对应位置的配对、双侧 Wilcoxon signed-rank 和未做多重比较校正。矩阵位置共享数据，不是独立动物或 session。

### F3-2｜第二段：首次报告 pooled 双方向 updating 的 p 值

**位置**：Results 2.3 第二段，第 5 页第 133–137 行。

**原文**：“ACC and OFC satisfied this bidirectional criterion, whereas DLPFC did not in the pooled analysis.”

**改动后**：“In the pooled data, ACC (earning, $p=1.70\mathrm{e}{-15}$; spending, $p=1.10\mathrm{e}{-06}$) and OFC (earning, $p=2.00\mathrm{e}{-18}$; spending, $p=6.50\mathrm{e}{-13}$) satisfied this bidirectional criterion, whereas DLPFC did not.”

**理由**：Figure 3C 的 bidirectional criterion 要求 earning 后沿资源状态轴正向移动、spending 后负向移动，并且两种方向分别显著；正文首次报告时给出两个方向各自的检验结果。

### F3-3｜第二段：个体与 shuffle 结果按双向标准表述

**位置**：Results 2.3 第二段，第 5 页第 135–138 行。

**原文**：“This pattern was reproduced in individual animals, and the bidirectional effect was absent after shuffling either choice or token labels (Supplementary Table 1).”

**改动后**：“Individual-animal results are reported in Supplementary Table 2. Neither choice-label nor token-label shuffling yielded bidirectional updating in any region (Supplementary Table 2).”

**理由**：原句的“在个体中重现”过于笼统。补表显示 ACC 的 W/T、OFC 的 W/U/T 满足双向标准；DLPFC pooled 不满足，但 U 满足。shuffle 中可能有单个方向显著，因此只说没有 control 满足**同时正向 earning 和负向 spending**的联合标准。

### F3-4｜新补表与方法：解决区域比较的观察单位

**位置**：Results 2.3 第一段，第 5 页第 120–123 行的 TODO；Supplementary Fig. 4 之后。

**原文**：“[TODO: specify the observation unit, pairing across regions, matrix entries included, test direction and correction for the two reported cross-region comparisons.]”

**改动后**：新增 Supplementary Table 1，列出 offer onset 和 wallet update 的 pooled/W/U/T `R² mean±SD`、脑区间 p 值及均值排序；原 updating 表顺延为 Supplementary Table 2。Methods 写明矩阵位置为观察单位、offer-onset 14×14 与 wallet-update 10×10 的范围、对应位置配对和未校正的双侧检验。

**理由**：两个极小 p 值需要读者知道比较的不是动物或 session，而是同一 epoch 矩阵中的对应时间位置。新表承载主文无法简短呈现的区域、epoch 和个体细节。

## Figure 4 — Resource-state modulation of offer value

### F4-1｜第一段：将因果措辞改为模型预测

**位置**：Results 2.4 第一段，第 5 页第 141–147 行。

**原文**：“The behavioral model suggested that diminishing marginal utility caused earning values to decrease as tokens accumulated, whereas spending values retain the separation attributable to reward magnitude (Fig. 4A,B; see Methods).”

**改动后**：“The behavioral model suggested that diminishing marginal utility would reduce earning values as tokens accumulated, whereas spending values would retain the separation attributable to reward magnitude (Fig. 4A,B; see Methods).”

**理由**：`would reduce` 和 `would retain` 明确这是行为模型给出的预测，不把模型假设直接写成已确立的神经因果事实。代表 OFC 单元仍紧接在预测之后。

### F4-2｜第二段：明确 nested-model comparison 是逐单元拟合

**位置**：Results 2.4 第二段，第 5 页第 148–151 行。

**原文**：“As the neurons are highly heterogeneous, we used a nested-model comparison to examine the state-dependent value-encoding at the population level.”

**改动后**：“We used a nested-model comparison to examine state-dependent value encoding beyond the independent effects of offers and holdings.”

**理由**：分析先对每个 unit 分别拟合基线模型 `M₁` 和加入 state-dependent earning value 的 `M₂`，再汇总各 unit 的增量。原文 `at the population level` 容易与下一段的 population value-space geometry 混淆。

### F4-3｜第二段：把统计结论写成 observed-versus-shuffled increment

**位置**：第 5 页第 151–155 行，续第 8 页第 156–157 行；Figure 4C 图注无边栏行号。

**原文**：“Around wallet update, $M_2$ accounted for the value representatioin in ACC, DLFPC, and OFC significantly better than $M_1$, measured with the explained variance, $\Delta R^2_{\mathrm{adj}}$ (Fig. 4C, significance tested against the value-label-shuffled control, Table 2).”

**改动后**：“Around wallet update, the increase in explained variance, $\Delta R^2_{\mathrm{adj}}$, was significantly greater than the shuffled-$V_E$ control in ACC, DLPFC and OFC (Fig. 4C).”

**理由**：修正 `representatioin`、`DLFPC` 和错误的 Table 2 指向。检验比较的是各 unit 的 observed `M₂−M₁` adjusted-R² 增量与新增 `V_E` predictor 被打乱后的增量；并非只检验两个模型的原始拟合优度是否不同。

**补充**：Figure 4C 图注与 Methods 说明：每个 unit 的新增 `V_E` predictor 在所有有效事件之间置换一次，其他 predictors 与 firing rates 保持不变；每个 100-ms bin 对 units 做配对双侧 Wilcoxon signed-rank，未跨 bin 校正。原文所指 Table 2 是 Figure 5 的 choice-conditioned TDR 表，不包含此 nested-model 检验。

### F4-4｜Supplementary Fig. 5：删除 coefficient-sign 面板并调整面板号

**位置**：Supplementary Fig. 5 图注；导师稿该图的 C、D 面板无边栏行号。

**原文**：“(C) Joint encoding of offer value and resource state. Matrices show the proportions of units classified by the signs of their state-independent offer-value and token-holding coefficients in ACC, DLPFC and OFC.” 原 D 面板是三只猴的 wallet-update nested-model 曲线。

**改动后**：“(C) Resource-dependent earning-value model comparison in individual animals. Solid lines show the across-unit mean increase in explained variance from $M_1$ to $M_2$ around wallet update for monkeys W, U and T; shading denotes $\pm$SEM.”

**理由**：Figure 4 的 coefficient-sign 分析已决定取消，因此对应 SI 图面板和专属 Methods 小节一并删除；保留与正文 Figure 4C 的 nested-model 检验直接对应的个体证据。Figure 4 正文和主图图注也将个体结果入口由 Supplementary Fig. 5D 改为 5C。

**补充**：导师稿 Supplementary Fig. 5C 的矩阵按两个回归系数的正负号分类神经元：一个系数对应 earning offer value，另一个对应当前 token holdings。新图保留 A/B 的 OFC 代表单元；原 D 的三只猴 nested-model 曲线移为 C，原 coefficient-sign C 面板不再展示。

### F4-5｜第三段：按更新后的 geometry 图描述区域差异

**位置**：Results 2.4 第三段，第 8 页第 158–167 行。

**原文**：“This was best exhibited in the ACC, but also evident in DLPFC and OFC (Fig. 4E).”

**改动后**：“The aspect ratio increased with resource state in ACC and showed a weaker tendency to increase in DLPFC and OFC (Fig. 4E).”

**理由**：Figure 4E 的 aspect ratio 是 spending-value 轴范围除以 earning-value 轴范围。新句具体说出 ACC 的变化方向及 DLPFC/OFC 较弱的趋势，不把三脑区写成同等强度，也不额外声称曲线严格单调。

**补充**：Figure 4D/E 和 Supplementary Fig. 6 使用重新绘制的 Choice FR 版本；该部分按 wallet update 对齐。关于新图精确 p 值和有效 unit 数，本轮没有从图上标记反推并补进正文。

### F4-6｜Figure 4 图注：最低水量档位的名称

**位置**：Figure 4A/B、D 图注，导师稿第 7 页；相关 SI 图注。

**原文**：“The zero-reward spending condition was omitted because monkeys rarely chose this option, yielding insufficient resource-state-update observations for stable condition averages.”

**改动后**：“The lowest spending-reward condition was omitted because monkeys rarely chose this option, yielding insufficient resource-state-update observations for stable condition averages.”

**理由**：行为图上的 `0` 是示意档位，不能直接称为实际实验中的零给水条件。新称呼与 Figure 1B 图注和 Methods 的 reward 设置一致。

## Figure 5 — Decision-related value representations

### F5-1｜第一段：修正从 offer value 到决策的过渡句

**位置**：Results 2.5 第一段，第 8 页第 168–170 行。

**原文**：“The resource-state-dependent offer value representations in the prefrontal regions point toward a mechanism that how the earning-spending decision may be formed.”

**改动后**：“The resource-state-dependent offer-value representations in prefrontal cortex point toward how the earning–spending decision may be formed.”

**理由**：删除不合语法的 `a mechanism that how`，保留导师从 Figure 4 的 offer-value representation 转入决策相关编码的推进。该句没有新增关于神经计算机制的结论。

### F5-2｜第二段：分别指向代表单元的两种 value tuning

**位置**：Results 2.5 第二段，第 9 页第 174–178 行。

**原文**：“In the example neuron show in Figure 5, firing increased with $V_E$ on both earning and spending trials, but with a steeper slope when earning was selected (Fig. 5A); $V_S$ tuning was positive when spending was selected but negative when earning was selected (Fig. 5B).”

**改动后**：“In the example neuron shown in Fig. 5, firing increased with $V_E$ on both earning and spending trials, but with a steeper slope when earning was selected (Fig. 5A); $V_S$ tuning was positive when spending was selected but negative when earning was selected (Fig. 5B).”

**理由**：修正 `neuron show` 的语法；Figure 5A 是 earning-value tuning，Figure 5B 是 spending-value tuning，分开引用方便读者与面板核对。

### F5-3｜第二段：首次报告 pooled choice-conditioned 结果

**位置**：Results 2.5 第二段，第 9 页第 178–181 行；Figure 5C 与 Supplementary Table 3（修订稿自动编号）。

**原文**：“At the population level, value encoding tended to be stronger when the corresponding option was chosen: $V_E$ encoding was enhanced on earning trials where this signal was evident, and $V_S$ encoding was enhanced on spending trials (Fig. 5C).”

**改动后**：“At the population level, value encoding tended to be stronger when the corresponding option was chosen: $V_E$ encoding was enhanced on earning trials where this signal was evident, and $V_S$ encoding was enhanced on spending trials (Fig. 5C). In the pooled populations, the matched-choice advantage was positive for both $V_E$ ($\Delta R^2=0.037$–$0.209$, all $p\leq1.18\times10^{-11}$) and $V_S$ ($\Delta R^2=0.123$–$0.299$, all $p\leq2.67\times10^{-18}$; one-sided Wilcoxon signed-rank tests across 100 resamples).”

**理由**：导师稿已有主要定性结论；增加 pooled 的增量范围、p 值和检验单位，使读者能在首次陈述时看到证据。

**补充**：`\Delta R^2` 比较被选择条件与未被选择条件中的 value encoding strength。三个脑区的全部精确数值及个体结果继续由补表承载。

### F5-4｜第二段：准确说明 choice-label shuffle 后的结果

**位置**：第 9 页第 180–182 行；同一 Supplementary Table。

**原文**：“These matched-condition advantages were smaller after choice-label shuffling (Supplementary Table 2).”

**改动后**：“After choice-label shuffling, the $V_E$ advantage was no longer significant (all $p\geq0.091$); the $V_S$ advantage remained significant, with a smaller observed $\Delta R^2$ ($0.041$–$0.070$, all $p\leq3.18\times10^{-12}$; Supplementary Table 3).”

**理由**：原句容易让人以为两类 value advantage 都被 shuffle 消除；实际 `V_S` 的 matched-choice advantage 在 shuffle 后仍显著。

**补充**：表中 p 值分别检验 real 或 shuffle 数据中的 `\Delta R^2` 是否大于零，没有进行 real-versus-shuffle 的直接显著性检验。因此 “smaller” 仅描述表中观测数值，不能写成两组之间显著降低。

### F5-5｜第三段：区分相对 chosen value 的排序与脑区比较

**位置**：Results 2.5 第三段，第 9 页第 182–190 行。

**原文**：“The pooled population encoding strength follows $V_S>V_{Chosen}>V_E$ in all three regions (Supplementary Table 3). These strength of representation also differed between the regions.”

**改动后**：“The pooled population encoding strength followed $V_S>V_{Chosen}>V_E$ in all three regions (Supplementary Table 4); individual-animal results are reported in the same table. The strengths of these representations also differed between regions.”

**理由**：修正时态和语法；明确 `V_S>V_{Chosen}>V_E` 是 pooled 的脑区内排序，个体例外由同一表展示。后一项“不同脑区之间强度不同”另指向跨区域比较表，不由脑区内排序表单独支持。

**补充**：本文的 $V_{Chosen}=c(\Delta V-b)$ 表示被选选项相对另一个选项的 bias-adjusted advantage，可为负；它不是被选奖励本身的绝对价值。这个定义是导师稿已有内容，此次没有更改。

### F5-6｜第四段：限定 temporal-order 结论的适用范围

**位置**：Results 2.5 第四段，第 9 页第 190–195 行。

**原文**：“For signals that we could estimate latencies, half-peak and onset estimates were overall consistent with the temporal progression from $V_E/V_S$ to $V_{Chosen}$ to Choice.”

**改动后**：“For signals with stable latency estimates, half-peak and onset estimates were overall consistent with the temporal progression from $V_E/V_S$ to $V_{Chosen}$ to Choice.”

**理由**：保留导师的总体时序判断，但不把有可计算 latency 的所有信号都等同于稳定可靠的估计。具体例外写在 onset 补表表注。

**补充**：例如 pooled ACC 的 $V_E$ onset 晚于 $V_{Chosen}$；“overall consistent” 不是说每个脑区、动物和时间指标都严格满足同一顺序。`stable` 是文字上的适用范围限定，并非新增一个分析阈值。

## Figure 6 — Good-based and action-based choice

### F6-1｜第二段：修正 Figure 6C 的三个区域定位

**位置**：Results 2.6 第二段，第 9 页第 201–203 行。

**原文**：“Following offer onset, the four choice conditions separated most clearly along the earning/spending axis in OFC (Fig. 6C, right)and along the left/right axis in DLPFC (Fig. 6C, middle).”

**改动后**：“Following offer onset, the four choice conditions separated most clearly along the earning/spending axis in OFC (Fig. 6C, right) and along the left/right axis in DLPFC (Fig. 6C, middle).”

**理由**：补上 `right)` 与 `and` 之间的空格。OFC 在 Figure 6C 右侧，DLPFC 在中间，ACC 在左侧；这些位置与现有图件一致。

### F6-2｜第二段：主图轨迹与强度表分别承担证据

**位置**：第 9 页第 203–208 行；Figure 6C 与原 Figure 6D。

**原文**：“The corresponding encoding trajectories confirmed distinct regional biases in choice format: DLPFC preferentially encoded the left/right action, OFC preferentially encoded the earning/spending identity of the selected option, and ACC carried substantially weaker choice signals overall with a stronger good-based choice encoding (Fig. 6C, left, and Supplementary Table 9).”

**改动后**：“The corresponding encoding trajectories and strength comparisons confirmed distinct regional biases in choice format: DLPFC preferentially encoded the left/right action, OFC preferentially encoded the earning/spending identity of the selected option, and ACC carried substantially weaker choice signals overall with a stronger good-based choice encoding (Fig. 6C, left; Supplementary Table 10).”

**理由**：Figure 6C 显示三个脑区在 earning/spending 与 left/right 二维坐标中的 population trajectories；编码强度的定量比较在 Supplementary Table 10。加入 `strength comparisons` 后，句子的证据入口分别指向轨迹与表格，而非让轨迹图单独承担强度推断。

**补充**：导师稿 Figure 6D 原是一组 $R^2(t)$ 时间曲线，分别画出 ACC、DLPFC、OFC 对 left/right action 与 earning/spending choice 两类标签的编码强度。更新后的主图只保留 A/B 代表单元和 C 面板二维轨迹，因此正文和图注不再引用 D；强度的数值与检验仍保留在 SI 表中。

### F6-3｜Figure 6 图注：删除不再展示的 D 面板说明

**位置**：Figure 6 图注，导师稿第 10–11 页；图注无边栏行号。

**原文**：“(D) Temporal encoding strength. Encoding strength ($R^2$, squared Pearson correlation between population projection and the corresponding choice label) is shown for the left/right axis (blue) and earning/spending axis (olive) in ACC, DLPFC and OFC. Shading denotes $\pm$SD across 100 bootstrap iterations; the vertical dashed line marks offer onset.”

**改动后**：“Large circles mark the population states at offer onset, and shaded regions show $\pm$SD across trial resamples.”

**理由**：本地交付的 `Choice.pdf` 已移除原 D 的两类 choice signal 时间曲线。保留 D 图注会使读者寻找不存在的面板；与强度有关的定量结论改由 Supplementary Table 10 承载。

**补充**：这句现在是 Figure 6 图注的末句，描述保留下来的 C 面板。导师稿的 D 面板原本画出 ACC、DLPFC 和 OFC 对 left/right action 与 earning/spending choice 两种选择标签的 $R^2(t)$ 时间曲线；本地 Figure 6 只有 A/B 代表单元和 C 面板二维轨迹，因而删除整个 D 面板及其图注。

### F6-4｜结果结尾：从跨脑区“最强”收窄为脑区内偏好

**位置**：Results 2.6 末段，第 9 页第 216–219 行。

**原文**：“In summary, these results identify a regional difference of choice representation, with earning/spending representations strongest in OFC, left/right representations strongest in DLPFC, and weaker choice signals in ACC with a relative earning/spending bias.”

**改动后**：“In summary, these results identify a regional difference of choice representation, with OFC preferentially representing earning/spending choice and DLPFC preferentially representing left/right action.”

**理由**：现有 pooled 与个体结果支持 OFC 内 earning/spending choice 相对 left/right action 更强、DLPFC 内相反；不能概括为同一 choice coordinate 在 OFC 或 DLPFC 对所有动物均跨脑区最强。ACC 信号较弱的结果仍在上一段说明，此处只收束证据较一致的两种脑区内偏好。

### F6-5｜Methods：按实际 choice-format TDR 配置修正参数

**位置**：Methods “Good-based and action-based choice formats”，第 21 页第 677–685 行；通用 TDR resampling 段也同步说明 Figure 6 的例外。

**原文**：“Ridge regression with $\lambda=5$ was used because the spatially mapped and task-defined value pairs were collinear by construction.”

**改动后**：“Ridge regression with $\lambda=1$ was used because the spatially mapped and task-defined value pairs were collinear by construction. The regression and QR column order was $[V_L,V_R,V_E,V_S,W,Choice_{LR},Choice_{ES}]$. Left/right choice indicated the selected option's side of the screen.”

**理由**：对照该分析实际执行的代码，ridge 参数为 1；补出回归和 QR 变量顺序，以及 left/right choice 的任务含义，避免把被选选项的身份与眼动方向混为一谈。

**补充**：Methods 另写明 100 次 resampling、每个 choice-label group 每次抽取 75 个 held-out trials、以 offer onset 后 0–500 ms 的平均 $R^2$ 表示强度，并对 resampling distributions 使用双侧 Wilcoxon rank-sum。检验单位是重复抽样迭代，而非独立动物或 session；本文没有在此次修订中重跑原始数据。

## Points left for later discussion

1. **Discussion**：导师稿的讨论结构整体保留。本地稿仅删去与 Figure 4 已取消的 coefficient-sign 分析及 offer-onset 附图有关的句子；其余解释留给导师继续处理。
2. **声明**：作者及单位已于 2026-10-09 按当前 Overleaf 版本同步到本地。作者贡献，以及伦理审批正式名称、protocol number、Funding、Acknowledgements、Competing interests 和 Data/Code availability，仍需作者共同确认。
3. **分析细节**：Figure 4 新 geometry 图的精确数值与 nested-model 各区有效 unit 数、窗口汇总值，以及 Figure 6 的部分生成缓存与方法配置，可在后续专项核对。本次没有从图上星号反推这些数字。


## 2026-10-09｜继承当前 Overleaf 信息与覆盖前核对

本节记录导师同意此前修订后，本地稿相对于此前本地版本的同步，以及与当前 Overleaf 导出文件夹的核对结果。此前各条目的导师稿页码、行号比较基准不变。本说明保留在本地，不作为 Overleaf 项目文件上传。

### S1｜作者列表：继承 Overleaf 中的 Lusha Zhu

**位置**：论文首页作者列表；对应 `sn-article.tex` 的 author 区块。

**原文（此前本地）**：Hualei Wang；Hangyu Si；Tianming Yang（通讯作者）。

**改动后**：Hualei Wang；Hangyu Si；Lusha Zhu；Tianming Yang（通讯作者）。

**理由**：当前 Overleaf 已有 Lusha Zhu，本地此前未同步。按 Overleaf 的作者顺序补入，防止以本地稿覆盖时丢失已有署名。

**补充**：Hualei Wang、Hangyu Si 的单位编号为 1、2；Lusha Zhu 为 3、4、5；Tianming Yang 为 1，通讯邮箱仍为 tyang@ion.ac.cn。

### S2｜作者单位：继承三个新增单位与单位标记

**位置**：论文首页单位列表；对应 `sn-article.tex` 的 affiliation 区块。

**原文（此前本地）**：仅有单位 1、2；单位 1 使用 `\affil*[1]`。

**改动后**：单位 1 使用 `\affil[1]`，与当前 Overleaf 一致；保留原单位 1、2，并补入以下单位：

- **3**：School of Psychological and Cognitive Sciences and Beijing Key Laboratory of Behavior and Mental Health, Peking University, Beijing, China.
- **4**：IDG/McGovern Institute for Brain Research, Peking University, Beijing, China.
- **5**：Peking-Tsinghua Center for Life Sciences, Peking University, Beijing, China.

**理由**：完整继承 Overleaf 的作者—单位对应关系及原有单位标记。作者和单位区块整体取自此次导出，避免逐项录入时遗漏。

### S3｜速率单位：确认沿用 tokens/s

**位置**：Results 2.1；Figure 1B、Figure 4A–B 图注；Methods 的任务条件和行为模型参数定义。

**原文（当前 Overleaf）**：Results 2.1 使用 `token/sec`；上述部分图注及任务条件使用 `tokens s⁻¹`；行为模型定义使用 `tokens/s`。

**改动后（本地）**：上述正文、图注和 Methods 均使用 `tokens/s`。

**理由**：同一速率量使用一种记法，earning rate 和 spending rate 保持一致。

**补充**：这些本地文字在此前修订中已统一，此次核对确认，无需再次改写。已核对 BHV.pdf：Figure 1B 图内标签仍为 `token/s`，与 `tokens/s` 表示同一速率，沿用此前“不为单复数重做图件”的决定。正文、图注和 Methods 的单位写法为 `tokens/s`；图内该标签的单复数差异明确保留。

### S4｜文件核对：记录正文与图件的配套关系

**核对结果**：当前 Overleaf 与本地有差异的论文文件为主稿、参考文献库及以下八个图件：BHV.pdf、Choice.pdf、ResourceStateTuning.pdf、ValueModulation.pdf、SM_BHVSummary.pdf、SM_TokenTuningCurve.pdf、SM_OfferValueGeometry.pdf、SM_OfferValueSingleUnit.pdf。这些为此前本地修订所用文件，此次未替换图件或参考文献库。其余五个被主稿引用的图件一致，主稿引用的十三个图件在本地均存在。文档类和参考文献样式文件一致。

**补充**：当前主稿仍保留五处 TODO，涉及伦理委员会与 protocol number、resampling 推断、latency 定义、chosen-value shuffle 和 choice-format 分析配置；本次同步没有据猜测填入这些信息。已有正文修订、统计表与图件保留在本地项目目录。覆盖时应使用相互配套的主稿、参考文献库与图件。
