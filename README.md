## データ可視化＆ビジネスインテリジェンス

- **Amazon QuickSight**: クラウドベースのビジネスインテリジェンスサービス
- **QuickSight ダッシュボード**: データを視覚的に表示するためのインタラクティブなダッシュボード
- **ビジネスインテリジェンス(BI)**: ビジネスデータの分析と可視化のためのツールや技術
- **QuickSight SPICE/SPICE(超高速並列インメモリ計算エンジン)**: QuickSight のインメモリエンジン
- **Amazon QuickSight レベルウェア計算-ウィンドウ(LAC-W)関数**: ウィンドウベースの計算関数
- **Amazon QuickSight レベルウェア計算-集計(LAC-A)関数**: 集計ベースの計算関数
- **Amazon QuickSight テーブル計算**: テーブル内の計算機能# AWS データサービス分類一覧

## データ統合・ETL（抽出、変換、ロード）

- **AWS Glue**: サーバーレスのデータ統合サービス
- **AWS Glue DataBrew**: コード不要でデータクレンジングと正規化を行うサービス
  - **AWS Glue DataBrew レシピ**: データ変換手順を定義するレシピ
- **AWS Glue トリガー**: ETL ジョブの実行をスケジュールまたはイベント駆動で開始する機能
- **AWS Glue 接続**: データソースへの接続情報を管理
  - **Java Database Connectivity(JDBC)接続/AWS Glue Java Database Connectivity(JDBC)接続**: JDBC を使用したデータベース接続
- **AWS Glue PySpark ジョブ**: Python/Spark を使用した ETL ジョブの実行
  - **AWS Glue PySpark Filter クラス**: データフィルタリングのためのクラス
- **AWS Glue ジョブ**: ETL ジョブを実行するための一般的な機能
  - **AWS Glue ジョブのブックマーク**: 処理済みデータを追跡する機能
  - **AWS Glue Python シェルジョブ**: Python シェルで実行される Glue ジョブ
  - **AWS Glue PySpark ジョブ**: PySpark 環境で実行される Glue ジョブ
- **AWS Glue クローラー**: データソースを自動的にスキャンしてメタデータを抽出する機能
- **AWS Glue Studio**: ビジュアルインターフェースで ETL ジョブを作成・管理するツール
- **AWS Glue 分類子**: データ形式を識別する機能
- **AWS Glue ノートブック**: 対話型で ETL スクリプトを開発する環境
- **AWS Database Migration Service(AWS DMS)**: データベース間の移行サービス
  - **CDC タスク**: 変更データキャプチャタスク
  - **CDCIncomingChanges メトリクス**: CDC の変更数を測定するメトリクス
  - **CDCLatencySource メトリクス**: CDC のレイテンシを測定するメトリクス
- **AWS Lambda**: サーバーレスでコードを実行するコンピューティングサービス（データ変換処理にも使用可能）
- **AWS Lambda ユーザー定義関数(UDF)**: カスタム関数を作成してデータ処理に利用
- **Lambda レイヤー**: Lambda 関数間で共有できるコード層
- **PySpark プログラム**: Python を使用した Apache Spark プログラム
- **FindMatches 機械学習(ML)変換/AWS Lake Formation FindMatches 変換**: AWS Glue で類似レコードを特定するための ML 変換
- **DateFrame.drop_duplicates()関数/Apache Spark の DataFrame dropDuplicates()API**: 重複レコードを削除する PySpark 関数
- **ETL クラスター**: ETL 処理を実行するためのクラスター
- **変更データキャプチャ(CDC)**: ソースデータベースの変更を追跡して適用する技術
- **Amazon AppFlow**: SaaS アプリケーションと AWS サービス間のデータ統合
  - **Amazon AppFlow SDK**: AppFlow を利用するためのソフトウェア開発キット
- **S3 Object Lambda エンドポイント**: S3 から取得するデータに対して変換を行うエンドポイント
- **FLEX 実行クラス**: AWS Glue の柔軟なリソース割り当てを行う実行クラス
- **スタンダード実行クラス**: AWS Glue の標準的なリソース割り当てを行う実行クラス
- **GlueVersion フィールド**: AWS Glue ジョブで使用する Glue のバージョンを指定するフィールド
- **AWS Glue Python シェルスクリプト**: Python シェルでの実行を可能にする AWS Glue のジョブタイプ
- **DynamicFrame スキーマクラス/DynamicFrame**: AWS Glue でスキーマを動的に処理するためのクラス
  - **AWS Glue の DynamicFrame ファイルグループ化オプション**: ファイルをグループ化するためのオプション
- **Amazon Aurora ゼロ ETL 統合**: Aurora から他の AWS サービスへの ETL 不要の統合機能
- **AWS Glue ResolveChoice 組み込み変換**: スキーマの曖昧さを解決するための変換
- **NEST_TO_MAP 変換**: ネストされた構造をマップに変換
- **NEST_TO_ARRAY 変換**: ネストされた構造を配列に変換
- **PIVOT 変換**: 行をカラムに変換する
- **AWS Glue Data Quality 変換/Evaluate Data Quality 変換**: データ品質を評価するための変換
  - **AWS Glue Data Quality ルールセット**: データ品質ルールの集合
  - **AWS Glue Data Quality スコア**: データ品質評価のスコア
  - **データ品質定義言語(DQDL)**: データ品質ルールを定義する言語
- **Great Expectations ライブラリ**: データ検証のための Python ライブラリ
- **PyDeequ ライブラリ**: データ品質評価のための Python ライブラリ
- **AWS DataSync タスク**: データ転送タスク
- **Amazon Textract**: ドキュメントからテキストや表を抽出するサービス
- **SFTP 環境**: SFTP プロトコルでファイル転送を行う環境

## ワークフロー管理・オーケストレーション

- **AWS Glue ワークフロー**: 複数の AWS Glue ジョブを連携させるワークフロー
- **AWS Step Functions/Amazon Step Functions**: サーバーレスワークフローを構築するためのオーケストレーションサービス
  - **Wait 状態**: 指定した時間だけ待機する状態
  - **Parallel 状態/Parallel**: 複数のブランチを並列実行する状態
  - **Choice 状態/Choice**: 条件に基づいて分岐する状態
  - **Map 状態/Map**: コレクション内の各項目に対して同じ処理を実行する状態
  - **Task**: タスクを実行する状態
  - **Step Functions 状態タイプ**: ステートマシンで使用できる状態の種類
- **AWS Step Functions ワークフロー**: Step Functions で定義されたワークフロー
- **AWS Step Functions ステートマシン**: Step Functions のワークフローを定義するステートマシン
- **Amazon Managed Workflows for Apache Airflow(Amazon MWAA)**: マネージド型の Apache Airflow サービス
  - **Amazon MWAA DAG**: MWAA で実行する Apache Airflow の DAG
- **Apache Airflow ワークフロー**: Apache Airflow で定義されたワークフロー
- **Apache Oozie**: Hadoop ジョブのワークフロー管理ツール
- **Amazon EventBridge**: イベント駆動型アプリケーションの構築に使用されるサーバーレスイベントバス
  - **Amazon EventBridge ルール**: イベントパターンに基づいてアクションをトリガーするルール
- **有効非巡回グラフ（DAG）**: ワークフローを表現するための有向グラフの一種
- **AWS Application Auto Scaling**: リソースを自動的にスケーリングするサービス
- **Amazon Simple Workflow Service**: ワークフローを構築・実行するためのサービス

## データストレージ＆ウェアハウス

- **Amazon Redshift**: ペタバイト規模のデータウェアハウスサービス
- **Amazon Redshift Data API**: SQL を使用して Redshift に対してクエリを実行する API
- **Amazon Redshift Spectrum**: S3 に保存されたデータに対して Redshift から直接クエリを実行
- **Amazon Redshift クラスター/Redshift クラスター**: プロビジョニング型の Redshift サービス
- **Redshift Serverless/Amazon Redshift Serverless**: サーバーレス型の Redshift サービス
- **Amazon Redshift クエリエディタ v2/クエリエディタ v2**: Redshift に対する SQL クエリを実行・管理するツール
- **Amazon Redshift マテリアライズドビュー**: クエリ結果をキャッシュするプリコンピュート済みのビュー
- **Create Table As Select(CTAS)**: クエリ結果から新しいテーブルを作成する SQL 構文
- **ワークロード管理**: Redshift でのクエリパフォーマンスを最適化する機能
  - **STL_PLAN_INFO**: クエリプランに関する情報を保存するシステムテーブル
  - **STL_USAGE_CONTROL**: ユーザーごとの使用量を制限するためのシステムテーブル
  - **STL_ALERT_EVENT_LOG**: クエリ実行時の警告やエラーを記録するシステムテーブル
- **クエリオプティマイザ**: クエリ実行計画を最適化する Redshift の機能
- **Amazon Elastic Block Store**: EC2 インスタンス用の高性能ブロックストレージ
- **Amazon DynamoDB**: フルマネージド型の NoSQL データベースサービス
  - **DynamoDB Accelerator(DAX)**: DynamoDB の読み取りパフォーマンスを向上させるインメモリキャッシュ
  - **WriteThroughputExceeded**: スループット制限を超えたときに発生するエラー
- **Amazon RDS**: リレーショナルデータベースのマネージドサービス
- **Amazon Aurora**: MySQL および PostgreSQL と互換性のある高性能クラウドデータベース
- **Amazon S3**: スケーラブルなオブジェクトストレージサービス
- **Amazon Redshift プロビジョニングクラスター**: 事前に容量を確保する Redshift クラスター
- **Redshift Spectrum テーブル**: Redshift Spectrum で参照できる外部テーブル
  - **Amazon Redshift Spectrum データベース**: Spectrum を通じてアクセスできる外部データベース
- **Redshift データ共有**: 異なるクラスター間でデータを共有する機能
- **SAP HANA**: インメモリデータベース
- **Microsoft SQL Server**: Microsoft のリレーショナルデータベース管理システム
- **MongoDB**: ドキュメント指向 NoSQL データベース
- **Aurora Serverless**: オンデマンドで自動スケーリングする RDS Aurora のサーバーレスオプション
- **Amazon Redshift オブジェクト**: Redshift 内に存在するデータベースオブジェクト
- **Redshift ストアドプロシージャ**: Redshift 内で実行できる保存済みの手続き
- **Amazon ElastiCache クラスター**: インメモリキャッシュのマネージドサービス
- **Amazon RDS Performance Insights 機能**: RDS データベースのパフォーマンス分析ツール
- **SQL Server Agent**: SQL Server のジョブスケジューリングコンポーネント
- **Amazon Redshift ストリーミング取り込み**: ストリーミングデータを Redshift に直接取り込む機能
- **EVEN 分散スタイル**: Redshift でデータを均等に分散させる方式
- **分散キー**: Redshift でデータ分散の基準となるキー
- **ソートキー**: Redshift でデータ格納の順序を決定するキー
  - **Amazon Redshift テーブルの複号ソートキー**: 複数のカラムを使用したソートキー
- **パーティションキー**: データをパーティションに分割するためのキー
- **ALL 分散スタイル**: Redshift ですべてのノードにデータを複製する分散方式
- **プライマリーキー**: テーブル内のレコードを一意に識別するキー
- **外部キー**: 他のテーブルの主キーを参照するキー
- **Amazon Redshift マネージドストレージ**: Redshift の自動的に管理されるストレージ
- **Amazon Redshift コマンド**: Redshift で使用される管理コマンド
  - **VACUUM SORT ONLY**: テーブルのソート順を回復するコマンド
  - **VACUUM DELETE ONLY**: 削除マークが付いた行を物理的に削除するコマンド
  - **VACUUM REINDEX/VACUUM REINDEX コマンド**: インデックスを再構築するコマンド
  - **VACUUM FULL**: 完全な VACUUM 操作を実行するコマンド
  - **VACUUM RECLUSTER コマンド**: データの再クラスタリングを行うコマンド
  - **ANALYZE コマンド**: テーブル統計情報を更新するコマンド
  - **ANALYZE COMPRESSION コマンド**: 最適な圧縮タイプを分析するコマンド
  - **UNLOAD コマンド**: クエリ結果を S3 にエクスポートするコマンド
- **Amazon Redshift フェデレーテッドクエリ/フェデレーテッドクエリ**: 外部データソースに対してクエリを実行する機能
- **Amazon Redshift ML**: Redshift での ML 機能を統合したサービス
- **Amazon Redshift の動的データマスキングポリシー**: 特定のユーザーに対してデータを動的に難読化する機能
- **Amazon Redshift の行レベルセキュリティ機能**: 行単位でのアクセス制御機能
- **Amazon Redshift の列レベルセキュリティ機能**: 列単位でのアクセス制御機能
- **Amazon Redshift のロールベースのアクセスコントロール機能**: ロールに基づくアクセス制御機能
- **SUPER データ型**: セミ構造化データを格納する Redshift のデータ型
- **Amazon Timestream/Amazon Timestream データベース**: 時系列データのためのデータベースサービス
- **Amazon Keyspaces/Amazon Keysoaces for Apache Cassandra**: Apache Cassandra 互換のマネージドデータベースサービス
- **Amazon DocumentDB**: MongoDB 互換のドキュメントデータベースサービス
- **Teradata/Teradata Vantage**: データウェアハウスプラットフォーム
- **Google BigQuery**: Google のクラウドデータウェアハウス
- **オンライントランザクション処理(OLTP)**: トランザクション処理に最適化されたデータベースタイプ
- **Amazon Elastic File System**: スケーラブルなファイルストレージサービス
- **Apache Iceberg**: テーブル形式のデータ管理

## ストレージ管理＆ライフサイクル

- **S3 Intelligent-Tiering**: アクセスパターンに基づいて自動的にデータを最適なストレージクラスに移動
- **ディープアーカイブアクセス階層**: S3 Intelligent-Tiering 内の極めて低頻度アクセス用の階層
- **S3 Storage Lens/Amazon S3 Storage Lens**: S3 ストレージの使用状況と活動傾向を可視化する分析ツール
- **S3 ライフサイクルポリシー/S3 ライフサイクルルール**: S3 オブジェクトの自動的な移行や期限切れを管理
- **Amazon S3 標準 - 低頻度アクセス(S3 標準 - IA)**: 低頻度アクセスデータ向けの低コストストレージクラス
- **S3 Glacier ストレージクラス**: 長期アーカイブ向けの低コストストレージクラス
- **S3 Glacier Deep Archive ストレージクラス**: 最も低コストの長期アーカイブストレージクラス
- **Amazon S3 Glacier Flexible Retrieval**: 数分から数時間でデータを取得できるアーカイブストレージ
- **Amazon Glacier Instant Retrieval**: 即時取得が可能なアーカイブストレージクラス
- **Amazon Glacier Flexible Retrieval**: 柔軟な取得オプションを提供するアーカイブストレージ
- **S3 バージョニング**: S3 オブジェクトの複数バージョンを保持する機能
- **AWS Storage Gateway**: オンプレミスとクラウドストレージを統合するサービス
- **Amazon S3 ファイルゲートウェイ**: S3 へのファイルインターフェースを提供するゲートウェイ
- **リーガルホールド**: データの削除や変更を一時的に防止する機能ストストレージクラス
- **S3 Glacier Deep Archive ストレージクラス**: 最も低コストの長期アーカイブストレージクラス
- **Amazon S3 Glacier Flexible Retrieval**: 数分から数時間でデータを取得できるアーカイブストレージ
- **Amazon Glacier Instant Retrieval**: 即時取得が可能なアーカイブストレージクラス
- **Amazon Glacier Flexible Retrieval**: 柔軟な取得オプションを提供するアーカイブストレージ
- **S3 バージョニング**: S3 オブジェクトの複数バージョンを保持する機能
- **AWS Storage Gateway**: オンプレミスとクラウドストレージを統合するサービス
- **Amazon S3 ファイルゲートウェイ**: S3 へのファイルインターフェースを提供するゲートウェイ
- **リーガルホールド**: データの削除や変更を一時的に防止する機能ストストレージクラス
- **S3 Glacier Deep Archive ストレージクラス**: 最も低コストの長期アーカイブストレージクラス

## カタログ＆メタデータ管理

- **データカタログ/中央メタデータリポジトリ**: データの構造や場所などのメタデータを管理する一般的な概念
- **Amazon Glue Data Catalog**: AWS 環境のデータソースの統合カタログサービス
- **AWS Glue Data Catalog リソースポリシー**: Glue Data Catalog へのアクセスを制御するポリシー
- **Apache Hive メタストア/Hive メタストア**: Hadoop エコシステムでのデータカタログサービス
- **AWS Glue CreatePartition API/Boto3 AWS Glue create_partition API**: プログラムでパーティションを作成する API
- **MSCK REPAIR TABLE/MSCK REPAIR TABLE コマンド**: Hive テーブルのパーティション情報を更新するコマンド
  - **MSCK REPAIR TABLE Orders**: Orders テーブルのパーティション情報を更新
  - **REPAIR TABLE Orders**: 別の構文で Orders テーブルのパーティション情報を更新
- **Athena ワークグループ**: Athena ユーザーのクエリをグループ化し管理する機能
- **Athena データソース**: Athena からアクセス可能なデータソースの設定
- **Athena クエリ設定**: Athena クエリの動作を制御する設定
- **Athena クエリエディタ**: Athena でクエリを作成・実行するためのインターフェース
- **AWS Glue Schema Registry**: データスキーマを管理・検証するレジストリ
- **Athena Boto3 get_query_execution API コール**: Athena クエリの実行状態を取得する API
- **Athena Boto3 start_query_execution API コール**: Athena クエリを開始する API
- **Athena クエリプラン**: Athena クエリの実行計画
- **Athena パーティション射影**: クエリのパフォーマンスを向上させるパーティション管理手法
- **データ定義言語(DDL)**: データベースのスキーマを定義するための言語
- **Amazon DataZone ポータル**: データ共有と管理のためのポータル

## ストリーミングデータ処理

- **Amazon Kinesis Data Stream/Amazon Kinesis Data Streams/Amazon Kinesis**: リアルタイムのデータストリーミングサービス
  - **Kinesis Client Library**: Kinesis ストリームからデータを処理するためのライブラリ
  - **Amazon Kinesis Producer Library/Kinesis Producer Library**: Kinesis にデータを送信するためのライブラリ
  - **IteratorAgeMilliseconds メトリクス**: 処理の遅延を測定するメトリクス
  - **AggregationEnabled 設定プロパティ**: レコードの集約を有効にする設定
  - **拡張ファンアウト機能**: 高スループットの消費者を実現する機能
  - **PutRecordBatch API**: 複数レコードを一度に送信する API
- **Amazon Kinesis Data Firehose/Amazon Kinesis Data Firehose 配信ストリーム/Data Firehose 配信ストリーム/Amazon Data Firehose**: ストリーミングデータをデータストアやアナリティクスサービスに配信
- **サブスクリプションフィルター**: ストリームから特定のデータを抽出するためのフィルター
- **Apache Kafka/Apache Kafka クラスター**: 分散ストリーミングプラットフォーム
  - **Apache ZooKeeper**: 分散アプリケーションの調整サービス
  - **RootDiskUsed**: ディスク使用率のメトリクス
  - **Target Volume-in-GiB**: 目標ボリュームサイズ
- **Amazon Managed Streaming for Apache Kafka(Amazon MSK)**: マネージド型の Apache Kafka サービス
  - **Amazon Managed Streaming for Apache Kafka プロビジョニング済みクラスター**: 事前にプロビジョニングされた MSK クラスター
  - **Amazon Managed Streaming for Apache Kafka Serverless**: サーバーレス型の MSK サービス
- **Amazon Managed Service for Apache Flink**: マネージド型の Apache Flink サービス
- **Amazon Simple Queue Service**: マネージド型のメッセージキューイングサービス
- **Amazon CloudWatch Logs**: ログの収集、監視、分析サービス
- **VPC フローログクエリ**: VPC ネットワークトラフィックのログに対するクエリ
- **Amazon Simple Notification Service**: メッセージ通知サービス
- **FluentBit**: ログデータコレクター
- **OpenTelemetry**: テレメトリデータの収集、処理、エクスポートのためのフレームワーク

## 大規模データ処理＆分析

- **Amazon EMR/EMR クラスター**: マネージド型 Hadoop フレームワークサービス
  - **コアノード**: データを処理・保存するノード
  - **タスクノード**: 処理のみを実行するノード
  - **Amazon EMR Serverless**: サーバーレスの分析エンジン
  - **Graviton インスタンス**: Arm ベースのプロセッサを使用するインスタンス
  - **EMR マネージドスケーリング**: クラスターのサイズを自動調整する機能
  - **EMR クラスターのスケーリングクールダウン期間**: スケーリング後の待機期間
  - **S3DistCp**: S3 と HDFS 間でデータをコピーするユーティリティ
- **Apache Hadoop クラスター**: 大規模データの分散処理フレームワーク
  - **Haddop Distributed File System(HDFS)/Hadoop Distributed File System**: Hadoop の分散ファイルシステム
- **Apache Hive**: Hadoop エコシステム上で SQL 風クエリを実行するためのデータウェアハウスソフトウェア
- **Apache Spark**: 大規模データ処理のための統合分析エンジン
  - **Apache Spark DataFrame**: Spark の構造化データ処理 API
  - **Apache Spark ML パイプライン**: 機械学習パイプラインの構築フレームワーク
  - **Spark SQL**: Spark のデータクエリ言語
- **Apache Pig**: Hadoop データの操作を容易にするための高レベル言語
- **Apache Flink**: ストリーム処理とバッチ処理のためのオープンソースの分散処理フレームワーク
- **Apache HBase**: Hadoop エコシステム上で動作する分散型の非リレーショナルデータベース
- **Amazon Athena/Amazon Athena**: S3 のデータに対して直接 SQL クエリを実行できるサーバーレスクエリサービス
- **Amazon Athena フェデレーテッドクエリ/Amazon Athena Federated Query**: 複数のデータソースにまたがるクエリを実行する機能
- **S3 Select**: S3 オブジェクト内のデータサブセットを取得するためのサービス
- **Amazon RDS for MySQL DB**: MySQL データベース用のマネージドサービス
- **Amazon EMR S3DistCP ユーティリティ**: Hadoop クラスターとの間でデータを効率的にコピーするツール
- **Apache Zeppelin**: インタラクティブなデータ分析用のウェブベースのノートブック
- **COUNT_DISTINCT 集計関数**: 重複を排除してカウントする集計関数
- **レイクハウスアーキテクチャ**: データレイクとデータウェアハウスの特徴を組み合わせたアーキテクチャ
- **Amazon OpenSearch Service**: 検索・分析エンジン
- **Amazon Managed Grafana/Grafana ダッシュボード**: 時系列データの可視化と監視ツール
- **Amazon SageMaker Studio**: 機械学習開発環境
  - **SageMaker Autopilot**: 自動機械学習サービス
  - **Amazon SageMaker Data Wrangler**: データ前処理ツール
- **Amazon Comprehend**: 自然言語処理サービス
- **Amazon Neptune ML**: グラフデータベース用の機械学習機能
- **Apache Gremlin スクリプト**: グラフデータベースのクエリ言語
- **ANSI SQL**: 標準 SQL
- **SPARQL**: RDF データ用のクエリ言語
- **Gremlin**: グラフトラバーサル言語
- **Splunk**: ログデータとリアルタイム分析プラットフォーム

## データ形式＆圧縮

- **Apache Parquet 形式**: 列指向のデータ保存形式
- **Apache Avro**: データシリアライゼーションフレームワーク
- **Snappy 圧縮**: 高速な圧縮・展開を目的としたデータ圧縮アルゴリズム

## データ転送＆共有

- **AWS Data Exchange**: クラウド上のデータ製品の検索、購入、共有を容易にするサービス
- **AWS DataSync**: オンプレミスと AWS 間の大規模データ転送を自動化するサービス
- **AWS Direct Connect/AWS Direct Connect 接続**: オンプレミスから AWS への専用ネットワーク接続
- **Amazon S3 Transfer Acceleration**: 遠距離間での S3 へのファイル転送を高速化
- **Transfer Family**: ファイル転送サービスのファミリー

## コンテナ＆サーバーレスコンピューティング

- **Amazon Elastic Kubernetes Service**: マネージド型 Kubernetes サービス
- **Amazon Elastic Container Service**: コンテナオーケストレーションサービス
  - **Amazon Elastic Container Service Service Connect**: サービス間通信機能

## セキュリティ＆アクセス管理

- **特定のポートからのアクセスを許可する自己参照ルール**: セキュリティグループの設定
- **AWS Secrets Manager**: データベース認証情報などのシークレットを安全に管理するサービス
- **クロスアカウント権限を持つ IAM ロール**: 異なる AWS アカウント間でのアクセス権限を管理
- **Amazon Cognito**: ユーザー認証と認可を管理するサービス
- **AmazonS3FullAccess ポリシー**: S3 リソースへのフルアクセスを許可する IAM ポリシー
- **AWSGlueServiceRole ポリシー/AWS Glue Service Role 管理ポリシー**: AWS Glue サービスに必要な権限を付与するロールポリシー
- **AWS CloudHSM/AWS CloudHSM クラスター**: ハードウェアセキュリティモジュールを提供するサービス
- **AWS KMS キー**: データ暗号化のためのキー管理サービス
- **サーバー側の暗号化(SSE-KMS)/SSE-KMS**: AWS KMS でマネージドされたキーを使用した S3 暗号化
- **サーバー側の暗号化(SSE-C)/SSE-C**: お客様が提供したキーを使用した S3 暗号化
- **サーバー側の暗号化(SSE-S3)**: S3 マネージドキーを使用した S3 暗号化
- **Amazon S3 マネージドキー**: S3 が管理する暗号化キー
- **AWS CloudTrail**: AWS リソースに対する操作の記録と監査を行うサービス
- **DSSE-KMS**: 二重暗号化を提供する S3 暗号化オプション
- **Amazon GuardDuty**: 悪意のあるアクティビティや不正行為を検出するサービス
- **s3:GetObjectAcl 権限**: S3 オブジェクトのアクセス制御リストを取得する権限
- **Amazon Sage Maker Full Access 管理ポリシー**: SageMaker へのフルアクセスを提供するポリシー
- **sts:AssumeRole**: 別の IAM ロールを引き受ける権限
- **sts:AddAssociation**: リソースへの関連付けを追加する権限
- **AccessDeniedExcepiton**: アクセス拒否例外
- **AWS Certificate Manager/Privacy Enhanced Mail(PEM)**: SSL/TLS 証明書の管理サービス
- **AWS Outposts**: AWS インフラをオンプレミスで実行するサービス

## データレイク＆ガバナンス

- **AWS Lake Formation**: データレイクの設定、セキュリティ、管理を簡素化するサービス
- **Apache Ranger**: Hadoop エコシステムのセキュリティ管理ツール
- **個人を特定できる情報(PII)**: 個人を識別できる情報
- **Access Analyzer for S3**: S3 バケットのアクセス分析ツール
- **AWS Schema Conversion Tool**: データベーススキーマを変換するツール
- **コンプライアンスモード**: 厳格なコンプライアンス要件に準拠したモード
- **ガバナンスモード**: 柔軟なデータガバナンスモード
- **Amazon Macie/Amazon Macie 検出ジョブ**: 機密データを自動的に検出して保護するサービス
- **AWS Resource Access Manager**: AWS リソースの共有を管理するサービス
