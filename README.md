# stock-value

EDINETから有価証券報告書をXBRLで取得し、解析・株価判定をするアプリ。

* EDINET: https://disclosure.edinet-fsa.go.jp
* XBRL: https://www.xbrl.or.jp/modules/pico7/index.php
* [Qiita:XBRL Japan](https://qiita.com/XBRLJapan)
* [JIS X7206](https://www.jisc.go.jp)
* [金融庁](https://www.fsa.go.jp/search/20211109.html) [XBRL Instance Guide](https://www.fsa.go.jp/search/20140919/2b_1.pdf)
* [Arelle](https://srbrnote.work/archives/5588)
* [YahooFinanceaPI2](https://myfrankblog.com/stock_price_with_yahoo_finance_api2/)

## install

```
unzip Arelle-master.zip
mv Arelle-master Arelle 
pip install lxml
pip install isodate
pip install yahoo_finance_api2
pip install pandas_datareader
```

## ToDo
* [x] データキャッシュ
* [ ] 重複企業の最適化
* [ ] 売上高、総資本の追加
* [ ] 長い関数の見直し
* [ ] DB蓄積
* [x] 継続動作時の最適化（キャッシュ活かす）
* [ ] 必要なファイルだけ抽出
* [ ] 最新の株価を取得する
* [ ] 株価の日時を出力する
