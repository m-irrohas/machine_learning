## NLP(自然言語処理)
とある業務で自然言語処理関係の勉強をひたすらしていた時期がありましたので，そのへんのことをまとめておきます。
これができて何がうれしいかとかいう質問には答えかねます。。。。

#### やったことまとめ
##### 1. マルコフチェインによる文章生成。
文章中のある単語における前後の単語(要するに文脈)から確率的に文章を生成する。
ルールベースなので，機械学習かもしれないが深層学習は使っていない。
計算量もそこまでないので，手軽でオヌヌメ
  
##### 2. Attention付オートエンコーダ実装
自己注意Attentionを用いてオートエンコーダを実装し，ある対話モデルで実験した(ような気がする。)。
記憶にないけど作ってたらしい。。。

##### 3. Transformerで対話モデル実装
流行りのTransformerを作ってみた。Transformerは簡単に言うとRNN・LSTMのようなGRUを用いず，自己注意onlyでオートエンコーダを実現する。
かなりうまくいったが，別のデータセットでも実験したみ。

##### 4. seqgan
覚えてないけど，どうやら敵対学習したらしい。
