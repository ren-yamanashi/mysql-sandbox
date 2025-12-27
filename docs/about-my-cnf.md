# my.cnf について

- MySQL サーバーおよび各種 MySQL クライアントプログラムは起動時に my.cnf ファイルから設定情報を読み取る
- ファイルは ini ファイル形式
  - "[", "]" に囲まれたセクション名の行の後ろに設定内容を記述
    - このセクションを MySQL では「オプショングループ」と呼ぶ
    - MySQL サーバーに関するもの: `[mysqld]`
    - コマンドラインクライアントに関するもの: `[mysql]`
    - mysqldump に関するもの: `[mysqldump]`
- 各設定内容は、`${オプション名} = ${値}` の形式で記述
- オプションは以下のドキュメントを参照
  - https://dev.mysql.com/doc/refman/8.0/ja/server-system-variables.html
  - https://dev.mysql.com/doc/refman/8.0/ja/innodb-parameters.html
