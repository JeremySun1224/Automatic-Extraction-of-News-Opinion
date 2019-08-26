## 新闻人物言论提取模型

### 安装

* 安装依赖保存在 **requirements.txt** 文件中
``` 
python -m venv venv 

```

* **model** 文件保存的是pyltp模型
* **similar_word**文件保存的是提取相近词算法以及近义词表，这里保存的是‘说’的近义词。
* **word2vec_model** 文件保存的是word2vec模型，以及实现算法。
* **clean_word** 是实现数据清洗、分词的pipeline。
* **extract_algorithm.py** 保存了人物及言论提取的主要算法。

## 接口说明

* 接口为**extract_algorithm**内的**present_data** 函数
* 输入： string ---> 类型：string, 即一段文本
* 输出： res---> 类型：dictionary，包含人物及其观点
