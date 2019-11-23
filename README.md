# Stock_Prediction_bi_GRU
Implementation of the following paper:[[bib](https://aclanthology.info/papers/P18-1183/p18-1183.bib)]

Yumo Xu and Shay B. Cohen. 2018. [Stock Movement Prediction from Tweets and Historical Prices](http://aclweb.org/anthology/P18-1183). In Proceedings of the 56st Annual Meeting of the Association for Computational Linguistics. Melbourne, Australia, volume 1.

Based on https://github.com/yumoxu/stocknet-code

Modifications are made to let it run on Python 3.7, Tensorflow 1.14, Cuda 10.1.

The best result I can get is 

`Accuracy=0.562500 & loss=1.104394555091858 when batchsize=128, learning rate=0.001`

and 
`Accuracy=0.565549 & Loss=1.1445451974868774 when batchsize=48, learning rate=0.001`

`Accuracy=0.553354 & Loss=1.9175328016281128 when batchsize=48, learning rate=0.001`
