# Extensions4Code
Visual Studio Code で、便利な「標準機能や設定」と「機能拡張」についてまとめる。  
  
## 1. 便利な標準機能や設定
1. 「日本語化する」：Code のインストール直後はUIも英語。なにはなくとも「Japanese Language Pack for Visual Studio Code」機能拡張をインストールして日本語化する。  
2. 「スペース文字を表示する」：Render Whitespace を「all」にする。Markdown の改行である「スペース2個」の有無を見分けるため。  
3. 「対応する括弧の色分け」：標準機能になったため、機能拡張を入れる必要はなくなった。  
4. 「対応する括弧にジャンプする」：括弧の内側にフォーカスを当てて「Ctrl」+「Shift」+「￥」で、対応する括弧にフォーカスがジャンプする。
5. 「ドキュメントのフォーマット」：エディタの右下のステータスバーで「言語モード」を選択し、エディタ上で右クリックして「ドキュメントのフォーマット」を実行すると、インデントなど見易く整形してくれる。  
  
## 2. 「Markdown」機能拡張
1. 「Markdown Preview Github Styling」：Markdown 記法で書いた文書をGithub のスタイルでプレビューできる。
2. 「Auto-Open Markdown Preview」：拡張子「.md」なファイルを開くと、プレビューウィンドウも自動で開く。
3. 「Markdown All in One」：目次、セクション番号、オートコンプリート、キーボードショートカットによる入力補助など。改行したときの自動採番、修正したときの番号振り直しなど。  
コマンドパレットで「Add/Update section numbers」「Create Table of Contents」  
「#」を無視して「##」から採番するには「settings.json」に「"markdown.extension.toc.levels": "2..6"」を追記。
4. 「Markdown Table」：Excel の範囲やCSVを貼り付けて、選択してコマンドでTable にできる。Tab キーでセル移動したり、行や列を挿入したりもできる。
5. 次点：「Excel to Markdown table」：表計算で範囲をコピーした状態で、コマンドパレットから呼び出すと、「table」記法にして貼り付けてくれる。
  
## 3. 「CSV」機能拡張
1. 「Rainbow CSV」：CSVファイルを開いた際に、列ごとに色分けしてくれる。  
2. 「Excel Viewer」：csvファイルを開く際に、コマンドパレットから呼び出すと、表計算ソフト風なUIになる。  
  
## 4. 「JSON」機能拡張
1. 「JSON」：jsonファイルを開くと、拡張機能ウィンドウに、折りたためるツリー表示を出せる。要素のなかに子要素が何個入っているか表示されたり、クリックしたらエディタ上でそこにジャンプしたりできる。巨大なjsonファイルを把握しやすくなる。  
  
## 5. その他の機能拡張
1. 「indent-rainbow」：インデントの階層を段階的に色分けして、階層の深さを読み取り易くしてくれる。  
2. 「Blockman - Highlight Nested Code Blocks」：ネストされたコードで、カーソル位置を内包する括弧をハイライトして、範囲を読み取り易くしてくれる。  
3. 「Geo Data Viewer」：KML（Google マップ）を開くと、地図上に表示してくれる。  
  