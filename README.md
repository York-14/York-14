# York-14

**Creator & Explorer**

I explore the intersection of **creative coding, generative art, perception, and digital tools**.

I build small experiments, visual systems, and simple digital experiences to explore how **order, complexity, and beauty** emerge.

## What I'm exploring

- Generative Art & Creative Coding
- Mathematical patterns and visual systems
- Perception, beauty, and complexity
- Simple digital tools and experiences
- AI-assisted creation

---

# Generative Flower — Order × Chaos

🌐 **[Interactive Web Experience](https://york-14.github.io/Generative-flower-Order-Chaos/)**

> Can beauty emerge from the balance between order and chaos?

This project explores this question through **generative art, mathematical dynamics, and computational models of beauty**.

Using a symmetric chaotic map inspired by the work of **Michael Field and Martin Golubitsky**, the project generates thousands of flower-like forms and explores the relationship between:

**Symmetry → Complexity → Chaos → Beauty**

---

## ✨ Explore the Flowers

### 2D — Generative Flower Studio

**[Open the interactive experience →](https://york-14.github.io/Generative-flower-Order-Chaos/)**

Explore a mathematical space of flower-like attractors by changing parameters such as:

- λ
- α
- β
- γ
- ω
- n

You can:

- Generate flowers randomly
- Explore parameter space
- Change colors and visual appearance
- Save flowers as PNG
- Compare two flowers and choose your favorite

The experience gradually learns your visual preference directly in the browser.

### 3D — Generative Flower

**[Open the 3D experience →](https://york-14.github.io/Generative-flower-Order-Chaos/3d.html)**

The 3D version extends the mathematical system by introducing a height dimension.

The resulting attractors can be rotated and explored interactively.

---

## The Question

### What makes a mathematical form beautiful?

A flower can look beautiful because it has:

- Order
- Symmetry
- Complexity
- Contrast
- Variation
- A sense of life

But where does beauty emerge?

Too much order can become repetitive.

Too much chaos can become noise.

This project explores the hypothesis that beauty may emerge somewhere between the two.

The goal is not to prove that this is the universal definition of beauty.

Instead, the goal is to build a system in which the hypothesis can be **visualized, explored, measured, and tested**.

---

## Mathematical Foundation

The flower-like forms are generated using a symmetric chaotic map in the complex plane.

By varying the parameters, a large variety of flower-like structures can be generated.

---

## From Mathematical Forms to a Shape Map

The project does not stop at generating individual flowers.

Thousands of generated forms can be analyzed and mapped into a visual space.

```text
Mathematical Parameters
          ↓
   Generative Dynamics
          ↓
     Flower-like Forms
          ↓
     Shape Features
          ↓
   Dimensional Reduction
          ↓
      Shape Map
          ↓
   Beauty Evaluation
```

The shape representation uses polar resampling and angular FFT features so that the representation is invariant to rotation and reflection.

The resulting feature space is reduced using:

- PCA
- UMAP
- t-SNE

and explored using HDBSCAN clustering.

---

## A Computational Model of Beauty

The project experiments with a simple hypothesis:

**Beauty = Order × Complexity × Contrast**

### Order

Measures related to:

- rotational symmetry
- reflection symmetry
- angular contrast

### Complexity

Measures related to:

- fractal / box-counting dimension
- Lyapunov exponent
- chaotic behavior

### Contrast

Measures related to:

- edge sharpness
- negative space
- visual clarity
- isolated noise

The three components are combined into an exploratory beauty score.

---

## Human Preference

A mathematical beauty function is only a hypothesis.

So the project also introduces human preference.

Two flowers are shown and the user chooses which one they prefer.

Each choice becomes a pairwise comparison.

A Bradley–Terry model is then used to estimate which characteristics are associated with the user’s preferences.

As more comparisons are made, the system gradually adapts its search toward the user’s aesthetic preference.

The preference data is stored only in the browser’s local storage and is not sent to a server.

---

## Order × Chaos

The central idea of this project is simple:

Beauty may emerge not from pure order or pure chaos, but from their interaction.

The flower becomes a visual laboratory for exploring this idea.

Instead of looking at a single beautiful image, we can explore an entire space of possible forms.

Instead of asking:

“Is this flower beautiful?”

we can begin asking:

“What properties make this form beautiful?”

And eventually:

“Can beauty itself be explored as a computational space?”

---

## Research Directions

This project is an ongoing exploration rather than a finished scientific model.

Future directions include:

- Exploring larger mathematical model spaces
- Better measures of visual complexity
- More rigorous symmetry descriptors
- Improved perceptual models
- Larger-scale human preference experiments
- Learning aesthetic preferences from pairwise comparisons
- Exploring the relationship between mathematical structure and perceived beauty
- Extending the system from 2D to 3D and beyond

---

## Creator

**York-14**

Creator & Explorer exploring:

- Generative Art
- Creative Coding
- Mathematical Visualization
- Perception
- Beauty
- Complexity
- Digital Creation

Intelligence is the ability to explore.

---

**日本語**

# 🌸 Generative Flower — Order × Chaos

> 秩序とカオスのバランスから、美しさは生まれるのか？

このプロジェクトは、生成アート・数理モデル・知覚・美しさの関係を探究するインタラクティブな実験です。

Michael Field と Martin Golubitsky の研究に着想を得た対称性を持つカオス写像を用いて、数千種類の花のような形態を生成します。

そして、

**Symmetry → Complexity → Chaos → Beauty**

という関係を、視覚的・数理的に探索します。

---

## ✨ 花を探索する

### 2D — Generative Flower Studio

**[インタラクティブ作品を見る →](https://york-14.github.io/Generative-flower-Order-Chaos/)**

数学的に生成される花の形を、パラメータを変化させながら探索できます。

主なパラメータ：

- λ
- α
- β
- γ
- ω
- n

できること：

- 花をランダムに生成
- パラメータ空間を探索
- 色や視覚表現を変更
- PNGとして保存
- 2つの花を比較して、好きな方を選択

ユーザーが選択した結果から、ブラウザ上で視覚的な好みを学習する仕組みも実験しています。

### 3D — Generative Flower

**[3D作品を見る →](https://york-14.github.io/Generative-flower-Order-Chaos/3d.html)**

2Dの数理モデルを拡張し、高さ方向の変数を加えることで、3次元の花のような形態を生成します。

生成された形態を回転させながら、立体的に探索できます。

---

## 問い

### 数学的に生成された形は、なぜ美しく感じられるのか？

花が美しいと感じられる理由には、

- 秩序
- 対称性
- 複雑性
- コントラスト
- 変化
- 生命感

などが関係しているかもしれません。

では、美しさはどこから生まれるのでしょうか？

秩序が強すぎれば、単調になる。

カオスが強すぎれば、ノイズになる。

このプロジェクトでは、

秩序とカオスの間に、美しさが現れる領域があるのではないか？

という仮説を探索します。

これは「美しさとは何か」という問いに対する普遍的な答えを証明するものではありません。

むしろ、

**美しさについての仮説を、可視化し、探索し、測定し、人間の知覚によって検証するための実験環境**

をつくることを目指しています。

---

## 数学的基盤

花のような形態は、複素平面上の対称性を持つカオス写像から生成されます。

パラメータを変化させることで、さまざまな対称性・複雑性を持つ花のような形態が現れます。

同じ数式から、

**秩序 → 複雑性 → カオス**

という異なる状態を連続的に探索できることが、このシステムの特徴です。

---

## 数学的な形から「形態の地図」へ

このプロジェクトでは、単に美しい花を1つ生成することだけを目的としていません。

大量に生成した形態を分析し、

「どのような形が存在し、互いにどのような関係にあるのか」

を探索します。

```text
数学的パラメータ
       ↓
  生成ダイナミクス
       ↓
   花のような形態
       ↓
    形状特徴量
       ↓
   次元削減・分析
       ↓
    形態の地図
       ↓
   美しさの評価
```

形状は極座標による再サンプリングと角度方向のFFTなどを用いて特徴量化し、回転や反転による影響を抑えた形状表現を試みています。

その特徴空間を、

- PCA
- UMAP
- t-SNE
- HDBSCAN

などを用いて探索します。

---

## 美しさを計算する

このプロジェクトでは、美しさについて一つの仮説を置いています。

**Beauty = Order × Complexity × Contrast**

### Order — 秩序

例えば、

- 回転対称性
- 鏡映対称性
- 角度方向のコントラスト

など。

### Complexity — 複雑性

例えば、

- フラクタル次元
- Box-counting dimension
- Lyapunov exponent
- カオス的挙動

など。

### Contrast — コントラスト

例えば、

- エッジの明瞭さ
- ネガティブスペース
- 視覚的な明瞭性
- 孤立したノイズ

など。

これらを組み合わせ、探索的な「美しさのスコア」を作ります。

---

## 人間の好みを取り入れる

しかし、数学的に定義した「美しさ」は、あくまで仮説です。

そこで、このプロジェクトでは人間の選択も取り入れます。

2つの花を表示し、

どちらが好きですか？

と尋ねます。

その一つ一つの選択をペア比較データとして蓄積します。

そして Bradley–Terry model を使い、どのような特徴を持つ形が選ばれやすいのかを推定します。

比較を繰り返すことで、システムがユーザーの美的嗜好に近い形態を探索することを目指します。

選択データはブラウザのローカルストレージに保存され、サーバーには送信されません。

---

## Order × Chaos

このプロジェクトの中心にある考えはシンプルです。

美しさは、純粋な秩序でも純粋なカオスでもなく、その相互作用から生まれるのではないか。

一つの美しい花を見るのではなく、

「存在し得る形態の空間」そのものを探索する。

そして、

「この花は美しいか？」

だけではなく、

「なぜこの形を美しいと感じるのか？」

さらに、

「美しさそのものを、計算可能な探索空間として扱うことはできるのか？」

という問いへ進んでいきます。

---

## 今後の探索

このプロジェクトは、完成した科学モデルではなく、継続的な探索です。

今後は、

- より広い数理モデルの探索
- 視覚的複雑性のより良い指標
- より厳密な対称性の記述
- 人間の知覚に近い美的モデル
- より大規模な人間の選好実験
- ペア比較からの美的嗜好の学習
- 数学的構造と知覚される美しさの関係
- 2Dから3D、さらに高次元への拡張

などを探究していきます。

---

## Creator

**York-14**

Creator & Explorer

Exploring:

- Generative Art
- Creative Coding
- Mathematical Visualization
- Perception
- Beauty
- Complexity
- Digital Creation

Intelligence is the ability to explore.

知能とは、探索する能力である。

---

🌐 [Generative Flowerを体験する](https://york-14.github.io/Generative-flower-Order-Chaos/)

🐙 ソースコードを見る

📷 [Instagram](https://www.instagram.com/york8worpco/)
