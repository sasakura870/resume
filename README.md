# 基本情報
+ 氏名 : 笹倉 直哉(ササクラ ナオヤ)
+ Twitter : [@n_sasakura870](https://twitter.com/n_sasakura870)
+ Qiita : [@sasakura_870](https://qiita.com/sasakura_870)
+ Wantedly : https://www.wantedly.com/users/110507727

詳しい略歴に関しては[Wantedly](https://www.wantedly.com/users/110507727)をご覧ください。

# ポートフォリオ
## Asobi
地元のローカルルールや自分で考えた遊びを記録・共有するサービスです。

ユーザーが投稿した遊びを閲覧する事ができ、ログインすれば遊びの投稿、いいね、コメント、ユーザーのフォローができます。

キーワード検索で調べたい単語に関連する遊び、ユーザー、タグが検索できます。

また、投稿された遊びをランダムに一つ表示する「Asobiガチャ」機能を実装しました。

こちらはRuby on Rails + Vue.js + AWSを利用して制作、デプロイしました。

Qiitaに技術的な詳細を記載した記事を書いています。

+ URL : http://www.asobi-app.com/
+ GitHub : https://github.com/sasakura870/asobi
+ Qiita : [就活用ポートフォリオとしてWebサービス「Asobi」を作りました。](https://qiita.com/sasakura_870/items/1eb666c80c4ceb815dd8)

### 主な機能
+ ユーザー登録
+ 遊びの投稿、下書き保存
+ 遊びに対するいいね、コメント
+ 遊びのタグ付け
+ 別のユーザー、タグのフォロー
+ キーワード検索
+ 遊びを1つだけランダムで表示する「Asobiガチャ」

### 使用技術
+ Ruby 2.6.3
+ Ruby on Rails 6.0.0
+ Vue.js 2.6.10
+ AWS
  + VPC
  + EC2
    + Nginx 1.16.1
    + Unicorn 5.5.1
  + Route 53
  + RDS
    + PostgreSQL 11.5
  + S3

# 職務経歴
## 2018年4月 ~ 2019年7月
**某受託開発会社 ソフトウェア開発**

未経験から入社。ソフトウェア開発者として、主に自動車の展示会で出展するHMIの試作機のソフトウェアを開発、テストする業務に携わりました。

### 詳細
#### 2019年6月 ~ 2019年7月
**大手自動車部品メーカー向け/各種デバイス制御ソフトウェアの改修**

##### 概要
展示会で使用されたモックの操作用タブレットGUIソフトウェア、及び送受信データ制御用PCの改修に携わりました。

全2名

##### 担当業務
一部のシステムの送受信データの仕様変更に伴い、操作用タブレットGUIのUDP通信による送受信のデータを改修しました。

既に納品されたソフトウェアの改修のため、ソフトウェア全体の把握を行い変更箇所の特定をしました。その後コードの改修による影響範囲をチームで確認しながら改修、動作確認テストを行いました。

##### 使用技術
+ C#
+ Unity

#### 2019年3月 ~ 2019年5月
**社内向け/ログ再生デスクトップアプリの開発**

##### 概要
ログファイルを読み取り、ログに記述された時間・通信方法・データを再現して指定した送信先に送信するデスクトップアプリの開発を行いました。

全1名

##### 担当業務
アプリの設計、開発、保守全般。

設計、開発、保守、それに伴う技術の選定全般を任されました。機能要件を洗い出し、それに合ったフレームワークの選定や設計を心がけました。

また直感で触れるようなGUIを目指し、ログファイルのドラッグ&ドロップ機能や複数のログファイルの再生も実装しました。

開発後にCAN通信のログファイルの再生機能の追加がありましたが、事前に改修が行いやすいようなプログラミングを心がけていたためスムーズに行う事ができました。

##### 使用技術
- C#
- .NET Framework

#### 2018年11月 ~ 2019年2月
**大手自動車部品メーカー向け/音声認識及び各種デバイス制御ソフトウェア開発**

##### 概要
音声認識による音声の取得とシリアル通信、UDP通信によるデータの送受信、計算処理を行うソフトウェアの開発に携わりました。

全3名

##### 担当業務
.NET Frameworkを使用したフォームアプリの開発を行いました。Unityを使用することもできましたが、GUIは送受信したデータを表示しながら設定を変更するだけの機能だったため軽量な .NET Frameworkを使用しました。

音声認識プログラムの開発のために、C#と相性の良い[Microsoft Speech API(SAPI)](https://docs.microsoft.com/en-us/previous-versions/office/developer/speech-technologies/hh361572(v=office.14)?redirectedfrom=MSDN)を使用しました。認識する言葉によって送信するデータを変更する仕様でしたが、言葉とデータの設定もアプリ内で完結するように実装しました。

また、通信のタイムラグを極力減らすため、コードのリファクタリングを行いました。

##### 使用技術
- C#
- .NET Framework
- Microsoft Speech API(SAPI)

# 資格・認定
|取得年月|資格|
|---|---|
|2020年1月|LPIC-1|


# 運営歴
|開催日|イベント名|
|---|---|
|2020年1月11日|[Ismet中部支部　誰でも歓迎！名古屋もくもく会](https://connpass.com/event/158832/)|
|2020年2月22日|[Ismet中部支部　誰でも歓迎！名古屋もくもく会 #2](https://ismet-chubu.connpass.com/event/163593/)|
