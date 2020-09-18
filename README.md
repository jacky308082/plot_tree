## 使用sklearn, lightgbm和xgboost來畫樹
### 能夠在不同套件下使用Python來畫出樹，當需要報告或知道其決策條件時，可以使用該些方法來成功得到圖表

## 如何開始

### 在本機端上開啟cmd
```sh
pip install graphviz
```

以下的code可以讓你使用anaconda來run graphviz
```sh
conda install graphviz 
```

再來檢測是否安裝成功
```sh
dot -v
```

### 安裝完成後
在每一個Library下，都必須用以下的方式加入環境變數(for Windows)
```sh
import os
os.environ["PATH"] += os.pathsep + 'C:/ProgramData/Anaconda3/Library/bin/graphviz'
```
如果有error，可以去檢查graphviz是否存在在上面code的資料夾

### 畫樹
接下來就可以畫樹，各Library的畫圖方法可以參考我提供的相關Example ipynb
