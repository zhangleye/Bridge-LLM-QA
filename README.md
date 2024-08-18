基于大语言模型的桥梁设计规范问答系统

张乐业1，田翔翔1，张洪俊2

（1. 江苏财会职业学院，连云港222061；

2. 万世先行数智交通科技有限公司，南京210016）
3. 
摘要：本文构建了基于大语言模型的桥梁设计规范问答系统。尝试了三种实现方案：对BERT预训练模型进行全参数微调、对BERT预训练模型进行参数高效微调、从零开始自建语言模型。通过自建的问答任务数据集，基于TensorFlow及Keras深度学习平台框架，构建和训练模型，预测答案在用户给定的桥梁设计规范中的开始位置和结束位置。实验结果显示：BERT预训练模型全参数微调方案在训练集、验证集和测试集上均达到了100%的精度，系统能够从用户给定的桥梁设计规范中抽取出答案，以回答用户的各种提问；而BERT预训练模型参数高效微调方案和自建语言模型方案虽然在训练集上表现良好，但在测试集上的泛化能力有待提高。本文的研究为专业领域问答系统的发展提供了有益参考。

关键词：问答系统；大语言模型；桥梁设计规范；预训练模型；全参数微调；参数高效微调

中图分类号：TP391；U442.5	文献标志码：A


Question answering system of bridge design specification based on large language model

Leye Zhang1，Xiangxiang Tian1，Hongjun Zhang2

（1. Jiangsu College of Finance & Accounting, Lianyungang, 222061, China;

2. Wanshi Antecedence Digital Intelligence Traffic Technology Co., Ltd, Nanjing, 210016, China）
3. 
 Abstract：This paper constructs question answering system for bridge design specification based on large language model. Three implementation schemes are tried: full fine-tuning of the Bert pretrained model, parameter-efficient fine-tuning of the Bert pretrained model, and self-built language model from scratch. Through the self-built question and answer task dataset, based on the tensorflow and keras deep learning platform framework, the model is constructed and trained to predict the start position and end position of the answer in the bridge design specification given by the user. The experimental results show that full fine-tuning of the Bert pretrained model achieves 100% accuracy in the training-dataset, validation-dataset and test-dataset, and the system can extract the answers from the bridge design specification given by the user to answer various questions of the user; While parameter-efficient fine-tuning of the Bert pretrained model and self-built language model from scratch perform well in the training-dataset, their generalization ability in the test-dataset needs to be improved. The research of this paper provides a useful reference for the development of question answering system in professional field.

Keywords: question answering system; large language model; bridge design specification; pretrained model; full fine-tuning; parameter-efficient fine-tuning

