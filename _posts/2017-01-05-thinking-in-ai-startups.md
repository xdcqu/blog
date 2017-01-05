---
id: 1324
title: AI 创业的一点思考
date: 2017-01-04T12:33:01+00:00
author: Eric Xu
comments: true
layout: post
guid: http://blog.youxu.info/?p=1324
permalink: /2017/01/04/thinking-in-ai-startups/
categories:
  - startup
tags:
  - deep-learning
comments: true
---

2016 年 8 月，我从 Fitbit 离职创业，做一个[用 AI 帮助程序员更好的写代码的公司](www.ai.codes)。在过去的四个月里，通过无数的模型，产品和数据的迭代，加之和用户交谈，以及观察其他的创业者，我积累了一些想法，写下来抛砖引玉。

#### 此 AI, 是名 AI, 非 AI.

这一波的 “AI” 创业热潮，准确的说应该是“深度学习算法”创业潮。人工智能本身是一个涵盖极大的领域，除了学习和表示（深度学习的主要领域）之外，还有推理，规划等等其他大量分支。普通人理解的人工智能，大多数都是“强人工智能”的范畴（一个可以完全代替人的智慧的机器）。而大量的创业公司都纷纷采用 .ai 做为域名后缀，实质上只是在“深度学习”这个子领域，解决一些特定的，以前只能靠人的智慧才能解决的问题。

就和 .com 时代一样，域名后缀的符号意义远大于实际意义。媒体，投资人和创业者都默默接受了 .ai 这个集体幻觉。总的来说，目前 AI 公司的井喷，是深度学习这项技术完成其技术扩散 ([diffusion of innovations](https://en.wikipedia.org/wiki/Diffusion_of_innovations)) 的体现。在 Google, Facebook 等技术领先企业的示范和大笔收购下，风险投资大量向 AI 倾斜。许多掌握机器学习和深度学习的人才，认识到深度学习可以用来解决一个具体的问题，也流动到创业公司开始创业。因为 AI 入门门槛很高，目前还是很容易从创业者的教育和工作经历来甄选到底一个公司做的是不是深度学习，还是挂羊头卖狗肉的。

#### 深度学习的确“创造”了许多创业公司可以挑战的新问题

有许多了解和从事机器学习的人，并不觉得这一波的“深度学习”技术有多神奇。这是可以理解的，因为深度学习的主要技术 30 年前都齐备了，只是最近被某种魔法召唤出来。在我看，这一波的 AI 创业潮，不是泡沫，是对多年没有在工业界铺开的机器学习技术的复仇。过去的十多年中，我们经历了互联网时代，社交网络时代和移动时代。有了众多的站点，社交网络和应用。机器学习和云计算解决了许多问题，如搜索引擎，大数据处理，但仍有许多问题，如图像，视频，语音，自然语言的处理，都是传统的机器学习方法没有能很好解决的。深度学习的出现，使得解决这些问题成为了可能。

解决问题的工具进化后，以前大家没觉得是问题的（主要是解决不了），现在变成了问题。一个最简单的例子是自动驾驶。我在 Google 自动驾驶部门工作的时候，视觉系统还是用的传统的物体识别方法，有许多规则和边界情况要额外处理。汽车一方面需要额外引入其他传感器的数据做判断，另一方面需要不断分解自动驾驶问题为行人识别，自行车识别，信号识别等子问题。所有的子问题加起来，工程复杂度太高，创业公司是很难组建出一个能解决这个问题的团队的，而且所谓的“解决”，也不能达到商用的地步。拜深度学习所赐，如今从视觉信号，模仿人类驾驶行为，就可以做到高质量的巡航控制。这时候，自动驾驶问题就变成了一个创业公司可以挑战的问题。2016 年这个领域新闻一个接一个。Cruise 今年被 GM 收购，Comma.ai 获得了 A16Z 的投资等等，都是自动驾驶领域创业公司成功的例子。在许多的细分行业，这样被深度学习“创造”的新问题不胜枚举。然而，

#### 想要成功，单解决一两个问题是不够的

深度学习是一项技术。这个黑科技可以作出更加准确的机器学习模型，但更好的模型仍然要通过产品落地。特别是创业公司，在没有相关平台支撑的条件下，解决一两个问题很难给用户带来实际价值。在技术史上，没有一家技术公司是依靠一个领先的机器学习模型就成功的。即便 Google 这个以 PageRank 为核心算法起家的技术公司，也是通过将技术包装成一个优秀的搜索引擎而落地的 （当年的 Yahoo! 甚至还看不上这个技术）。

这里面的原因，可以分成 To B 和 To C 两个方向来说。

目前深度学习所解决的问题，大部分都在图像，人脸，视频，文本等领域——因为深度模型大部分都是为解决这些问题而设计的。靠一两个深度学习专家，创业公司完全有实力去挑战如图像分类，语音识别等通用问题。然而，解决通用问题的门槛只有一个：只要跳过了这个门槛，前方就很难再建护城河了。对用户有价值的通用问题，特别是 To B 的通用问题，一定是对巨头有价值的。2016 年，Google 和 Microsoft 都发布了图像，语音识别等通用 API。一个明确的趋势是，云服务商正在把这些基于 AI 的服务做成平台的一部分。在同样的图像分类服务面前，巨头的服务一定比创业公司要廉价。如果没有巨大的先发优势。创业公司在这个方向很难抵抗云服务巨头的侵蚀。此外，把针对通用问题的机器学习模型，浅包装成一个 API，的确容易切入市场，但也容易被巨头和其他创业公司碾压。现在市场上有许多浅包装深度模型的公司，提供如“鉴定黄色图片”等服务。在我看来这些服务的可替代性太强，大家技术差别也不大，最终能胜出的，只会是一两家有先天优势的公司（比如云服务巨头，或者第一个进入市场的公司）。To B 的 AI 创业公司的挑战不在技术上，而在产品创新上。怎么制造差异化服务，让这个服务无可替代——这就看各家公司的想象力了。

在 To C 方向，2016 年许多创业公司都做了很多尝试。今年很火的 [Prisma](http://prisma-ai.com/), 就是将风格迁徙神经网络运用到用户照片上，将照片转换成各种艺术家风格。Prisma 可以算是提供了一个杀手级的特性了。即便这样，创业公司想靠一个特性和巨头竞争也是不可能的。Prisma 不可能靠这一个特性取代 Instagram，即使 Instagram 没有这些人工智能的滤镜。原因很简单，IG 控制了移动时代的大量的用户群，因此 Prisma 制作的照片最终还要通过 Instagram 才能传播出去。To C 方向的先发优势是不可估量的：一旦用户形成使用习惯和网络效应，再好的 AI 产品也很难转化现有用户。其实这个问题困扰所有的公司。比如 Google 今年连续在 Gmail, Google Docs 里做了许多 AI 创新，还发布了 Allo 这个全新聊天工具。可是，大量用户依然用着 Office 和 Facebook Messenger。

说了这么多，好像很悲观。To B 和 To C 都困难重重的样子。其实机会还是非常多的，只是没有“AI = 创业机会”这样一个自动成立的等式而已。

#### AI 创业公司的优势

先说什么不是优势，或者护城河。其一，如果创业是凭借着一个“独特的算法或模型”，这个切入点是靠不住的。AI 创业已经过了 2014－2015 巨头为了收人而收购公司的阶段。目前投入到创业浪潮中的，都不大可能是当时巨头收漏了的。在这种大环境下，没有任何一项技术是别人不知道的，或者非常领先所有竞争对手的。目前宣称有独特模型和算法的，是把赌注押在一个特定的方法上，而和全世界的所有研究者竞争。目前来说这注定是无效的——谁也不知道明天 DeepMind 会公开什么黑科技，一下子超越了你的独特模型。或许在这个赛道上再走几年，有些公司的确能够领先其他。目前大家都在同样的起跑线上，模型或者算法的领先可以忽略不计。

其他，“把标准问题做到极致”既不是护城河，也不是竞争优势。如果回到 2012-2014 年，哪个创业公司能够用深度学习在 ImageNet 上刷出第一，肯定是立即像 [DNNResearch](https://techcrunch.com/2013/06/12/how-googles-acquisition-of-dnnresearch-allowed-it-to-build-its-impressive-google-photo-search-in-6-months/) 那样被巨头揽走。其中一个原因，是用深度学习的人太少了。现如今，世界上攻克标准问题的团队，百分之百都是用深度模型。当全世界的学术团队都来刷榜的时候，创业公司耗散精力去刷榜是不经济的。而且，刷榜要求的，许多时候是特定的工程技巧，未必能用到产品中。一个典型的例子是当年 Netflix 竞赛的第一名，它们的模型过于复杂，没法产品化，Netflix [最终也没有采用](http://arstechnica.com/gadgets/2012/04/netflix-never-used-its-1-million-algorithm-due-to-engineering-costs/)。

在我看来，AI 创业，还是要落实在**深入解决一个非标准（不能拿标准的深度学习模型一套就能用）的问题上**。只有在非标准的问题上，切实的了解用户需求才变成可能。标准的问题，如图像识别，自动驾驶，可以说，最终产品的亮点大家都差不多，因此人工智能也就不自动成为一个亮点。在非标准的问题上深耕，无形中就构建了两个护城河：1，竞争对手需要花时间了解这个问题之后才能提出解决方案和产品；2，你比竞争对手先收集许多解决这个领域特定问题的数据，因此在同一时间节点上，你的模型永远领先对手几个月。这就像微软的搜索引擎或许使用的模型很先进，但因为没有足够的数据因此质量永远落后 Google 几个月一样。

#### 最后的话

解决非标准的问题，需要的就不仅仅是 AI 人才。对特定行业的了解，痛点的把握，对用户的理解等等，往往比 AI 更加重要。在这一点上，AI 创业者可能会死磕模型和数据，或者只想着找最顶尖的 AI 研究者，而忘记了真正对用户有价值的东西。模型只是整个产品世界里很小的一部分。AI 创业公司不代表 AI 是唯一重要的事情，这一点算是我前面四个月学到的一点经验。