# torch-model-vis

## Aim
Visualization of [input -> module -> output]
Visualization of [grad] (If there is ground-truth) 

## Want to do
[ ] ピックアップするモジュールの選択方法の決定
*  weight の分散でソート -> 上位3つ 下位3つを表示

## Design
vis = ModelVis()
model = Model()

vis(model)
