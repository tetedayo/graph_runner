# GRAPH RUNNER 2.0

座標平面に関数を描き、その曲線に沿ってキャラクターがゴールを目指すブラウザゲームです。

## 主な機能

- スタートは原点 `(0, 0)`、ゴールは `(8, 0)`
- 関数を入力するとグラフがリアルタイムで変化
- 最大4本の式を色分けして表示し、走行する式を選択
- 障害物への衝突判定と、3つのステージ
- iPhoneの縦画面で文字入力中もグラフを見られる配置
- 外部ライブラリ不要。`index.html` だけで動作

## 遊び方

式の入力例: `x*(8-x)/8`、`sin(x)`、`sqrt(x)`。
iPhoneではファイルプレビューではなく、GitHub Pagesで公開したURLをSafariで開いてください。

## GitHub Pagesで公開する

1. GitHub Freeの場合、`Settings > General > Danger Zone > Change repository visibility` からリポジトリをPublicに変更します。
2. `Settings > Pages` を開きます。
3. `Build and deployment > Source` で `Deploy from a branch` を選びます。
4. `Branch: main`、`Folder: /(root)` を選択して `Save` を押します。
5. Pagesに表示される公開URLを確認します。予定URL形式: `https://tetedayo.github.io/graph_runner/`。

このゲームはDesmos公式製品ではありません。数式リストの操作感を参考にした独立の実装です。
