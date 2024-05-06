# selfrag-quickstart
## groundness-1
```
您将收到指示、证据和输出。
您的任务是评估证据中提供的信息是否完全支持输出。
使用以下蕴涵量表生成分数：
5：完全支持 - 输出中的所有信息均得到证据或证据提取的支持。 这是一个有点极端的情况，仅适用于输出和部分证据几乎相同的情况。
4：大部分支持 - 输出中的大部分信息都有证据支持，但有一些次要信息不受支持。 换句话说，如果输出是证据的释义或证据描述的不太具体的版本，则应将其视为 4。
3：部分支持——输出在一定程度上得到证据的支持，但输出中存在证据中未讨论的主要信息。 例如，如果指令询问两个概念，而证据仅讨论其中任何一个，则应将其视为 3。如果输出涵盖证据中未讨论的大量新信息，则应将其视为 3。
2：支持很少 - 输出和证据只是松散相关，并且输出中的大部分信息不受证据支持。
1：忽略/矛盾 - 输出完全忽略证据或与证据相矛盾。 如果证据与指令无关，也可能发生这种情况。
确保不使用任何外部信息/知识来判断输出是否正确。
只检查输出是否有证据支持，而不检查输出是否遵循说明。

###
说明：解释自然语言处理中词嵌入的使用

输出：词嵌入是自然语言处理（NLP）最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。 词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。 它们允许将单词处理为数值，从而使机器能够更轻松地执行 NLP 任务。

证据：词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 从概念上讲，它涉及从每个单词一维的空间到维数低得多的连续向量空间的数学嵌入。 生成这种映射的方法包括神经网络、单词共现矩阵的降维、概率模型、可解释的知识库方法以及单词出现的上下文的显式表示。 单词和短语嵌入用作底层输入表示时，已被证明可以提高句法解析和情感分析等 NLP 任务的性能。

得分：4
说明：虽然措辞不完全相同，但证据验证了输出中的所有声明，例如 NLP 中的定义和用例。 因此，应评定为4分。

###
指令：xxx

输出：xxx

证据：xxx

分数：
```

## groundness-2
```
您将收到指令、证据、输出以及可选的前面的句子。 如果给出前面的句子，则输出应该是前面句子后面的句子。 您的任务是评估证据中提供的信息是否完全支持输出，并就您的判断提供解释
使用以下蕴涵量表生成分数：
[完全支持] - 输出中的所有信息均得到证据或证据摘录的支持。 这仅适用于输出和部分证据几乎相同的情况。
[部分支持] - 输出在某种程度上得到证据的支持，但输出中存在证据中未讨论的主要信息。 例如，如果指令询问两个概念，而证据仅讨论其中一个，则应将其视为[部分支持]。
[不支持/矛盾] - 输出完全忽略证据、与证据无关或与证据相矛盾。 如果证据与指令无关，也可能发生这种情况。

确保不使用任何外部信息/知识来判断输出是否正确。 只检查输出是否有证据支持，而不检查输出是否遵循说明。

###
说明：解释自然语言处理中词嵌入的使用。
前面的句子：词嵌入是自然语言处理 (NLP) 中最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。
输出：词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。
证据：词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 单词和短语嵌入用作底层输入表示时，已被证明可以提高 NLP 任务的性能，例如句法解析、情感分析、下一个标记预测以及类比检测。
评分：[完全支持]
解释：输出句子讨论了词嵌入的应用，证据提到了所有应用句法解析、情感分析、下一个标记预测以及类比检测作为应用。 因此，评分应为【完全支持】。

###
操作说明：
前面的句子：
输出：
证据：
分数：
```

## groundness-3
```
您将收到指令、证据、输出以及可选的前面的句子。 如果给出前面的句子，则输出应该是前面句子后面的句子。 您的任务是评估证据中提供的信息是否完全支持输出，并就您的判断提供解释。
使用以下蕴涵量表生成分数：
[完全支持] - 输出中的所有信息均得到证据或证据摘录的支持。 这仅适用于输出和部分证据几乎相同的情况。
[部分支持] - 输出在某种程度上得到证据的支持，但输出中存在证据中未讨论的主要信息。 例如，如果指令询问两个概念，而证据仅讨论其中一个，则应将其视为[部分支持]。
[不支持/矛盾] - 输出完全忽略证据、与证据无关或与证据相矛盾。 如果证据与指令无关，也可能发生这种情况。

确保不使用任何外部信息/知识来判断输出是否正确。 只检查输出是否有证据支持，而不检查输出是否遵循说明。

###
说明：解释自然语言处理中词嵌入的使用。
前面的句子：词嵌入是自然语言处理 (NLP) 中最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。
输出：词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。
证据：词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 单词和短语嵌入用作底层输入表示时，已被证明可以提高 NLP 任务的性能，例如句法解析、情感分析、下一个标记预测以及类比检测。
评分：[完全支持]
解释：输出句子讨论了词嵌入的应用，证据提到了所有应用句法解析、情感分析、下一个标记预测以及类比检测作为应用。 因此，评分应为【完全支持】。

###
操作说明：
输出：
证据：
分数：
```

## need-Retrive - 1 
```
根据指示，请判断从网络（例如维基百科）查找一些外部文档是否有助于生成更好的响应。 请回答[是]或[否]并写下解释。

##
说明：给出保持健康的三个秘诀。
需要检索吗？：[是]
说明：可能有一些在线资源列出了保持健康的三个技巧，或者有一些可靠的资源来解释不同行为对健康的影响。 因此检索文档有助于提高对此查询的响应。

##
说明：描述一次你不得不做出艰难决定的时刻。
需要检索吗？：[否]
说明：本教程询问的是一些个人经验，因此不需要寻找一些外部文档。

##
说明：以第三人称叙述的方式写一个关于主角必须做出重要职业决定的短篇故事。
需要检索吗？：[否]
说明：这个指令要求我们写一个短篇故事，不需要外部证据来验证。

##
说明： 法国的首都是哪里？
需要检索吗？：[是]
说明：虽然指令只是要求我们回答法国首都（这是众所周知的事实），但检索此问题的网络文档仍然会有所帮助。

##
  说明： 给定半径，求圆的面积。 半径 = 4
需要检索吗？：[否]
说明：这是一个数学问题，虽然我们可能能够找到一些描述公式的文档，但不太可能找到准确提及答案的文档。

##
说明：将给定句子中的单词排列成语法正确的句子。 棕色狐狸迅速跳了起来
需要检索吗？：[否]
说明：此任务不需要任何外部证据，因为它是一个简单的语法问题。

##
说明：解释植物细胞呼吸的过程。需要检索吗？：[是]
说明：此说明要求对科学概念进行详细描述，并且我们很有可能找到可靠且有用的文档来支持响应。

##
说明：{说明}
需要检索吗？：
```

## need-Retrive - 2
```
您将获得指令、证据、输出句子和前面的句子（可选）。 如果给出前面的句子，则输出应该是前面句子后面的句子。 你的任务是确定输出句子中的信息是否可以得到证据的充分验证，或者是否需要进一步的外部验证。 如果输出的句子可以仅用证据验证或不需要任何验证，请回复[不检索]。 如果需要附加信息来验证输出句子，请用[检索]响应。 请解释你的判断。

##
说明：解释自然语言处理中词嵌入的使用。
前面的句子：词嵌入是自然语言处理 (NLP) 中最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。
证据：词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 从概念上讲，它涉及从每个单词一维的空间到维数低得多的连续向量空间的数学嵌入。
输出：词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。
评分：[检索]
解释：输出讨论了词嵌入的应用，而证据仅讨论了词嵌入的定义及其工作原理。 因此，我们需要检索其他证据来验证输出是否确实正确。
###
指令：{指令}
前面的句子：{preceding_sentences}
证据：{证据}
输出：{目标输出}
评分：
```

## need-Retrive - 3
```
您将获得指令、证据、输出句子和前面的句子（可选）。 如果给出前面的句子，则输出应该是前面句子后面的句子。 你的任务是确定输出句子中的信息是否可以得到证据的充分验证，或者是否需要进一步的外部验证。 如果输出的句子可以仅用证据验证或不需要任何验证，请回复[不检索]。 如果需要附加信息来验证输出句子，请用[检索]响应。 请解释你的判断。

##
说明：解释自然语言处理中词嵌入的使用。
前面的句子：词嵌入是自然语言处理 (NLP) 中最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。
证据：词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 从概念上讲，它涉及从每个单词一维的空间到维数低得多的连续向量空间的数学嵌入。
输出：词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。
评分：[检索]
解释：输出讨论了词嵌入的应用，而证据仅讨论了词嵌入的定义及其工作原理。 因此，我们需要检索其他证据来验证输出是否确实正确。
###
指令：{指令}
证据：{证据}
输出：{目标输出}
评分：
```

```
您将获得指令、证据、输出句子和前面的句子（可选）。 如果给出前面的句子，则输出应该是前面句子后面的句子。 你的任务是确定输出句子中的信息是否可以得到证据的充分验证，或者是否需要进一步的外部验证。 分三种情况：
- 如果输出的句子可以仅用证据来验证，则回复[继续使用证据]。
- 如果该句子不需要任何事实验证（例如，主观句子或常识句子），则回答[不检索]。
如果需要附加信息来验证输出句子，请用[检索]响应。 请解释你的判断。

##
说明：解释自然语言处理中词嵌入的使用。
前面的句子：词嵌入是自然语言处理 (NLP) 中最强大的工具之一。 它们是向量空间中单词或短语的数学表示，允许测量单词和使用它们的上下文之间的相似性。
证据：
词嵌入
词嵌入是自然语言处理 (NLP) 中一组语言建模和特征学习技术的统称，其中词汇表中的单词或短语被映射到实数向量。 从概念上讲，它涉及从每个单词一维的空间到维数低得多的连续向量空间的数学嵌入。
输出：词嵌入对于情感分析、文本分类、预测序列中的下一个词以及理解同义词和类比等任务非常有用。
评分：[检索]
解释：输出讨论了词嵌入的应用，而证据仅讨论了词嵌入的定义及其工作原理。 因此，我们需要检索其他证据来验证输出是否正确。
###
指令：{指令}
前面的句子：{preceding_sentences}
证据：{证据}
输出：{目标输出}
评分：
```

```
您将获得指令、证据、输出句子和前面的句子（可选）。 如果给出前面的句子，则输出应该是前面句子后面的句子。 你的任务是确定输出句子中的信息是否可以得到证据的充分验证，或者是否需要进一步的外部验证。 分三种情况：
- 如果输出的句子可以仅用证据来验证，则回复[继续使用证据]。
- 如果该句子不需要任何事实验证（例如，主观句子或常识句子），则回答[不检索]。
- 如果需要附加信息来验证输出语句，请使用[检索]进行响应。 请解释你的判断。

##
说明：解释word embedd的使用
```


# relevance - 1
```
您将收到一份说明、证据以及可能的一些前面的句子。 当有前面的句子时，你的注意力应该放在后面的句子上。 您的工作是确定证据是否与初始指令和前面的上下文相关，并提供有用的信息来完成指令中描述的任务。 如果证据符合此要求，请回答[相关]； 否则，生成[不相关]。

###
说明：给定 A、B、C、D 四个选项，选择最佳答案。

输入：地球自转原因
A：AM和PM的循环
B：火山喷发的形成
C：潮汐的循环
D：重力的产生

证据：自转引起昼夜循环，昼夜循环也产生相应的温度和湿度循环，从而产生相应的温度和湿度循环。 随着地球自转，海平面每天上升和下降两次。

评级：[相关]
解释：证据明确提到轮转会导致昼夜循环，如答案选项 A 中所述。

###
说明：竞选美国众议院的年龄

证据：宪法规定了在美国参议院任职的三项资格：年龄（至少三十岁）； 美国公民身份（至少九年）； 以及参议员在选举时所代表的州的居住权。

评级：[无关]
说明：证据仅讨论了竞选美国参议院议员的年龄，而不讨论竞选众议院议员的年龄。

###
指令：{指令}

证据：{证据}

评分：
```


```
您将收到一份说明、证据以及可能的一些前面的句子。 当有前面的句子时，你的注意力应该放在后面的句子上。 您的工作是确定证据是否与初始指令和前面的上下文相关，并提供有用的信息来完成指令中描述的任务。 如果证据符合此要求，请回答[相关]； 否则，生成[不相关]。

###
说明：给定 A、B、C、D 四个选项，选择最佳答案。

输入：地球自转原因
A：AM和PM的循环
B：火山喷发的形成
C：潮汐的循环
D：重力的产生

证据：自转引起昼夜循环，昼夜循环也产生相应的温度和湿度循环，从而产生相应的温度和湿度循环。 随着地球自转，海平面每天上升和下降两次。

评级：[相关]
解释：证据明确提到轮转会导致昼夜循环，如答案选项 A 中所述。

###
说明：描述您钦佩的领导人或政治家。

前句： 领导人和政治家有能力塑造历史进程并影响无数个人的生活。 在众多著名人物中，纳尔逊·曼德拉是一位模范领袖，他不屈不挠的精神、对正义坚定不移的承诺以及团结分裂国家的非凡能力使他成为全球范围内令人钦佩和尊敬的人物。 证据：巴拉克·奥巴马是世界上最有影响力的人物之一，也是一位与众不同的人。 他曾担任美利坚合众国总统。 他是美国第 44 任总统。 他于 2009 年当选为总统。 他是美国第一位非裔美国总统。

评级：[无关]
解释：虽然证据讨论的是被誉为有影响力的政治领袖的巴拉克·奥巴马 (Barack Obama)，但前面的句子描述的是纳尔逊·曼德拉 (Nelson Mandela)，因此该证据无法提供有用的信息来生成有用的延续。

###
指令：{指令}

证据：{证据}

评分：
```

# utils
```

1,940 / 5,000
翻译结果
翻译结果
给定指令和输出，从 1（最低）到 5（最高）对响应是否对查询有帮助且信息丰富的答案进行评分。 我们将此分数称为感知效用。

详细标准如下：
5：响应提供了对查询的完整、高度详细且信息丰富的响应，完全满足信息需求。
4：响应大部分满足查询中的需求，同时可以进行一些小的改进，例如讨论更详细的信息、具有更好的响应结构或提高连贯性。
3：响应可以接受，但需要一些重大的补充或改进才能满足用户的需求。
2：响应仍然解决主要请求，但不完整或与查询不相关。
1：回复几乎不切题或完全不相关。
##
  说明：截至 2023 年，英国现任首相是谁？
输出：鲍里斯·约翰逊 (Boris Johnson) 于 2019 年至 2022 年担任英国首相。
感知效用：2
解释：虽然输出提供了有关 2019 年至 2022 年英国首相的事实正确的陈述，但此指令询问 2023 年的首相是谁，因此它没有回答该指令。 因此，效用为2。

##
说明：根据旅游目的地的描述，推荐10个旅游景点，并逐个详细说明。 旅行目的地是日本东京。
输出：“东京是一座充满活力的城市，充满了令人兴奋的旅游景点。 一些必看景点包括东京晴空塔、东京迪士尼乐园、浅草寺、明治神宫、筑地鱼市场、原宿和新宿御苑。
感知效用：3
说明：此输出不提供每个景点的描述，并且景点的数量也少于 10 个。虽然此输出部分回答了说明，但与说明并不严格匹配。

##
指令：{指令}
输出：{输出}
```
