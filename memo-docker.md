# react,nde.js用のコンテナ作るまでの殴り書き
sudo apt update

sudo apt install npm

package.jsonを作るコマンド
npm init

docker-compose run --rm react-train sh -c "npx create-react-app react-train"

参考サイト
https://zenn.dev/coco9122/articles/react-start-app-coco9122
reactプロジェクト作成コマンド
npx create-react-app myapp
以下フォルダ構成

```
.myapp/
 ├── node_modules/ インストールしたモジュールが入る
 ├── public # 公開フォルダ
 │   ├── index.html
 │   :
 │   └── robots.txt
 ├── src # ここをいじって開発する
 │   ├── index.js
 │   ├── index.css
 │   :
 │   ├── App.js
 │   └── App.css
 ├── .gitignore
 ├── package.json # インストールすべきパッケージ情報
 ├── package-lock.json # 実際にインストールしたモジュールのバージョン情報など
 └── README.md
```



Reactアプリ作成
$ docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app react-sample"