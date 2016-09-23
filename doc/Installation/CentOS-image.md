source: Installation/CentOS-image.md
> NOTE: このイメージをデプロイした後、全てのパスワードを変更して頂くことを強く勧めます!!

> NOTE: 上記の注意事項を繰り返し読んで下さい!

CentOS 7上にlibrenmsの環境を構築したイメージをダウンロードできるように準備しました。イメージの詳細は以下の通りです:

イメージはVirtualBoxを用いて構築した。a vmdk is provided along with an ova which was exported using OFV 1.0 version. 
これらはVMWare Fusion、Workstation、PlayerおよびVirtualBoxでの動作を確認しています。

Any issues with these images should be reported via [Github](https://github.com/librenms/librenms/issues) or our IRC channel ##librenms on the Freenode network.

#### Setup

  - UK Keyboard
  - Etc/UTC Timezone
  - 4 Poller Wrapper threads

#### ソフトウェア

  - PHP 7
  - MariaDB
  - Syslog-ng

### Features

  - Oxidized install but not configured
  - Weathermap plugin enabled
  - Billing enabled
  - RRDCached enabled
  - Service checks enabled
  - Syslog enabled

#### ダウンロード

[OVA Image](http://www.lathwood.co.uk/librenms/librenms_centos_7.ova) - 1.1G

  - md5sum: 53f0c06c26255e859144e471ae85eedc

  - sha256sum: 9d902e8452ec8f88ab96180b46113ab5c8ef9213b16cebbbf3f88df37670ebd4

[VMDK Image](http://www.lathwood.co.uk/librenms/librenms_centos_7.vmdk) - 2.8G

  - md5sum: 8c54cb929ba9e16bc9a985a292b8f9d9

  - sha256sum: 944d1164f0664334fdb50e425049819a18da5568c56b6b49681a9ebe13ae9489

#### 認証情報

> SSHパスワードの2文字目は「大文字のI(アイ)」であることに注意して下さい。

  - SSH
    - username: librenms
    - password: `CIne3fwdfds`

> SSHパスワードの2文字目は「大文字のI(アイ)」であることに注意して下さい。

  - MySQL/MariaDB
    - username: root
    - password: `NIfceu3fqfd`

    - username: librenms
    - password: `D42nf23rewD`

  - WebUI
    - username: librenms
    - password: `D32fwefwef`
