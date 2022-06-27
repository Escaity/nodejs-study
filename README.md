## nodejs-study
サーバサイドプログラミング入門用リポジトリ

### Docker起動

カレントディレクトリをnodejs-studyに変更した後、以下実行

    docker-compose up -d

Dockerコンテナのコンソールにアクセスする

    docker-compose exec app bash

nodeを利用してJavaScriptファイルを実行する

    node app.js 100 // 5050
	
コンテナから抜ける時は"exit"と入力、コンテナを破棄するには以下実行

    docker-compose down
	
