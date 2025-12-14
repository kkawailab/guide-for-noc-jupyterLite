# Nature of Code（JupyterLite ノートブック）

このフォルダには Daniel Shiffman の『The Nature of Code』を章ごとに短くまとめたノートブックと、JupyterLite（Pyodide）上ですぐに動かせる小さなPython例が入っています。

## 目次
- [構成](#構成)
- [JupyterLiteでの使い方](#jupyterliteでの使い方)
- [メモ](#メモ)
- [p5.js版ノートブック](#p5js版ノートブック)

## 構成
- `notebooks/ch00-introduction.ipynb` 〜 `notebooks/ch10-neural-networks.ipynb` : 章ごとに1ノートブック
- 各ノートブックは短いMarkdownの振り返りと、外部依存のない自給自足のPython例で構成

## JupyterLiteでの使い方
1. `notebooks/` ディレクトリをJupyterLiteワークスペースにアップロードまたは配置します。
2. 任意の章のノートブックを開き、上から順にセルを実行します。Pyodideのみで動くよう重い依存は避けています。
3. 最初のセルにある「試してみよう」のパラメータを変えながら各トピックを探索してください。

## メモ
- 例はテキスト出力中心の最小実装です。JupyterLite内で完結させるため外部描画ライブラリは使っていません。
- p5のような描画環境が使える場合は、ここでのベクトル/物理コードを置き換えて視覚化することもできます。

## p5.js版ノートブック
- ディレクトリ: `notebooks-p5/`
- カーネル: [jupyterlite/p5-kernel](https://github.com/jupyterlite/p5-kernel)（`p5.js`カーネルを選択）
- 各章に対応したp5.jsスケッチが1セルで入っています。`試してみよう`の定数を変えて挙動を確認してください。
