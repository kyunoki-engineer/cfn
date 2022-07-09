# cfnフォルダの概要
Cloudformationテンプレートを作成している。

始めにAWSアカウントにVPCを作成。

その後に各テンプレートを作成。


・VPC-NW.yml

　SubnetやRouteTeble、InternetGateway、NatGatewayなどを構築

・Security.yml

　EC2、RDS、ELBなどのSecurityGroupを構築
  
 ・AppS3bucket.yml
 
 　S3bucketを構築

・EC2-EBS.yml

  EC2、EBSなどの構築
  
・ELB.yml

  ELBの構築
  
・DB.yml

  DBの構築
