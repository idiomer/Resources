# Resources
资源整理

## 一、NLP

### 词库
- [中文停用词](https://github.com/goto456/stopwords): 包含文本格式（一行一词）的“百度停用词表”、“哈工大停用词表”、“四川大学机器智能实验室停用词表”和作者自己整理的停用词表

- [新华词典](https://github.com/pwxcoo/chinese-xinhua): 收录了包括14032条歇后语，16142个汉字，31648个成语


### 语料库
- [中文公开聊天语料库](https://github.com/codemayq/chinese_chatbot_corpus): 开源常见中文聊天语料，包括：小黄鸡语料、微博语料、贴吧论坛回帖语料、电视剧对白语料、青云语料、PTT八卦语料、豆瓣多轮、chatterbot

- [50w中文闲聊语料](https://github.com/yangjianxin1/GPT2-chitchat#%E9%97%B2%E8%81%8A%E8%AF%AD%E6%96%99%E5%88%86%E4%BA%AB): 由作者[GaoQ1](https://github.com/GaoQ1)提供的比较高质量的闲聊数据集，整理出了50w个多轮对话的语料。[百度网盘【提取码:jk8d】](https://pan.baidu.com/s/1mkP59GyF9CZ8_r1F864GEQ) 或 [GoogleDrive](https://drive.google.com/file/d/1nEuew_KNpTMbyy7BO4c8bXMXN351RCPp/view?usp=sharing)

- [LCCC](https://github.com/thu-coai/CDial-GPT#%E6%95%B0%E6%8D%AE%E9%9B%86%E6%A6%82%E5%86%B5): LCCC(Large-scale Cleaned Chinese Conversation)主要包含两部分: LCCC-base 和 LCCC-large. 设计了一套严格的数据过滤流程来确保该数据集中对话数据的质量。 这一数据过滤流程中包括一系列手工规则以及若干基于机器学习算法所构建的分类器。 所过滤掉的噪声包括：脏字脏词、特殊字符、颜表情、语法不通的语句、上下文不相关的对话等。

- [中文文本分类数据集THUCNews](http://thuctc.thunlp.org/#%E4%B8%AD%E6%96%87%E6%96%87%E6%9C%AC%E5%88%86%E7%B1%BB%E6%95%B0%E6%8D%AE%E9%9B%86THUCNews): THUCNews是根据新浪新闻RSS订阅频道2005~2011年间的历史数据筛选过滤生成，包含74万篇新闻文档（2.19 GB），均为UTF-8纯文本格式。在原始新浪新闻分类体系的基础上，重新整合划分出14个候选分类类别：财经、彩票、房产、股票、家居、教育、科技、社会、时尚、时政、体育、星座、游戏、娱乐

- [nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus): 语料库“大杂烩”，包括：维基百科json版(wiki2019zh)、新闻语料json版(news2016zh)、百科类问答json版(baike2018qa)、社区问答json版(webtext2019zh) ：大规模高质量数据集、翻译语料(translation2019zh)

### 模型

#### BERT
- [BERT](https://github.com/google-research/bert) [[Paper](https://arxiv.org/abs/1810.04805)]

- [ALBERT](https://github.com/google-research/albert) [[Paper](https://arxiv.org/abs/1909.11942)]

- [bert-for-tf2](https://github.com/kpe/bert-for-tf2):  TensorFlow 2.0 Keras implementation of BERT, ALBERT and adapter-BERT


#### GPT-2
- [gpt2-ml](https://github.com/imcaspar/gpt2-ml): 基于THUCNews和nlp_chinese_corpus语料训练（清洗约15G）的15亿参数GPT2中文预训练模型，提供[pretrain模型](https://github.com/imcaspar/gpt2-ml#pretrained-model)和[colab notebook](https://github.com/imcaspar/gpt2-ml#google-colab)开箱即用的体验。作者提供的pretrain模型在google drive上，issue中有网友上传了一份到[百度网盘](https://github.com/imcaspar/gpt2-ml/issues/23)中。

- [GPT2-Chinese](https://github.com/Morizeyao/GPT2-Chinese): 中文的GPT2训练代码，使用BERT的Tokenizer或Sentencepiece的BPE model。可以写诗，新闻，小说，或是训练通用语言模型。支持字为单位或是分词模式或是BPE模式（需要略微修改train.py的代码）。支持大语料训练。提供规模不算太大的[pretrain模型](https://github.com/Morizeyao/GPT2-Chinese#%E6%A8%A1%E5%9E%8B%E5%88%86%E4%BA%AB)，包括：散文模型，诗词模型，对联模型

- [GPT2-chitchat](https://github.com/yangjianxin1/GPT2-chitchat): 可多轮对话的闲聊机器人，基于GPT2-Chinese实现。提供[pretrain模型](https://github.com/yangjianxin1/GPT2-chitchat#%E9%97%B2%E8%81%8A%E8%AF%AD%E6%96%99%E5%88%86%E4%BA%AB)

- [CDial-GPT](https://github.com/thu-coai/CDial-GPT): 中文对话预训练模型（中文GPT模型而非GPT-2）,提供[pretrain模型](https://github.com/thu-coai/CDial-GPT#%E6%A8%A1%E5%9E%8B)



## 二、CV

