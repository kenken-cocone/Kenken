# 積分不等式：面積評価を用いた問題集

## 解説：面積評価による積分不等式の証明

面積評価は、関数のグラフで囲まれた領域の面積を不等号で関係付けることで、積分不等式を証明する手法です。

**基本原理**

関数 $\mathrm{f}(\mathrm{x})$ と $\mathrm{g}(\mathrm{x})$ について、区間 $\mathrm{a} \leqq \mathrm{x} \leqq \mathrm{b}$ で $\mathrm{f}(\mathrm{x}) \leqq \mathrm{g}(\mathrm{x})$ が成り立つとき：

$$\int_{\mathrm{a}}^{\mathrm{b}} \mathrm{f}(\mathrm{x}) \mathrm{d}\mathrm{x} \leqq \int_{\mathrm{a}}^{\mathrm{b}} \mathrm{g}(\mathrm{x}) \mathrm{d}\mathrm{x}$$

この性質を利用して、複雑な積分を上下から評価し、不等式を示します。

**【グラフをここに挿入予定】**

**証明の基本戦略**

1. **比較関数の設定**：被積分関数 $f(x)$ に対して、上下から評価可能な比較関数 $g(x)$ , $h(x)$ を見つける

2. **長方形による評価**：$f(x)$ を縦横が定数の長方形で上下から評価し、積分値の粗い上限・下限を得る

3. **台形による精密評価**：必要に応じて、台形を用いてより精密な評価を行う（複雑な形状の曲線の場合に用いることは非常にまれ）

   

---

## 問題1

次の不等式を証明せよ。

$$\frac{1}{3} < \int_{0}^{1} \mathrm{x}^{(\sin \mathrm{x} + \cos \mathrm{x})^2} \mathrm{d}\mathrm{x} < \frac{1}{2}$$

---

## 問題2

次の不等式を証明せよ。

$$\frac{\pi}{4} < \int_{0}^{1} \sqrt{1 - \mathrm{x}^3} \mathrm{d}\mathrm{x} < 1$$

---

作成日：2026年7月4日

対象：大学入試対策
