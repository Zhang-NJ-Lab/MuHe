Word2vec训练出的结果每次都不一样，如果想要一致需要设置随机种子（seed）和worker.
The results of Word2vec training are different every time. If you want to be consistent, you need to set a random seed and worker.
英文文献使用nltk的主要目的不是为了分词而是为了自定义词典，如果nltk效果不好，则可使用简单的文本替换功能去连接词，如把‘solar cell’替换为“solar-cell”
The main purpose of using nltk in English documents is not to segment words but to customize the dictionary. If nltk does not work well, you can use simple text replacement functions to connect words, such as replacing ‘solar cell’ with “solar-cell”
为了保留数据集中化学式的准确性，预处理中不进行全文小写化操作。
In order to preserve the accuracy of the chemical formulas in the data set, the full-text lowercase operation is not performed in the preprocessing.
Chemdataextractor代码可在官网上获得。
The Chemdataextractor code is available on the official website.
当数据集过大时导致txt文件难以打开，可直接在Pycharm里进行操作
When the dataset is too large making it difficult to open the txt file, you can do it directly in Pycharm