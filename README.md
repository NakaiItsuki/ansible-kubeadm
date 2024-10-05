# ansible-kubeadm
## 構成例
以下の構成図の環境で実行することを想定しています。
![sample-cluster](sample-cluster.png)
## 前準備
Ansibleのコードを実行する前に、以下の作業を行う必要があります。
- 各VM（or 物理マシン）の作成
- Ubuntuのインストール
- SSH公開鍵認証の設定
- Ansibleの実行環境の準備
## 実行
```
ansible-playbook -i inventory.yaml -bk deploy.yaml
```
