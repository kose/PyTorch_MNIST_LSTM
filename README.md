# PyTorch MNIST LSTM

MNIST を LSTM で推論する、モノです。

ラインセンサーのスキャンラインをイメージしましょう。
手書き数字(MNIST)のx軸の28次元の特徴を、時系列 t0 〜 t27 でラインスキャンするイメージで
時系列データとみなして学習します。

PyTorch の LSTM (many to one) 関数を図で示します。

![LSTM](LSTM.png)

MINISTに適用すると、n = 28, N = 10 で、ハイパーパラメータとして hidden_dim = 128, lstm_layers = 2 を
使用したコードになっています。


## Reference

- [Basic MNIST Exsample](https://github.com/pytorch/examples/tree/main/mnist)
- [今度こそわかるぞRNN, LSTM編](https://qiita.com/kazukiii/items/df809d6cd5d7d1f57be3)
- [【PyTorch】MNISTの分類問題をいろんなモデルで実装する【全結合層・CNN・RNN・LSTM】](https://lotti.info/mnist-dence-cnn-rnn-lstm/)
