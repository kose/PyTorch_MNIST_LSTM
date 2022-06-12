# PyTorch MNIST LSTM

MNIST を LSTM で推論する、モノです。

ラインセンサーのスキャンラインをイメージしましょう。
手書き数字(MNIST)のx軸の28次元の特徴を、時系列 t0 〜 t27 でラインスキャンするイメージで
時系列データとみなして学習します。

many to one の LSTM の一般形の図は以下です。

MINISTで適用すると、n = 28, N = 10 で、ハイパーパラメータとして hidden_dim = 128, lstm_layers = 2 を
使用したコードになっています。

![LSTM](LSTM.png)


## Reference

- [今度こそわかるぞRNN, LSTM編](https://qiita.com/kazukiii/items/df809d6cd5d7d1f57be3)
- [【PyTorch】MNISTの分類問題をいろんなモデルで実装する【全結合層・CNN・RNN・LSTM】](https://lotti.info/mnist-dence-cnn-rnn-lstm/)
