#                       iflab任务三笔记


## 从零入门CPU部署大模型&应用开发

### 背景知识

### 一、大模型咋来的？（发展演化过程）：
1990s统计语言模型（SLM）eg. n-gram统计模型  有一定生成能力，可辅助解决问题，但受数据稀疏影响严重
2013 神经语言模型（NLM）eg. RNN-LM、word2vee  克服前代不足，无监督学习语义特征表示
2018 预训练语言模型（PLM） eg. ELMO、BERT、GPT-1/2  能有效捕捉上下文语义，迁移能力提升
2022 大语言模型（LLM）eg. GPT-3、ChatGPT、Claude  规模扩展带来性能提升，解决问题途径通用

### 二、怎么构建大模型：
1.预训练（人背书，机械训练）
2.有监督微调（监督背诵并鞭策，监督并人为更正）
3.基于人类反馈的强化学习对齐（根据已学进行输出，搜索相关信息并输出人类可以正常理解的内容）

### 三、开源与闭源大模型
开源：代码信息可公开使用
闭源：内容不进行公开

### 四、大模型时代挖掘模型能力的开发范式
目的：利用大模型帮助自己提升学习效率
1.Prompt工程 提示词 大模型基于此进行回答
2.Embedding 帮助更好的利用大模型
3.参数高效微调 帮助更快输出

### 五、大模型应用开发
用户→请求客户端（gradio、streamlit）→输入服务端（大模型API、大模型本地部署）→服务端输出→客户端回复→用户

## CPU开发开源大模型应用

### 步骤：第一步：下载代码文件

### 第二步：利用model scope配CPU环境

### 第三步：跟随教程操作

### 一、使用 IPEX-LLM 推理大语言模型
1.上传文件
2.安装环境
3.切换环境
4.下载模型，量化模型，创建文件
5.在CPU上运行大模型进行对话
6.在CPU上进行流式对话

### 二、使用 IPEX-LLM 和 Gradio/Streamlit 构建大模型应用
1.安装Gradio/streamlit
2.修改、运行文件
3.进行对话

### 三、成果展示
<https://pan.baidu.com/s/1BerdQo26vnLVfjC8s1yPXA?pwd=1111>![3ce2c31bb6519ec874c0a2061d40d57](C:\Users\haiha\Documents\WeChat Files\wxid_lg9ksa3qsxqz22\FileStorage\Temp\3ce2c31bb6519ec874c0a2061d40d57.png)

## 学习感悟
很早之前就听说过chat-GPT，了解到它能根据人的问题进行回答甚至还能帮写论文感到十分有兴趣，但由于懒得找梯子只选择去网上看别人玩。大语言模型给我的第一印象就是突然出现可以利用一些奇妙的方法登陆一些网站，之后里面的AI就会回答你的一切问题，十分方便。经过任务三的学习，我了解到大语言模型是从上个世纪就开始发展出来的，并非是一瞬间研究出来的，并且不光是已研究的大模型，我们甚至可以用我们的CPU部署一个大模型，供我们进行使用。

## Agent智能体
名称：代码匠

简介：C语言代码一键生成，编程master亲自讲授，知识点同步掌握！

配置信息：你是代码匠，专门处理用户编程需求，通过提示词快速生成C语言代码，并以耐心细致的语气指导用户理解代码及背后的知识点。你的能力有:
-解析用户需求，快速生成C语言代码。
-列出编写代码所需的知识点。
-鼓励用户学习并理解代码逻辑。

模块能力：代码能力 联网能力

开场白：你好，我是代码匠，专帮你解决C语言编程难题，让我们猛猛开始吧！

预置问题：如何用C语言实现一个简单的计算器？
请编写一个C语言程序，实现数组排序。
我想用C语言做一个学生管理系统，应该如何开始编写代码？

智能体配置及成果展示：
<https://pan.baidu.com/s/1eKd5FY4Va-Y5FXbW3cmehw?pwd=2222>![b0d79fd9ff16dacdbf1a53ab795d88f](C:\Users\haiha\Documents\WeChat Files\wxid_lg9ksa3qsxqz22\FileStorage\Temp\b0d79fd9ff16dacdbf1a53ab795d88f.png)

<https://pan.baidu.com/s/1XA_3n_CUiI11GoOAYAj_xg?pwd=3333>![83a6d24f69240a13a3cc713d9023b5f](C:\Users\haiha\Documents\WeChat Files\wxid_lg9ksa3qsxqz22\FileStorage\Temp\83a6d24f69240a13a3cc713d9023b5f.png)

Agent链接：<https://chatglm.cn/share/FNQuF>