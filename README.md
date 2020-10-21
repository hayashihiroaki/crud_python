|  |内容 | 
|:-----------:|:------------:|
| アプリケーション名      | crud   |
| アプリケーション概要 |アプリケーションの基本的な処理であるCreate（生成）・Read（	読み取り）・Update（更新）・Delete（削除）が行えます。|
| URL |http://13.115.147.133/|
| テスト用アカウント  |  ユーザー名：test<br>パスワード：test30561 |
| 利用方法   | 投稿された情報を閲覧することができます。ユーザー登録、ログインすることで自身でも投稿することが可能です。 |
| 目指した課題解決   | 手軽に情報を収集したり意見を共有できるよう他ユーザーの投稿が見られ、自身でも投稿ができるTwitterのようなサービスを想定して作成しました。 |
| 洗い出した要件|投稿・投稿一覧表示・投稿詳細。投稿削除・投稿編集機能|
| 実装した機能についてのGIF|実装した機能について、それぞれどのような特徴があるのか列挙しましょう。GIFを添えることで、イメージがしやすくなります。|
| データベース設計|	![ER図](https://gyazo.com/00b45d4ff0d1a44c62b2761c3de97163.png)|
| ローカルでの動作方法|`git clone https://github.com/hayashihiroaki/crud_python.git`<br>  `cd crud_python` <br>`pip install pipenv`<br> `pipenv install`<br> `pipenv install django`<br> `pipenv shell`<br> `pip install --upgrade django-crispy-forms` <br>python: 3.9 <br>django: 3.1.2|