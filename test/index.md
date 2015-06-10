#test

markdown

和の公式

$$ a\;\;\;b $$


$$ \frac{a |- b c \;\;\; d|- d dd}{ eee |- eee } (rule\;error) $$
を計算する関数を C++ で実装せよ。

[test]
解答
----

```cpp
int f(int n) {
  int ret = 0;
  for (int k = 1; k <= n; k++) {
    ret += k;
  }
  return ret;
}
```
