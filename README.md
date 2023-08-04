# 2023ウェブインテリジェンス特論最終課題用

## ソースコードに関して

・実行環境がサーバーでありlocalでないためファイルパスは少々相違が生じている部分があります。

## 利用モデルに関して

・BERTモデル：Japanese_L-12_H-768_A-12_E-30_BPE 2

・DeBERTa-V2~3：Huggingfaceからモデル呼び出し

・juman++(形態素解析ツール)：[jumanpp-2.0.0-rc3](https://nlp.ist.i.kyoto-u.ac.jp/?JUMAN%2B%2B)https://nlp.ist.i.kyoto-u.ac.jp/?JUMAN%2B%2B

→juman++はファイル容量が大きいため、こちらのリンクからlocalに落としてダウンロード

##データセットに関して

・訓練、検証、テストデータそれぞれ5分割交差検証用に(1)~(5)まで作成し「data」に格納




