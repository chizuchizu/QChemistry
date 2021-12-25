---
# try also 'default' to start simple
theme: seriph 
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false

footer: "量子化学勉強会 1日目"
---


# Hi There

<BarBottom  title="量子化学勉強会">
</BarBottom>

---

# 光とは波である

<div class="grid grid-cols-[50%,50%] gap-4"><div>

<br>

> 「電磁波」とは、電磁的エネルギーが空間を振動しながら伝播していく物理現象を指して言う言葉です。 ( [第2回「光」は「電磁波」の一種｜CCS：シーシーエス株式会社](https://www.ccs-inc.co.jp/guide/column/light_color/vol02.html)) 

<br>

- 光の強さ: 振幅の2乗に比例
- エネルギー: 振動数に比例
  - 短波長: 赤外線
  - 長波長: 紫外線



</div><div>

<div class="img2"></div>

<style>
  .img2{
    background-image:url(./img/wave-detail.png);
    background-repeat:no-repeat;
    background-size:340pt 230px;
    width:360pt;
    height:300px
  }
</style>
</div></div>

---




---

# 光電効果(photoeletric effect)
金属の表面に紫外線を当てたら電子が飛び出てくる
<div class="grid grid-cols-[50%,50%] gap-4"><div>
<br>

## 光が粒子であることがわかった



</div><div>
<div class="img1"></div>

<style>
  .img1{
    background-image: url(./img/121.png);
    background-repeat: no-repeat;
    background-size: 360pt 150px;
    width: 360pt;
    height: 150pt
  }
</style>

### 用語
- 光子(Photon): 光を粒子とみたときの名称
- 光電子: 飛び出る電子
- 光(電磁波の意味で)
  - 振動数 $\nu$: 1秒間に振動する回数
  - 強さ: 振幅の2乗に比例
</div></div>
---

<div class="grid grid-cols-[50%,50%] gap-4"><div>

# 普通に考えると

- 光のエネルギー = 光電子のエネルギー  (エネルギーの保存則)
  - 光のエネルギーは振動数と強さに比例
  - エネルギーが強い → 電子が飛ぶ
<div class="img2"></div>
</div><div>

# 結果
- 電子のポーンは光の強さに依存しない
  - 強さはエネルギーじゃないの!?
- 光が強くても電子がポーンしない
  - 振動数が小さい時
  - なぜ??


## こいつら波じゃねーじゃん!!

</div></div>


<style>
  .img2{
    background-image:url(./img/1.2.1.png);
    background-repeat:no-repeat;
    background-size:300pt 250px;
    width:300pt;
    height:300px
  }
</style>

---

# Einsteinの説明
_

振動数$\nu$の光を**エネルギー$h\nu$を持つ粒子**(光子)とみなす.
 1つの光子が1つの電子と衝突する際にエネルギーを受け渡している.

光の強さは光子の数だから、電子のポーンには影響しない!


<div class="grid grid-cols-[50%,50%] gap-4"><div>

$$
K = E - W = h(\nu - \nu_0)
$$
- $K$: 光電子の運動エネルギー
- $E$: 光のエネルギー($h\nu$でしたね)
- $h$: プランク定数($6.6 \times 10^{-34} Js$)
- $\nu_0$: 限界振動数
  - 初めてポーンするときの振動数(前ページを参照)

<br>

### 光は粒子でした　めでたしめでたし
</div><div>
<div class="img2"></div>


<style>
  .img2{
    background-image:url(./img/koden-energy.png);
    background-repeat:no-repeat;
    background-size:150pt 180px;
    width:150pt;
    height:180px
  }
</style>


</div></div>

---

# 粒子も波でワ❓

<div class="grid grid-cols-[50%,50%] gap-4"><div>

## ブラッグ反射

X線をいろいろな方向から当てると角度$\theta$によって反射したり反射しなかったり.


ブラッグの条件
$$
2d sin\theta = n\lambda
$$
$d$: 原子面間隔, $\lambda$: 波長, nは任意の自然数
<br>

位相が同じだと強めあう(干渉)

- 反射する
- 光が干渉している 
- 位相が同じ光がたくさん


<style>
  .img2{
    background-image:url(./img/bragg.png);
    background-repeat:no-repeat;
    background-size:200pt 200px;
    width:250pt;
    height:250px
  }
</style>

</div><div>

## 電子でも成立

Davisson-Germerの実験ともよばれている.

<br>

<div class="img2"></div>
</div></div>

---

# de Broglie波
粒子の波動性

$$
p = \frac{h}{\lambda}
$$
photonの運動量$p$はコンプトン効果からわかる. $h$はプランク定数, $\lambda$は波長


de Broglie方程式
$$
\lambda = \frac{h}{p}=\frac{h}{m\nu}
$$


