dockerコマンド
----------------------------

- docker run : コンテナを起動
- docker stop : コンテナを停止
- docker ps : コンテナ一覧を表示
- docker pull : コンテナイメージを取得
- docker images : コンテナイメージ一覧を表示
- docker exec : 起動中のコンテナ内でコマンドを実行
- docker attach : コンテナに接続
- docker logs : コンテナのログを表示

dockerの情報表示

`docker info`{{execute}}

ローカルに存在するコンテナイメージの確認

`docker images`{{execute}}

コンテナイメージの検索

`docker search centos`{{execute}}

コンテナイメージのダウンロード

`docker pull centos`{{execute}}

コンテナイメージが追加されたことを確認

`docker images`{{execute}}

コンテナの起動

`docker run -ti centos bash`{{execute}}

コンテナ内で起動するプロセスの確認 - bashだけが起動している

`ps ax`{{execute}}

コンテナからexitするとコンテナが終了する。

`exit`{{execute}}

終了したコンテナを確認する。

`docker ps -a`{{execute}}
