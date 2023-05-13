---
---
# RDS

## Aurora Cluster (ap-northeast-1)

|DBクラスタ識別子|エンジン|エンジンバージョン|リージョンとAZ|サブネットグループ|パラメータグループ|ライターインスタンス|リーダーインスタンス|ライターエンドポイント|リーダーエンドポイント|
|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
|database-1|aurora-mysql|5.7.mysql_aurora.2.10.3|ap-northeast-1c<br>ap-northeast-1a<br>ap-northeast-1d|rds-ec2-db-subnet-group-1|default.aurora-mysql5.7|database-1-instance-1|testdb<br>database-1-instance-1-ap-northeast-1a|database-1.cluster-cs5yre5qdxto.ap-northeast-1.rds.amazonaws.com|database-1.cluster-ro-cs5yre5qdxto.ap-northeast-1.rds.amazonaws.com|

## Aurora Instance (ap-northeast-1)

|DBクラスタ識別子|DBインスタンス識別子|エンジン|エンジンバージョン|リージョンとAZ|サイズ|サブネットグループ|パラメータグループ|エンドポイント|
|:--|:--|:--|:--|:--|:--|:--|:--|:--|
|database-1|database-1-instance-1|aurora-mysql|5.7.mysql_aurora.2.10.3|ap-northeast-1c|db.r6g.large|rds-ec2-db-subnet-group-1|default.aurora-mysql5.7|database-1-instance-1.cs5yre5qdxto.ap-northeast-1.rds.amazonaws.com|
|database-1|database-1-instance-1-ap-northeast-1a|aurora-mysql|5.7.mysql_aurora.2.10.3|ap-northeast-1a|db.r6g.large|rds-ec2-db-subnet-group-1|default.aurora-mysql5.7|database-1-instance-1-ap-northeast-1a.cs5yre5qdxto.ap-northeast-1.rds.amazonaws.com|
|database-1|testdb|aurora-mysql|5.7.mysql_aurora.2.10.3|ap-northeast-1d|db.r6g.large|rds-ec2-db-subnet-group-1|default.aurora-mysql5.7|testdb.cs5yre5qdxto.ap-northeast-1.rds.amazonaws.com|

