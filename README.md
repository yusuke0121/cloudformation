![Autoscaling+ALBTemplate構成図](https://user-images.githubusercontent.com/81822861/132930528-d4920826-823d-45b0-a461-9c642e76a409.png)
# cloudformation
YAML template

# 作成template
VPC  
ApplicationLoadBalancer  
EC2Autoscaling  
RDS  

Network,Instance,DBInstanceのクロススタックで構成。

起動テンプレートにapache,mysplをインストールするよう
Userdateで記載。



