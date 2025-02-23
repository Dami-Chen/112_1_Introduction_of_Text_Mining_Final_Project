## 產業新聞分類與關鍵字檢索

### 主題簡介
在股票市場中，產業新聞會作為消息面反映企
業價值。作為投資者，不免需要了解企業所屬
產業的動態，而查詢新聞又非常費時，因此想
要自動化這個流程，隨時爬取最新的產業新聞
並提取關鍵字、觀察近年話題分布的變化。
完整的理想系統架構如下：
1. 決定有興趣的產業類別。
2. 從數個網站爬取最新產業新聞，並記錄
其發布時間。
3. 將這些新聞依產業別分類。如果該新聞
與使用者有興趣的產業無關，則捨棄新
聞，否則加入該產業的新聞集。
4. 對 每 個 產 業 的 新 聞 集 進 行 Latent
Semantic Analysis，觀察近兩年每季的
話題分布變化與關鍵字。

### 實作方法
產業分類
- 監督式模組 (NB, KNN, SVM linear & RBF kernels)
- 10% training data - for validation
- precision recall metrics & curves

### 結果分析
[口頭報告](https://www.canva.com/design/DAF4MZbz0q8/LRUGRIitryhsOSK9Yu4pvw/edit?utm_content=DAF4MZbz0q8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

更多內容可參考附件 文字探勘初論第4組期末報告.pdf
