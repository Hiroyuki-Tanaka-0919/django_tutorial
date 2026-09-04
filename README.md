# Django チュートリアル（Windows編）
- URL：https://docs.djangoproject.com/ja/6.1/intro/

## 開発環境
- Windows 11 Pro (25H2)
- Python 3.12
- Django 6.1
- SQLite3 3.49.1

## ダウンロード
```
git clone https://github.com/Hiroyuki-Tanaka-0919/django_tutorial.git
```
## 移動
```
cd django_tutorial
```
## 仮想環境の設定
```
py -3.12 -m venv venv
```
## 仮想環境の有効化
```
.\venv\Scripts\activate.ps1
```
## Djangoのインストール
```
py -3.12 -m pip install -r requirements.txt
```
## DataBaseの初期化
```
py -3.12 manage.py migrate
```
## Djangoの起動
```
py -3.12 manage.py runserver
```
## サイトの表示
```
http://127.0.0.1:8000
```
## Djangoの停止
```
Ctrl + C
```
## 仮想環境の終了
```
deactivate
```

## 進捗
- 2026/09/03：環境構築と初期設定
- 2026/09/04：はじめての Django アプリ作成、その 1
