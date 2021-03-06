# Event-extraction-paper
Event extraction paper List

-HMEAE: Hierarchical Modular Event Argument Extraction   在本文中，我们提出一种分层模块化事件参数提取方法（HMEAE）模型，提供有效的概念层次的归纳偏差事件参数角色。具体来说，我们设计一个神经网络模块，用于每个基本的概念层次的单位，然后是层次使用将逻辑操作转化为面向角色的模块化对特定参数进行分类的网络角色。因为许多参数角色共享相同的高层单元模块，它们的相关性可以用于提取特定的事件参数更好。[paper](https://www.aclweb.org/anthology/D19-1584.pdf) [code](https://github.com/thunlp/HMEAE)

-Event Detection without Triggers   本文提出了一种不需要触发词进行的事件检测（TBN-NAM）模型，并取得了SOTA的效果。具体地，将输入的句子与事件类型进行多个二分类，输出为0或1，从而检测句子中是否包含目标类型的事件。本文还利用atteneion机制进行局部的特征提取，结合全局特征更好地进行特征融合，使分类结果更加准确。[paper](https://www.aclweb.org/anthology/N19-1080.pdf) [code](https://github.com/liushulinle/event_detection_without_triggers)

-How Does Context Matter? On the Robustness of Event Detection with Context-Selective Mask Generalization   本文强调鲁棒性建模在ED模型中的重要性来。我们首先指出了三个明显的例子来说明现有ED模型的脆弱性。在分析其原因的基础上，我们提出了一种新的ED训练机制，称为上下文选择掩码泛化（context selective mask generalization），它可以有效地挖掘特定于上下文的学习模式，并对ED模型进行鲁棒化。[paper](https://www.aclweb.org/anthology/2020.findings-emnlp.229.pdf) [code]()

-Incremental Event Detection via Knowledge Consolidation Networks   本文首次提出增量事件检测任务，设计了一种知识整合网络来实现增量事件检测，并取得了SOTA的效果。具体地，第一步，使用Bert作为trigger extractor；第二步，为了解决语义模糊问题，采用了原型增强回顾来保留具有代表性的样例；最后，对于增量学习存在的catastrophic forgeting问题所造成的class imbalance,设计了一种分层的知识蒸馏，分别对features-level和predictions-level进行知识蒸馏，使模型在预测新的class的同时，不会遗忘之前的class。[paper](https://www.aclweb.org/anthology/2020.emnlp-main.52.pdf)

-Reading the Manual:Event Extration as Definition Cpmprehension    本文将事件抽取任务转化为阅读理解任务，通过从注释手册派生的直白陈述的增量细化来提取事件信息，并且在读取到新的定义时，将其定义为新的事件类型。具体地，从要抽取信息地text中，生成statement(someone do someting with something at sometime),模型在单句上下文中运行，运行一次记作一个round,每一round填充一个槽位，直至生成完整的statement。[paper](https://www.aclweb.org/anthology/2020.spnlp-1.9.pdf)
