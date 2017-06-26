- 講義開始
https://youtu.be/ZpBuUYDRLMg?t=6m30s

https://youtu.be/ZpBuUYDRLMg?t=


# 準備
- Visual C#の起動 https://youtu.be/ZpBuUYDRLMg?t=7m25s
- 今日の資料 https://youtu.be/ZpBuUYDRLMg?t=9m44s
- ゲームの定義の一つ https://youtu.be/ZpBuUYDRLMg?t=10m21s

# 乱数
- 乱数を使う時の準備 https://youtu.be/ZpBuUYDRLMg?t=14m47s
  - Randomクラスの変数 rand を static で定義
- 0以上intの範囲内の整数の乱数を生成 https://youtu.be/ZpBuUYDRLMg?t=17m18s
  - C言語の乱数と同じスタイル
  - 使いづらいのでC#ではほぼ使わない
- サイコロの例(1～6の乱数) https://youtu.be/ZpBuUYDRLMg?t=21m18s
  - 0～5の乱数を求めておいて、それに1を足して1～6にする
- 0以上、指定の値「未満」の乱数 https://youtu.be/ZpBuUYDRLMg?t=29m
- 指定の値以上、指定の値「未満」の整数の乱数 https://youtu.be/ZpBuUYDRLMg?t=30m11s
  - 整数の乱数は、これを使うとよい
- 0～1未満の実数 https://youtu.be/ZpBuUYDRLMg?t=35m52s

## 演習
NextDoubleを使って、1～6の整数の乱数を得るには？

- 考え方 https://youtu.be/ZpBuUYDRLMg?t=50m26s
- 答え https://youtu.be/ZpBuUYDRLMg?t=53m25s

## 演習
ラベルの速度(vx, vy)とラベルのLeftとTopを乱数にする

- 答え https://youtu.be/ZpBuUYDRLMg?t=1h9m26s

# 配列～沢山のものを動かす(1) 
https://youtu.be/ZpBuUYDRLMg?t=1h14m44s

## 演習
ラベルを2つ追加して、それぞれが画面内を動いて、跳ね返るようにする

- https://youtu.be/ZpBuUYDRLMg?t=1h15m11s
- 解答 https://youtu.be/ZpBuUYDRLMg?t=1h44m13s
  - ラベルの名前を確認
  - vx,vyを増やす
  - `label1`や`vx`,`vy`と出てくる場所を探して、コピー＆ペーストで増やして、書き換える
  - 一度に作業する量が多すぎると混乱するので、1機能ずつやるとよい
  - 移動を増やす  https://youtu.be/ZpBuUYDRLMg?t=1h45m21s
  - 跳ね返りを増やす https://youtu.be/ZpBuUYDRLMg?t=1h45m53s
    - 動きがおかしかったら、どうしてそのように動くかを考えて、原因を予想するとよい
      - 例：全部同じ動きをする → 速度の変数を書き換え忘れている
  - マウスで消す https://youtu.be/ZpBuUYDRLMg?t=1h49m30s
  - 速度と座標の乱数を増やす https://youtu.be/ZpBuUYDRLMg?t=1h50m14s

## 配列の定義
- 説明 https://youtu.be/ZpBuUYDRLMg?t=1h52m24s
- 実装 https://youtu.be/ZpBuUYDRLMg?t=1h54m20s

## 配列の利用
- コード内のvxとvyを、配列に書き換える https://youtu.be/ZpBuUYDRLMg?t=1h59m48s
- 添え字を変数にする https://youtu.be/ZpBuUYDRLMg?t=2h8m18s

# 繰り返し(for文)
- https://youtu.be/ZpBuUYDRLMg?t=2h11m3s
- for文の構文と、処理される順番 https://youtu.be/ZpBuUYDRLMg?t=2h16m50s
- 繰り返しの例を実行するボタンを作る https://youtu.be/ZpBuUYDRLMg?t=2h21m19s
- vxとvyに乱数を求めている箇所をfor文に書き換える https://youtu.be/ZpBuUYDRLMg?t=2h34m17s

# ラベルなどのコントロールをプログラムで生成する
- https://youtu.be/ZpBuUYDRLMg?t=2h40m13s
- Labelの配列を作る　https://youtu.be/ZpBuUYDRLMg?t=2h41m9s
- ラベルを1つプログラムで作る https://youtu.be/ZpBuUYDRLMg?t=2h43m9s
- 繰り返しループに生成コードを入れて、3つのラベルを作って配列に記録する https://youtu.be/ZpBuUYDRLMg?t=2h49m26s
- 配列のラベルを移動させる https://youtu.be/ZpBuUYDRLMg?t=2h59m45s
- 定数(const)を使って、ラベルの数を定義 https://youtu.be/ZpBuUYDRLMg?t=3h56s
- 配列のラベルを跳ね返らせる https://youtu.be/ZpBuUYDRLMg?t=3h3m52s
- 配列のラベルをマウスで消す https://youtu.be/ZpBuUYDRLMg?t=3h5m3s
- 不要になったラベルを消す https://youtu.be/ZpBuUYDRLMg?t=3h6m29s

以上。成果物は 

 


