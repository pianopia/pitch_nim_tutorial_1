---

# Nim言語チュートリアル

---

## そもそもNimってどんな言語？

---

- モジュールごとのホットコードリローディングもサポート
- 

---

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
