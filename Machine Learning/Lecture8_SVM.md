# 支援向量機 SVM
 SVM是一種監督式學習的模型，其用於分類與迴歸分析中分析資料的演算法。
給定一組訓練實例，每個訓練實例被標記為屬於兩個類別中的一個或另一個，SVM訓練演算法建立一個將新的實例分配給兩個類別之一的模型，使其成為非概率二元線性分類器。
SVM模型是將實例表示為空間中的點，這樣對映就使得單獨類別的實例被儘可能寬的明顯的間隔分開。然後，將新的實例對映到同一空間，並基於它們落在間隔的哪一側來預測所屬類別。
除了進行線性分類之外，SVM還可以使用所謂的核技巧有效地進行非線性分類，將其輸入隱式對映到高維特徵空間中。
當資料未被標記時，不能進行監督式學習，需要用非監督式學習，它會嘗試找出資料到簇的自然聚類，並將新資料對映到這些已形成的簇。
將支持向量機改進的聚類演算法被稱為支持向量聚類[2]，當資料未被標記或者僅一些資料被標記時，支持向量聚類經常在工業應用中用作分類步驟的預處理。