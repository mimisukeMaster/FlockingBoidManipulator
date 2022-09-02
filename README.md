# Floking Boid Manipurator
### Flocking Boid アルゴリズムにより動く魚群をイベントによって全体の動きを操作可能にしたコードです。

|イベント|魚群の動き|
|:---:|:---:|
|画面をクリックした時|中心の座標に魚たちを集める|
|障害物を検知した時|アルゴリズムを意識しながら逃げます|
***

- 画面クリック時<br>
(0, 3, 0)の座標へ集まります。

- 障害物を検知した時<br>
それを避ける方向のベクトルを計算し逃げます。


https://user-images.githubusercontent.com/81568941/188129234-dec00ad4-2a1c-4e2d-925e-194cc9956330.mp4

## Special Thanks
このプロジェクトはhekomiさんの[UnityECSBoidsSimulation](https://github.com/hecomi/UnityECSBoidsSimulation)をCloneし改変したものです。hekomiさんには申し訳ないですが、ForkしていないのでFork表示がされていません。ありがとうございます。
