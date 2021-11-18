# 1st-DL-CVMarathon-
出處：CUPOY機器學習百日馬拉松

## Day12 補缺失值與標準化
![image](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294161/1594005946906)


## Day13 常用Dataframe操作
![image](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294163/1594006601881)

![image](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294163/1594006650641)

## Day14 相關係數
.00-.19: 非常弱相關
.20-.39: 弱相關
.40-.59: 中度相關
.60-.79: 強相關
.80-1.0: 非常強相關

![image](https://ai100-fileentity.cupoy.com/ml100/dailytask/1586225294165/1594007553801)

## Day 28 特徵組合-數值與數值組合
特徵工程的核心概念 : 領域知識
-   機器學習的關鍵在特徵工程
-   特徵工程的關鍵在領域知識
-   最有效提升模型預測力

## Day 29 特徵組合-類別與數值組合

![image](https://user-images.githubusercontent.com/63281304/112740704-d1656a80-8fb1-11eb-9bf8-302ca44ab397.png)

## Day 30 特徵選擇
1.  特徵需要適當的增加與減少，以提升精確度並減少計算時間
  -   增加特徵 : 特徵組合 (Day 28) ，群聚編碼 (Day 29) 
  -   減少特徵 : 特徵選擇 (Day 30)

2.  特徵選擇有三大類方法 
-  過濾法 (Filter) : 選定統計數值與設定門檻，刪除低於門檻的特徵
-  包裝法 (Wrapper) : 根據目標函數，逐步加入特徵或刪除特徵
-  嵌入法 (Embedded) : 使用機器學習模型，根據擬合後的係數，刪除係數低於門檻的特徵


## Day 33 機器如何學習
1.  定義好模型 (可以是線性回歸、決策樹、神經網路等等)
    -  一個機器學習模型中會有許多參數 (parameters)，例如線性回歸中的 w (weights) 跟 b (bias) 就是線性回歸模型的參數
    -  當我們輸入一個 x 進到模型中，不同參數的模型就會產生不同的 ŷ，希望模型產生的 ŷ 跟真實答案的 y 越接近越好
2.  評估模型的好壞
    -  定義一個目標函數 (Objective function) 也可稱作損失函數 (Loss function)，來衡量模型的好壞
    -  線性回歸模型我們可以使用均方差 (mean square error) 來衡量
3.  找出最好的模型參數
    -  模型的參數組合可能有無限多組
    -  許多像是梯度下降 (Gradient Descent)、增量訓練 (Additive Training) 等方式，這些演算法可以幫我們找到可能的最佳模型參數


