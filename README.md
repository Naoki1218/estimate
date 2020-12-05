バージョン情報  
Ruby 2.6.5  
Rails 5.2.4.4  
PostgreSQL 13.1  
-------------------------------------------------------------------------------

概要
・見積書を簡単に作成するアプリケーションです。  
・管理者権限があれば各部署で従業員登録、製品登録、クライアント登録、在庫管理などができます。  
・タイピングミスによる作り直し、クレームが無くなります。  
・紙での記録保存が減らせます。  

-------------------------------------------------------------------------------
機能一覧  
ログイン機能  

登録・削除・登録情報編集機能（下記管理者のみ可）  
ユーザー登録・削除・登録情報編集機能  
顧客登録・削除・登録情報編集機能  
製品登録・削除・登録情報編集機能  

見積書作成機能（顧客名、数量は記入必須）  
コメント機能（値引理由の記入必須）  
見積書内容修正機能（編集）  

顧客検索機能  
製品検索機能  

PDF出力機能  
-------------------------------------------------------------------------------

設計
-------------------------------------------------------------------------------
[カタログ設計・機能一覧・テーブル設計・ER図・ワイヤーフレーム](https://docs.google.com/spreadsheets/d/1FujtZGR9_B0whramo-mk7RiRKassdA5JuwIrUBpIjaM/edit?usp=sharing)

-------------------------------------------------------------------------------
[画面推移図](https://cacoo.com/diagrams/2HG4sTlmwdHzti0a/EC671)


使用gem
-------------------------------------------------------------------------------
ransack  
Kaminari  
devise  
rails_admin  
cancancan  
grover  
