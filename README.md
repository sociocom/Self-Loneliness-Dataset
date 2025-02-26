# Self-Loneliness-Dataset

書き手と読み手の孤独感を収集したデータセットです．  
* 書き手の孤独感の程度と，読み手が推測する書き手の孤独感の程度を収集しました．
* 書き手の孤独感の程度は日本語版UCLA孤独感尺度（第3版）によって測りました．
* 書き手となる参加者は，以下の質問に対して4段階（1:決してない、2:ほとんどない、3:時々ある、4:常にある）で回答するとともに，その理由を自由記述で記入しました．
    * 質問1「あなたは現在、孤独感がありますか？」
    * 質問2「あなたは現在、他人（ペット等含む）から受ける愛情が満たされていますか？」
    * 質問3「あなたは現在、自分の行動によって社会環境（友達、家族、会社、学校、世間など）に受け入れられていますか？」
    * 質問4「あなたは現在、自分が受け入れられている・社会環境（友達、家族、会社、学校、世間など）に属していると感じますか？」
* 読み手は「あなたは現在、孤独感がありますか？」に対する回答の理由から，書き手の孤独感の程度（FALSE：無，TRUE：有）を推測しました．
* 読み手がTRUEと判断したデータには社会的欲求（愛情，社会的認知，自尊心と帰属意識）の欠如の有無を付与しました．
* データは1,041件あります．

## データ例

|  | 自由記述　| 書き手 | 読み手 |
|---------|-----------------------------|------|--------|
| 孤独感尺度 |  | 59   |        |
| 質問1   | 周りとの関係性が乏しいため  | 3    | TRUE  |
| 質問2   | 猫が可愛いから癒される     | 3    |        |
| 質問3   | 掃除など頑張っても感謝はされない | 2 |        |
| 質問4   | 周囲との能力の差を感じる | 2    |        |


## 文献情報

## 謝辞

## ライセンス

## 連絡先

## カラム

| カラム名        | 説明 |
|---------------|------------------------------------------------------------------------------------------------------------------------------------|
| **Text1**  | 質問1に対する回答の理由（自由記述） |
| **Writer** | 日本語版UCLA孤独感尺度（第3版）の総点（書き手の孤独感） |
| **Reader** | 読み手が評価した孤独感（TRUE，FALSE） |
| **la**        | 愛情（欠如していればTRUE） |
| **sr**        | 社会的認知（欠如していればTRUE） |
| **sb**        | 自尊心と帰属意識（欠如していればTRUE） |
| **else**      | その他（欠如していればTRUE） |
| **Score1** | 質問1に対する回答（1~4点） |
| **Text2**   | 質問2に対する回答の理由（自由記述） |
| **Score2**  | 質問2に対する回答（1~4点）|
| **Text3**   | 質問3に対する回答の理由（自由記述） |
| **Score3**  | 質問3に対する回答（1~4点） |
| **Text4**   | 質問4に対する回答の理由（自由記述） |
| **Score4**  | 質問4に対する回答（1~4点）|
