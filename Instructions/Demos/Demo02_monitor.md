---
demo:
  title: 'デモ 02: Azure の Linux 仮想マシンの監視'
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# デモ 02: Azure の Linux 仮想マシンの監視

## 資格情報のタスク

+ 仮想マシン (クイックスタート テンプレート) を作成します。
+ VM Insights を構成します。
+ アラートを作成します。  
+ パフォーマンスの問題を特定します。 
+ 仮想マシンのサイズを変更します。 

## リソース要件

+ Linux 仮想マシン (カスタム テンプレートを使って作成)

## 参照スライド 

+ Azure リソース マネージャーのテンプレート
+ Azure Monitor の主な機能
+ Azure Monitor のコンポーネント
+ メトリックとログ

  
## 参照ステップ

詳細な手順については、次のリンクを参照してください。

+ [Deploy a simple Ubuntu Linux VM](https://learn.microsoft.com/azure/virtual-machines/linux/quick-create-template)
+ [Azure Monitor エージェント用に VM insights を有効にする](https://learn.microsoft.com/azure/azure-monitor/vm/vminsights-enable-portal#enable-vm-insights-for-azure-monitor-agent) 
+ [チュートリアル: Azure リソースのメトリック アラートを作成する](https://learn.microsoft.com/azure/azure-monitor/alerts/alerts-create-metric-alert-rule)


## 参照スライド (省略可能)

追加のコンテキストには、これらのスライドを使用します。



## ディスカッション ポイント

1. 単純な Linux Ubuntu マシンに**カスタム テンプレートをデプロイする**を使用します。 これは、受講生が演習で VM を作成する方法です。 テンプレートの使用について説明します。 

1. VM Insights を有効にします。 データ収集ルールを使用する方法と、Log Analytics ワークスペースを選択する方法を確認します。 

1. メトリックのアラート ルールを作成します。 たとえば、CPU 使用率に基づいて新しいアラート ルールを作成します。

1. アクション グループの使用方法と、アクション グループをアラートに割り当てる方法について説明します。 

1. アラートがトリガーされたときに監視する方法を確認します。

1. リソース テンプレートをエクスポートする方法で閉じます。 
