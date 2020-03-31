# tensorflow2-keras-learn
 Tensorflow2のkerasの勉強の記録です。
 
 社内向けのハンズオン、モブプログラミングの資料が多いです。

# Requirement
 
* Tensorflow 2.0.0
* Pillow 6.1.0
 
# Installation
 
Jupyter Notebookでipynbファイルを開いてください。

# Contents

1. 多層パーセプトロン(Multilayer perceptron:MLP)による、<br>MNIST(手書き数字認識用データセット)の認識
1. 畳み込みニューラルネットワーク(Convolutional Neural Network:CNN)による、<br>Cifar10(10クラス一般物体認識用データセット)の認識
1. ファインチューニングによる、17flowers(17クラスの花認識用データセット)の認識
1. 検討中
    1. データ拡張を用いて精度向上にトライ+ Grad-CAM可視化<br>参考：[データのお気持ちを考えながらData Augmentationする](https://blog.shikoan.com/manual-augmentation/)
    1. 画像クラス分類モデルを改造し年齢推定モデルを作成
    1. 画像クラス分類モデルの入力を複数入力に改造<br>参考：[超簡単 Kerasで複数Input統合モデル](https://qiita.com/FukuharaYohei/items/58cfbce0ed81833a2da1)
    1. 画像クラス分類モデルの出力を複数出力に改造<br>参考：[複数の分類を出力するディープラーニング](https://qiita.com/cvusk/items/1439c1c6dde160c48d13)
    1. LSTMによる時系列データの分類
    1. SSDやpix2pixをクローンして推論を実行
    1. Kaggleの過去コンペ<br>参考：[Kaggleに登録したら次にやること ～ これだけやれば十分闘える！Titanicの先へ行く入門 10 Kernel ～](https://qiita.com/upura/items/3c10ff6fed4e7c3d70f0)
    

# Note

コメントは処理ブロックにしか記載していません（一部例外はあります

参加者同士で各行の処理を説明しあってください。

また、やる気のある方は、以下のチャレンジをおススメします。

個人的に実施してみましたが、画像処理に必要な知識が、かなり網羅されていると思います。

* [画像処理100本ノック](https://github.com/yoyoyo-yo/Gasyori100knock)
* [ディープラーニング∞本ノック](https://github.com/yoyoyo-yo/DeepLearningMugenKnock)
 
# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
tensorflow2-keras-learn is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
