---

# Nim言語

---

## そもそもNimってどんな言語？

---

- 組み込みからWebまで使える
- 静的型付け言語
- C言語, C++, Javascript, Objective-Cにトランスパイル

---

- メタプログラミングに強い
- AST（言語構文を）カスタマイズできる
- 実行速度がどの言語よりも速い

---

```
# コメントは#
# procが関数定義になります。
proc add(x: int): int =
  return x + 1

# デフォルトでresultがreturn値として存在
proc add(x: int): int =
  result = x + 1

# 最後の式が評価されてreturnされます
proc add(x: int): int =
  x + 1
```

---
