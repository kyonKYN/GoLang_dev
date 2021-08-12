# Go言語 開発環境構築

構築した時の手順は書きかけ

クローン後の手順は大丈夫(なはず)


## 開発環境

|環境|ソフト|
|---|---|
|仮想環境|Docker|
|エディター|VSCode|

### VSCode拡張機能
|拡張機能|用途|
|---|---|
|Go|言語補完用|
|Remoto-Containers|Dockerの環境読み込む用|


## 参考
[Dockerの構築](https://qiita.com/uji_/items/8c9eda89526abe0ba900)

[デバッグ環境の構築](https://future-architect.github.io/articles/20201117/)


## 手順

### Dockerのインストール

### Dockerコンテナの設定を書く

---

## クローンした場合

### コンテナの立ち上げ
VSCodeのRemote-ContainersのOpen Folder in ContainersでGoLangフォルダを開く

### Go言語拡張機能のインストール
1. VSCodeのGoの拡張機能をインストール
2. Goの開発環境をインストール

go mod init

### 実行テスト

1. ターミナルで`go run main.go`を実行
    - `Hello,World`と表示されれば次へ

2. デバッガーで実行
    - デバッグが行われれば成功

3. 環境構築完了
    - お疲れ様

