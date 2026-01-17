# LightGBM + Python + marimo + Neovim 環境構築手順書

1. Python仮想環境（venv）の構築
```shell
python -m venv .venv
.\.venv\Scripts\Activate.ps1 #Powershellのコードのため、環境に応じて変更
```

2. ライブラリのインストール
```shell
pip install -U pip
pip install lightgbm pandas scikit-learn marimo matplotlib
```

3. marimoの起動
```shell
marimo edit
```

4. 環境の破棄
```shell
deactivate
cd ..
remove-item -recurse -force horserace-lm #Powershellのコードのため、環境に応じて変更
```
