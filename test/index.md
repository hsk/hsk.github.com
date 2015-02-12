#test

markdown

和の公式
$$ \sum\_{k=1}^n k = \frac{1}{2}n(n+1) $$
を計算する関数を C++ で実装せよ。

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

