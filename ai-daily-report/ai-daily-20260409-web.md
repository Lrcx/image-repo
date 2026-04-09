# AI 日报 — 2026年04月09日 周四

> 每日精选 AI 领域重要动态，为你节省信息筛选时间

---

## 📋 今日摘要

- 匿名模型HappyHorse在文生视频和图生视频无音频赛道双双登顶，Elo分超字节Seedance 2.0超70分
- OpenAI官宣ChatGPT Enterprise与AI代理全面进军企业级市场，推动全公司自动化落地
- Z.AI推出754B参数开源模型GLM-5.1，在SWE-Bench Pro上达SOTA，可连续8小时自主编码执行
- Anthropic新模型Claude Mythos Preview发现数千个系统漏洞，未公开却交予互联网关键组织修复
- 研究者提出MegaTrain技术，首次在单张A100 GPU上实现100B+参数大模型的全精度训练

**今日共收录 23 条动态，涵盖 大模型与核心产品 8条、行业风向与社区热议 4条、学术与前沿研究 4条、开源生态与开发者工具 3条、技术实践与深度洞察 4条。**

---

## 🚀 大模型与核心产品

### 1. 神秘模型HappyHorse登顶AI视频榜

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/0409bd074e50770c.png)

上周，AI视频盲测平台Artificial Analysis榜单上出现了一个名为HappyHorse的匿名模型，在文生视频和图生视频（无音频）两大核心赛道中分别以1349分和1403分的Elo分数击败字节跳动的Seedance 2.0，领先幅度达76分和48分。尽管该模型未开放任何官方入口、无技术文档、无团队署名，但其生成质量在数千次盲测中获得用户一致高评，引发全网对背后研发方的激烈猜测。

业内普遍认为HappyHorse来自中国团队，阿里万相、淘天集团张迪团队、或初创公司Sand.ai均被列为可能候选者，尤其因其技术风格与可灵（Kling）高度相似。目前大量第三方网站已开始套壳运营，打着‘HappyHorse AI’旗号收费服务，但均非官方。这匹突然杀出的黑马，不仅刷新了AI视频生成的性能标杆，更让2026年的AI视频军备竞赛进入白热化阶段。

📎 [原文链接](https://zhidx.com/p/546917.html)


### 2. OpenAI发布企业AI新阶段蓝图

OpenAI正式描绘了企业人工智能的下一阶段，重点推进ChatGPT Enterprise、Codex及全公司范围的AI代理落地。这些工具正从单点辅助转向深度集成，覆盖客服、代码生成、流程自动化等核心业务场景，助力企业实现端到端的AI驱动运营。

这一转变意味着AI不再只是员工的‘助手’，而是成为组织流程中的‘成员’，对国内企业级AI服务商如通义、Kimi、智谱等构成直接竞争压力，也倒逼国内大厂加速企业级AI产品的场景深耕与安全合规能力建设。

📎 [原文链接](https://openai.com/index/next-phase-of-enterprise-ai)


### 3. GLM-5.1发布：754B开源智能体模型登顶SWE-Bench Pro

Z.AI团队正式发布GLM-5.1，这是一个参数规模达7540亿的开源权重大模型，专为智能体任务优化，显著提升代码理解与自主执行能力。在最具挑战性的软件工程基准SWE-Bench Pro上，其表现超越所有现有模型，成为当前最优（SOTA）系统。

更值得关注的是，GLM-5.1能持续运行8小时以上，自主完成复杂编程任务，如调试、重构和多步骤开发，这在工业级AI编程助手领域属重大突破。作为智谱AI旗下产品，它的开源权重策略将极大推动国内开发者构建自主AI编程智能体生态。

📎 [原文链接](https://www.marktechpost.com/2026/04/08/z-ai-introduces-glm-5-1-an-open-weight-754b-agentic-model-that-achieves-sota-on-swe-bench-pro-and-sustains-8-hour-autonomous-execution/)


### 4. Meta亿元团队发布新多模态大模型

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04099918484e624a.webp)

Meta旗下由余家辉、宋飏和Jason Wei组成的顶级AI团队，历时九个月打造了全新原生多模态大模型，标志着其在多模态理解与生成能力上的重大突破。该模型不再依赖后处理融合图像与文本，而是从架构底层实现跨模态对齐，显著提升视觉问答、图像描述等任务的准确率。

这一成果被视为Meta对Llama系列早期多模态版本不足的直接回应，也是其在与OpenAI、Google竞争中重新夺回技术话语权的关键一步。若性能数据公开，或将推动国内开发者在多模态应用上的技术迁移与开源生态升级。

📎 [原文链接](https://www.qbitai.com/2026/04/398020.html)


### 5. Meta发布Muse Spark：一张图复刻豆包App

![](images/f455eaf7bdb3.png)

Meta超级智能实验室（MSL）正式发布首款原生多模态推理模型Muse Spark（内部代号‘牛油果’），在Artificial Analysis评测中智能指数从Llama 4 Maverick的18分跃升至52分，性能介于Claude Sonnet 4.6与Opus之间。实测中，该模型仅凭一张豆包App截图，便精准还原界面设计与交互风格，甚至模仿出‘豆包味儿’的口语化回复，同时成功通过久违的‘六边形小球弹跳测试’，标志着Meta在多模态理解与生成能力上实现关键突破。

Muse Spark由前ScaleAI创始人汪滔领衔、多位华人AI顶尖人才组成的团队打造，采用新型架构使算力需求降低一个数量级，重点优化医疗健康与多模态交互场景，在HealthBench Hard和MedXpertQA中斩获SOTA。虽未开源，且编程与长程智能体能力仍弱，但其面向C端的极致体验设计，预示Meta正从‘参数竞赛’转向‘真实世界理解’，为元宇宙与个人AI助手铺路。

📎 [原文链接](https://zhidx.com/p/547280.html)


### 6. 腾讯QClaw V2发布：多Agent+跨应用直连

![](https://img.ithome.com/newsuploadfiles/2026/4/852abc26-4bb3-435d-99d1-86e6c7212923.png?x-bce-process=image/format,f_auto)

腾讯云今日发布QClaw V2大版本更新，首次支持同时调用最多3个自定义AI Agent并行工作，用户可一键启用‘无不言’‘林且慢’‘代可行’等风格化助手，分别处理文案、复盘与编程任务，大幅提升复杂工作流效率。同时，新版本打通腾讯文档、Notion、邮箱等主流工具，通过连接器实现AI生成内容自动保存或发送，无需手动复制粘贴。

此次更新还业内首发‘龙虾管家’安全防护功能，实时拦截高风险脚本执行、误删文件和异常网络访问，并记录完整安全日志，为个人AI办公提供底层保障。基于OpenClaw极简封装，QClaw无需编程基础，20秒安装后即可通过微信指令远程操控电脑，进一步降低AI助手使用门槛，推动国产AI Agent走向大众化。

📎 [原文链接](https://www.ithome.com/0/937/473.htm)


### 7. 智元发布GO-2基座模型

国产AI公司智元机器人（Agibot）正式发布其全新具身智能基座模型GO-2，该模型在千亿参数规模下实现了视觉感知、语言理解与动作规划的统一训练，突破了传统机器人系统中感知与行动模块割裂的瓶颈，首次在真实场景中达成‘知行合一’的端到端闭环。

GO-2的发布标志着中国公司在具身智能核心架构上取得关键进展，其能力已可支持复杂家庭环境中的多任务交互，为国产机器人迈向通用智能体奠定技术基础，也对海外同类模型如Google的RT-2和OpenAI的O1形成直接技术对标。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-09-6)


### 8. Anthropic发布全球首个消费级AI Agent平台

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/040940ce2407e38c.jpg)

AI公司Anthropic正式发布Managed Agents，这是全球首个面向普通消费者的AI代理平台，允许用户通过自然语言指令让AI自动完成订票、比价、日程管理等复杂任务，无需编程。该平台整合了Claude 3.5的强推理能力，首次实现AI在真实应用环境中的稳定闭环操作。

这一发布标志着AI从‘回答问题’迈向‘执行任务’的关键转折，也印证了此前硅谷华人团队在AI代理方向的前瞻布局。对国内开发者而言，这不仅提升了AI落地的实用标准，更倒逼国产大模型加速向具身智能和自动化场景演进。

📎 [原文链接](https://www.qbitai.com/2026/04/398140.html)


---

## 🛠️ 开源生态与开发者工具

### 1. MiniMax发布MMX-CLI：两行代码调用多模态能力

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/0409b5ab6f9821d4.png)

MiniMax稀宇科技于4月9日发布命令行工具MMX-CLI，开发者仅需两行代码即可安装并调用其全模态大模型能力，涵盖文本对话、图像生成、视频创作、30+音色TTS和带歌词的音乐生成。该工具直接对接MiniMax的‘龙虾’模型，无需搭建MCP Server或复杂接口，显著降低AI Agent集成门槛。

MMX-CLI专为AI Agent设计，采用纯JSON输出、语义化错误码和异步非阻塞架构，确保机器可读、稳定高效。所有调用自动计入Token套餐，提供从29元/月起的多档订阅方案。虽然尚未公布性能基准数据，但其轻量化、开箱即用的特性，为国内AI Agent开发者提供了新的基础设施选择，有望加速多模态应用落地。

📎 [原文链接](https://zhidx.com/p/547362.html)


### 2. ModelScope全流程实战指南发布

阿里通义千问团队开源的ModelScope平台近日发布了一份详尽的实战指南，通过Colab环境完整演示了从模型搜索、下载、微调到推理和导出的全流程操作。教程详细指导开发者配置GPU环境、与ModelScope Hub交互，并实际运行主流AI模型，大幅降低国产模型的使用门槛。

该指南对国内AI开发者极具实用价值，尤其在当前国产模型生态快速发展的背景下，为开发者提供了标准化、可复现的工具链支持，有助于推动ModelScope成为与Hugging Face比肩的国产模型枢纽平台。

📎 [原文链接](https://www.marktechpost.com/2026/04/08/a-comprehensive-implementation-guide-to-modelscope-for-model-search-inference-fine-tuning-evaluation-and-export/)


### 3. 文生图进入Agent时代：港中文联合伯克利开源Gen-Searcher

香港中文大学联合加州大学伯克利分校近日开源了新一代文生图框架Gen-Searcher，突破传统单一生成模式，引入类似AI Agent的多轮搜索与迭代机制。用户输入文本提示后，Gen-Searcher会像人类设计师一样，先检索相似图像、分析风格特征、再逐步优化生成结果，而非一次性输出。

实验显示，Gen-Searcher在COCO和DreamBooth等主流数据集上，图像质量较Stable Diffusion等模型提升37%，尤其在复杂场景和细节控制上表现突出。这一突破标志着文生图从“直接生成”迈向“智能搜索-迭代”新范式，为国产AI图像工具提供了可落地的技术路径，对开发者和创意工作者具有重要参考价值。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-09-8)


---

## 💡 技术实践与深度洞察

### 1. 美团推出AI浏览器Tabbit，帮用户省下每天半小时

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04096b14a3afd55c.jpg)

美团旗下AI团队GN06正式推出AI浏览器Tabbit公测版（0.25），目标是让普通用户在日常浏览网页时，无需编程就能让AI自动完成信息整理、文案撰写、数据抓取等重复性工作。与传统AI聊天框不同，Tabbit深度嵌入浏览器上下文，能根据当前页面内容精准理解用户意图，比如自动识别网页中的错别字或跨页总结论文，大幅降低使用门槛。产品无缝兼容Chrome书签与账号，无需配置API，开箱即用。

Tabbit的核心竞争力在于开放性：不绑定美团自研模型，而是接入OpenAI、Claude、Gemini等主流模型，用户可自由切换，避免被单一模型限制。目前用户留存表现优异，已出现跨境电商从业者用其自动化运营、清华学生批量整理论文、盲人律师通过语音指令完成网页操作等真实案例。团队选择用C++重写浏览器内核，确保Windows端高性能运行，目标不是取代Chrome，而是成为知识工作者的效率工作站。

📎 [原文链接](https://36kr.com/p/3759372854706953?f=rss)


### 2. AI医疗助手如何靠人工把关？

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04098b28e603794a.png)

在医疗与生命科学领域，AI智能体正被用于自动化临床数据分析、药物研发和监管申报，但因涉及患者隐私和GxP合规要求，关键决策不能完全交由机器。本文介绍如何利用AWS服务构建人机协同（HITL）机制，在提升效率的同时确保人工审核介入，实现安全可控的AI落地。

这套方案为国内医疗AI企业提供了可借鉴的工程路径——尤其在面对国家数据安全与医疗器械监管日益严格的背景下，如何平衡自动化与人工监督，将成为国产医疗AI产品能否通过合规审查的关键。

📎 [原文链接](https://aws.amazon.com/blogs/machine-learning/human-in-the-loop-constructs-for-agentic-workflows-in-healthcare-and-life-sciences/)


### 3. Amazon Nova可通过Bedrock微调了

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04091d7a35600c62.png)

亚马逊正式开放Amazon Nova模型在Bedrock平台上的微调能力，开发者现在可基于自有数据训练专属AI模型。以意图分类器为例，用户能通过标注语料优化模型对特定业务场景的理解，配合超参数调优和损失曲线监控，显著提升任务准确率并减少响应延迟。

这一功能降低了企业定制大模型的门槛，尤其适合有垂直领域数据的客户，无需从头训练即可获得性能更优的AI服务。虽然不属国产模型，但作为AWS核心AI服务的重要升级，对国内使用云原生AI的开发者具有实用参考价值。

📎 [原文链接](https://aws.amazon.com/blogs/machine-learning/customize-amazon-nova-models-with-amazon-bedrock-fine-tuning/)


### 4. Claude Cowork高效使用17招

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04098f477df1496f.png)

Claude Cowork作为Anthropic推出的AI协作工具，常被误用为‘高级聊天机器人’，但海外开发者Nav Toor通过400多次实践发现，真正提升效率的关键不是写长提示词，而是建立系统化的上下文架构。他提出17个步骤，涵盖项目清单文件、全局指令、持久背景文件、子Agent调度等，强调‘花时间设好框架，后续只需短指令’，从而让AI像专业员工一样稳定输出高质量成果。

这套方法的核心是将AI工作流模块化、自动化：通过定制Skill、插件堆叠、定时任务连接Gmail/Notion等工具，实现无人值守的日常办公自动化；同时通过严格权限控制和文件隔离，规避误删、数据泄露等风险。对国内开发者而言，这套‘架构优先’的思路远比优化Prompt更有实操价值，尤其适合团队构建标准化AI工作流，提升协作效率。

📎 [原文链接](https://zhidx.com/p/547005.html)


---

## 🔬 学术与前沿研究

### 1. 单卡训练百亿大模型？MegaTrain颠覆训练范式

来自加州大学圣地亚哥分校的研究团队发布了一项突破性成果MegaTrain，通过内存优化与梯度压缩算法，首次实现在单张A100 GPU上完成超过1000亿参数大模型的全精度训练，无需模型并行或多卡协同。传统方法需数百张GPU，而该技术将训练成本压缩至原先的1%以下。

这一突破有望彻底改变中小团队和研究机构的AI研发门槛，让百亿级模型训练不再依赖超算资源，推动开源社区和国产AI生态加速发展。尽管目前仍属学术原型，但其工程思路已为未来高效训练提供全新路径。

📎 [原文链接](https://arxiv.org/abs/2604.05091)


### 2. 清华发布AutoSOTA：一周刷新105个SOTA

清华大学团队近日发布自动化AI科研工具AutoSOTA，该系统能自主设计、训练和优化模型，在短短七天内成功刷新了包括NeurIPS、ICLR、CVPR等顶会在内的105个当前最优（SOTA）结果，覆盖自然语言处理、计算机视觉等多个领域。

这一成果标志着AI科研正从‘人工调参’转向‘自动化创新’，大幅降低重复性实验门槛，让研究者更聚焦于核心问题。AutoSOTA的出现或将重塑AI论文的产出模式，推动行业回归真正的创新本质，而非算力竞赛。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-09-3)


### 3. 智能预测让集装箱少走冤枉路

解决了集装箱在码头里被反复搬运、浪费时间和资源的问题

用历史数据训练机器学习模型，精准判断哪些集装箱需要清关和会滞留多久

帮助码头合理安排堆场和设备，减少无效搬运，每年可节省大量运营成本

📎 [原文链接](https://arxiv.org/abs/2604.06251)


### 4. 让AI诊断更可靠：分离理解与推理

解决了AI在医疗诊断中胡说八道、无法追溯的问题

用代码规则做诊断推理，AI只负责听懂症状，不参与判断

可直接用于临床辅助诊断，也能推广到其他需要严谨推理的领域，省算力又更可信

📎 [原文链接](https://arxiv.org/abs/2604.06375)


---

## 🌐 行业风向与社区热议

### 1. Anthropic秘密部署AI漏洞猎手

![](https://www.artificialintelligence-news.com/wp-content/uploads/2026/03/image-5.png)

Anthropic最新AI模型Claude Mythos Preview在测试中自动发现了全球主流操作系统和浏览器中数千个潜在安全漏洞，远超人工检测能力。但公司并未像往常一样发布模型或公开细节，而是选择低调将成果交付给负责维护互联网基础设施的核心组织，如IETF、CA/Browser Forum等，协助定向修复。

这一做法标志着AI安全从‘技术展示’转向‘责任闭环’：企业不再追求舆论声量，而是优先保障实际系统安全。此举提升了AI在基础设施防护中的可信度，也为国内AI公司如何处理高风险发现提供了新范式，值得国内大厂关注。

📎 [原文链接](https://www.artificialintelligence-news.com/news/anthropic-keeps-new-ai-model-private-after-it-finds-thousands-of-external-vulnerabilities/)


### 2. 商汤发布家庭AI新终端可悠

商汤科技旗下绝影团队正式发布家庭AI智能终端产品可悠（Care U），这是国内首个实现跨手机、平板、智能屏、机器人等多设备无缝协同的AI家庭中枢，基于自研大模型技术，可实时理解用户多模态指令并调度不同终端协同响应。

可悠的发布标志着家庭AI从单一语音助手向全场景智能体演进，不仅提升居家服务效率，也为国产大模型在真实生活场景落地提供了新范式，对国内AI硬件生态具有重要推动意义。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-08-19)


### 3. Starlink高管空降掌舵xAI

![](images/d1820d044f9e.jpg)

埃隆·马斯克旗下AI公司xAI迎来重大人事调整，SpaceX旗下Starlink的高级副总裁迈克尔·尼科尔斯正式接任xAI总裁。尼科尔斯曾主导Starlink从0到1的卫星系统建设，拥有深厚工程管理经验。他上任后直言xAI当前模型训练效率‘低得令人尴尬’，并宣布即刻启动组织重组，目标是在未来两个月内显著提升算力效能。与此同时，xAI核心团队迎来多位来自谷歌、Meta、Mistral AI的AI专家，全面重构模型训练、产品与基础设施体系。

此次重组标志着xAI从‘创始人主导’转向‘工程化运营’，马斯克正以特斯拉和SpaceX的硬核工程文化重塑AI团队。随着多名联合创始人离职、人才召回计划启动，以及SpaceX工程师进驻xAI办公室，公司正试图通过整合星链的算力与运维经验，快速追赶OpenAI和谷歌。这一系列动作不仅关乎xAI能否突围，更可能重塑全球AI基础设施的竞争格局。

📎 [原文链接](https://zhidx.com/p/547319.html)


### 4. 众擎机器人完成2亿美元B轮融资

![](https://cdn.jsdelivr.net/gh/Lrcx/image-repo@master/blogs/04091e05c9ee4366.png)

国产人形机器人公司众擎机器人近日完成2亿美元B轮融资，估值突破百亿元人民币，成为国内机器人领域又一重磅融资案例。本轮融资由河南投资集团汇融基金领投，消费电子巨头立讯精密首次战略入局，联合领投，显示出制造业龙头对人形机器人产业化落地的强烈兴趣。

包括中创智领、龙岗金控、北京昌发展等多家地方国资与产业资本共同参与，老股东也全部跟投，反映出市场对国产机器人技术路径和商业化前景的高度认可。随着产业资本深度绑定，众擎有望加速产品落地，推动人形机器人从实验室走向工厂与场景化应用。

📎 [原文链接](https://36kr.com/newsflashes/3759548282995201?f=rss)


---

*以上内容由 AI 自动生成并整理，仅供参考。*

---

**声明：** 本日报内容来源于公开渠道，版权归原作者所有。