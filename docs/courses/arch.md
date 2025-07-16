# Architecting on AWS

## 追加資料

-  [ホワイトボード資料(PDF)](https://d38j18cshs86vq.cloudfront.net/Appendix_Arch.pdf)
-  [ディスカッション資料(PDF)](https://d38j18cshs86vq.cloudfront.net/Appendix_Arch_GD.pdf)
   <!-- - [ディスカッション資料(PPTX)](https://d38j18cshs86vq.cloudfront.net/Temp/Arch_GD_0516.pptx) -->
   <!-- - [ディスカッションサンプル(PDF)](https://d38j18cshs86vq.cloudfront.net/Temp/Arch_GD_Example.pdf) -->

## グループディスカッション

-  コース中にグループディスカッションを行います
   -  マイクとカメラの使える環境の準備をお願いします
-  以下の Google Slide にアクセスできるかご確認ください
   -  [サンプル Google Slide](https://docs.google.com/presentation/d/1teOZTSorFLgsIENdOp_rhYPYI6_PAMkfvLZeWr7883Y/edit?usp=sharing)
   -  グループ分けの参考にさせていただくためで、アクセスできなくても問題ありません

## モジュール

### モジュール 1

-  [クラウド (クラウドサービス) とは？](https://aws.amazon.com/jp/cloud/)
-  [AWS の クラウドが選ばれる 10 の理由](https://aws.amazon.com/jp/aws-ten-reasons/)
-  [AWS の製品・サービス一覧](https://aws.amazon.com/jp/products/)
-  [AWS のドキュメント](https://docs.aws.amazon.com/ja_jp/index.html)

-  [AWS のデータセンター](https://aws.amazon.com/jp/compliance/data-center/data-centers/)
-  [AWS グローバルインフラストラクチャ](https://aws.amazon.com/jp/about-aws/global-infrastructure/)
-  [AWS Well-Architected](https://aws.amazon.com/jp/architecture/well-architected/)
-  [AWS Well-Architected Framework](https://wa.aws.amazon.com/)
-  [API とは - API ビギナーズガイド - AWS](https://aws.amazon.com/jp/what-is/api/)

### モジュール 2

-  [責任共有モデル | AWS](https://aws.amazon.com/jp/compliance/shared-responsibility-model/)
-  [責任共有モデルとは何か、を改めて考える | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/rethinksharedresponsibility/)
-  [AWS アカウント ルートユーザーの認証情報と IAM ユーザーの認証情報](https://docs.aws.amazon.com/ja_jp/general/latest/gr/root-vs-iam.html)
-  [AWS CLI 経由で MFA を使用してアクセスを認証する](https://aws.amazon.com/jp/premiumsupport/knowledge-center/authenticate-mfa-cli/)
-  [ポリシーの評価論理](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/reference_policies_evaluation-logic.html)
-  最小権限実現への 4 ステップアプローチ [前編](https://aws.amazon.com/jp/blogs/news/systematic-approach-for-least-privileges-jp/) / [後編](https://aws.amazon.com/jp/blogs/news/systematic-approach-for-least-privileges-jp2/)
-  [IAM の一時的な認証情報](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/id_credentials_temp.html)
-  [Organizations 導入事例: TVer](https://aws.amazon.com/jp/solutions/case-studies/tver-case-study/?did=cr_card&trk=cr_card)
-  [AWS SSO を図解してみた](https://dev.classmethod.jp/articles/aws-sso-wakewakame/)
-  [AWS マルチアカウント管理を実現するベストプラクティスとは ?](https://aws.amazon.com/jp/builders-flash/202007/multi-accounts-best-practice/)
-  [【実録】アクセスキー流出、攻撃者のとった行動とその対策 | DevelopersIO](https://dev.classmethod.jp/articles/accesskey-leak/)

### モジュール 3

-  [Networking & Content Delivery - サービス別資料](https://aws.amazon.com/jp/aws-jp-introduction/aws-jp-webinar-service-cut/#networking)
-  [AWS-08 パケットの気持ちになって辿る Amazon VPC のルーティング](https://resources.awscloud.com/aws-summit-online-japan-2020-on-demand-aws-sessions-2-45123/aws-08-aws-summit-online-japan-2020-720p)
-  [ネットワークの勉強方法を聞いてみた。 | AWS](https://aws.amazon.com/jp/builders-flash/202106/way-to-learn-network/?awsf.filter-name=*all)

### モジュール 4

-  [クラウドコンピューティング製品 | AWS](https://aws.amazon.com/jp/products/compute/)
-  [インスタンスタイプ](https://aws.amazon.com/jp/ec2/instance-types/)
-  [インスタンス購入オプション](https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/instance-purchasing-options.html)
-  [リザーブドインスタンス（RI）- Amazon EC2 | AWS](https://aws.amazon.com/jp/ec2/pricing/reserved-instances/)
-  [Compute Savings Plans とリザーブドインスタンスの比較表](https://docs.aws.amazon.com/ja_jp/savingsplans/latest/userguide/sp-ris.html)
-  [Savings Plans とは？ | Amazon EC2 ことはじめ](https://d1.awsstatic.com/events/jp/2021/summit-online/AWS-13_AWS_Summit_Online_2021_CMP01.pdf#page=25)
-  [Amazon EC2 だけじゃない︕最⾼のコスト効率を⼿に⼊れるためのスポットインスタンス使いこなし術](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-27_AWS_Summit_Online_2020_CMP01.pdf)
-  [スポットインスタンス導入事例: 株式会社コミックス・ウェーブ・フィルム](https://aws.amazon.com/jp/solutions/case-studies/comix-wave-film/?did=cr_card&trk=cr_card)
-  [購入オプション導入事例：株式会社ナビタイムジャパン | AWS](https://aws.amazon.com/jp/solutions/case-studies/navitime-2020/)
-  [株式会社ディー・エヌ・エー様における EC2 スポットインスタンスの大規模活用のための工夫とコンテナ技術を用いた設計例の紹介](https://aws.amazon.com/jp/blogs/news/how-dena-succesfully-applied-ec2-spot-on-production-and-reference-architecture-using-containers/)
-  [Amazon EBS ボリュームの種類](https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/ebs-volume-types.html)
-  [HPC 導入事例：塩野義製薬株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/shionogi/)
-  [サーバーレスコンピューティング | AWS](https://aws.amazon.com/jp/serverless/)

### モジュール 5

-  [AWS が提供するクラウドストレージサービス](https://aws.amazon.com/jp/products/storage/)
-  [S3 導入事例：株式会社テレビ東京](https://aws.amazon.com/jp/solutions/case-studies/tv-tokyo/)
-  [Amazon S3 ストレージクラス](https://aws.amazon.com/jp/s3/storage-classes/)
-  [Amazon S3 Transfer Acceleration Speed Comparison](http://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html)
-  [S3+Lambda 導入事例：株式会社スクウェア・エニックス](https://aws.amazon.com/jp/solutions/case-studies/square-enix/)
-  [Snowball 導入事例：KDDI 株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/kddi_2022/)
-  [AWS 認定インストラクターと学ぶストレージの基本 - builders.flash](https://aws.amazon.com/jp/builders-flash/202411/learn-aws-storage-basic/)
-  [AWS ファイルストレージサービスの選び方 | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/choose-filestorageservice/)

### モジュール 6

-  [AWS が提供するクラウドデータベース](https://aws.amazon.com/jp/products/databases/)
-  [NoSQL とは?（NoSQL データベースの解説と SQL との比較）| AWS](https://aws.amazon.com/jp/nosql/)
-  [今⽇からはじめる!AWS のデータベースと最適なサービスの選び⽅](https://d1.awsstatic.com/events/jp/2021/summit-online/AWS-10_AWS_Summit_Online_2021_DAT01.pdf)
-  [Amazon.com におけるデータベース移⾏事例](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-30_AWS_Summit_Online_2020_DAT02.pdf)
-  [AWS を活用した 2023 年のプライムデー – 数字が示す驚異的なメトリクス | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/prime-day-2023-powered-by-aws-all-the-numbers/)
-  [RDS 導入事例：ビジネスエンジニアリング株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/b-en-g/)
-  [Aurora 導入事例：任天堂株式会社、株式会社ディー・エヌ・エー | AWS](https://aws.amazon.com/jp/solutions/case-studies/nintendo-dena-2020/)
-  [Amazon Aurora Global Database の使用 - Amazon Aurora](https://docs.aws.amazon.com/ja_jp/AmazonRDS/latest/AuroraUserGuide/aurora-global-database.html)
-  [Amazon Aurora Global Database をリージョン間でフェイルオーバーさせてみた | DevelopersIO](https://dev.classmethod.jp/articles/amazon-aurora-global-database-failover-between-region/)
-  [論理レプリケーションと物理レプリケーション](https://pages.awscloud.com/rs/112-TZM-766/images/20200929_BlackBelt_HowToScale_Aurora_MySQL_pub.pdf#page=53)
-  [メモリ内キー値ストアとは？ | AWS](https://aws.amazon.com/jp/nosql/key-value/)
-  [Amazon DynamoDB がニーズに合うかどうかを判断し、移行を計画する方法 | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/how-to-determine-if-amazon-dynamodb-is-appropriate-for-your-needs-and-then-plan-your-migration/)
-  [Amazon DynamoDB スケーリングのベストプラクティス | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/dynamodb-scaling-best-practice/)
-  [Amazon DynamoDB Auto Scaling: 規模を問わないパフォーマンスとコストの最適化 | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/amazon-dynamodb-auto-scaling-performance-and-cost-optimization-at-any-scale/)
-  [DynamoDB 導入事例：グリー株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/gree-ddb/)
-  [データウェアハウス (DWH) とは? | AWS](https://aws.amazon.com/jp/data-warehouse/)
-  [列指向データベースとは？ | AWS](https://aws.amazon.com/jp/nosql/columnar/)
-  [Black Belt: Amazon Redshift](https://d1.awsstatic.com/webinars/jp/pdf/services/20200318_AWS_BlackBelt_Redshift.pdf)
-  [Redshift 導入事例：全日本空輸株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/ana/)
-  [キャッシュとは？ | アマゾン ウェブ サービス (AWS)](https://aws.amazon.com/jp/caching/)
-  [Redis と Memcached | AWS](https://aws.amazon.com/jp/elasticache/redis-vs-memcached/?nc=sn&loc=3&dn=3)
-  [キャッシングの課題と戦略](https://aws.amazon.com/jp/builders-library/caching-challenges-and-strategies/)
-  [インメモリデータベースとは何ですか?](https://aws.amazon.com/jp/nosql/in-memory/)
-  [ElastiCache 導入事例：ワンダープラネット株式会社](https://aws.amazon.com/jp/solutions/case-studies/wonder-planet-case-study/?did=cr_card&trk=cr_card)
-  [Autora & DynamoDB & ElastiCache 導入事例：The Pokemon Company](https://aws.amazon.com/jp/solutions/case-studies/the-pokemon-company-case-study/)
-  [DMS 導入事例：株式会社出前館 | AWS](https://aws.amazon.com/jp/solutions/case-studies/demaecan/)
-  [DMS+SCT 導入事例:住信 SBI ネット銀行](https://cloud.watch.impress.co.jp/docs/news/1173107.html)
-  [Amazon Aurora DSQL の紹介 | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/introducing-amazon-aurora-dsql/)
-  [Aurora DSQL の制約を知ってより理解を深める | DevelopersIO](https://dev.classmethod.jp/articles/aurora-dsql-non-support/)

### モジュール 7

-  [可用性 - 信頼性の柱](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/reliability-pillar/availability.html)
-  [Amazon CloudWatch](https://aws.amazon.com/jp/cloudwatch/)
-  [AWS CloudTrail](https://aws.amazon.com/jp/cloudtrail/)
-  [製品の比較 - Elastic Load Balancing | AWS](https://aws.amazon.com/jp/elasticloadbalancing/features/)
-  [AutoScaling 導入事例：スマートニュース株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/smartnews/)

### モジュール 8

-  [クラウドソリューション | AWS](https://aws.amazon.com/jp/solutions/)
-  [AWS クイックスタート | AWS](https://aws.amazon.com/jp/quickstart/)
-  [AWS で始める Infrastructure as Code](https://d1.awsstatic.com/events/jp/2021/summit-online/AWS-31_AWS_Summit_Online_2021_MAD05.pdf)
-  [CloudFormation 導入事例：本田技研工業株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/honda/)
-  [AWS での管理とガバナンス – アマゾン ウェブ サービス](https://aws.amazon.com/jp/products/management-tools/)

### モジュール 9

-  [マイクロサービスの概要 | AWS](https://aws.amazon.com/jp/microservices/)
-  [スタートアップのためのマイクロサービス入門 | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/techblog-microservices-introduction/)
-  [マイクロサービス 導入事例：PayPay 株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/paypay/)
-  [5 年間の AWS 利用動向について国内最大級の請求代行サービスの登録アカウントから調査〜技術トレンド、コロナ禍によって急速に伸びたサービスを分析〜](https://classmethod.jp/news/20211125-aws-user-report/)
-  [コンテナ - ユースケース別クラウドソリューション | AWS](https://aws.amazon.com/jp/containers/)
-  [Docker とは | AWS](https://aws.amazon.com/jp/docker/)
-  [ECS 導入事例: ベースフード株式会社](https://aws.amazon.com/jp/solutions/case-studies/basefood-aws-is-how/)
-  [EKS 導入事例：株式会社フロム・ソフトウェア](https://aws.amazon.com/jp/solutions/case-studies/fromsoftware/)
-  [スタートアップのためのコンテナ入門 – 導入編 | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/techblog-container-introduction/)
-  [スタートアップのためのコンテナ入門 – AWS Fargate 編 | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/techblog-container-fargate-1/)
-  [スタートアップのためのコンテナ入門 – Kubernetes 編 | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/techblog-container-k8s-1/)
-  [メルカリのコンテナアーキテクチャを公開！ 利便性の高いアプリを実現する AWS 活用法 | AWS Startup ブログ](https://aws.amazon.com/jp/blogs/startup/event-report-aws-container-talk-with-mercari/)

### モジュール 10

-  [プライベートネットワーク経由で AWS S3 にアクセスする 7 つのアーキテクチャの紹介](https://dev.classmethod.jp/articles/how_to_private_connect_s3/)
-  [VPC エンドポイント - Amazon Virtual Private Cloud](https://docs.aws.amazon.com/ja_jp/vpc/latest/privatelink/vpc-endpoints.html)
-  [接続: よくある質問 - Amazon VPC | AWS](https://aws.amazon.com/jp/vpc/faqs/#Connectivity)
-  [Amazon S3 用の AWS PrivateLink - Amazon Simple Storage Service](https://docs.aws.amazon.com/ja_jp/AmazonS3/latest/userguide/privatelink-interface-endpoints.html#types-of-vpc-endpoints-for-s3)
-  [パートナー - AWS Direct Connect | AWS](https://aws.amazon.com/jp/directconnect/partners/?partner-solutions-cards.sort-by=item.additionalFields.partnerNameLower&partner-solutions-cards.sort-order=asc&awsf.partner-solutions-filter-location=*all)
-  [VPN 導入事例：コクヨ株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/kokuyo-serverworks/)

### モジュール 11

-  [サーバーレスコンピューティング - ユースケース別クラウドソリューション | AWS](https://aws.amazon.com/jp/serverless/)
-  [サーバーレスを始めよう](https://aws.amazon.com/jp/serverless/patterns/start-serverless/)
-  [サーバーレスパターン](https://aws.amazon.com/jp/serverless/patterns/serverless-pattern/)
-  [サーバーレスの効果とは?](https://aws.amazon.com/jp/serverless/patterns/serverless-benefit/)
-  [サーバーレスの勉強方法を聞いてみた。 | AWS](https://aws.amazon.com/jp/builders-flash/202101/way-to-learn-serverless/)
-  [Lambda 導入事例：株式会社スクウェア・エニックス](https://aws.amazon.com/jp/solutions/case-studies/square-enix/)
-  [サーバーレス 導入事例：ライフネット生命保険株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/lifenet-insurance-ncdc/)
-  [サーバーレス 導入事例: 株式会社大創産業](https://aws.amazon.com/jp/solutions/case-studies/daiso-case-study/?did=cr_card&trk=cr_card)
-  [技術用語を比喩から学ぼう ! - 第 1 回「疎結合」](https://aws.amazon.com/jp/builders-flash/202003/metaphor-loose-coupling/?awsf.filter-name=*all)
-  [技術用語を比喩から学ぼう ! - 第 2 回「パブサブ」](https://aws.amazon.com/jp/builders-flash/202004/metaphor-pubsub/?awsf.filter-name=*all)
-  [Kinesis 導入事例：株式会社 Gunosy | AWS](https://aws.amazon.com/jp/solutions/case-studies/gunosy/)
-  [Kinesis 導入事例：株式会社フロム・ソフトウェア | AWS](https://aws.amazon.com/jp/solutions/case-studies/fromsoftware/)
-  [Q: Amazon Kinesis Data Streams および Amazon SQS はそれぞれどのような場合に使用しますか?](https://aws.amazon.com/jp/kinesis/data-streams/faqs/)
-  [Step Functions 導入事例：Liberty Mutual 保険](https://aws.amazon.com/jp/solutions/case-studies/liberty-mutual-case-study/)

### モジュール 12

-  [グローバルエッジネットワーク | AWS](https://aws.amazon.com/jp/cloudfront/features/#Global_Edge_Network)
-  [キャッシュとは？ | アマゾン ウェブ サービス (AWS)](https://aws.amazon.com/jp/caching/)
-  [CloudFront がコンテンツを配信する方法 - Amazon CloudFront](https://docs.aws.amazon.com/ja_jp/AmazonCloudFront/latest/DeveloperGuide/HowCloudFrontWorks.html)
-  [CloudFront 導入事例: 株式会社資生堂 | AWS](https://aws.amazon.com/jp/solutions/case-studies/shiseido/)
-  [AWS Shield 脅威ランドスケープレビュー : 2020 年の振り返り | Amazon Web Services ブログ](https://aws.amazon.com/jp/blogs/news/aws-shield-threat-landscape-review-2020-year-in-review/)
-  [Amazon S3 オリジンへのアクセスの制限 - Amazon CloudFront](https://docs.aws.amazon.com/ja_jp/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html)
-  [Amazon CloudFront 用の AWS マネージドプレフィックスリストを使用したオリジンへのアクセス制限](https://aws.amazon.com/jp/blogs/news/limit-access-to-your-origins-using-the-aws-managed-prefix-list-for-amazon-cloudfront/)
-  [Edge Services を利用した DDoS 防御の構成（AWS WAF/Shield）](https://pages.awscloud.com/rs/112-TZM-766/images/B1-03.pdf)
-  [AWS Outposts（AWS サービスをオンプレミス環境で実行）| AWS](https://aws.amazon.com/jp/outposts/)
-  [Outpost 導入事例: Riot Games が AWS を利用してゲームを改善](https://aws.amazon.com/jp/solutions/case-studies/riot-games-reinvent/)

### モジュール 13

-  [災害対策 (DR) を計画する - 信頼性の柱](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/reliability-pillar/plan-for-disaster-recovery-dr.html)
-  [マルチリージョン、ちょっとその前に…- サービスの可⽤性について考える](https://d1.awsstatic.com/events/jp/2021/summit-online/AWS-53_AWS_Summit_Online_2021_Thinking-about-Availability.pdf)
-  [AWS でのディザスタリカバリ (DR) アーキテクチャ、パート I：クラウドでのリカバリの戦略](https://aws.amazon.com/jp/blogs/news/disaster-recovery-dr-architecture-on-aws-part-1-strategies-for-recovery-in-the-cloud/)
-  [マルチリージョン導入事例：東京海上日動火災保険株式会社 | AWS](https://aws.amazon.com/jp/solutions/case-studies/tokiomarine-nichido/)

## ラボ

--8<-- "lab.md"

### ラボ 1

#### 目標

-  AWS のメリットを確認する
-  AWS の操作に慣れる

#### 注意点

-  タスク 1 はスキップしてください

#### 時間の余った方向け追加課題

-  AWS の操作方法の特徴をおさえ、使い分けを考えてみてください
   -  AWS のインフラを構築するには、他にも SDK といった選択肢があります
   -  ヒント: 管理コスト, 一貫性, 再現性

### ラボ 2

#### 目標

-  AWS のネットワークインフラを確認する
   -  VPC, サブネット, ルートテーブル, IGW, NAT
-  EC2 インスタンスを起動し、セキュアに接続する
   -  参考: [セッションマネージャー | BlackBelt](https://pages.awscloud.com/rs/112-TZM-766/images/20200212_AWSBlackBelt_SystemsManager_0214.pdf#page=60)

#### 注意点

-  タスク 9 までを目標に進めてください
   -  タスク 10 以降はオプションとします

#### 時間の余った方向け追加課題

-  オプションタスクに取り組んでください
-  VPC の作成ウィザードで「VPC のみ」ではなく「VPC など」のオプションを使って作成してみましょう
   -  [タスク 4 までをスキップする⼿順](https://d38j18cshs86vq.cloudfront.net/lab2.pdf)
-  構築したリソースを紙とペンで描いてみましょう

### ラボ 3

#### 目標

-  アプリケーションに RDS を追加する
-  マネージドデータベースの管理レイヤーを確認する

#### 時間の余った方向け追加課題

-  オプションタスクに取り組んでください
-  複数のインスタンス間で DB 認証情報をどのように共有するのか考えましょう

### ラボ 4

#### 目標

-  アプリケーションを高可用な構成にする

#### 時間の余った方向け追加課題

-  どういった観点で可用性が確保できたか考えてください
-  ルートテーブルを新たに追加した理由はなんですか？

### ラボ 5

#### 目標

-  サーバーレスアプリケーションを構築する
-  EC2 アプリケーションとサーバーレスの違いを考える

#### 時間の余った方向け追加課題

-  オプションタスクに取り組んでください
-  EC2 アプリケーションとサーバーレスアプリケーションを比較してみましょう
   -  管理コスト, 自由度, 開発工数, クォータ など...

### ラボ 6

#### 目標

-  エッジを活用したアプリケーションを構築する
-  (オプション) リージョン間フェイルオーバーを設定する

#### 時間の余った方向け追加課題

-  オプションタスクに取り組んでください
-  DestinationBucket をプライベートに戻し、CloudFront でリージョン間フェイルオーバーする方法を考えましょう
   -  適当な画像を DestinationBucket にのみアップロードして動作を確認しましょう
-  ユーザーが ELB に直接アクセスできない設定を考えてみましょう
