---

# Nim言語

---

## そもそもNimってどんな言語？

---

### Nimってどんな言語？ その１
- 組み込みからWebまで使える
- 静的型付け言語
- C言語, C++, Javascript, Objective-Cにトランスパイル

---

### Nimってどんな言語？ その２
- メタプログラミングに強い
- AST（言語構文を）カスタマイズできる
- 実行速度がどの言語よりも速い

---

## 実際の記述を見てみよう

---

### 変数宣言

```
# 代入可能な変数
var token = "aa;owienkaksoiefp0a"

# 代入不可の変数
# このように複数を同時に宣言できます
let
    key: string = "a;osiia;nksdf"
    status: int = 3

# 定数
const level = 3
```

---

# 関数宣言

```
\# procが関数定義になります。
proc add(x: int): int =
  return x + 1

\# デフォルトでresultがreturn値として存在
proc add(x: int): int =
  result = x + 1

\# 最後の式が評価されてreturnされます
proc add(x: int): int =
  x + 1
```

---
