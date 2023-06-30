[模擬試験（本番レベル）①）](https://www.udemy.com/course/aws-associate/learn/quiz/4591360/result/950377312#overview)

# サービス別

## EBS
### SSD 
- 汎用SSD gp1は250 MiB/s gp2は1000 MiB/s
- プロビジョンドIOPS(io1,io2) 1000 MiB/s
- プロビジョンドIOPS(io2 Block Express) 4000 MiB/s
### HDD
- スループット最適化HDD 500 MiB/s
- コールドHDD 250 MiB/s

## SQS
### デッドレターキュー

## Kinesis Data Streams
## Kinesis Data Firehose
### データレコードがストリームに加えられてからデフォルトで24時間以内までアクセスできるように設定

## CloudFront
### ディストリビューション設定
### フィールドレベル暗号化、アップロード時のデータの暗号化ができる
### 1つのAWSリージョンにALBとEC2で構成されたアプリを構築して、ディストリビューションにALBをオリジンサーバーにすることで、グローバルに最適なコンテンツ配信ができる
### エッジロケーションにおけるファイル圧縮処理

## AWS Compute Optimizer

## Amazon Simple Workflow

## Dynamo DB
### SQSによるメッセージング構成
### オンデマンドモード
### Dynamo DBストリーム、Dynamo DBへの登録・変更などをトリガーにしてLambda関数を動作させることができる

## RDS
### Optimized Writes, 書き込み処理を最大50%向上
### AutoScalingはストレージ容量の拡張
### マルチAZクラスター、プライマリーDBインスタンスに加えて、それぞれ別のAZに2つのリードレプリカを作成する、冗長性とパフォーマンスを向上させる

## Amazon EMR
### ログ解析

## Kinesis Data Analytics
### ストリーミングデータを標準SQLでリアルタイムなデータ処理実行

## S3
### イベント通知、バケット内イベントの発生をトリガーにして、SNS/SQS/Lambdaに通知可能
### 日付ベースの順次命名を付与して保存することでアクセス時のパフォーマンスを向上させることができる

## タグ
### EC2インスタンスの開発用タグで分類分けを行い、そのタグが設定されているEC2インスタンスのみに操作ができるようにIAMポリシーを与えることで本番用への削除権限を与えないようにできる

