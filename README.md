# awq

Add Weblio result to Quizlet

weblio英和辞典で検索結果の単語ページを開くたびに見出し語と語意を保存し、Editページで整形して単語帳サービスquizletにインポートできる形で出力する。

## 使い方
開発者モードで.crxをインストールしてhttp://ejje.weblio.jp/content/[適当な英単語] にアクセスすると見出し語と語意をchrome内のストレージに保存します。  
データの整形は、アドレスバー横のアイコンをクリックするとEditボタンから別タブで開くoption.htmlに飛ぶので、使いたい語意や改行、コンマなどをクリックでトグルしてください。  
option.html最下段のExportボタンでQuizletインポート用データをクリップボードにコピーします。改行区切り文字はセミコロンに設定してください。  
アイコン上の数字はストレージに保持している単語数です。  
何十個も一度に保持したりすると落ちます。よくわからない。保存の仕方がダサいので
