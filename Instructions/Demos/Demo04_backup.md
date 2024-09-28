---
demo:
  title: 'デモ 04: Azure Linux 仮想マシンのバックアップ'
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# デモ 04: Azure Linux 仮想マシンのバックアップ

## 資格情報のタスク

+ Azure Backup を構成する 

## リソース要件

+ Linux 仮想マシン

## 参照ステップ

詳細な手順については、このリンクをご覧ください。

+ [クイック スタート: ポータルで仮想マシンをバックアップする](https://learn.microsoft.com/azure/backup/quick-backup-vm-portal)
+ [クイック スタート: Azure portal を使用して ARM テンプレートを作成およびデプロイする](https://learn.microsoft.com/azure/azure-resource-manager/templates/quickstart-create-templates-use-the-portal)

## 参照スライド

追加のコンテキストには、これらのスライドを使用します。  

+ Azure Backup とは
+ 仮想マシンを保護するオプション

## ディスカッション ポイント

1. テンプレートのインポートを確認します。 これは、クラスに VM を作成した 4 番目の方法です。
   
1. Recovery Services コンテナーの必要性について説明します。 コンテナーは、データ ソースと同じリージョンにある必要があります。 

1. ポータルで仮想マシンのバックアップにアクセスして有効にする方法を確認します。 

1. Standard バックアップ ポリシーと拡張バックアップ ポリシーの違いについて説明します。 

1. **datasource の種類**ドロップダウンを使用して、バックアップ センターで保護できるリソースを確認します。

1. 既定のバックアップ ポリシーと、カスタム バックアップ ポリシーを作成できることを示します。

1. 1 つのバックアップ ポリシーをさまざまな仮想マシンで使用する方法について説明します。

1. バックアップ ポリシーの構成設定 (スケジュールと保持期間) を確認します。

1. バックアップ ジョブを監視する方法を確認します。

1. (資格情報ではなく) 仮想マシンを復元する方法を確認します。 
