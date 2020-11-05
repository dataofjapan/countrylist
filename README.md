# 国リスト

ISO、世界銀行、国連に掲載の国情報を集約し、緯度経度（国境を図形 bounding-box として見た際の中心点、いわゆる centeroid）を付与した。
以下のような利用を想定している。

### 想定利用

- 国表記が定かでないデータセットを、国コードを元に、特定の国際機関の正式な表記へクレンジングしたい。
- 国表記のみ存在するデータセットへ、緯度経度を付与し、地図上でマッピングしたい。

## 収録データの属性一覧

### ISO 及び国連による国コード

- iso:alpha-3
- iso:alpha-2
- iso:3166-2
- un:m49_code

### 国の中心座標（国境を図形 bounding-box として見た際の中心点、いわゆる centeroid）

- centeroid:latitude
- centeroid:longitude

### 世界銀行及び国連による国名・エリア名表記

- wb:country
- un:country_or_area

### 世界銀行 掲載データ

- wb:region
- wb:income_group
- wb:lending_category
- wb:other

### 国連 掲載データ

- un: region
- un:sub-region
- un:intermediate-region
- un:region-code
- un:sub-region-code
- un:intermediate-region-code

## データソース / Data Source

- [WorldBank | Country and Lending Groups](https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups)
- [ISO | "alpha-3" & "alpha-2" codes](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes)
- [United Nations Statistics Division | Standard country or area codes for statistical use (M49)](https://unstats.un.org/unsd/methodology/m49/overview)
- [Google Dataset Publishing Language | countries.csv](https://developers.google.com/public-data/docs/canonical/countries_csv)

## ファイル取得日 / File Acquisition Date

- 2020-11-05

## ライセンス

- [the Creative Commons Attribution 4.0 License.](https://creativecommons.org/licenses/by/4.0/)
