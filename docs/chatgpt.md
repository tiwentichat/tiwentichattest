ChatGPT提示词清单
===


这是一份关于 ChatGPT 各种提示词的案例库/快速参考备忘单，列出了工具类和角色类的150+案例，以及初始的入门方法（其实我觉得入门约等于掌握）

[入门](#入门)<!--rehype:style=background: rgb(210 168 255);--> 
[通用](#通用)<!--rehype:style=background: rgb(12 75 51);--> 
[编程](#编程)<!--rehype:style=background: rgb(39 160 193);-->  
[写邮件](#写邮件)<!--rehype:style=background: rgb(211 55 49);-->  
[电子表格](#电子表格)<!--rehype:style=background: rgb(26 188 156);-->  
[社交媒体](#社交媒体)<!--rehype:style=background: rgb(57 59 60);-->  
[阅读](#阅读)<!--rehype:style=background: rgb(64 196 255);-->  
[设计](#设计)<!--rehype:style=background: rgb(214 66 146);-->  
[数据分析](#数据分析)<!--rehype:style=background: rgb(57 59 60);-->  
[付费广告](#付费广告)<!--rehype:style=background: rgb(72 143 223);-->
[电商写作](#电商写作)<!--rehype:style=background: rgb(150 220 254);-->  
[写作/博客](#写作/博客)<!--rehype:style=background: rgb(92 107 192);-->  
[制作课程](#制作课程)<!--rehype:style=background: rgb(6 147 13);-->  
[视频相关](#视频相关)<!--rehype:style=background: rgb(92 107 192);-->  
[协助研究](#协助研究)<!--rehype:style=background: rgb(0 72 153);-->  
[搜索引擎优化](#搜索引擎优化)<!--rehype:style=background: rgb(6 147 13);-->  

入门
------------

### 入门技巧
<!--rehype:wrap-class=row-span-1-->

ChatGPT这个工具最强大之处在于：<b>这个工具可以教你怎样使用这个工具。</b>

#### 初级也是终极技巧 

```html
    你可以做什么？
    你可以教我那些学科的知识？
```
<!--rehype:className=wrap-text -->

### 进阶技巧一 

```html
    让我们一步一步思考..
    这句话是上一代版本时有人发现的一个咒语，加了这句话后，GPT给出的回复质量就会明显提高。虽然随着版本迭代这个咒语已经被官方收编，我们不需要特意添加它，但是它所代表的逻辑还是存在的：
    我们在和ChatGPT对话时，如果是一步一步的分步骤提问、提供更多细节，ChatGPT给我们的回复依然是更好的。
```

### 进阶技巧二 

```html
    你是...，你的对象是...，你的目标是...  
    使用上这套咒语后，你就可以得到一个指定人设的角色
```




工具类案例库---------------


### 通用

- **为你的公司或创意取名**
    ``` {.wrap}
    1. 你能为我的科技创业公司提供一个有创意的名字吗？
    2. 帮我想一个引人注目的名字，用于我的烘焙业务。
    ```
- **为一门课程或培训计划制定大纲**
    ``` {.wrap}
    1. 请为初学者网页开发课程制定一个大纲。
    2. 你能为一个客户服务研讨会制定培训计划大纲吗？
    ```
- **针对特定职位提供面试问题**
    ``` {.wrap}
    1. 我正在应聘软件工程师职位，你能给我一些面试问题吗？
    2. 请为市场经理职位提供一些常见的面试问题。
    ```
- **为商业合作伙伴、客户或客户提供礼品建议**
    ``` {.wrap}
    1. 我需要为我的客户提供礼品建议，你能帮忙吗？
    2. 你能提供一些独特的礼品建议，让我送给我的商业合作伙伴吗？
    ```
- **从名单或电子邮件列表中随机选择获胜者**
    ``` {.wrap}
    1. 我想从100个名字的名单中选择一个获胜者，你能帮忙吗？
    2. 你能从1000个电子邮件地址列表中随机选择5个，作为赠品抽奖活动的获奖者吗？

{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 编程

- **解释为什么一段代码无法运行**
    ``` {.wrap}
    这段代码为什么不能运行？
    var x = 5;
    var y = 0;
    console.log(x/y);
    ```
- **解释一段代码的含义**
    ``` {.wrap}
    这段代码是干什么的？
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **使用指定的语言重写代码**
    ``` {.wrap}
    将这段代码翻译成 Python：
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **编写完整的软件程序**
    ``` {.wrap}
    1. 用 Python 编写一个计算给定数字阶乘的程序？
    2. 如何在 JavaScript 中发出 HTTP 请求？
    ```
- **生成正则表达式（regex）**
    ``` {.wrap}
    1. 创建一个匹配所有电子邮件地址的正则表达式？
    2. 生成一个 8 位数字密码的正则表达式
    ```
- **为代码库添加注释**
    ``` {.wrap}
    给这段代码加上注释：
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **更改一行代码的 CSS**
    ``` {.wrap}
    更新此行的 CSS，将字体颜色更改为蓝色：
    <p class="example">Hello, QuickRef.ME!</p >
    ```
- **更改一行代码的 HTML**
    ``` {.wrap}
    将“header”类添加到此标题标记中：
    <h1>Hello, QuickRef.ME!</h1>
    ```



{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)





### 写邮件


- **创建电子邮件活动**
    ``` {.wrap}
    1. 邀请杰克周末共进晚餐的邮件
    2. 为我们的新客户入门流程创建电子邮件序列
    ```
- **格式化和校对电子邮件**
    ``` {.wrap}
    校对并格式化我刚写的这封电子邮件:
    你好，你能提供一些关于ChatGPT的实用技巧吗？
    ```
- **提供有效的电子邮件营销技巧**
    ``` {.wrap}
    1. 给我一些如何提高电子邮件活动的打开和点击率的技巧
    2. 建议让我的电子邮件内容更具吸引力和与我的订阅者相关性的方法。
    ```
- **自动回复电子邮件**
    ``` {.wrap}
    给他发一封电子邮件，内容是：“好的建议，即将推出”：
    你好，你能提供一些关于ChatGPT的实用技巧吗？
    ```
- **从文本中提取电子邮件地址**
    ``` {.wrap}
    为我提取所有电子邮件地址：
    Sed sit amet sodales tom@gmail.com, at jack@quickref.me enim. 18261@outlook.com ut eros
    ```



{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)


### 电子表格
- **帮助创建电子表格公式**
    ``` {.wrap}
    你能帮我创建一个公式，用于计算单元格A1到A10的总和吗？
    ```
- **解释一个公式的含义**
    ``` {.wrap}
    你能简单地解释一下 =SUM(A1:A10) 这个公式的含义吗？
    ```
- **为占位符创建虚拟数据**
    ``` {.wrap}
    你能为我生成一些虚拟数据，用作电子表格中的占位符吗？
    ```
- **帮助创建复杂的宏**
    ``` {.wrap}
    我需要创建一个宏，用于计算单元格B1到B10的平均值，并将结果插入到单元格C1中。你能帮我实现吗？
    ```
- **提供提高电子表格效率的技巧**
    ``` {.wrap}
    你能给我一些提高电子表格效率的技巧吗？ 
    ```



{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)





### 社交媒体
- **为任何话题提供模因创意（梗）**
    ``` {.wrap}
    你能给我提供一些[狗]相关的模因创意吗？
    ```
- **提供在任何话题上能推动用户参与的帖子构思**
    ``` {.wrap}
    我想发布一篇有关气候变化的帖子，能够吸引我的关注者参与进来。你能帮我提供一些构思吗？
    ```
- **生成标签和标题**
    ``` {.wrap}
    我需要为一张美丽的日落照片添加一些标签和标题。你能为我生成一些吗？
    ```
- **提供建议并回复**
    ``` {.wrap}
    我刚刚收到一条询问一个项目进展情况的消息。你能为我提供一个回复建议吗？
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 阅读
- **概括长篇的文本**
    ``` {.wrap}
    你能为我总结一下这篇文章吗？[你的文本]
    ```
- **翻译外语**
    ``` {.wrap}
    你能把这个句子翻译成西班牙语吗？[你的文本]
    ```
- **推荐类似另一本书的书**
    ``` {.wrap}
    你能推荐一些类似于《饥饿游戏》的书吗？
    ```



{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 设计
- **为你创建一个AI设计提示**
    ``` {.wrap}
    你能帮我为一个新的体育品牌的标志生成一个设计提示吗？
    ```
- **博客或视频缩略图建议**
    ``` {.wrap}
    你能推荐一些吸引眼球的缩略图设计给我的最新健康饮食YouTube视频吗？
    ```
- **字体搭配**
    ``` {.wrap}
    你能为旅游博客标题设计建议字体搭配吗？
    ```
- **颜色搭配**
    ``` {.wrap}
    你能为婚礼摄影网站推荐一个配色方案吗？
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 数据分析
- **从大段文字中提取数字**
    ``` {.wrap}
    请提取这段文本中的所有数字：[your text]
    ```
- **根据您提供的文本或数据创建表格**
    ``` {.wrap}
    您能否从这些数据中创建一个表格？：[your data]
    ```
- **从大型列表中筛选数据**
    ``` {.wrap}
    请根据某些条件过滤此列表：[your list]
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)




### 付费广告
- **提供广告创意点子**
    ``` {.wrap}
    给我一个新产品发布的广告创意点子。
    ```
- **检查跟踪代码是否有误（标签管理器等）**
    ``` {.wrap}
    检查我的标签管理器代码是否有误。
    ```
- **提供广告文案点子**
    ``` {.wrap}
    为一个[旅行]公司提供建议的广告文案。
    ```
- **Facebook 受众建议**
    ``` {.wrap}
    为服装品牌广告活动推荐 Facebook 受众。
    ```
- **为您的广告创建正文、标题和/或呼叫操作**
    ``` {.wrap}
    为一项新的健身计划广告创建标题、正文和呼叫操作。
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)




### 电商写作
- **编写或重写产品描述**
    ``` {.wrap}
    请帮我为我的最新商品撰写一个新的并具有吸引力的产品描述。
    ```
- **编写或重写上诉信**
    ``` {.wrap}
    我需要帮助重写上诉信以使其更具说服力。
    ```
- **编写或重写供应商联络电子邮件**
    ``` {.wrap}
    你能否帮我写一封有效的电子邮件与潜在供应商联系？
    ```
- **帮助您找到可以作为捆绑销售的商品**
    ``` {.wrap}
    请推荐一些可供客户捆绑销售的商品。
    ```
- **组织产品和定价数据**
    ``` {.wrap}
    你能帮我将产品和定价信息整理成一个整洁、可管理的电子表格吗？
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)




### 写作/博客
- **为您的创意写作项目创建标题**
    ``` {.wrap}
    短篇小说合集的标题：[您的文章]
    ```
- **创建大纲**
    ``` {.wrap}
    有关锻炼的论文大纲
    ```
- **提供内容创意**
    ``` {.wrap}
    关于可持续时尚的博客想法？
    ```
- **总结您提供的任何文本**
    ``` {.wrap}
    总结这篇关于可再生能源的文章？[您的文章]
    ```
- **创建完整的博客文章**
    ``` {.wrap}
    [财务规划]的博客文章？
    ```
- **扩展句子、段落或长文本的内容**
    ``` {.wrap}
    扩展这个有关爵士乐的句子？[您的句子]
    ```
- **改变您写作的语气**
    ``` {.wrap}
    把这份报告的语气变成谈话的？[您的报告]
    ```
- **校对或编辑您的写作**
    ``` {.wrap}
    校对这篇文章？[您的文章]
    ```
- **使用标题格式化文本（适用于博客文章）**
    ``` {.wrap}
    为我的博客文章格式化标题？[您的文章]
    ```
- **检查任何文本是否存在偏见**
    ``` {.wrap}
    检查这篇文章是否存在偏见？[您的文章]
    ```
- **检测任何文本的抄袭**
    ``` {.wrap}
    检测这篇论文的抄袭？[您的论文]
    ```
- **为您提供域名创意**
    ``` {.wrap}
    [园艺博客]的域名？
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)


### 制作课程
- **将事实或统计数据列表转换为多项选择测试题**
    ``` {.wrap}
    你能把这个世界历史事实列表转换成多项选择测试题吗？[你的列表]
    ```
- **特定主题的作业想法**
    ``` {.wrap}
    我需要一些关于美国革命历史作业的想法。你能提供一些建议吗？
    ```
- **从学生名单创建指定的小组**
    ``` {.wrap}
    我班上有30名学生的名单。你能把他们分成6个小组做小组项目吗？
    ```
- **根据测试成绩创建曲线**
    ``` {.wrap}
    我需要根据他们的测试成绩为我的班级创建分级曲线。你能帮忙吗？
    ```
- **评分作业**
    ``` {.wrap}
    你能为这篇历史文章评分并提供任何需要改进的反馈吗？
    ```


{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 视频相关
- **从转录文本创建时间戳**
    ``` {.wrap}
    你能为这个播客集的转录文本创建时间戳吗？[你的转录文本]
    ```
- **将 YouTube 视频转换为带格式的博客文章**
    ``` {.wrap}
    你能把这个有关烹饪的 YouTube 视频转换成带有标题和项目符号的博客文章吗？[视频链接]
    ```
- **构思视频大纲或脚本**
    ``` {.wrap}
    我需要一个关于冥想好处的视频大纲。你能帮忙吗？
    ```
- **回复评论**
    ``` {.wrap}
    你能就我的 YouTube 视频上的这个负面评论写出有思考性和礼貌的回复吗？
    ```
- **为缩略图提供创意想法**
    ``` {.wrap}
    我需要一些关于“DIY家居装饰”的缩略图想法。你能提供一些建议吗？
    ```
- **分析你的脚本或转录文本，并告诉你的语气**
    ``` {.wrap}
    你能分析这个有关环境问题的视频脚本，并告诉我语气是什么吗？[你的脚本]
    ```
- **任何主题的视频想法**
    ``` {.wrap}
    我想制作一系列关于时尚的视频。你能提供一些单独视频的想法吗？
    ```
{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)



### 协助研究
- **帮助研究2021年之前的任何事情**
    ``` {.wrap}
    1. 用简单的语言解释量子计算是什么
  
    2. 你有什么创意为一个10岁孩子的生日庆祝活动吗？
  
    3. 如何用Javascript进行HTTP请求？
  
    4. 你能告诉我导致美国内战爆发的事件吗？
  
    5. 关于印刷机的发明，你能告诉我什么？
  
    6. 你能研究一下奥林匹克运动会的历史吗？
  
    7. 你能提供关于法国大革命的信息吗？
  
    8. 我对拜占庭帝国的历史很感兴趣，你能帮我了解更多吗？
  
    9. 等等...
    ```

  
{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)


### 搜索引擎优化 (SEO)
- **生成或寻找关键词**
    ``` {.wrap}
    1. 为 [主题] 生成相关关键词列表

    2. 为 [主题] 识别长尾关键词以进行内容优化

    3. 找到 [主题] 的表现最佳关键词

    4. 为 [主题] 生成LSI关键词列表

    5. 找到竞争较小的 [主题] 关键词

    6. 为 [主题] 关键词创建同义词列表

    7. 找到 [主题] PPC广告活动的最佳关键词

    8. 找到 [主题] 语音搜索优化的最佳关键词

    9. 列出 [主题] 特色片段的最佳关键词

    10. 找到 [主题] 视频优化的最佳关键词

    11. 找到 [主题] 的最佳关键词

    12. 找到 [主题] AMP优化的最佳关键词

    13. 找到 [主题] 社交媒体优化的最佳关键词
    ```


- **更多关于SEO的ChatGPT提示** {.active}
    ```{.wrap}
    1. 为 [topic] 创建元描述和标题标签

    2. 找到与 [topic] 相关的内部链接机会

    3. 为 [topic] 内容生成博客文章和文章主题的创意

    4. 研究行业特定术语以在 [topic] 内容中使用

    5. 找到权威网站以获取与 [topic] 内容相关的回链

    6. 创建一个与 [topic] 相关的XML网站地图示例

    7. 研究最佳的 [topic] 元标签

    8. 研究最佳的 [topic] 内容的内部链接结构

    9. 生成人们关于 [topic] 提出的问题列表

    10. 为与 [topic] 相关的图像创建最佳的alt标签列表

    11. 创建 [topic] 的相关子主题列表

    12. 找到发布与 [topic] 相关内容的最佳时间

    13. 研究最佳的 [topic] 外部链接策略

    14. 找到最受欢迎的用于 [topic] SEO 的工具列表

    15. 创建 [topic] 的潜在影响者列表

    16. 研究最佳的 [topic] 模式标记

    17. 找到最佳的 [topic] 内容标题标签

    18. 创建潜在的与 [topic] 相关的链接建设机会列表

    19. 研究最佳的 [topic] 回链锚文本

    20. 创建潜在的与 [topic] 相关的客座博客机会列表

    21. 研究最佳的 [topic] 本地SEO策略

    22. 研究最佳的 [topic] 网站性能分析工具

    23. 创建潜在的与 [topic] 相关的合作伙伴列表

    24. 研究最佳的 [topic] 移动优化策略

    25. 研究最佳的 [topic] 电子商务优化策略。提供关键字群。

    26. 创建潜在的与 [topic] 相关的联盟营销机会列表

    27. 什么是与 [topic] 相关的最佳联盟营销网站？

    28. 研究最佳的 [topic] 国际SEO策略

    29. 创建潜在的与 [topic] 相关的播客或播客嘉宾机会列表

    30. 研究最佳的 [topic] Google我的企业优化策略

    31. 查找与[主题]相关的流行内容话题

    32. 研究[主题]的最佳SEO策略，并提供可行的步骤

    33. 创建一个与[主题]相关的潜在视频系列或网络研讨会想法列表

    34. 研究与[主题]相关的竞争对手策略

    35. 查找与[主题]相关的规范标记示例

    36. 创建一个针对多个地理位置的示例关键词列表，用于[主题]

    37. 生成针对客户购买漏斗不同阶段的关键词想法列表，用于[主题]

    38. 识别与[主题]相关的行业标签

    ```
{.collapsible}

[💡 我要添加新案例](https://github.com/tiwentichat/reference/blob/main/docs/chatgpt.md)





参考资料
---------

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) _(github.com)_


- [https://prompts.chat](https://prompts.chat)

- [https://github.com/PlexPt/awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)

- [https://www.emergentmind.com/](https://www.emergentmind.com/)

- [https://quickref.me/chatgpt](https://quickref.me/chatgpt)

- [https://gpt3demo.com/](https://gpt3demo.com/)

- [https://flowgpt.com](https://flowgpt.com)

- 以及[OpenAI](https://openai.com/) 的Prompts Library


<style>
em { font-size: 0.785em; }
strong {font-weight: 400;}
ul.collapsible > li > pre { padding-left: 0; padding-right: 0; font-size: 0.925em;}
</style>

