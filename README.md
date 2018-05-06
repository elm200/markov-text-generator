# markov-text-generator
マルコフ連鎖を使って自分のツイートっぽい文章を生成する

## 前提

以下のソフトウェアがインストール済であること。

- Python 3
- pandas
- Mecab
- mecab-python3

## 準備

Twitterの公式サイトから、自分のツイートをダウンロードしておく。
その zip ファイルを解答すると、tweets.csv というファイルが現れるので、
それをこのプロジェクトのあるディレクトリに置いておく。

## 実行

```
$ python text_generator.py
```
