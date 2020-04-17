docker infoコマンドによる確認

`docker info`{{execute}}

dockerプロセスの起動状況の確認

`ps ax | grep -e docker -e container`{{execute}}

dockerブリッジの確認

`ip link show docker0`{{execute}}

dockerブリッジに設定されているIPアドレスの確認

`ip address show docker0`{{execute}}