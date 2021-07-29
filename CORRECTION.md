# 誤植

読者の皆様から誤植の報告をいただきました。どうもありがとうございます。誤植を見つけられたら、issueを立て、ご連絡いただければと思います。

### コード

以下のコードの修正は公開しているファイルにはすでに反映済みです。

| コードブロック | 場所 | 訂正 |
| ---- | ---- | --- |
| 4-2 || BertJapanese-Tokenizer -> BertJapaneseTokenizer |
| 5-5 | 下から4行目のコメント内 | iput_ids -> input_ids |
| 6-5 | 下から6行目のコメント内 | scores -> scoresのサイズ |
| 8-5 | p113の上から15, 21, 22行目、p114の下から14, 15行目（計5ヶ所） | tokenizer -> self |
| 8-11 | 下から9行目 （このままでも間違いではありませんが、`return_dict=True`は入れても入れなくても出力は同じなので、削除しました。） | (\*\*encoding, return_dict=True) -> (\*\*encoding)|
| 8-16 | p126の下から3行目、p127の上から4行目（計2ヶ所） | (\*\*batch, return_dict=True) -> (\*\*batch)|
| 8-17 | 上から14行目 | (\*\*encoding, return_dict=True) -> (\*\*encoding)|
| 8-21 | p136の上から7, 22, 23行目、p137の下から13, 14行目（計5ヶ所） | tokenizer -> self |
| 8-23 | p141の下から13行目 | (\*\*encoding, return_dict=True) -> (\*\*encoding)|
| 9-4 | p148の上から5, 12行目、p149の上から15, 16行目、p150の上から10行目（計5ヶ所） | tokenizer -> self |

### 本文

| ページ | 場所 | 訂正 |
| ---- | ---- | --- |
| iv | 前書き最終行 | 読者の皆様の -> 読者の皆様に |
| p2  | 箇条書きの「形態素解析」の項 | 活用系 -> 活用形 |
| p3  | 箇条書きの「文章校正」の項 | 第10章 -> 第9章 |
| p6  | 参考文献[1] | NACACL -> NAACL |
| p12 | 図2.1(b) | x<0でyが0より少し小さい値になってしまっていますが、正確にはx<0ではy=0、x>=0ではy=xです。| 
| p21 | 最終行 | 再起的 -> 再帰的 |
| p25 | 下から2行目 | 出力値$h_i$計算する際 -> 出力値$h_i$を計算する際 |
| p27 | 上から2行目 | 式の先頭に -（マイナス）をつける。 |
| p28 | 上から1行目 | 図2.6(a) -> 図2.6 |
| p34 | 3.1.2項、最初の段落の3行目 | Scale -> Scaled |
| p36 | 3.1.5項、上から2行目 | Layer Normalizatin -> Layer Normalization |
| p37 | 下から1行目 | e^S_i -> e^P_i |
| p41 | 参考文献[2] | NACACL -> NAACL |
| p48 | コードブロック#4-4の出力の直後の文 | マシーンラーニング -> マシンラーニング |
| p53 | 出力例の下 | num_hidden_layer -> num_hidden_layers |
| p53 | 出力例の下 | max_position_embedding -> max_position_embeddings |
| p55 | 上から3行目 | 隠れ状態の次元は728 -> 隠れ状態の次元は768 |
| p63 | 上から2行目 | predict_topk_mask -> predict_mask_topk |
| p73 | 出力例の上から3行目 | size -> scoresのサイズ |
| p78 | 1段落の最終行 | 本項をを -> 本項を |
| p79 | 2段落の最終行 | m_1 -> m |
| p83 | 下から5行目 | train_step -> training_step |
| p84 | 上から1行目 | train_step -> training_step |
| p84 | 上から2行目 | train_step -> training_step |
| p85 | 上から4行目 | ModelCehckpoint -> ModelCheckpoint |
| p85 | 本文の下から2行目 | checkpoint.bert_model_path -> checkpoint.best_model_score |
| p92 | 下から3行目 | 選択肢ない -> 選択しない |
| p107 | ページ下部のIREXの固有表現のカテゴリーのリスト | 「固有物名」が抜けていました。|
| p121 | 本文最終段落中の2箇所と図8.2のキャプション| BertForToeknClassification -> BertForTokenClassification |
| p179 | A-1節の最終段落の下から2行目 | アルゴリズムをを -> アルゴリズムを |

