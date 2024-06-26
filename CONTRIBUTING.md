## 参加方法

## 開発準備

まず始めに以下のコマンドを実行してください。

```text
npm install
```

### Issueを探す/立てる

1. [Issues](https://github.com/stzn/swift-migration-guide-jp/issues)の中から解決したい Issue を選択(あるいは作成)してください
2. 選択した Issue の Assignees に自身を設定してください 

### PRを開く

1. まずこのリポジトリを fork してください
2. 作業用のブランチを作成し、変更をコミット&プッシュしてください
3. このリポジトリの `main` ブランチに対してPRを開いてください

### ビルド方法

リポジトリのルートディレクトリで `docc preview Guide.docc` を実行します。

DocCを実行した後、`docc` が出力するリンクを開いて、ブラウザでローカルプレビューを表示します。

> 注意:
>
> Swift.org から toolchain をダウンロードして DocC をインストールした場合、
> `docc` は toolchain のインストールパスを基準とした `usr/bin/` にあります。
> シェルの `PATH` 環境変数にそのディレクトリが含まれていることを確認してください。
> 
> Xcode をダウンロードして DocC をインストールした場合は、
> 代わりに `xcrun docc` を使用してください。

### PRのレビューについて

PRを開くと、レビュアーが自動でアサインされます。コードレビュー中に変更を求められた場合、必要な修正を行い、準備ができたらレビュアーに再度レビューを依頼してください。
