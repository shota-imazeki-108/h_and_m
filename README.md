# h_and_m
- なんもわからんかった笑。
- だらだら適当にやって最後だけ本気出すの良くない。反省。
- recboleは便利だなと思ったが、リソースやら選んだモデルの構造わからなくて上手く活用できなかった気がする。
    - https://techlife.cookpad.com/entry/2021/11/04/090000
    - https://www.kaggle.com/code/astrung/recbole-lstm-sequential-for-recomendation-tutorial
    - https://recbole.io/docs/search.html

## 上位解法
- 上位勢はNNではなくLGBMなどが多い印象。
- ネガティブサンプリングが上手くいかずにやめてしまったが、チームによっては候補を数百出したあとにsampleでランダムに取ったりしていた。
- これによって、季節性のあるアイテムなども候補に入ってきていそう。
- あと過去に買ったことのある商品や1年前の購買情報なども利用していた。
- 思っていたよりシンプルな解法が多くてびびる。
- 思いついたことを怠けずちゃんとやった人が上位に行ったと思われる。。。