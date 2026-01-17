# LightGBM + Python + marimo + Neovim 環境構築手順書

1. Python仮想環境（venv）の構築
python -m venv .venv
.\.venv\Scripts\Activate.ps1

2. ライブラリのインストール
pip install -U pip
pip install lightgbm pandas scikit-learn marimo matplotlib

3. marimoの起動
marimo edit

4. 環境の破棄
deactivate
cd ..
remove-item -recurse -force horserace-lm
