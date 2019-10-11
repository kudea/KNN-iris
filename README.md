# KNN-iris
## Without importing sklearn
## 程式說明：
1. 程式執行後結果顯示於標準輸出中(error以反白顯示)，並附上一個.txt檔

2. 將k=1~20的執行過程印出，以”Wrong-----“來標示error
### KNN演算法
為縮減空間複雜度，在對每一個 training data point 計算完距離後，確認是否比原本 k 個最近的某一點更近，以便更新列表

a. 所需空間即為 k

b. 空間複雜度為 O(k)

c. 當列表一有更新便須重新對整個列表做排序，時間複雜度最糟為 O(n * k * logk)。
