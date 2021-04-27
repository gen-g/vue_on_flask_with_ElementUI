# vue_on_flask_with_ElementUI

[vue_on_flask](https://github.com/gen-g/vue_on_flask)の続きです．

今回も原則[FlaskとVue.jsでSPA Webアプリ開発](https://qiita.com/y-tsutsu/items/67f71fc8430a199a3efd)に従っています．

今回は，Vue.jsの見た目を少し変えてみます．

UIライブラリにElement UIを使います．

# 事前準備
 
以下のコマンドを実行してローカルに環境を作る

```
git clone https://github.com/gen-g/vue_on_flask
cd vue_on_flask
mv vue_on_flask {app name}<-自由に新しい名前をつけてください
cd {app name}
rm -rf frontend/node_modules package-lock.json && npm install
npm run build
pipenv -python 3.7
pipenv install flask
```

できているかどうか確認するため，サーバを立ち上げてみる

```
cd backend
pipenv run start
```

としてlocalhostにアクセスする．

以下のようなページが表示されれば準備完了

<img src="https://github.com/gen-g/vue_on_flask/blob/img/img.png" width=100%>


---



