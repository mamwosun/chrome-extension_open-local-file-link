# 機能
IEと違いChromeだとローカルファイルへのリンク（file://～）があっても開けないので、拡張で開けるようにする

# Chromeストア
https://chrome.google.com/webstore/detail/nikfmfgobenbhmocjaaboihbeocackld

# Todo
- [x] ローカルファイルのリンクをクリックしたらChromeでも開く
- [x] 開くことができるページを設定できるようにする（すべてのページで開けるとセキュリティ的にまずいので制限する）
- [ ] \<pre>や\<code>内のローカルファイルのパスをリンク化
- [ ] pptやxlsなどは直接ファイルを開くようにする（Native Messaging + レジストリ変更が必要）
