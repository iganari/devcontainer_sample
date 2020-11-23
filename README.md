# devcontainer_sample

## dev container を設定していく (Getting started)

https://code.visualstudio.com/docs/remote/containers#_installation

+ ホストマシンに Docker をいれておく
  + 例: Docker Desktop for Windows/Mac.
+ VS Code の拡張機能 Remote Development を入れておく
+ git コマンドでこの Repository を開く
+ VS Code でこのディレクトリを開く
+ Remote Container でこのディレクトリを開く
+ VS Code の Terminal で gcloud コマンドなどが実行できればOK


## 初期から構築したい場合

---> 別記事

## この Repo の改修点

+ Dockerfile
  + gcloud コマンドや Terraform コマンドなど
+ devcontainer.json
  + Host の SSH の設定を引き継ぐため
  + mount の部分にホストの .ssh を入れる
  + gitconfig も引き継ぐ
+ root で起動する
  + mount のせい(root以外でマウントできない)

## 参考URL

Developing inside a Container
https://code.visualstudio.com/docs/remote/containers




#vscodejp