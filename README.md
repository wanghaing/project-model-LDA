# project-model-LDA
Lda主题模型
#python实现的LDA算法

#模型参数在lda.py文件的前几行修改，参数分别为：

#''' alpha = 0.1
#
#beta = 0.1
#
#K = 10 //主题个数

#iter_num = 50 //迭代次数

#top_words = 20 //每个主题显示的词的个数

#wordmapfile = './model/wordmap.txt' //wordmap文件存储位置

#trnfile = "./model/test.dat" //训练文件

#modelfile_suffix = "./model/final" //模型文件的存储位置以及前缀 '''

#输入文件的要求： 每行为一篇文档，分词后用空格隔开。

#1. `final.others` 保存模型训练时选择的参数 
#alpha = 0.1
#beta = 0.1
#ntopics = 10//主题个数
#ndocs = 100//文章个数，一行一个文章
#nwords = 5051//文字个数（去重）
#liter = 50//迭代次数
#1.`wordmap.text` 保存词与id的对应关系，主要用作topN时查询 （如果重复直接跳过，下一位置直接顶上，序号连续）
#2. `final.twords` 输出每个类高频词topN个 
#3. `final.tassgin` 输出文章中每个词分派的结果，文本格式为词id:类id 
#4. `final.theta` 输出文章与类的分布概率，文本一行表示一篇文章，概率1   概率2 ...表示文章属于类的概率 
#5.`final.phi` 输出词与类的分布概率，是一个K*M的矩阵，其中K为设置分类的个数，M为所有文章的词的总数，











