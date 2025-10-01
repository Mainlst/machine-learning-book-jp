# Machine Learning with PyTorch and Scikit-Learn 日本語メモ

このリポジトリは、Sebastian Raschka ほか著 *Machine Learning with PyTorch and Scikit-Learn* に付属する公式ノートブックをもとにした **非公式日本語訳＆学習メモ集** です。翻訳と補足は有志によるもので、出版社や著者とは無関係です。詳細な帰属情報は `NOTICE.md` を参照してください。

原著リポジトリ: <https://github.com/rasbt/machine-learning-book>

## 勉強用・雑多OKのポリシー

- 学習ノート、訳語の検討メモ、章ごとの補遺など **自由な草稿の置き場** として利用します。
- 原著の本文を逐語訳するのではなく、理解の助けとなる要約・注釈・コード補足を中心にします。
- 訳語統一は `GLOSSARY.md`、翻訳ルールは `TRANSLATION_GUIDE.md` に整理しています。更新時は必ず確認してください。

## リポジトリ構成ハイライト

- `ch01/` 〜 `ch19/`: 書籍各章のノートブック & Python スクリプト
- `ERRATA/`: 誤植や補足説明のメモ
- `supplementary/`: Colab での実行ガイドなど追加資料
- ルート: 翻訳作業向けのメタ情報 (`NOTICE.md`, `GLOSSARY.md`, `TRANSLATION_GUIDE.md` など)

章別 README やノートブックにも和訳メモを追加する場合、ここで定めた方針との整合性を保ってください。

## セットアップ手順

1. Anaconda / Miniconda をインストール
2. 環境ファイルから仮想環境を作成

   ```bash
   conda env create -f environment.yml
   conda activate mlbook-ja
   ```

3. `jupyter lab` もしくは `jupyter notebook` を起動し、必要な章のノートブックを開く

GPU を利用する場合は PyTorch のインストール手順に応じて適宜バージョンを変更してください。最小構成は `environment.yml` を参照するか、`python_environment_check.py` でバージョン確認ができます。

## ドキュメントと運用ルール

- `NOTICE.md`: 原著への帰属とライセンス表記
- `GLOSSARY.md`: 訳語対訳と用語メモ
- `TRANSLATION_GUIDE.md`: 訳し方・記法のガイドライン
- `.pre-commit-config.yaml`: フォーマット確認用のフック設定（必要に応じて `pre-commit install` を実行）

Pull Request を送る際は、翻訳ルールに従っているか・新規用語を `GLOSSARY.md` に追加したか等をチェックリスト形式で確認しましょう。

## ライセンス

- 原著ノートブックおよびコードは MIT ライセンス（`LICENSE.txt` 参照）
- 日本語訳と追加メモも MIT ライセンスで公開します（`NOTICE.md` に表記）

コントリビューションの際はライセンスとポリシーに従い、出典が必要な資料は必ず明記してください。

## 謝辞

原著著者の Sebastian Raschka さん、Yuxi (Hayden) Liu さん、Vahid Mirjalili さんに感謝します。また、翻訳と補足を手伝ってくださる全てのコントリビュータに感謝いたします。# *Machine Learning with PyTorch and Scikit-Learn* Book

##  Code Repository


Paperback: 770 pages  
Publisher: Packt Publishing  
Language: English

ISBN-10: 1801819319   
ISBN-13: 978-1801819312  
Kindle ASIN: B09NW48MR1  

[<img src="./.other/cover_1.jpg" width="248">](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/)



## Links

- [Amazon link](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/) 
- [Packt link](https://www.packtpub.com/product/machine-learning-with-pytorch-and-scikit-learn/9781801819312)
- [Blog post summarizing the contents](https://sebastianraschka.com/blog/2022/ml-pytorch-book.html)

