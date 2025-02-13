﻿神經網絡編程實戰:Java語言實現 


資料來源:http://www.hzcourse.com/web/refbook/detail/7846/226
https://www.tenlong.com.tw/products/9787111600121
GITHUB:https://github.com/jash-git/Neural_Network_Programming_with_Java_SecondEdition-data.git


目錄大綱
譯者序 
作者和審校者簡介 
前言 
第1章 神經網絡入門 1
1.1 探索神經網絡 1
1.2 人工神經網絡 2
1.2.1 神經網絡是如何組織的 3
1.2.2 基本元素—人工神經元 3
1.2.3 賦予神經元生命—激活函數 4
1.2.4 可變參數—權重 5
1.2.5 額外參數—偏置 6
1.2.6 由部分到整體—層 6
1.2.7 神經網絡體系結構 7
1.2.8 單層網絡 7
1.2.9 多層網絡 8
1.2.10 前饋網絡 8
1.2.11 反饋網絡 8
1.3 從無知到認知—學習過程 9
1.4 開始編程—神經網絡實踐 10
1.5 神經元類 12
1.6 NeuralLayer類 14
1.7 ActivationFunction接口 15
1.8 神經網絡類 15
1.9 運行程序 17
1.10 本章小結 19
第2章
神經網絡學習 20
2.1 神經網絡的學習能力 21
2.2 學習模式 22
2.2.1 監督學習 22
2.2.2 無監督學習 22
2.3 學習過程 23
2.3.1 尋找損失函數最優下降方向 24
2.3.2 在學習過程中更新權重 25
2.3.3 計算損失函數 25
2.3.4 一般誤差和總體誤差 27
2.3.5 神經網絡的迭代學習什麼時候停止比較好 27
2.4 學習算法示例 28
2.4.1 δ規則 29
2.4.2 學習率 30
2.4.3 實現δ規則 30
2.4.4 δ規則學習的核心—train和calcNewWeight方法 31
2.4.5 另一種學習算法—Hebbian學習 34
2.4.6 學習機 35
2.5 在實踐中理解學習過程 37
2.6 測試 41
2.7 本章小結 43
第3章 感知機和監督學習 44
3.1 監督學習—訓練神經網絡 45
3.1.1 分類—尋找合適的類別 45
3.1.2 回歸—將實際輸入映射到輸出 46
3.2 一個基本的神經結構—感知機 48
3.2.1 應用和限制 49
3.2.2 線性可分 49
3.2.3 “異或”問題 50
3.3 多層感知機 52
3.3.1 MLP屬性 52
3.3.2 MLP權重 53
3.3.3 遞歸MLP 54
3.3.4 編碼實現MLP 54
3.4 MLP學習 55
3.4.1 反向傳播算法 56
3.4.2 動量項 58
3.4.3 編碼實現反向傳播 58
3.4.4 Levenberg-Marquardt算法 62
3.4.5 編碼實現基於矩陣代數的Levenberg-Marquardt算法 64
3.4.6 極限學習機 66
3.5 實例1—基於δ規則和反向​​傳播的“異或”問題 69
3.6 實例2—預測入學狀態 72
3.7 本章小結 75
第4章 自組織映射 76
4.1 無監督神經網絡 76
4.2 無監督學習算法 77
4.2.1 競爭學習 78
4.2.2 競爭層 80
4.3 Kohonen自組織映射 82
4.3.1 將神經網絡代碼擴展至Kohonen 83
4.3.2 零維SOM 84
4.3.3 一維SOM 84
4.3.4 二維SOM 85
4.3.5 2D競爭層 87
4.3.6 SOM學習算法 89
4.3.7 鄰近神經元的影響—鄰域函數 90
4.3.8 學習率 91
4.3.9 競爭學習的一個新類 92
4.3.10 SOM可視化 95
4.3.11 繪製訓練數據集和神經元權重的2D圖 97
4.3.12 測試Kohonen學習 99
4.4 本章小結 105
第5章 預報天氣 106
5.1 神經網絡用於回歸問題 106
5.2 加載/選擇數據 108
5.2.1 創建輔助類 108
5.2.2 從CSV文件加載數據集 111
5.2.3 創建時序結構 112
5.2.4 丟棄NaN 113
5.2.5 獲取天氣數據 114
5.2.6 天氣變量 115
5.3 選擇輸入和輸出變量 115
5.4 預處理 117
5.4.1 歸一化 117
5.4.2 應用NeuralDataSet處理歸一化 121
5.4.3 應用學習算法進行歸一化 123
5.4.4 天氣預報的Java實現 123
5.4.5 收集天氣數據 123
5.4.6 延遲變量 126
5.4.7 加載數據並開始運行 126
5.4.8 相關性分析 128
5.4.9 創建神經網絡 131
5.4.10 訓練和測​​試 131
5.4.11 可視化神經網絡的輸出 133
5.5 神經網絡實驗設計 134
5.5.1 設計實驗 134
5.5.2 結果和模擬 135
5.6 本章小結 138
第6章 疾病分類識別 139
6.1 分類問題的基礎 139
6.1.1 分類數據 140
6.1.2 處理分類數據 141
6.2 邏輯回歸 142
6.2.1 多分類與二分類 143
6.2.2 混淆矩陣 144
6.2.3 敏感性與特異性 144
6.2.4 實現混淆矩陣 145
6.3 分類神經網絡 147
6.4 用神經網絡進行疾病識別 147
6.4.1 乳腺癌識別 148
6.4.2 糖尿病識別 151
6.5 本章小結 154
第7章 客戶畫像聚類 155
7.1 聚類任務 156
7.1.1 聚類分析 156
7.1.2 聚類評估和驗證 157
7.1.3 實現 158
7.1.4 外部驗證 159
7.2 應用無監督學習 159
7.3 畫像過程 160
7.3.1 預處理 160
7.3.2 Java實現 161
7.3.3 信用卡—客戶畫像信用分析 161
7.3.4 產品畫像 165
7.3.5 多少個簇合適 166
7.4 本章小結 167
第8章 文本識別 168
8.1 模式識別 168
8.1.1 類已知 169
8.1.2 類未知 170
8.2 神經網絡用於模式識別 171
8.2.1 數據預處理 171
8.2.2 文本識別（光學字符識別） 172
8.2.3 數字識別 172
8.2.4 數字表示 172
8.2.5 Java實現 173
8.2.6 數據生成 173
8.2.7 神經結構 174
8.2.8 實驗 174
8.2.9 結果 176
8.3 本章小結 179
第9章 神經網絡優化與調整 180
9.1 神經網絡實現的常見問題 181
9.2 輸入數據選擇 181
9.2.1 數據相關性 182
9.2.2 數據轉換 183
9.2.3 降維 183
9.2.4 數據過濾 184
9.2.5 交叉驗證 186
9.2.6 神經網絡結構選擇 187
9.3 在線重訓練 189
9.3.1 隨機在線學習 190
9.3.2 實現 190
9.3.3 應用 191
9.4 自適應神經網絡 193
9.4.1 自適應諧振理論 193
9.4.2 實現 194
9.5 本章小結 195
第10章 神經網絡當前趨勢 196
10.1 深度學習 196
10.2 深度架構 198
10.2.1 如何用Java實現深度學習 199
10.2.2 神經模糊 201
10.2.3 神經遺傳 203
10.3 實現混合神經網絡 204
10.4 本章小結 207
參考文獻 208