# DataLoader Csv Convert
Apex DataLoader から Export した CSVを、別配列のCSVに成形する実装のサンプル。

## 前提
- 入出力ともに Windows-31J, CRLF, カンマ区切り, 引用符 "
- 入力の 1行 は 出力の 1行と 一対一に対応
    - 集計とかはしない

## エスケープ
以下のみ
- " =>  "" 