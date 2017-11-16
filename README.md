# HTML Validator

Nu Html Checker を利用して HTML ページのチェックを行うユーザースクリプト。

「メッセージなし」「Info または Warning のみ」「Error あり」によって3パターンのアイコンを表示し、さらに Info 以上のメッセージがあるときはアイコン押下でメッセージを表示します。

## 動作確認

Firefox 57.0 + [Violentmonkey 2.8.18](https://addons.mozilla.org/ja/firefox/addon/violentmonkey/) でチェックしていますが、 Chrome など他ブラウザでもたぶん動くと思います。

## サンプル

アイコン（左下にチラッと見える黄色いやつ）を押下してメッセージを表示した様子。

![画面キャプチャー（赤背景のブロック内に行数やメッセージが一覧表で表示されている）](https://user-images.githubusercontent.com/4138486/32880474-28171f10-caf1-11e7-9198-c1718904cba6.png)

## おことわり

* 動作原理は hokaccha 氏の [gm-html5validator](https://github.com/hokaccha/gm-html5validator) を参考にしましたが、ソースコードはゼロから書き直しています。
* 各種アイコンは Clker-Free-Vector-Images 氏が [Pixabay に公開されているデータ](https://pixabay.com/ja/%E7%9B%AE%E7%9B%9B%E3%82%8A-%E3%82%A2%E3%82%B9%E3%82%BF%E3%83%AA%E3%82%B9%E3%82%AF-%E3%82%AF%E3%83%AD%E3%82%B9-%E8%B5%A4-%E7%B7%91-%E9%BB%84%E8%89%B2-%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF-%E8%AD%A6%E5%91%8A-40678/) を利用しています。