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

---
# csv-count.sh

## Overview
Count occurences of values in the first column of a CSV file.

## Usage
```bash
./csv-count.sh data.csv

## Behavior
- Extracts the first column
- Counts occurrences
- Sorts by frequency (descending)

## Example

Input (data.csv):
apple
banana
apple

Output:
2 apple
1 banana

---

##　概要
CSVの１列目の値をカウントして、多い順に表示します。

##　使い方
./csv-count.sh data.csv

## 動作
・１列目を抽出
・出現回数をカウント
・多い順にソート

---

# CSV Filter Script

## Overview

Simple Bash script to filter CSV data using grep.

## Usage

```bash
./csv-filter.sh data.csv Berlin

## Example Output

John,25,Berlin
Anna,31,Berlin

## Features
- Filter CSV rows
- Simle Bash + grep
- Fast command line usage

---

# Empty Line Check Script

## Overview

Simple Bash script to detect empty lines in a file using grep.

## Usage

```bash
./empty-line-check.sh sample.csv

##Example Output

5:

## Features
- Detect empty lines
- Show line numbers
- Simple Bash + grep
- Useful for CSV cleanup


