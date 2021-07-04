# docker_for_meal_planning_suggest
朝食おススメ用アプリのDocker環境

必須要件 \
docker

~~~
git clone https://github.com/fumifumitaro/meal_planning_suggest.git

#dockerの立ち上げ
docker-compose up -d

#コンテナ内にアクセス
docker-compose exec php bash

#composer install
docker-compose run composer composer install

#npm install & npm run dev
docker-compose run node npm i
docker-compose run node npm run dev

#コンテナ内で各種コマンドの実行
cp .env.example .env
php artisan key:generate
php artisan view:clear
~~~

以上のコマンド実行後https://localhostに接続