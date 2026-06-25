# 左右反転画像　生成プログラム filp.py
# 1.概要
引数で指定した画像の左右反転画像を作成する python 3 で動作するプログラムです。
# 2.ソースコード
```python
# このプログラムは python3用です。
# あらかじめ pip install pillow で pillow をインストールしておきます。
from PIL import Image
import sys

input_image = sys.argv[1]
output_image = sys.argv[2]
```
