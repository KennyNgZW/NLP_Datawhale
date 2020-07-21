# NLP_Datawhale
records of NLP learning process from Datawhale

## Task 1 赛题理解
本次赛题是通过对已进行匿名化处理（中文-->数字）的文本进行分类（分成14类），对应关系如下——{'科技': 0, '股票': 1, '体育': 2, '娱乐': 3, '时政': 4, '社会': 5, '教育': 6, '财经': 7, '家居': 8, '游戏': 9, '房产': 10, '时尚': 11, '彩票': 12, '星座': 13}。

另，训练集和测试集中的原始数据形式如下：
![image](https://github.com/KennyNgZW/NLP_Datawhale/blob/master/dataform_text_classification.png)

赛题目的是希望能了解需要分析的内容中数字之间的关系，可以直接提取他们的关系而不需要其他的特征构造的方式或者简单的统计方式（分组之后进行sum, mean, max, nunique之类）。
