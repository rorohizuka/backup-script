# backup.sh

## Overview
This script backs up `.log` files into a date-based folder.

## Usage
Run the script in the directory containing `.log` files.
```bash
./backup.sh

## Behavior
- Creates a folder: backup/YYY-MM-DD/
- Copies all .log files into that folder
- Displays "no log files" if none are found
- Shows start and end time

---

##　概要
`.log` ファイルを日付ごとのフォルダにバックアップするスクリプトです。

## 使い方
`.log` ファイルがあるディレクトリで実行します。
```bash
./backup.sh

## 動作
・backup/YYYY-MM-DD/フォルダを作成
・すべての.log　ファイルをそのフォルダにコピー
・.log ファイルがない場合はno log files と表示
・開始時刻と終了時刻を表示



