# 決策樹

## 說明
決策樹是由多個決策組成的樹狀結構模型，樹的每個分支都是一個決策點，分支會根據其中一個特徵的值切分資料，被切分的資料再進到下一分支，不斷切分資料直到樹的最大深度為止。假如我們可以用天氣預報數據訓練決策樹，預測未來某一天是否下雨，此時其中一個分支可能就是:若溫度大於臨界值，則判斷會下雨，將資料切成兩份，然後進入下一個分支，再根據風量大小進行第二次判斷，最後得到是否下雨的預測分類。


## 亂度指標
為了找出最好的決策組合，訓練決策樹做分類時需要藉由亂度指標評估決策點的好壞\
常用的分類樹亂度指標有:

- Information Gain
- Gain ratio
- Gini index(Gini Impurity)

回歸樹的指標則有:
- MSE
- MAE

## 優缺點
- 可解釋性強
- 訓練快
- 容易過擬合

