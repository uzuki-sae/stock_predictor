# stock_predictor
｜背景：transformer最初の試し
｜目標：株価を予測する
｜進捗：失敗（訓練かとともに損失は減りつつあるが、予測する数値は時間次第で変化しない。予測できる範疇を越えたと推測される）
｜実装:pytorch
｜機材：google colaboratory
｜データセット：Yahooファイナンスから過去の株価から入手したCSVファイル
｜インプット：過去の株価
｜アウトプット：未来の株価
｜方法：transformerを訓練してモデルを手にいれる。
｜ファイル：Transformer_stock_predict.ipynbは執行ファイルです。nikkei1.txtとnikkei2.txtは予測する銘柄およびその銘柄コードのリストです。
