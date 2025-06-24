# Dune Sim ETL Template

## 概要
Dune Sim APIからデータを取得し、Snowflakeに保存、dbtで整形するテンプレートです。

## 構成
- Pythonによるデータ取得＆ロード
- Snowflakeへの保存
- dbtによる変換処理

## 使用方法

### 1. Pythonセットアップ
```bash
pip install -r requirements.txt
python dune_etl/dune_loader.py
