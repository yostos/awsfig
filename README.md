# AWSFig

Generate AWS CDK script from AWS Architecture figure

Amazon Bedrock - Claude3を使ってAWSの構成図から同じ構成を作成するための
AWS CDKのTypeScriptを生成します。

## Description

AWS Solution Architectの方が Playgrandでよくデモをしているようなので、
コマンドラインからできるように作ってみました。

- 生成したコードの正確性は検証していません。
- サンプルコードで、認証情報の扱いやエラーハンドリングは適当です。

## Requirement

- [venv](https://docs.python.org/3/library/venv.html) (Python仮想環境)
- [AWS SDK for Python (Boto3)](https://aws.amazon.com/jp/sdk-for-python/)

## Usage

以下で実行できます。

```fish
python3 -m venv venv
source venv/bin/activate.fish      # シェルにfishを使っていることを前提としています。
                                   # 自身のシェルに合わせてコマンドを変更してください。
./awsfig.py -f aws.png
```

![Demo](https://github.com/yostos/awsfig/blob/main/images/demo.gif)

## Licence

[MIT](https://github.com/yostos/awsfig/blob/main/LICENSE)

## Author

[yostos](https://github.com/yostos)
