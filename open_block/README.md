### ブロックのUIを開いたことを検知する

## 基本

[barrel_1.json](https://github.com/hikoma0000/detection/blob/main/open_block/barrel_1.json)をadvancementsとして使用することで、樽を開いたことを検知しつつfunctionを実行できる。

> `"reward:hoge"`に実行させたいfunctionを入力すること

## 仕組み

……書けたら書く



## より良い方法

[open.json](https://github.com/hikoma0000/detection/blob/main/open_block/open.json)をpredicateとして、
[barrel_2.json](https://github.com/hikoma0000/detection/blob/main/open_block/barrel_2.json)をadvancementsとして使用するとスッキリする。

> 使用する際にはbarrel_2.jsonの`"reference:open"`を導入するデータパックに合わせて変更すること

<br><br><br><br>

# 更により良い方法

## Ai-Akaishi氏の[`CloseDetector`](https://github.com/Ai-Akaishi/CloseDetector)を使う
