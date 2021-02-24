# 平面の運動量の教材



## 1.チョン押し
  * 使いどころ
    * y方向のみ力積を受けると、y方向のみ速度が変化する。
    * x方向の速度は一定


![ストロボ](hovFig\z00013.jpg)  
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/tfy5O6SmMCY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[ストロボ映像はこちらから](https://phys-ken.github.io/2020buturikenkyu_slides/hovFig/animation_z.html)

---

## 2.2次元の衝突
* 使いどころ
  * 衝突の観察
  * x方向の運動量は互いに変化しない
  * y方向は、運動量が保存している。


![ストロボ](stFig/fig/z00005.jpg)

[動画(元動画)](https://www.youtube.com/watch?v=IpGUibvlSUE&feature=youtu.be)  
[軌跡つき動画](https://www.youtube.com/watch?v=UD6FcBrEHSc&feature=youtu.be)  
[ストロボ映像はこちらから](https://phys-ken.github.io/2020buturikenkyu_slides/stFig/2D_Mom.html)



### 運動のグラフ(x方向)
![ストロボ](stFig/fig/z00005.jpg)
![vx](stFig/vxt.png)


### 運動のグラフ(y方向)
![ストロボ](stFig/fig/z00005.jpg)
![vy](stFig/vyt.png)

## 3.概要
* なぜ作ったか
  * 平面の運動量のちょうどよい教材が見つけられなかった
    * 知っている人は教えてください!
* 過去の例会で益田さんが紹介していた、kinoveaを使ってみたかった

* 作成方法
  * 動画は、すべて今井さんが撮影したもの
  * 動画を、Youtubeにアップロードしてから、ダウンロード
    * スローカメラの映像は、fpsの認識がうまくいかず、分析に失敗することがあった。
  * kinoveaで、座標軸を描画する
  * kinoveaで軌跡を表示する。
    * 画像認識して、指定した物体を動画内で勝手に物体を追跡してくれる
    * 動画を出力すると、位置、速度、加速度の値を読み取って、csvで出力してくれる。
    
  * 岩手県教育センターの、多重露光3で、ストロボ映像化する。
    * 多重露光3は、スローカメラは本当に使えない。何らかの方法で、動画のメタデータを再設定する必要あり