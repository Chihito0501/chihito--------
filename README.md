# Chihito portfolio

授業で作ったような、HTMLとCSSだけのシンプルな構成にしています。アニメーションや難しいJavaScriptは使っていません。

## 開き方
1. ZIPを右クリックして「すべて展開」。
2. VS Codeの「ファイル」→「フォルダーを開く」で、このフォルダを選ぶ。
3. `index.html` をエクスプローラーからダブルクリックするとブラウザで表示できます。

## 提出する前に必ず直すところ
- `index.html` 内の `【ここに...】` をすべて自分の内容にする。
- 自己紹介の「※ここに自分の趣味...」を消して、具体的な内容にする。
- スキル欄に、実際には使ったことのない言語・ツールがあれば消す。
- 課題04のスクリーンショット4枚以上と、高専祭の実際の写真4枚以上に入れ替える。
- 課題04の作品リンク（GitHubやGoogle ColabのURL）を追加する。
- 高専祭の自分の担当と活動内容を書く。
- `https://github.com/Chihito0501` が自分のGitHubか確認する。

### 写真の入れ方
例えば課題04の1枚目を `python-1.png` として `assets` フォルダに入れたら、`index.html` で

`src="assets/python-1.svg"` を `src="assets/python-1.png"` に変更します。

ほかの7枚も同じ手順です。**今のSVG画像は仮画像なので、そのまま提出しないでください。**

### リンクの入れ方
例えば `【Google ColabやGitHubのURLをここに追加する】` を次のHTMLに変更します。

```html
<a href="https://github.com/自分のアカウント/作品の名前" target="_blank" rel="noopener noreferrer">作品を見る</a>
```

### デザイン変更
`style.css` の `#3157a2` はメインの青色です。好きな色に変更できます。

## GitHub Pagesで公開する
1. GitHubで Public の新しいリポジトリを作成。
2. `index.html`、`style.css`、`assets` フォルダをZIPではなく中身のままアップロード。
3. Settings → Pages で `Deploy from a branch`、`main`、`/(root)` を選択して Save。
4. 公開URLを開いて表示を確認し、先生に指定された方法で提出。

**AIを利用して作った下書き**なので、学校のAI使用ルールを確認し、自分で文章・作品・画像を完成させてください。
