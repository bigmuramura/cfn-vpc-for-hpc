# HPC 用の VPC 設定

- NAT Gateway 起動・停止（作成・削除）の切り替えパラメータ付き
- S3 VPC エンドポイント Gateway 型を作成

リソース名に付与するプレフィックは以下の項目を要変更

```
Mappings:
  Constant:
    EnvName:
      ProjectName: hpc
      Environment: dev
```

作成されるリソース名の例:

- hpc-dev-vpc
- hpc-dev-public-rtb1
- hpc-dev-public-nacl1