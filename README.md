# 左右反転画像　生成プログラム filp.py
## 1.概要
引数で指定した画像の左右反転画像を作成する python 3 で動作するプログラムです。
## 2.ソースコード
```python
# このプログラムは python3用です。
# あらかじめ pip install pillow で pillow をインストールしておきます。
from PIL import Image
import sys

# コマンドライン引数から入力画像と出力画像のファイル名を取得
input_image = sys.argv[1]
output_image = sys.argv[2]
```
## 3.使い方
### 3.1. 実行例
- コマンドラインフォーマット
```python
python3 filp.py <input_image_path> <output_image_path>
```
- 利用例
```python
python3 filp.py input.jpg output.jpg
```
### 3.2. 出力結果
- 以下のように入力画像の左右反転画像が出力されます。
- 
