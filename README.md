# 中文句子情緒分類

## 訓練資料來源
- [Datasets:Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset](https://huggingface.co/datasets/Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset)

## 基礎模型
- [google-bert/bert-base-chinese](https://huggingface.co/google-bert/bert-base-chinese)

## 安裝套件
- torch (版本號)
- torchvision (版本號)
- torchaudio (版本號)
- transformers (版本號)
- datasets (版本號)
- evaluate (版本號)
- accelerate (版本號)
- scikit-learn (版本號)
(版本號可用 pip list，或是 conda list 來檢視)
...

## 說明
模型用途：
用於對中文對話文本進行情緒分類
能識別 8 種不同的情緒語調
支援的情緒類別：
平淡語氣 (neutral)
關切語調 (caring)
開心語調 (happy)
憤怒語調 (angry)
悲傷語調 (sad)
疑問語調 (questioning)
驚奇語調 (surprised)
厭惡語調 (disgusted)
模型架構：
基礎模型：google-bert/bert-base-chinese
最大序列長度：512 tokens
輸出層：8 分類
訓練細節：
使用 80% 資料作為訓練集，20% 作為測試集
訓練 3 個 epochs
使用 weighted F1-score 作為評估指標
採用動態學習率和權重衰減以優化訓練效果

## 成果
![](執行過程的擷圖或說明圖片)
...
[影片名稱或其它標題](你的影片連結)
...

## 其它你想要補充標題和內容
...
...
