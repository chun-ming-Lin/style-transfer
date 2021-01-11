# style-transfer practice

References: [Author: fchollet](https://keras.io/examples/generative/neural_style_transfer/#lets-take-a-look-at-our-base-content-image-and-our-style-reference-image)

<p align = 'center'>
<img src = '101.jpg', height = '246px'>
<img src = 'udnie.jpg', height = '246px'>
<img src = '101_at_iteration_200.png'>
</p>
<p align = 'center'>
with 200 iteration

* style: 利用斜方差(gram-matrix)保留特徵
* content: 利用均方差(MSE)保留輪廓

* 較早期風格轉換方法，比較慢
