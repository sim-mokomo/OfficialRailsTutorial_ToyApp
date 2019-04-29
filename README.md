# OfficialRailsTutorial_ToyApp

*自分のための見直し用なので、外部の人が見ることを想定していない*

## 大事なこと

- アプリ作成時、まずはモデル構造から作成する。
    - toy_appではまず「User」と「MicroPost」を作成した。

- 関連をもたせたい場合
    - 単数-複数: has_many
    - 単数-単数: belongs_to
    
- ActiveRecord::Baseの継承
    - データベースのカラムをRubyの属性のように扱うことができる
- ActionController:Baseの継承
    - モデルの操作
    - HTTP requestのフィルタリング
    - ViewをHTMLとしての出力