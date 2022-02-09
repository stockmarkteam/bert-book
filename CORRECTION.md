# 誤植

読者の皆様から誤植の報告をいただきました。どうもありがとうございます。誤植を見つけられたら、issueを立て、ご連絡いただければと思います。

### コード

以下のコードの修正は公開しているファイルにはすでに反映済みです。

| コードブロック | 場所 | 訂正 | 反映 |
| ---- | ---- | ---- | ---- |
| 4-2 || BertJapanese-Tokenizer -> BertJapaneseTokenizer | 第3刷 |
| 5-5 | 下から4行目のコメント内 | iput_ids -> input_ids | 第3刷 |
| 6-5 | 下から6行目 | scores -> scoresのサイズ | 第3刷 |
| 8-5 | p113の上から15, 21, 22行目、p114の下から14, 15行目（計5ヶ所） | tokenizer -> self | 第3刷 |
| 8-11 | 下から9行目 （このままでも間違いではありませんが、`return_dict=True`は入れても入れなくても出力は同じなので、削除しました。） | (\*\*encoding, return_dict=True) -> (\*\*encoding)| 第3刷 | 
| 8-16 | p126の下から3行目、p127の上から4行目（計2ヶ所） | (\*\*batch, return_dict=True) -> (\*\*batch)| 第3刷 |
| 8-17 | 上から14行目 | (\*\*encoding, return_dict=True) -> (\*\*encoding)| 第3刷 |
| 8-21 | p136の上から7, 22, 23行目、p137の下から13, 14行目（計5ヶ所） | tokenizer -> self | 第3刷 |
| 8-23 | p141の下から13行目 | (\*\*encoding, return_dict=True) -> (\*\*encoding)| 第3刷 |
| 9-4 | p148の上から5, 12行目、p149の上から15, 16行目、p150の上から10行目（計5ヶ所） | tokenizer -> self | 第3刷 |

### 本文

| ページ | 場所 | 訂正 | 反映 |
| ---- | ---- | ---- | ---- |
| iv | 前書き最終行 | 読者の皆様の -> 読者の皆様に | 第3刷 |
| v | 目次2.4.2 | Long-Short Term Memoty -> Long Short-Term Memory | 第5刷 |
| p2  | 箇条書きの「形態素解析」の項 | 活用系 -> 活用形 | 第3刷 |
| p3  | 箇条書きの「文章校正」の項 | 第10章 -> 第9章 | 第5刷 |
| p6  | 参考文献[1] | NACACL -> NAACL | 第3刷 |
| p12 | 図2.1(b) | x<0でyが0より少し小さい値になってしまっていますが、正確にはx<0ではy=0、x>=0ではy=xです。| 第3刷 |
| p21 | 最終行 | 再起的 -> 再帰的 | 第3刷 |
| p22 | 下から7行目 | ベクトル$h'\_i$をSoftmax変換 -> ベクトル$h'\_(i-1)$をSoftmax変換 | 第5刷 |
| p24 | 2.4.2項見出し | Long-Short Term Memoty -> Long Short-Term Memory | 第5刷 |
| p25 | 下から2行目 | 出力値$h_i$計算する際 -> 出力値$h_i$を計算する際 | 第3刷 |
| p27 | 上から2行目 | 式の先頭に -（マイナス）をつける。 | 第3刷 |
| p28 | 上から1行目 | 図2.6(a) -> 図2.6 | 第3刷 |
| p34 | 上から8行目 | と表現されます。 -> と表現されます（$K^T$は行列$K$の転置行列を表す）。 | 第5刷 |
| p34 | 3.1.2項、最初の段落の3行目 | Scale -> Scaled | 第3刷 |
| p36 | 3.1.5項、上から2行目 | Layer Normalizatin -> Layer Normalization | 第5刷 |
| p36 | 3.2.1項、上から5行目 | 受け入れるられる -> 受け入れられる | 第5刷 |
| p36 | 3.2.1項、上から8行目 | 末尾にに -> 末尾に | 第5刷 |
| p37 | 下から1行目 | e^S_i -> e^P_i | 第3刷 |
| p41 | 参考文献[2] | NACACL -> NAACL | 第3刷 |
| p48 | コードブロック#4-4の出力の直後の文 | マシーンラーニング -> マシンラーニング | 第3刷 |
| p53 | 出力例の下 | num_hidden_layer -> num_hidden_layers | 第3刷 |
| p53 | 出力例の下 | max_position_embedding -> max_position_embeddings | 第3刷 |
| p55 | 上から3行目 | 隠れ状態の次元は728 -> 隠れ状態の次元は768 | 第3刷 |
| p63 | 上から2行目 | predict_topk_mask -> predict_mask_topk | 第3刷 |
| p73 | 出力例の上から3行目 | size -> scoresのサイズ | 第3刷 |
| p78 | 1段落の最終行 | 本項をを -> 本項を | 第3刷 |
| p79 | 2段落の最終行 | m_1 -> m | 第3刷 |
| p83 | 下から5行目 | train_step -> training_step | 第3刷 |
| p84 | 上から1行目 | train_step -> training_step | 第3刷 |
| p84 | 上から2行目 | train_step -> training_step | 第3刷 |
| p85 | 上から4行目 | ModelCehckpoint -> ModelCheckpoint | 第3刷 |
| p85 | 本文の下から2行目 | checkpoint.bert_model_path -> checkpoint.best_model_score | 第3刷 |
| p92 | 下から3行目 | 選択肢ない -> 選択しない | 第5刷 |
| p107 | ページ下部のIREXの固有表現のカテゴリーのリスト | 「固有物名」が抜けていました。| 第3刷 |
| p117 | 例文 | Ltdだ。 -> Ltdである。 | 第5刷 |
| p118 | 上から3行目 | 「Tencent Holdings Limited」 -> 「Tencent Holdings Ltd」 | 第5刷 |
| p121 | 本文最終段落中の2箇所と図8.2のキャプション| BertForToeknClassification -> BertForTokenClassification | 第3刷 |
| p128 | 上から15行目 | 〜再現率は下がってしまします。 -> 〜再現率は下がってしまいます。 | 第5刷 |
| p132 | 上から2行目| この線は -> この例は | 第5刷 |
| p135 | 下から1行目| ここでで -> ここで | 第5刷 |
| p156 | 箇条書き1つめ| categry -> category | 第5刷 |
| p179 | A-1節の最終段落の下から2行目 | アルゴリズムをを -> アルゴリズムを | 第3刷 |
