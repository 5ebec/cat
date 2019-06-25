# Capture Area OCR
選択範囲を翻訳してくれるやつ
(GNOME環境のみ)

## 必要なもの
 - Python 3.x
 - pip
 - gnome-screenshot
 - Tesseract

[Tesseractのインストール方法](https://github.com/tesseract-ocr/tesseract/wiki)  
Ubuntuの場合は以下
```shell
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
```

## 準備
```shell
$ pip install requirements.txt
```

## 使い方
```shell
$ python capture-area-ocr.py
```
マウスカーソルで選択した範囲の英文と，その日本語訳が出力される
