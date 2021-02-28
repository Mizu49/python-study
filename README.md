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

## VS Codeの拡張機能を使った開発環境
[VS CodeでDocker開発コンテナを便利に使おう](https://qiita.com/Yuki_Oshima/items/d3b52c553387685460b0#%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83%E6%A7%8B%E7%AF%89)