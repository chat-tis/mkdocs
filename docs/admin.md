

管理者は名前の上にマークがつきます。  
![Screenshot](img/admin2.jpg)  

[ブラウザ版の全体メニュー](pc_menu.md#_1)の[ユーザー一覧](#_1)画面で、管理者ロール・ユーザー権限・初期化の設定ができます。    

## <ユーザー一覧画面>  
![Screenshot](img/admin1.jpg)  

### ①管理者ロール

以下、6つの内から1つだけ管理者ロールを選択することができます。  

#### 1.システム管理者
Chatisのシステム全体の管理者となり、以下の2.～6.すべての権限を持ちます。  
!!! Note
    TIS所属の一部ユーザーにのみ付与されています  

#### 2.施設管理者
- [ブラウザ版の全体メニュー](pc_menu.md#_1)から、自施設**＋**子施設の[部屋一覧](pc_group.md#_2)画面、[ユーザー一覧](user.md)画面、[安否確認](anpi.md)画面を表示できます。  

- [ユーザー一覧](user.md)画面で、他のユーザーの管理者ロールを変更することができます。(管理者を増やすことができます)  

- [お知らせ](notice.md#_2)を作成することができます。  

!!! Note
    グループの作成・削除・ユーザー追加、ユーザーのパスワード初期化・ユーザー権限付与・管理者ロール変更、安否確認の作成・集計・分析、お知らせの作成ができるようになります

!!! Info
    施設の情報システムご担当者には最初からこの権限が付与されています

#### 3.施設横断部屋

- [ブラウザ版の全体メニュー](pc_menu.md#_1)から、全施設の[部屋一覧](pc_group.md#_2)画面を表示できます。  

!!! Tip
    他施設のユーザーを含んだグループの作成・削除・ユーザー追加ができるため、施設を横断した部会や、委員会のグループを作成するときにご利用ください  

#### 4.部屋

- [ブラウザ版の全体メニュー](pc_menu.md#_1)から、自施設**＋**子施設の[部屋一覧](pc_group.md#_2)画面を表示できます。  

!!! Note
    グループの作成・削除・ユーザー追加ができるようになります

#### 5.ユーザー

- [ブラウザ版の全体メニュー](pc_menu.md#_1)から、自施設**＋**子施設の[ユーザー一覧](user.md)画面を表示できます。  

!!! Note
    ユーザーのパスワード初期化・ユーザー権限付与ができるようになります

#### 6.部屋・ユーザー

- [ブラウザ版の全体メニュー](pc_menu.md#_1)から、自施設**＋**子施設の[部屋一覧](pc_group.md#_2)画面、[ユーザー一覧](user.md)画面を表示できます。  

!!! Note
    グループの作成・削除・ユーザー追加、ユーザーのパスワード初期化・ユーザー権限付与ができるようになります

### ②ユーザー権限

以下、6つの内からユーザー権限を複数選択することができます。

#### 1.WEB給与
[スマホ版のメニュー](admin.md#_6_)から、[WEB給与](salary.md)を閲覧できます。  
#### 2.健診結果(PHR)
[スマホ版のメニュー](admin.md#_6_)から、[健康診断結果](phr.md)を閲覧できます。  
#### 3.ログイン可
<!--デフォルトではチェックが付いている？ 2022.9.8 emura-->
チェックを外したユーザーはログイン画面に強制的に遷移します。  
#### 4.VIP
VIP職員には、一般職員(非VIP)からのコンタクト(チャット)ができないようになります。  
VIP職員→一般職員(非VIP)へのコンタクトは可能です。  
#### 5.安否
[安否確認](anpi.md)の作成・分析画面を表示できます。  
#### 6.日報
[スマホ版のメニュー](admin.md#_6_)から、[日報](nipo.md)を閲覧できます。  

### ③設定

#### 1.パスワード初期化
[パスワードを初期化](password.md)することができます。  
#### 2.QRコード印刷
スマホ版Chatisインストールに必要なQRコードやログイン情報が記載された[Chatisインストール用QRコード](install.md#_1)を印刷することができます。
#### 3.ロック解除
アカウントロックを解除することができます。   
!!! Warning
    ログイン時に10回パスワードを間違えた場合はアカウントがロックされます。  
#### 4.引換コード変更
「Chatisインストール用QRコード」 内のiOS用[QRコードを初期化](ioscode.md)することができます。  
#### 5.電話番号初期化
アカウント認証時に設定した電話番号を初期化することができます。  
機種変更で電話番号が変更になった場合にご利用ください。  
!!! Warning
    このボタンで[アカウント認証](sms.md)が解除され、[WEB給与明細](salary.md)などの個人に紐付くサービスが使用できなくなります。  
#### 6.名前変更
通常、ユーザー本人のみ変更できる名前を管理者でも変更できます。  
#### 7.退職
退職扱い(ユーザー削除)にすることができます。  
間違って退職扱いにした場合は[システム管理者](#1_1)までお問い合わせ下さい。  
!!! Warning
    退職扱いのユーザーはユーザー一覧に表示されず、チャットもご利用できなくなります。  