# udacity-nlp

该目录中的项目为个人在 [udacity  自然语言处理](https://cn.udacity.com/course/natural-language-processing-nanodegree--nd892-cn) 课程中完成的项目。

## 隐马尔可夫词性标注

**目录：hmm-tagger**

词性标注是指根据周围语境中的单词判断某个单词句法类别的流程。通常用于消除自然语言短语的歧义，因为它可以快速完成，并且准确率高。词性标注可以用于很多自然语言处理任务，例如在语音合成中确定正确的发音（例如 *dis*-count 是名词，而 dis-*count* 是动词），以便检索信息和区分单词含义。

在 notebook 中，使用 [Pomegranate](http://pomegranate.readthedocs.io/) 库构建词性标注隐马尔可夫模型，并使用“通用”标签集。[在使用更大型的标签集对实际文本语料库进行标注时，隐马尔可夫模型的准确率达到了 96% 以上](http://www.coli.uni-saarland.de/~thorsten/publications/Brants-ANLP00.pdf)。隐马尔可夫模型还用于语音识别和语音生成、机器翻译、生物信息学基因识别和计算机视觉人类手势识别，等等。

## 机器翻译

**目录：machine_translation**

## 语音识别

**目录：nlp_vui**


