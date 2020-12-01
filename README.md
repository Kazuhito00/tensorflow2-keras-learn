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
1. ファインチューニングによる、17flowers(17クラスの花認識用データセット)の認識<br>参考：[TensorFlow2で機械学習をはじめたいと思ってる方へ](https://qiita.com/tatsuya11bbs/items/7d7a2c920730ae0c592a)
1. Object Detection APIを使用した物体検出ハンズオン<br>
[Tensorflow2-ObjectDetectionAPI-Colab-Hands-On](https://github.com/Kazuhito00/Tensorflow2-ObjectDetectionAPI-Colab-Hands-On) ※別リポジトリ
1. 検討中
    1. データ拡張を用いて精度向上にトライ、Grad-CAM可視化<br>参考：[データのお気持ちを考えながらData Augmentationする](https://blog.shikoan.com/manual-augmentation/)
    1. 画像クラス分類モデルを改造し年齢推定モデルを作成
    1. 画像クラス分類モデルの入力を複数入力に改造<br>参考：[超簡単 Kerasで複数Input統合モデル](https://qiita.com/FukuharaYohei/items/58cfbce0ed81833a2da1)
    1. 画像クラス分類モデルの出力を複数出力に改造<br>参考：[複数の分類を出力するディープラーニング](https://qiita.com/cvusk/items/1439c1c6dde160c48d13)
    1. LSTMによる時系列データ or 音の分類<br>音声データ取り扱いの参考：[TensorFlowメモ（Simple Audio Recognition）](https://work-in-progress.hatenablog.com/entry/2020/02/08/111004)
    1. Kaggleの過去コンペ<br>参考：[Kaggleに登録したら次にやること ～ これだけやれば十分闘える！Titanicの先へ行く入門 10 Kernel ～](https://qiita.com/upura/items/3c10ff6fed4e7c3d70f0)
    

# Note

コメントは処理ブロックにしか記載していません（一部例外はあります

参加者同士で各行の処理を説明しあってください。

また、やる気のある方は、以下のチャレンジをおススメします。

個人的に実施してみましたが、画像処理に必要な知識が、かなり網羅されていると思います。

* [画像処理100本ノック](https://github.com/yoyoyo-yo/Gasyori100knock)
* [音声情報処理n本ノック](https://github.com/tam17aki/speech_process_exercise)
* [ディープラーニング∞本ノック](https://github.com/yoyoyo-yo/DeepLearningMugenKnock)

# Note2
より発展的な内容のためのリンク集です。

* [Browse State-of-the-Art](https://paperswithcode.com/sota)
* [機械学習関係の論文の調査共有リポジトリ](https://github.com/arXivTimes/arXivTimes)
* [機械学習に利用可能なデータセット集](https://github.com/arXivTimes/arXivTimes/tree/master/datasets)
* [機械学習に有用なツール集](https://github.com/arXivTimes/arXivTimes/tree/master/tools)
* [LIONBRIDGE.AI：機械学習向けデータセットライブラリ](https://lionbridge.ai/ja/datasets/library/)
* [LIONBRIDGE.AI：【50個掲載】機械学習に使えるデータセットまとめ](https://lionbridge.ai/ja/datasets/the-50-best-free-datasets-for-machine-learning/)
* [機械学習品質マネジメントガイドライン](https://www.cpsec.aist.go.jp/achievements/aiqm/)

# Note3
将来的に機械学習プロジェクトへ携わる方への参考情報です。

* [失敗から学ぶ機械学習応用](https://www.slideshare.net/HiroyukiMasuda1/ss-181844477)
* [機械学習の未解決課題](https://www.slideshare.net/HiroyukiMasuda1/unsolved-machine-learning-problems-196997933)
* [機械学習モデルの判断根拠の説明](https://www.slideshare.net/SatoshiHara3/ver2-225753735)
* [コンピュータビジョンの観点から見たAIの公平性](https://www.slideshare.net/cvpaperchallenge/ai-229094219)
* [公平な機械学習へ向けての技術と課題](https://qiita.com/ly9988/items/6017404d23cfd38500c1)
* [機械学習のデータセットの重要性](https://qiita.com/nonbiri15/items/b29fe079d359d531bf85)


# Other memo
* [ML Visuals by dair.ai(スライド用素材)](https://docs.google.com/presentation/d/11mR1nkIR9fbHegFkcFq8z9oDQ5sjv8E3JJp1LfLGKuk/edit#slide=id.p)
* [NN SVG(SVGでのネットワーク作図)](https://alexlenail.me/NN-SVG/)
 
# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
tensorflow2-keras-learn is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
