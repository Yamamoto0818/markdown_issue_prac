#  ③mermaidで記述できるダイアグラムのチュートリアル

引用元 (https://www.engineer-route.com/column/8973/)

## Mermaidとは
ダイアグラム作成およびチャート作図用のJavaScriptライブラリです。
フローチャート、シーケンス図、ガントチャート、円グラフなどいろいろな図表を作成できます。
作図にはマークダウン記法が利用でき、作図したものはPNG/JPEGで書き出す事もできます。

zennやGithubやNotionなどエンジニアがよく使うサービスに対応しているのも嬉しい所です。

## VSCodeで使うMermaid
VSCode + Mermaidを利用するとマークダウンで書かれた図表のプレビューや、図表の書き出しができます。
手順書やちょっとした説明の際に図表が使えると分かり易くスッキリとまとめる事ができる為、オススメです。

## VSCode + Mermaidの準備
使用開始までの手順は以下となります
- [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)のインストール
- [Markdown Preview Mermaid Support](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)プラグインのインストール
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)プラグインのインストール
 ※必須ではないですが、扱いやすくなります。

以上

あとは以下の様にマークダウンファイル内に記述してプレビューするだけです

以下のコード貼ってみてください。

```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

以下のようになれば成功です。
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## まとめ
図表ツールやエクセル、パワーポイント等を使用せずにいつも利用しているエディタで図表が作れるととても効率的ですよね。
ぜひお試しください