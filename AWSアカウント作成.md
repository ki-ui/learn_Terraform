### IAM
rootユーザ(IDPWを持つ自分)から発行される子アカウントみたいなもの？  
PWを持たず、rootユーザから付与された権限でアクセス管理される。  

### AWS マネジメントコンソール  
IDとPWが必要な、webからAWSの全機能にアクセスできるサイト  
よって、パスワードを持たないIAMユーザはアクセスできない  

### IAM追加
https://console.aws.amazon.com/iam/home?region=us-east-2#/home  
追加したら**アクセスキー**と**シークレットアクセスキー**が発行された。  
こいつを介して制御を行う。  

### bashrcに記載
export AWS_ACCESS_KEY_ID=HOGEHOGEHOGEHOGEHOGEGHOEGHEO  
export AWS_SECRET_ACCESS_KEY=HOGEHOGEHOGEHOGEHOGEGHOEGHEO  
export AWS_DEFAULT_REGION=ap-northeast-1  
