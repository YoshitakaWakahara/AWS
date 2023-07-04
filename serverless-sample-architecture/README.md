# serverless framework
CFnとLambda用のソースコードを一式パッケージ化している
インフラの構築・更新をslsのコマンドで実行可能
確かに手軽に構築はできるが、slsの学習コストと、CFnとLamdaを分けて管理できない点が気掛かり

# Lambda
API Gatewayのeventの発火で動かすことができる
boto3のライブラリを使うことが一般的?

# DynamoDB
key-value型のDB、プライマリキーに加えて検索用のソートキーを設定できる
本格的に習熟するにはNoSQLの学習が必要そう

# API Gateway
GETなどのリクエストを受け付けるエンドポイントを作成する
多数のエンドポイントの管理方法やテストの方法などを勉強したい

# Code Commit, Code Build, Code Pipiline
ローカルの端末とCode Commitを繋げる方法がよくわかっていない、Gitの鍵とAWSの鍵がそれぞれ絡んで複雑、どこかで一連の構築までする