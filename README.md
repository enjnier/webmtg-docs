# webmtg-docs

これは個人開発のWeb会議システムに関連するドキュメントをMkDocsで作成したプロジェクトです。
紹介ページを <https://enjnier.github.io/webmtg-docs/> に公開していますので、興味のある方はご覧ください。

## Rye + Material for MkDocs

本プロジェクトは `Rye` と `Material for MkDocs` を使用しています。

ローカル環境で利用する際の手順を以下に記載します。
前提として [Rye](https://rye.astral.sh/) が利用できる環境であること。

1. 仮想環境（.venv）を作成する

    ```bash
    rye sync
    ```

2. Liveモードでドキュメントを参照する

    ```bash
    rye run serve
    ```

`pyproject.toml` に `mkdocs serve` コマンドを定義しています。

```yml
[tool.rye.scripts]
serve = "mkdocs serve -a 127.0.0.1:8100"
```

## 利用について

このリポジトリは個人開発のWeb会議システムに関するドキュメントを公開するものです。内容の参照や個人的な学習目的での利用は自由ですが、商用利用や大規模な再配布についてはお控えください。
