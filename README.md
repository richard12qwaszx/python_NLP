# 中文句子情緒分類

## 訓練資料來源
- [Datasets:Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset](https://huggingface.co/datasets/Johnson8187/Chinese_Multi-Emotion_Dialogue_Dataset)

## 基礎模型
- [google-bert/bert-base-chinese](https://huggingface.co/google-bert/bert-base-chinese)

## 安裝套件
absl-py                   2.1.0                
accelerate                1.4.0                    
aiohappyeyeballs          2.4.6                    
aiohttp                   3.11.12                  
aiosignal                 1.3.2                    
asttokens                 3.0.0                    
async-timeout             5.0.1                   
attrs                     25.1.0                 
bzip2                     1.0.8                          
charset-normalizer        3.4.1                   
colorama                  0.4.6                    
comm                      0.2.2                    
contourpy                 1.3.1                    
cycler                    0.12.1                   
datasets                  3.3.2                    
debugpy                   1.8.12                   
decorator                 5.1.1                    
dill                      0.3.8                    
evaluate                  0.4.3                    
exceptiongroup            1.2.2                   
executing                 2.2.0                    
filelock                  3.13.1                   
fonttools                 4.56.0                   
frozenlist                1.5.0                    
h5py                      3.13.0                   
huggingface-hub           0.29.1                   
idna                      3.10                     
ipykernel                 6.29.5                   
ipython                   8.32.0                   
jedi                      0.19.2                   
jinja2                    3.1.4                    
joblib                    1.4.2                    
jupyter-client            8.6.3                    
jupyter-core              5.7.2                    
keras                     3.8.0                    
kiwisolver                1.4.8                    
libffi                    3.4.6                
liblzma                   5.6.4                
liblzma-devel             5.6.4                
libsqlite                 3.48.0               
libzlib                   1.3.1                
markdown-it-py            3.0.0                
markupsafe                2.1.5                
matplotlib                3.10.0               
matplotlib-inline         0.1.7                
mdurl                     0.1.2                
ml-dtypes                 0.5.1                
mpmath                    1.3.0                
multidict                 6.1.0                
multiprocess              0.70.16              
namex                     0.0.8                
nest-asyncio              1.6.0                
networkx                  3.3                  
numpy                     2.1.2                
openssl                   3.4.1                
optree                    0.14.0               
packaging                 24.2                 
pandas                    2.2.3                
parso                     0.8.4                
pillow                    11.0.0               
pip                       25.0.1             
platformdirs              4.3.6              
prompt-toolkit            3.0.50             
propcache                 0.3.0              
psutil                    7.0.0              
pure-eval                 0.2.3              
pyarrow                   19.0.1             
pygments                  2.19.1             
pyparsing                 3.2.1              
python                    3.10.0          
python-dateutil           2.9.0.post0     
pytz                      2025.1          
pywin32                   308             
pyyaml                    6.0.2           
pyzmq                     26.2.1          
regex                     2024.11.6       
requests                  2.32.3          
rich                      13.9.4          
safetensors               0.5.2           
scikit-learn              1.6.1           
scipy                     1.15.1          
seaborn                   0.13.2          
setuptools                75.8.0          
six                       1.17.0          
sqlite                    3.48.0          
stack-data                0.6.3           
sympy                     1.13.1          
threadpoolctl             3.5.0           
tk                        8.6.13          
tokenizers                0.21.0          
torch                     2.6.0+cu118     
torchaudio                2.6.0+cu118     
torchvision               0.21.0+cu118    
tornado                   6.4.2           
tqdm                      4.67.1          
traitlets                 5.14.3          
transformers              4.49.0          
typing-extensions         4.12.2          
tzdata                    2025.1          
ucrt                      10.0.22621.0    
urllib3                   2.3.0           
vc                        14.3            
vc14_runtime              14.42.34433     
vs2015_runtime            14.42.34433     
wcwidth                   0.2.13          
wheel                     0.45.1          
xxhash                    3.5.0           
xz                        5.6.4           
xz-tools                  5.6.4           
yarl                      1.18.3          

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
[NLP](https://youtu.be/D3J28MfLVjw)
...

## 其它你想要補充標題和內容
...
...
