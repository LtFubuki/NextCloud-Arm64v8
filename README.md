git clone https://github.com/LtFubuki/NextCloud-Arm64v8.git

cd NextCloud-Arm64v8

docker build -t ltfubuki/nextcloud-arm64v8 .

cd docker-compose/insecure/postgres/apache/

* *EDIT db.env DB_PASSWORD

docker-compose up -d
