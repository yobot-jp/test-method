# このサイトについて

世の中には数多くの安全対策グッズがあるが、何が本当に安全なのか？わからない。

定量的な評価のもとに安全性を評価し、商品開発に活かすことを目的とする。

# テスト前の準備について

- まず、テスト対象商品のディレクトリをきる。　 ex: mkdir tape

- 次に、package.json を作成し、バージョンを 0.0.1 とする。

- 最後に、その配下で、実験前、実験中、実験後の内容を記載する 3 つのファイルを作る

touch pre-test.md test.md post-test.md

# ブランチルール

- バージョニングは、[Semver](https://semver.org/lang/ja/)に則って行う

```
# 例: 1.0.0のとき
$ npm version patch
v1.0.1

$ npm version minor
v1.1.0

$ npm version major
v2.0.0
```

- ブランチ命名は、「対象商品」/「version」

ex: tape/0.0.1
