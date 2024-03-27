> 导读：苹果分享了其多模态模型的详情，Cerebras推出迄今为止最大的人工智能芯片，微软“收购”了Inflection AI，Stability AI首席执行官辞职，等等！

# 热点新闻

### MM1: 多模态大语言模型预训练的方法、分析和见解

![topnews1.jpeg](https://img2.imgtp.com/2024/03/27/4hLUr1Cb.jpeg)

苹果发布了一篇论文，详细介绍了其在训练多模态大型语言模型（MLLMs）方面的努力，重点关注了不同架构组件和数据选择的重要性。作者发现，在大规模多模态预训练中，平衡的图像-字幕、交错的图像-文本和仅文本数据的混合是实现最先进结果（SOTA）的关键。他们还发现，图像编码器、图像分辨率和图像标记数量具有显著影响，而视觉语言连接器的设计则不那么重要。接着，作者介绍了MM1，这是一个拥有多达300亿参数的多模态模型系列，包括密集模型和混合专家（MoE）变体。这些模型展示了优秀的预训练指标，并在各种多模态基准上进行了监督微调后表现出竞争力。

### Cerebras公布其下一代芯片规模人工智能芯片

![topnews2.jpeg](https://img2.imgtp.com/2024/03/27/tWCnfDM0.jpeg)

Cerebras推出了Wafer Scale Engine 3（WSE-3）。这是世界上最大的单一芯片，拥有4万亿个晶体管，比其前身增加了50%以上，采用了台积电的尖端5纳米技术。这一进步使得该芯片在不增加功耗的情况下性能翻倍，能够驱动新一代的人工智能超级计算机，包括即将在达拉斯完成的8-exaflop（每秒80亿亿次操作）超级计算机。采用WSE-3芯片的CS-3计算机旨在训练极大规模的神经网络模型，其尺寸可达24万亿个参数，这比当前最大的语言模型如OpenAI的GPT-4的能力高出10倍以上。此外，Cerebras宣布与高通达成合作伙伴关系，旨在将人工智能推理的成本降低十倍，有可能彻底改变人工智能技术的可及性和可持续性。

### 微软聘请DeepMind联合创始人穆斯塔法·苏莱曼（Mustafa Suleyman）负责新的消费者人工智能部门

![topnews3.jpeg](https://img2.imgtp.com/2024/03/27/jPPTZPH3.jpeg)

微软宣布聘请谷歌DeepMind联合创始人、AI初创公司Inflection的首席执行官穆斯塔法·苏莱曼（Mustafa Suleyman）领导公司内的新消费者人工智能部门，命名为Microsoft AI。此举旨在通过让苏莱曼领导下的消费者人工智能部门整合微软面向消费者的产品，加强微软在生成式人工智能市场的地位。新部门将专注于将人工智能技术融入微软的产品，包括用于Windows的AI增强版Copilot以及改进Bing搜索引擎的生成式人工智能功能。此次招聘还包括Inflection团队的一些关键成员，包括Karén Simonyan担任首席科学家等重要人物。

### Stability AI的首席执行官辞职，以“追求分散式人工智能”为由

![topnews4.jpeg](https://img2.imgtp.com/2024/03/27/i6PApiMQ.jpeg)

Stability AI的首席执行官Emad Mostaque辞去了他的职务，以专注于分散式人工智能为由，这一举动是在公司其他关键开发人员最近离职之后进行的。在此期间，首席运营官Shan Shan Wong和首席技术官Christian Laforte将作为联合首席执行官，同时董事会将寻找永久性的替代者。这一领导层变动发生在人工智能初创公司世界动荡的时期，与此同时，竞争对手初创公司Inflection AI失去了关键人员，他们转投微软。尽管面临这些挑战，Stability AI仍在继续开发和商业化其人工智能产品，包括其旗舰产品Stable Diffusion和最新模型Stable Cascade，同时还提供付费会员资格以供商业用户使用其模型。


---
## 工具篇

![tools.jpeg](https://img2.imgtp.com/2024/03/27/Pdhr2YDM.jpeg)

* 英伟达在其GTC开发者大会上推出了GR00T，这是一个面向人形机器人的基础模型，同时还发布了重要的机器人技术声明。 [链接](https://spectrum.ieee.org/nvidia-gr00t-ros)

* 英伟达发布了Blackwell B200 GPU，提供高达20 petaflops的FP4运算能力，对LLM推理工作负载的性能提升达到30倍，可能具有显著的效率提升。 [链接](https://www.theverge.com/2024/3/18/24105157/nvidia-blackwell-gpu-b200-ai)

* 推出 Stable Video 3D，这是一个生成模型，通过从单张图像生成高质量的多视角和3D网格，推进了3D技术，具有两种不同应用的变体。 [链接](https://stability.ai/news/introducing-stable-video-3d)

* Nvidia的人工智能“数字人类”工具被开发人员用于为视频游戏角色提供语音、动画和对话生成，从而实现独特的玩家互动和实时反应。 [链接](https://www.theverge.com/2024/3/19/24105681/nvidia-ai-ace-video-game-character-npc-covert-protocol)

* AI视频生成技术正在通过提供新的视频内容创建和操作方式，彻底改变各个行业。而Open-Sora的开发标志着该领域的重大进步，提供了一种经济高效的解决方案，拓宽了内容创作者的视野。 [链接](https://www.marktechpost.com/2024/03/07/colossal-ai-team-introduces-open-sora-an-open-source-library-for-video-generation/)

* Adobe Substance 3D的人工智能功能通过使用文本描述来为3D模型生成逼真的纹理和背景图像，简化了3D工作流程。 [链接](https://www.theverge.com/2024/3/18/24104718/adobe-firefly-substance-sampler-stager-3d-tools-beta)

* Google DeepMind的TacticAI利用人工智能分析利物浦足球俱乐部的角球数据，并提供建议以确定球员的位置并预测结果。 [链接](https://www.technologyreview.com/2024/03/19/1089927/google-deepminds-new-ai-assistant-helps-elite-soccer-coaches-get-even-better/)


---
## 商业篇

![business.jpeg](https://img2.imgtp.com/2024/03/27/wQmvrWwz.jpeg)

* 沙特阿拉伯计划投资400亿美元用于人工智能，旨在成为全球最大的人工智能投资者，并实现经济多元化。 [链接](https://www.nytimes.com/2024/03/19/business/saudi-arabia-investment-artificial-intelligence.html)

* 丹麦与英伟达合作建立一个国家人工智能创新中心，拥有世界上最强大的人工智能超级计算机之一，以加速医疗保健、生命科学以及绿色转型等领域的研究和创新。 [链接](https://novonordiskfonden.dk/en/news/denmark-to-build-one-of-the-worlds-most-powerful-ai-supercomputers-accelerating-solutions-to-societal-challenges/)

* 人工智能被用于设想治疗疾病的方法，像Insilico这样的公司利用人工智能加速药物的发现和开发，有可能彻底改变数字生物学领域。 [链接](https://www.technologyreview.com/2024/03/20/1089939/a-wave-of-drugs-dreamed-up-by-ai-is-on-its-way/)

* 苹果正在与谷歌就将谷歌的Gemini人工智能引擎整合到iPhone中进行谈判，这可能会动摇人工智能行业，并为iPhone软件引入新功能。 [链接](https://www.bloomberg.com/news/articles/2024-03-18/apple-in-talks-to-license-google-gemini-for-iphone-ios-18-generative-ai-tools)

* 苹果已收购加拿大人工智能初创公司DarwinAI，以增强其人工智能技术，并提高其供应链的效率。 [链接](https://qz.com/apple-generative-ai-buy-canadian-startup-darwinai-1851336368)

* 微软支付6.5亿美元购买Inflection AI的软件许可，并雇佣了大部分员工，引发了潜在的反垄断担忧。 [链接](https://www.bloomberg.com/news/articles/2024-03-21/microsoft-to-pay-inflection-ai-650-million-after-scooping-up-most-of-staff)

* 62%的游戏工作室在游戏开发过程中使用人工智能，AI工具改善了交付和运营，缩短了原型制作时间，并在世界构建中提供了帮助，而一些开发者因缺乏时间或技术知识而犹豫不决。 [链接](https://www.eurogamer.net/ai-already-used-by-62-of-studios-unity-report-claims)

* 英伟达和Hippocratic AI开发了AI“代理”，在视频通话中的表现优于人类护士，每小时成本显著较低，并旨在通过“超低延迟的对话反应”与患者建立人际关系。 [链接](https://www.foxbusiness.com/technology/nvidia-announces-ai-powered-health-care-agents-outperform-nurses-cost-9-hour)


---
## 科研篇

![research.jpeg](https://img2.imgtp.com/2024/03/27/hs2NL7K3.jpeg)

* 人工智能利用强化学习教会了一个双腿机器人跑步、跳跃，并在新情景下进行适应，使其能够执行各种动态动作，无需针对每个动作进行显式训练。 [链接](https://www.technologyreview.com/2024/03/18/1089899/how-ai-taught-cassie-the-two-legged-robot-to-run-and-jump/)

* 像ATT3D这样的摊销方法同时优化多个提示，以提高效率，实现快速的文本到3D合成，但LATTE3D解决了限制，以在显着更大的提示集上实现快速、高质量的生成。 [链接](https://research.nvidia.com/labs/toronto-ai/LATTE3D/)

* 引入了一个名为DROID的大规模机器人操作数据集，其中包含了作者和贡献者的详细清单。 [链接](https://droid-dataset.github.io/)

* 学术期刊正在发布由人工智能生成的科学论文，其中包含ChatGPT短语“根据我最近的知识更新”。 [链接](https://www.404media.co/email/a2a944f8-235a-4c75-8d00-955edbbfcb4e/)


---
## 重点关注

![concerns.jpeg](https://img2.imgtp.com/2024/03/27/YzjWzezU.jpeg)

* OpenAI的GPT商店面临着垃圾信息、版权侵权、学术不诚实、冒充以及试图越狱OpenAI模型的问题，引发了对可用的GPT质量和合法性的担忧。 [链接](https://techcrunch.com/2024/03/20/openais-chatbot-store-is-filling-up-with-spam/)

* 由人工智能生成的深度伪造色情内容是一个普遍存在的问题，影响着成千上万的名人，英国的立法旨在解决这个问题。 [链接](https://www.theguardian.com/technology/2024/mar/21/celebrities-victims-of-deepfake-pornography)

* 旧金山湾区的一位研究人员探讨人工智能的潜在危险，为志同道合的人举办晚宴，并进行关于人工智能存在风险的推测性讨论。 [链接](https://www.newyorker.com/magazine/2024/03/18/among-the-ai-doomsayers)

* 美国各州正在领导监管深度伪造技术，特别是在政治和色情领域，至少有15个州通过了法律来解决这个问题，而联邦立法者正在提出各种法案，以在所有五十个州建立统一标准。 [链接](https://www.ignorance.ai/p/states-are-racing-ahead-of-congress)

* 中国社交平台开始打击以过度定价销售肤浅的人工智能课程的网红，导致其内容被删除并暂停其账户。 [链接](https://www.technologyreview.com/2024/03/20/1089950/ai-influencer-douyin-wechat-suspension/)


---
## 趣事

![fun.png](https://img2.imgtp.com/2024/03/27/R6TRZPBU.png)

* 作者尝试使用文本到图像模型，并分享了他们最受欢迎的10个人工智能图像系列以及用于生成它们的简单提示，倡导少即是多的方法，并强调了创作人工智能生成图像的乐趣。 [链接](https://www.whytryai.com/p/my-popular-text-to-image-series)


---
> Copyright © 2024 AI DECA SHOW, All rights reserved.