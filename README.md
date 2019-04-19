### ◆完成予定:2019年5月末

## 概要
地元のイベントを活性化させるためのサービス

## 機能一覧(2019年4月19日時点)
* イベント投稿/閲覧/編集/削除機能
* イベント分類機能
  (→イベント一覧・自分の投稿したイベント・既に終了したイベント・現在開催中のイベント・これから開催されるイベントの5種類)
* イベント検索機能
  (→イベント名・住所の2種類)
* マップの表示とイベントの開催地のプロット
* 新規登録機能
* ユーザー情報更新機能
* メールアドレスでのログイン機能
* パスワードを忘れた場合のメール送信機能を用いたパスワード再設定機能
* 永続的セッションの導入
* メール送信機能を用いたお問い合わせ機能
* Twitter/Facebook/LinkedInでの共有機能
* ポップアップとカルーセルを使用したアプリのチュートリアル
* 単体テスト/統合テスト(モデルスペック/リクエストスペック/フィーチャースペック)

## 完成までに実装予定(2019年4月19日時点)
* お気に入り機能
* イベント分類機能
  (→お気に入りしたイベント・最近人気のイベントの2種類)
* 自分好みのイベントを探す機能
  (→質問に答えていくと自分に合っているイベントを教えてくれる)
* Twitter/Facebook/GitHubでのログイン機能
* イベントのガントチャート
* イベント検索機能
  (→現在地の位置情報・カレンダー上のイベント開催日程の2種類)
* お問い合わせフォームのスパム対策
  (→reCAPTCHA v3 の導入)
* URL上に記されているuser_idの暗号化
* デザインの修正  
以上に加え、必要な機能を思いつき次第実装

## 使用している技術一覧
### バックエンド
Ruby, Ruby on Rails
### フロントエンド
HTML, CSS, Sass, Semantic UI, JavaScript, jQuery
### テスト
RSpec
### データベース
MySQL
### セッション管理
CookieStore
### API
Map JavaScript API, Geocoding API
### ライブラリ
jQuery, jQuery.cookie.js, slick, Waypoints.js, Animate.css
