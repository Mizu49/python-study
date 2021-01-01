# python-study
pythonの勉強に使ってるリポジトリです

## Dockerの使い方メモ

- コンテナ起動して内部に入る  
`$ docker-compose up -d`  
`$ docker-compose exec python3 bash`  

- コンテナ終了  
`$ docker-compose down`

- 構成を変更したときは再ビルド  
`$ docker-compose build`  
`$ docker-compose up -d`

[参考サイト：テックアカデミー](https://techacademy.jp/magazine/47408)  
[参考サイト：Qitta docker-composeで都合の良いPython3実行環境を作成する](https://qiita.com/muneki/items/bdb4c24b188d972b5289)