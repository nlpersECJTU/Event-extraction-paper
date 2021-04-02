# Event-extraction-paper
Event extraction paper List
-HMEAE: Hierarchical Modular Event Argument Extraction   在本文中，我们提出一种分层模块化事件参数提取方法（HMEAE）模型，提供有效的概念层次的归纳偏差事件参数角色。具体来说，我们设计一个神经网络模块，用于每个基本的概念层次的单位，然后是层次使用将逻辑操作转化为面向角色的模块化对特定参数进行分类的网络角色。因为许多参数角色共享相同的高层单元模块，它们的相关性可以用于提取特定的事件参数更好。[paper](https://www.aclweb.org/anthology/D19-1584.pdf) [code](https://github.com/thunlp/HMEAE)

-Event Detection without Triggers   本文提出了一种不需要触发词进行的事件检测（TBN-NAM）模型，并取得了SOTA的效果。具体地，将输入的句子与事件类型进行多个二分类，输出为0或1，从而检测句子中是否包含目标类型的事件。本文还利用atteneion机制进行局部的特征提取，结合全局特征更好地进行特征融合，使分类结果更加准确。[paper](https://www.aclweb.org/anthology/N19-1080.pdf) [code](https://github.com/liushulinle/event_detection_without_triggers)
