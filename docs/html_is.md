## HTMLを書いてみる
---
### ブラウザで表示してみる

とにかくなにかブラウザで表示してみよう。エディタで次のHTMLコードをコピペして、
sayaka.htmlと名前を付けて保存しましょう。

sayaka.html
  ```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>美樹さやか</title>
</head>
<body>
  <h1>美樹さやか</h1>
</body>
</html>
  ```

[ブラウザでの表示](../sample/sayaka.html) のようになれば成功です！

### HTMLの要素
以下はHTMLの基本的な要素です。

- `<!DOCTYPE html>`・・・最初に書く決まりみたいなもの
- `<html>`・・・HTMLのコード全体が入る。必ず必要。
- `<head>`・・・meta要素やtitle要素、検索のキーワードなど
- `<meta>`・・・ページで使う文字コードなど。meta charset="utf-8"としておけば特に問題ない。
- `<title>`・・・ページのタイトルでブラウザのタブに表示される
- `<body>`・・・表示したいコンテンツ全体が入る。
- `<h1>`・・・文書の各段落のタイトルを入れる。大きさでh1～h6まである。

これらの要素はタグで囲まれた、始まり要素＜〇〇〇＞と終わり要素＜／〇〇〇＞でセットになっています。
ただしmeta要素のように始まりだけの要素もあります。
ほかにも色々な要素がありますが、とりあえずここまでにします。
ちなみに`<p>〇〇〇</p>`は段落を入れる要素です。続く・・・

---
[目次に戻る](../index.md)
