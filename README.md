Ansible playbooks
====

Overview

Ansibleで利用するplaybookのコード  

## Description

Ansibleで利用するplaybookのコード
基本的にLinuxディストリビューションやMacで開発環境を整えたり、  
LinuxサーバにOSSを導入したりするためのコード  
自分で利用するためのものなので、何が起きても自己責任

## Requirement

- Ansible 2.0.x

Ansibleが動作するOS
UNIXベースのOSなら基本的に動作するはず
Windowsでは動作しない模様(Vagrantのprovisioningには利用可能な様子)

## Usage

inventoryファイル：develop
developファイルのIPアドレスをセットアップしたいサーバのIPアドレスに変更し、

```ansible-playbook site.yml -i develop```

## Licence

フリー

ご自由にどうぞ。
ただし、動作保障等は一切ありません。
何が起きても自己責任で解決してください。

## Author

schwarz471