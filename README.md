プロジェクトの概要
　cloudformationを使用して下記のAWSインフラストラクチャーを実装した上、
CloudWatchアラートで運用監視の環境を構築しました。
　・VPC（Subnet、RouteTable,InternetGatewayなどを含む）
　・EC2（EC2のセキュリティグループなどを含む）
　・RDS（RDSのセキュリティグループ、インバウンドルールなどを含む）
　・ALB（ターゲットグループ、ALBのリスナーなどを含む）
　・CloudWatch（メトリクス、アラーム）
　・WAF（WebACL、WEB ACLをALBに関連付け）
