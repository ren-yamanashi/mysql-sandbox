# SHOW 命令

- SHOW STATUS
  - MySQL サーバーの実行状態に関する情報を表示
  - メモリの使用状態、接続の累積情報など

- SHOW VARIABLES
  - 稼働中の MySQL サーバーの設定状態を表示
  - サーバー全体の設定を確認したい場合は `SHOW GLOBAL VARIABLES` を使用

- SHOW ENGINE INNODB STATUS
  - InnoDB の情報を表示
  - バッファプールなどのメモリの状態やロックの状態などを確認できる
  - 特権ユーザーのみ実行可能
  - 長いので `\G` をつけて実行するといい
