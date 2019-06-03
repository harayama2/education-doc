# progate(Rails)メモ
## キーワード
  - ## 1,2,3講
    - アプリの作成・起動
    - コントローラ
    - ルーティング
    - アクション
    - モデルとテーブル
    - テーブルに保存
    - リンク
    - find_byメソッド
    - params変数
    - 変数展開（#{}）

  - ## 4,5講
    - バリデーション（presence,length,uniqueness）
    - フォームの送信(form_tagメソッド)
    - name属性の追加（連想配列的に扱える）
    - リダイレクト（redirect_to）
    - レンダー
    - サクセスメッセージ（flash変数）
    - エラーメッセージの表示（学習編５講スライド参照）

  - ## 6,7,8講
    - マイグレーションファイルの追加
    - ユーザ登録
    - 画像編集機能（アイコンの変更）
    - パスワード機能
    - ログイン処理
    - session変数（ユーザ情報を保持）

  - ## 9,10,11講

## 知っておいたがよかった事
- ルート　→　コントローラ　→　ビュー　の順で処理を書くと分かり易い
- ファイル構造を軽く把握する（よく使うフォルダに、何をいじれる、どんなファイルがあるのか？）
- 案外エラー文は読むと分かるから、アレルギーを起こさず立ち向かう姿勢は多少必要
- postとgetの違い（DBを書き換えるか・書き換えないか？？）
- webの仕組み（基本的な技術、用語の理解）
  - リクエストとリスポンス
  - クライアントとwebサーバの関係