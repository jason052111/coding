我這次使用的是一般CNN的model來訓練，
一開始我先將各檔案的圖片先resize為100*100，
並且在對各檔做預處理，將所有類型的圖片先分類，
之後建立model並且將train和valid檔內的data放入model訓練，
訓練完後將權重檔匯出，並且進行預測和匯出為excel檔。
Valid set 的Accuracy為31%，
此模型訓練完後發現他在越後面的Epoch會導致valid loss變得越來越嚴重，
並且準確度也不是很高。
