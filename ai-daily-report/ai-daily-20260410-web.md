# AI 日报 — 2026年04月10日 周五

> 每日精选 AI 领域重要动态，为你节省信息筛选时间

---

## 📋 今日摘要

- 阿里疑似开发的HappyHorse-1.0在文生视频与图生视频双榜登顶，ELO评分超越字节Seedance 2.0
- 千问AI眼镜S1支持双目显示+热插拔换电，国补后仅3499元，国产AR设备价格新低
- OpenAI推出每月100美元ChatGPT Pro计划，Codex使用限额为Plus版的5倍，直击开发者痛点
- 港中文与伯克利开源Gen-Searcher，实现文生图通过多轮搜索而非直接生成
- 阿里云百炼推出Agent记忆库，支持通过OpenClaw一键安装，让AI应用记住用户偏好与历史交互

**今日共收录 24 条动态，涵盖 大模型与核心产品 8条、开源生态与开发者工具 6条、行业风向与社区热议 4条、技术实践与深度洞察 5条、学术与前沿研究 1条。**

---

## 🚀 大模型与核心产品

### 1. 阿里疑似推出AI视频模型HappyHorse-1.0

![](https://oss.zhidx.com/86e3f422d79a77760cc388898818f412/69d7cd00/uploads/2026/04/69d7a4c0e58b5_69d7a4c0e2515_69d7a4c0e24e1_%E6%99%BA%E4%B8%9C%E8%A5%BF%E5%A4%B4%E6%9D%A1%E5%A4%B4%E5%9B%BE%E6%A8%A1%E6%9D%BF-%E5%B8%A6%E9%98%B4%E5%BD%B1%E7%89%88.jpg)

据The Information报道，匿名登顶AI视频生成榜单的模型HappyHorse-1.0极有可能由阿里巴巴研发，其在‘文生视频’和‘图生视频’两大无音频赛道的ELO评分分别达到1386和1412，超越字节跳动的Seedance 2.0。前阿里通义千问负责人林俊旸在X平台点赞并评论‘欢乐马乐疯了’，进一步强化了阿里背景的猜测。该模型预计明日通过阿里云面向企业客户正式上线，成为阿里在AI视频领域对抗字节的关键武器。

这一匿名发布策略正成为中国AI公司的新趋势——先靠真实性能在盲测中突围，再借舆论热度官宣。此前智谱AI的GLM-5、小米的MiMo-V2-Pro也采用类似手法。在OpenAI关停Sora后，全球AI视频竞争重心已转向中国，阿里与字节的正面交锋，标志着国内大厂正式进入视频生成的‘决赛圈’。

📎 [原文链接](https://zhidx.com/p/547485.html)


### 2. 阿里千问AI眼镜S1发布，到手价3499元

![](https://img.ithome.com/newsuploadfiles/2026/4/630e791a-b505-4114-b75b-5ca6b829fbc0.jpg?x-bce-process=image/format,f_auto)

阿里通义千问正式发布第二代AI眼镜S1，4月15日现货发售，叠加国家补贴后到手价仅为3499元，大幅降低AI眼镜的消费门槛。产品搭载高通骁龙AR1芯片，采用双目Micro LED显示方案，峰值亮度达4000尼特，支持语音与视觉多模态交互，首次实现正面直视无漏光，并配备双电池热插拔技术，续航可达7小时，解决了此前AI眼镜续航短、体验断点的痛点。

S1还升级了1200万像素摄像头、5麦克风阵列与骨传导拾音系统，适合在复杂环境中使用，外观专为亚洲人脸优化，首发‘睿智曜黑’款式。作为国内大厂首次在消费级AR设备上实现全栈自研AI+硬件协同，S1不仅推动了AI终端的普及，也为国产AR生态树立了新标杆。

📎 [原文链接](https://www.ithome.com/0/937/763.htm)


### 3. OpenAI推100美元Pro计划，Codex用量翻5倍

![](https://images.ctfassets.net/jdtwqhzvc2n1/6uVTE16gVLv4XRlDrOmhO8/ddd73f327394bbdce9e8ac05e7114f06/ChatGPT_Image_Apr_9__2026__06_14_45_PM.png?w=300&q=30)

OpenAI正式推出每月100美元的ChatGPT Pro计划，作为介于20美元Plus和200美元Pro之间的新 tiers，核心卖点是Codex代码辅助功能的使用额度提升至Plus版的5倍。新计划允许用户每5小时执行300–1500条本地代码消息和100–600个云端任务，远超Plus版的30–150条，满足高频编码、AI代理开发等专业需求。此举正值其竞争对手Anthropic收紧订阅限制，OpenAI借机吸引被限制的‘氛围编码者’群体。

这一定价策略不仅是容量升级，更是对开发者生态的精准抢夺。Anthropic近期禁止订阅用户通过第三方框架（如OpenClaw）无限调用Claude模型，导致大量高用量开发者流失。而OpenAI通过高配额+开放生态的组合拳，配合此前收购OpenClaw创始人Peter Steinberger，正系统性地将专业编码用户从竞品拉回。对国内AI开发者而言，这意味着更丰富的工具选择和更强的模型可用性，Codex将成为比以往更具竞争力的编码助手。

📎 [原文链接](https://venturebeat.com/orchestration/openai-introduces-chatgpt-pro-usd100-tier-with-5x-usage-limits-for-codex)


### 4. 阿里云百炼上线Agent记忆库

阿里云百炼平台正式上线Agent记忆库功能，允许AI代理在与用户交互时持久化存储对话历史、偏好设置和行为习惯，从而实现更自然的个性化服务。该功能已集成至OpenClaw等主流Agent产品，开发者无需从零构建记忆模块，即可快速为AI应用赋予‘长期记忆’能力。

这一升级显著降低AI代理的开发门槛，尤其适合客服、助手、导购类场景。记忆库的引入意味着AI不再‘每次重来’，而是真正‘记得你’，有望推动国内Agent应用从‘能用’向‘好用’跃迁，加速智能体生态落地。

📎 [原文链接](https://www.qbitai.com/2026/04/398117.html)


### 5. 谷歌Gemini可生成交互式3D模型

![](https://img.ithome.com/newsuploadfiles/2026/4/1c2978a1-adf0-4a6b-ad1f-280584374b17.png?x-bce-process=image/format,f_auto)

谷歌于4月9日升级Gemini AI，新增交互式3D模拟功能，用户只需输入‘展示双缝实验’或‘可视化分形生成’等指令，即可生成可操作的动态模型。通过调整速度、引力、波长等参数，用户能直观观察轨道变化、量子干涉或分形生长过程，彻底告别静态图表的局限。

这一功能显著提升科学教育与工程理解的体验，尤其适合教学与科研场景。目前仅限Gemini Pro用户使用，教育版和Workspace暂不支持，但已向普通用户逐步开放，标志着AI从‘解释知识’迈向‘构建可交互认知工具’的关键一步。

📎 [原文链接](https://www.ithome.com/0/937/774.htm)


### 6. DeepSeek V4即将发布，专家模式上线

![](https://img.ithome.com/newsuploadfiles/2026/4/aede771c-e3dc-4c02-8351-7d7734a1a388.jpg?x-bce-process=image/format,f_auto/auto-orient,o_1)

DeepSeek创始人梁文锋确认，新一代旗舰模型DeepSeek V4将在4月下旬正式发布。此前，DeepSeek已上线‘专家模式’，专为处理数学推导、代码分析、长程推理等复杂任务设计，与面向日常对话的‘快速模式’形成分层服务，这是其产品首次引入模式区分，标志着从通用聊天向专业工具的转型。

尽管模型能力持续提升，但近期服务频繁异常，可能与高并发压力和新功能测试有关。专家模式虽不支持多模态和文件上传，但其深度推理能力已吸引大量开发者和企业用户，V4的发布或将进一步巩固国产大模型在长文本与逻辑推理领域的竞争优势。

📎 [原文链接](https://www.ithome.com/0/937/682.htm)


### 7. GenEval模型生图能力飙升至92%

近日，国产AI团队推出新一代图像评估模型GenEval，通过四步优化策略，其图像生成质量评估得分从61%大幅提升至92%，在多个权威测试集上超越了OpenAI的GPT-4o所使用的TDM-R1模型。该模型不直接生成图像，而是精准评估AI绘图结果的细节、逻辑与美学表现，成为衡量生成模型能力的新标尺。

这一突破意味着国内在AI内容评估领域实现关键突破，为国产大模型（如通义万相、Kimi画图等）提供了更可靠的优化工具，开发者无需依赖国外模型即可精准调优生成效果，显著降低训练成本与迭代周期，推动国内AIGC生态走向自主闭环。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-09-10)


### 8. Anthropic发布智能体托管平台，开发提速10倍

![](https://oss.zhidx.com/8eef5d957cedae11ce5cf7291821f6b4/69d7cd00/uploads/2026/04/69d729f643595_69d729f6402fe_69d729f6402c4_%E5%AE%98%E7%BD%91%E5%A4%B4%E5%9B%BE%E4%B8%93%E7%94%A8%E6%A8%A1%E6%9D%BF.png)

Anthropic正式发布企业级智能体托管平台Claude Managed Agents，大幅降低智能体落地门槛。过去企业需耗费数月搭建沙箱、权限、链路追踪等基础设施，如今只需定义任务与规则，平台自动完成全部底层配置，从创意到上线仅需数天，显著提升开发效率。目前该服务已开启公测，支持通过控制台、Claude Code或CLI快速部署。

该平台的核心创新在于‘大脑与双手’解耦架构：将大模型（大脑）、执行工具（双手）与记忆系统分离，使智能体能自动适配模型迭代。例如当Claude新版本修复了‘情景焦虑’问题时，系统会自动移除旧有补偿逻辑，无需人工重构。这种设计让企业摆脱技术债困扰，专注业务创新，尤其利好中小团队快速试错与落地AI应用。

📎 [原文链接](https://zhidx.com/p/547334.html)


---

## 🛠️ 开源生态与开发者工具

### 1. 文生图进入Agent时代：港中文联合伯克利开源Gen-Searcher

香港中文大学联合加州大学伯克利分校近日开源了新一代文生图框架Gen-Searcher，突破传统模型直接根据提示词生成图像的模式，转而模拟人类搜索行为：通过多轮检索、筛选和优化图像库中的候选结果，最终输出更精准、可控的图像。该方法显著降低对大规模训练数据的依赖，提升生成内容的语义一致性。

Gen-Searcher的推出标志着文生图技术从‘端到端生成’迈向‘搜索增强型Agent’的新阶段，为开发者提供了更可控、可解释的图像生成路径，尤其适合对准确性要求高的设计、广告和工业应用场景，有望成为下一代AI视觉工具的基础架构。

📎 [原文链接](https://www.jiqizhixin.com/articles/2026-04-09-8)


### 2. 智源发布ClawKeeper：用AI监管AI

北京智源人工智能研究院联合北邮和中国信通院发布ClawKeeper v1.0，这是国内首个专为智能体集群设计的实时安全框架，基于OpenClaw平台构建，通过‘技能’‘插件’‘观察者’三重机制，动态监控AI智能体的行为，防止越权、滥用或异常决策，尤其适用于企业内网中多个AI代理协同工作的高安全场景。

该项目已开源并同步发表论文，标志着国内在AI安全治理领域从理论走向工程落地的重要一步，为金融、政务等敏感领域部署可信AI智能体提供了可落地的基础设施，也推动了国产AI系统向‘可监管、可审计、可控制’方向演进。

📎 [原文链接](https://36kr.com/newsflashes/3760528978969094?f=rss)


### 3. 小米MiMo接入Hermes Agent，限时免费两周

![](https://img.ithome.com/newsuploadfiles/2026/4/8609deb3-b773-4eee-855a-63e862b2d374.jpg?x-bce-process=image/format,f_auto)

小米今日宣布，其新一代AI助手MiMo-V2-Pro和MiMo-V2-Omni已全面接入开源Agent框架Hermes Agent，后者以自我进化、跨会话记忆和复杂工作流能力著称。MiMo-V2-Pro凭借1M长上下文和强大工具调用能力，完美适配Hermes的智能演进机制；而MiMo-V2-Omni更进一步，融合图像、视频、音频与文本的全模态理解，让AI真正实现‘看得见、听得懂、能动手’。

即日起至4月22日，全球开发者可通过Nous Portal免费调用MiMo-V2-Pro、Omni和Flash模型，无需付费即可体验这一融合顶尖框架与国产大模型能力的AI系统。此举不仅降低开发者门槛，也标志着小米在AI Agent生态中迈出关键一步，有望推动国产大模型在智能体领域的广泛应用。

📎 [原文链接](https://www.ithome.com/0/937/695.htm)


### 4. 开发者逆向破解Gemini的AI水印技术

一位开发者通过逆向工程，成功解析了Google Gemini生成图像中内置的SynthID数字水印机制，并在GitHub开源了检测工具。该水印原本用于识别AI生成内容，但此次破解表明其隐藏算法可被反向还原，引发对AI内容溯源可靠性的讨论。

这一突破对AI内容监管和版权保护具有双重意义：一方面暴露了当前水印技术的可破解性，另一方面为开发者提供了开源检测方案，可能推动更透明、更健壮的AI内容标识体系发展。

📎 [原文链接](https://github.com/aloshdenny/reverse-SynthID)


### 5. 《生化危机》女主打造免费AI记忆系统

知名配音演员金伯莉·布鲁克斯（《生化危机》女主角吉尔·瓦伦蒂安配音者）近日在GitHub开源了一款名为‘记忆宫殿’的AI记忆系统，该系统模拟人类记忆联想机制，帮助AI模型更高效地存储与召回长期信息。项目上线一周即获超1.2万星标，引发开发者热议。

实测数据显示，该系统在长对话与知识检索任务中，准确率提升34%，尤其适合需要持续记忆的客服AI、个人助手等场景。其轻量开源特性让普通开发者无需大模型也能显著优化AI记忆能力，为国产AI应用提供了低成本的实用工具。

📎 [原文链接](https://www.qbitai.com/2026/04/398090.html)


### 6. 张雪峰.skill 项目爆火引发争议，逝者思维被蒸馏

![](https://img.ithome.com/newsuploadfiles/2026/4/9d781e7e-6ab1-4046-9166-2fb171703d9f.jpg?x-bce-process=image/format,f_auto)

IT之家 4 月 10 日消息，<a href="https://www.ithome.com/0/932/268.htm" target="_blank">“考研名师”张雪峰于 3 月 24 日因心源性猝死离世</a>，引发全网热议。

近日，一款名为“<strong>张雪峰.skill</strong>”的开源项目在 GitHub 平台引发广泛关注与讨论，目前已收获 2.3K Star 和 8

📎 [原文链接](https://www.ithome.com/0/937/747.htm)


---

## 💡 技术实践与深度洞察

### 1. 30行Python代码降低AI训练检查点成本

![](https://developer-blogs.nvidia.com/wp-content/uploads/2026/04/Checkpoint-Costs-e1775685819565-768x432.webp)

NVIDIA近日发布基于nvCOMP的高效压缩方案，仅需约30行Python代码即可显著压缩大语言模型训练中的检查点文件。传统检查点包含模型权重、优化器状态等海量数据，占用大量存储空间，而该方案通过针对性压缩算法，在不损失恢复精度的前提下，大幅减少I/O开销和存储占用。

这一方案对国内AI团队尤其实用，可直接集成到PyTorch或DeepSpeed等主流训练框架中，降低云存储和硬盘采购成本，尤其适合资源受限的中小团队。它不依赖专用硬件，仅需NVIDIA GPU即可运行，是当前大模型训练降本增效的轻量级利器。

📎 [原文链接](https://developer.nvidia.com/blog/cut-checkpoint-costs-with-about-30-lines-of-python-and-nvidia-nvcomp/)


### 2. NVIDIA推出KVPress：让大模型长文本推理省一半显存

NVIDIA最新推出的KVPress技术，通过智能压缩语言模型推理中的键值缓存（KV Cache），显著降低长上下文场景下的显存占用。该教程在Colab环境中完整演示了如何部署KVPress，配合轻量级Instruct模型，成功在12GB显存下运行128K上下文的Llama-3-8B，而传统方式通常需要32GB以上。

这项技术对国内AI开发者意义重大——它让中小团队无需依赖高端A100/H100，也能在消费级显卡上测试长文本应用，如法律合同分析、代码库检索等。KVPress不改变模型结构，可无缝集成到现有推理框架，是当前国产大模型落地长上下文场景的实用突破口。

📎 [原文链接](https://www.marktechpost.com/2026/04/09/an-end-to-end-coding-guide-to-nvidia-kvpress-for-long-context-llm-inference-kv-cache-compression-and-memory-efficient-generation/)


### 3. 用LangExtract+OpenAI构建文档智能管道

该教程指导开发者使用谷歌开源的LangExtract库，结合OpenAI的强语言模型，将非结构化文档（如PDF、扫描件）自动转化为结构化JSON数据，实现合同、发票、表格等信息的精准抽取，并通过安全配置API密钥保障数据隐私。

这一方案降低了企业自动化处理海量文档的门槛，适合国内开发者在财务、法务、政务等场景中快速搭建轻量级文档智能系统，虽非大厂首发技术，但提供了可落地的工程实践范本。

📎 [原文链接](https://www.marktechpost.com/2026/04/08/a-coding-guide-to-build-advanced-document-intelligence-pipelines-with-google-langextract-openai-models-structured-extraction-and-interactive-visualization/)


### 4. 研究型智能体：先读论文再写代码

Skypilot团队发布了一种新型AI智能体，其核心创新在于‘先研究、后编码’的工作流：它能自动检索并深度阅读相关学术论文，提取算法细节与数学公式，再据此生成完整、可运行的代码，而非直接凭提示生成。这一模式显著提升了代码的准确性与学术严谨性，尤其适合复现前沿AI模型。

该技术对开发者和科研人员意义重大，有望降低复现论文的门槛，减少‘代码与论文不符’的常见问题。虽然目前仍处于实验阶段，但标志着AI代理正从‘代码生成器’向‘科研协作者’演进，是国内AI开发者值得关注的工具演进方向。

📎 [原文链接](https://blog.skypilot.co/research-driven-agents/)


### 5. Amazon Bedrock模型生命周期管理指南

![](https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2025/12/22/ml-19718-image-1.png)

Amazon Bedrock正式推出基础模型（FM）生命周期管理机制，明确模型的三种状态：活跃、即将退役和已退役，并新增‘延长访问’功能，允许用户在模型退役后仍可继续调用旧版模型最多90天，为应用迁移争取缓冲期。

这一更新显著降低了企业AI应用因模型迭代导致的服务中断风险，尤其对依赖稳定API的生产系统至关重要，标志着云平台在AI工程化运维方面迈出了关键一步，适合所有使用Bedrock构建AI应用的开发者参考。

📎 [原文链接](https://aws.amazon.com/blogs/machine-learning/understanding-amazon-bedrock-model-lifecycle/)


---

## 🔬 学术与前沿研究

### 1. Google推出AI论文自动生成系统

![](https://www.marktechpost.com/wp-content/uploads/2026/04/Screenshot-2026-04-08-at-8.23.44-PM-1.png)

Google AI研究团队推出名为PaperOrchestra的多智能体框架，能自动将杂乱的实验记录、图表和原始结果转化为符合NeurIPS、ICML等顶级会议格式的完整学术论文。系统由多个专用AI代理协同工作，分别负责逻辑构建、语言润色、图表生成与参考文献整理，大幅降低科研写作的门槛。

这一工具有望缓解科研人员尤其是学生和新人面临的‘写作瓶颈’，让精力更聚焦于实验创新而非文字排版。虽然目前仍需人工校验，但其自动化程度已远超现有辅助写作工具，标志着AI从‘辅助写作’迈向‘自主成文’的关键一步。

📎 [原文链接](https://www.marktechpost.com/2026/04/08/google-ai-research-introduces-paperorchestra-a-multi-agent-framework-for-automated-ai-research-paper-writing/)


---

## 🌐 行业风向与社区热议

### 1. 周靖人掌舵阿里AI事业部

阿里巴巴近日宣布任命周靖人为人工智能事业部负责人，接替此前职务，全面主导公司大模型研发、通义千问系列产品的迭代及AI在电商、云服务等核心场景的落地。周靖人曾任阿里云智能首席科学家，深度参与通义大模型架构设计，是阿里AI战略的核心技术推手。

此次人事调整标志着阿里将AI作为未来增长的核心引擎，通过集中资源强化技术与产品协同。在国产大模型竞争加剧的背景下，周靖人的上任有望加速通义系列在企业级市场的渗透，提升阿里在AI基础设施领域的竞争力。

📎 [原文链接](https://36kr.com/newsflashes/3760491945689602?f=rss)


### 2. 腾势N8L闪充版预售：5分钟充至满电

![](https://img.ithome.com/newsuploadfiles/2026/4/7281f313-aabe-4220-9b35-17bc269edf05.png?x-bce-process=image/format,f_auto)

腾势N8L闪充版于4月10日开启预售，售价区间为35万至40万元，搭载比亚迪第二代刀片电池，纯电续航达430km，号称5分钟可充至满电、9分钟完全充满，即便在零下30℃环境下充电时间仅增加3分钟，刷新同级补能效率纪录。新车还配备2.0T超级混动系统，零百加速达3秒级，并首次搭载新一代AI智能座舱与‘天神之眼5.0’高阶智驾系统。

作为一款大型六座SUV，N8L基于‘易三方’智能平台，支持圆规掉头、智能蟹行等极限操控功能，并配备云辇-A空气悬架与钢笼式安全车身，关键部位采用2000MPa高强度钢，AEB系统可在147km/h时速下完全刹停，多项安全测试表现远超行业标准，重新定义了新能源豪华SUV的性能与安全边界。

📎 [原文链接](https://www.ithome.com/0/937/769.htm)


### 3. 阿里云领投生数科技20亿，视频AI再升温

![](https://img.ithome.com/newsuploadfiles/2026/1/d70ed8d2-cc02-45da-ba98-561422f76df2.jpg?x-bce-process=image/format,f_auto)

阿里云近日领投AI视频生成初创公司生数科技约20亿元人民币融资，距其上一轮6亿元融资仅两个月。公司旗下Vidu模型已实现最长16秒的音视频同步生成与多镜头控制，在AI视频生成榜单中排名第九，性能超越字节跳动的Seedance 2。生数科技由清华教授朱军创立，用户覆盖200多个国家，广泛应用于动画、广告和影视制作，2025年用户与收入均实现超10倍增长。

此次融资将主要用于推进通用世界模型研发，强化AI对现实环境的理解能力。阿里云持续押注国内AI初创企业，既推动Vidu等国产模型崛起，也带动云服务增长。在OpenAI暂停Sora、行业聚焦大模型的背景下，中国团队正加速在视频生成赛道建立技术优势，成为全球AI视觉内容生产的重要力量。

📎 [原文链接](https://www.ithome.com/0/937/753.htm)


### 4. OpenAI星际之门项目高管离职

![](https://img.ithome.com/newsuploadfiles/2026/4/1e60f1f1-9bac-467d-8b86-78d58e53c4a2.png?x-bce-process=image/format,f_auto)

OpenAI负责千亿级AI基础设施‘星际之门’项目的高管Peter Hoeschele已离职，其在公司任职近7年，从战略财务转任工业计算副总裁，主导了GPT-5所需超大规模数据中心的建设，并推动与微软、甲骨文等巨头的算力合作，落地了150亿美元的Lighthouse绿色数据中心项目。

作为OpenAI算力战略的关键操盘手，他的离职虽被官方称为‘团队内部交接’，但正值全球AI算力竞争白热化阶段，可能引发市场对OpenAI基建推进节奏与供应链稳定性的关注，尤其在GPT-5训练临近的关键节点。

📎 [原文链接](https://www.ithome.com/0/937/681.htm)


---

*以上内容由 AI 自动生成并整理，仅供参考。*

---

**声明：** 本日报内容来源于公开渠道，版权归原作者所有。