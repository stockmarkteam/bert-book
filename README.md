# 「BERTによる自然言語処理入門: Transformersを使った実践プログラミング」

こちらは、[「BERTによる自然言語処理入門: Transformersを使った実践プログラミング」、(編) ストックマーク株式会社、(著) 近江 崇宏、金田 健太郎、森長 誠 、江間見 亜利、（オーム社）](https://www.amazon.co.jp/dp/427422726X)のサポートページです。


## 誤植

誤植は[こちら](https://github.com/stockmarkteam/bert-book/blob/master/CORRECTION.md)のページにまとめられています。誤植を見つけられた方は、issueを立ててご連絡いただければ幸いです。

## エラー

コードブロック#6-3, #7-3, #8-3, #9-3で生じるエラーに関しては[こちら](https://github.com/stockmarkteam/bert-book/wiki/pytorch_lightning%E3%81%AEimport%E6%99%82%E3%81%AE%E3%82%A8%E3%83%A9%E3%83%BC%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)をご確認ください。現在、GitHubで公開されているノートブックファイルではこの対応が既に反映されています。

## コード

本書は、Googleの無料の計算環境である[Colaboratory](https://colab.research.google.com/)を利用して、コードを実行することを想定していますが、AWSの無料の計算環境である[Amazon SageMaker Studio Lab](https://studiolab.sagemaker.aws/)を利用することもできます(事前の[メールアドレスによる登録](https://studiolab.sagemaker.aws/requestAccount)が必要です)。Colaboratoryの基本的な使い方は本書の付録を、SageMaker Studio Labの使い方は[こちら](./README_studio-lab.md)をご覧ください。

以下のボタンから、それぞれの計算環境で各章のNotebookを開くことができます。

|Chapter| Google Colaboratory | Amazon SageMaker Studio Lab |
|:---:|:---:|:---:|
|4| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter4.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter4.ipynb) |
|5| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter5.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter5.ipynb) |
|6| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter6.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter6.ipynb) |
|7| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter7.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter7.ipynb) |
|8| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter8.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter8.ipynb) |
|9| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter9.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter9.ipynb) |
|10| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stockmarkteam/bert-book/blob/master/Chapter10.ipynb) |  [![Open In SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/stockmarkteam/bert-book/blob/master/Chapter10.ipynb) |


なおSageMaker Studio Labを用いる場合には、いずれかのNotebookの冒頭で 
```Python
!pip install torch==1.9 matplotlib pandas 
``` 
によりライブラリの追加インストールを行なってください。
