# python-study
pythonの勉強に使ってるリポジトリです

## Dockerの使い方メモ

- 初回起動  
`docker-compose up -d --build` : イメージビルドから起動迄
- コンテナ起動して内部に入る  
`docker-compose up -d`  
`docker-compose exec python3 bash`  

- コンテナ終了  
`docker-compose down`

[参考サイト](https://techacademy.jp/magazine/47408)