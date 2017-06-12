# How to Use
## Step.1
- `npm i -g yarn`

## Step.2
- `yarn`

## Step.3
- `yarn start`
 - 新規ファイルを追加した場合は、 `yarn start` し直してください

# packageの内容説明
- /src配下にそれぞれhtml, scss, jsディレクトリがあるのでそこにファイルを追加してください
 - `yarn start` 後であれば、ファイルの変更を自動検知してbrowser側を自動で更新してくれます
- [eslint-airbnb-base](https://github.com/airbnb/javascript)のルールに則っています(es5用）
 - いつくかカスタマイズしてるので詳細を知りたかったら `.eslintrc` を見てください
 - airbnbのルールは絶対ではありませんので、厳しいルールがあればプロジェクトにそって変更しましょう
- [eslint](http://eslint.org/docs/rules/)でエラーが出たらルールを[ここ](http://eslint.org/docs/rules/)で調べましょう
- [stylelint](https://github.com/stylelint/stylelint-config-standard#suggested-additions)のルールは[ここ](https://github.com/stylelint/stylelint-config-standard#suggested-additions)を調べましょう
- [htmlhint](https://github.com/yaniswang/HTMLHint/wiki/Rules)のルールは[ここ](https://github.com/yaniswang/HTMLHint/wiki/Rules)を見てください

# コマンド

- `yarn lint` …… /src配下のファイルを検証します。
- `yarn fmt` …… /src配下のscss, jsファイルのエラーを可能な限り自動修正します。
- `yarn dist` …… サーバーレスでbuildします。

# 注意

html, scss, jsファイルは、コミット前にチェックされ、エラーがあるとコミットに失敗します。
（scss, jsファイルは、エラーがあっても、可能な限り自動修正されます。）
