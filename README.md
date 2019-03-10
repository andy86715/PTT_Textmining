# PTT 鄉民用字資料研究案
「文字探勘導論」課程期末研究報告

## Introduction
本研究以PTT為主，希望了解網路使用者的留言用字愛好以及看出各版之間的差異性以及相同之處，抓出各版常共同出現之不好詞語以便版主管理，方便其訂定相關規章。

資料來源：PTT八卦板、棒球版、汽車板、西洽版
## Methods
本研究使用Jieba中文斷詞技術做文字切割並使用Ngram及自定義辭典做斷字的正確與否檢驗。接著使用Word2vec詞語向量化產出相似語，最後以文字雲方式呈現

[程式碼1：PTT爬蟲](/01_PTT爬蟲.ipynb/)

[程式碼2：Ngram建立自訂義字典](/02_Ngram.ipynb/)

[程式碼3：Word2Vec演算法產生文字雲](/03_Word2Vec.ipynb/)
## Results

[書面報告](https://github.com/andy86715/PTT_Textmining/blob/master/final%20report/群組P期末書面格式.pdf)

[投影片簡報](https://github.com/andy86715/PTT_Textmining/blob/master/final%20report/文字探勘期末報告.pdf)
