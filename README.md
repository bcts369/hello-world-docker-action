# Hello world docker action

Docker コンテナのアクションを作成します


- アクションが実行する内容の詳細
- 必須の入力引数と出力引数
- オプションの入力引数と出力引数
- アクションが使用するシークレット
- アクションが使用する環境変数
- ワークフローでアクションを使う使用方法の例

このアクションは"Hello World"もしくは"Hello" + ログに挨拶する人物名を出力します。

## Inputs

### `who-to-greet`

**必須** 挨拶する相手の名前。 デフォルトは `"World"`。

## 出力

### `time`

挨拶した時間。

## 使用例

```
uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
```

Status badge

[![Actions Status](https://github.com/bcts369/actions-playground/workflows/Timer%20per%20one%20hour/badge.svg)](https://github.com/bcts369/actions-playground/actions)

[![Actions Status](https://github.com/bcts369/hello-world-docker-action/workflows/HelloWorld/badge.svg)](https://github.com/bcts369/hello-world-docker-action/actions)