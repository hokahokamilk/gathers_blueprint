config/db.ts や config/auth.ts の中で、Secrets Manager / SSM から値を取得する

目的: 環境ごとの設定や定数をまとめる場所

値そのものは AWS Secrets / SSM に置きますが、どの値をどの環境で使うかを決める処理 は config フォルダに残す