|  |内容 | 
|:-----------:|:------------:|
| アプリケーション名      | crud   |
| アプリケーション概要 |アプリケーションの基本的な処理であるCreate（生成）・Read（	読み取り）・Update（更新）・Delete（削除）が行えます。|
| URL |http://13.115.147.133/|
| テスト用アカウント  |  ユーザー名：test<br>パスワード：test30561 <br>ユーザー名2：test2<br>パスワード2：test30561|
| 利用方法   | ユーザー登録、ログインすることで文章を投稿することが可能です。投稿された情報を閲覧することができます。 |
| 目指した課題解決   | techcampでは、rubyを使い開発を行ってきましたので、違う言語も扱えるようにするため基本的な機能を持ったアプリケーションをpythonで開発致しました。手軽に情報を収集したり意見を共有できるよう他ユーザーの投稿が見られ、自身でも投稿ができるTwitterのようなサービスを想定して作成しました。 |
| 洗い出した要件|ユーザー管理・投稿・投稿一覧表示・投稿詳細。投稿削除・投稿編集機能|
| 実装した機能についてのGIF|<h4>ユーザー管理・投稿一覧表示機能</h4>![user](https://gyazo.com/746d0ab5583bcb05ef7c787376503bd6.gif)ログインログアウト機能実装。新しい投稿が上から表示されるよう実装。ログインの有無でログイン・ログアウト・サインインページへのリンクボタンを状態に応じて表示。ログインユーザーのみ投稿ができるよう未ログインの場合、newpostを選択するとログインページに遷移するよう実装。headerが常にブラウザ上部に表示されるよう実装。<br>![colou](https://gyazo.com/d135f80c732cae86029c7c2f7075b201.gif)画面左右どちらかの矢印をクリックしたあとスライドショーが始まるようを実装。画面左にある歯車アイコンをクリックすることでサイトを自分の好きな色にカスタマイズが可能。<br><br><h4>投稿・投稿詳細機能</h4>![post](https://gyazo.com/d6f2107a06a520cdb30e5656c97a9253.gif)投稿完了した際、投稿詳細ページに遷移するよう実装。<br>投稿のidを特定し投稿別に表示できるよう実装。<br><br><h4>投稿削除・投稿編集機能</h4>![edit](https://gyazo.com/920483184ee29eed8dacfc16155ae551.gif)投稿タイトルから詳細ページに遷移できるよう実装。編集に成功した場合詳細ページに遷移するよう実装。編集・削除ボタン配置。<br>投稿ユーザー以外が編集・削除不可になるよう実装。|
| データベース設計|	![ER図](https://gyazo.com/00b45d4ff0d1a44c62b2761c3de97163.png)|
| ローカルでの動作方法|`git clone https://github.com/hayashihiroaki/crud_python.git`<br>  `cd crud_python` <br>`pip install pipenv`<br> `pipenv install`<br> `pipenv install django`<br> `pipenv shell`<br> `pip install --upgrade django-crispy-forms` <br>python: 3.9 <br>django: 3.1.2|