# Sotai-on Melody Score 仕様書

## 例

Working...

## 数値の意味

- 標準色を白または黒とする。
- 標準色の 0 を C4 とする。
- 標準白の 0 に別な音 (A4, G#5 等) に変更することも可能。
- 1 上がると半音上がり、 2 上がると全音上がる
- 0 から半音下がるときは、一段下の色になり、 $\color{rgba(94, 135, 201, 1)}{\textsf{9}}$ となる
- 9 から半音上がるときは、一段上の色になり、 $\color{rgba(223, 84, 82, 1)}{\textsf{0}}$ となる

## 色の意味

- $\color{rgba(82, 158, 114, 1)}{\textsf{緑 (012)}}$ → 白から見て半音20個分、下
- $\color{rgba(94, 135, 201, 1)}{\textsf{青 (012)}}$ → 白から見て半音10個分、下
- 標準 (012) → 起点となる色。0スタート
- $\color{rgba(223, 84, 82, 1)}{\textsf{赤 (012)}}$ → 白から見て半音10個分、上
- $\color{rgba(202, 152, 73, 1)}{\textsf{黄 (012)}}$ → 白から見て半音20個分、上
- $\color{rgba(157, 104, 211, 1)}{\textsf{紫 (012)}}$ → 白から見て半音30個分、上

## Q&A

- Q: 四分音符や全音符、休符などは無いの？

はい、四分音符や全音符はありません。タイミングは音程を覚えるより早く身につくため、省略しています。また、休符自体はありませんが、半角スペースにより音が無い瞬間を表現することは可能です。

- Q: 和音は扱えますか？

現時点では扱うことは出来ません。数値を縦に並べれば出来るかもしれません・・。

