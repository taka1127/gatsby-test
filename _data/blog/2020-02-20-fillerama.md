---
template: BlogPost
path: /fillerama
date: 2020-05-20T14:59:36.571Z
title: Servlet＆JSP　アプリケーション
thumbnail: /assets/b491d3e887edbbf140889322d3f1b2ca.jpg
---
# アプリケーション情報
---
作成期間：2020/5/18~2020/5/22
### 接続先情報

#### URL: https://posters-test.herokuapp.com/IndexServlet 

(PaaS herokuを利用。 DBと連携していないためログインはできません。）

---
### 開発環境(言語、ツール、OS、DB、サーバー）
言語：Java, Servlet, JSP, HTML/CSS

ツール：Eclipse

OS: Windows

DB: H2 （ローカル環境）

---

### Githubリポジトリ
https://github.com/taka1127/Posters

--- 
### 投稿サイト「 Postersポスターズ」の要件

#### ① ログイン機能
・アプリケーションにログインする。
・ユーザーIDとパスワードの入力によりユーザー認証を行う。
・ユーザーは登録されている必要がある。

#### ② ユーザー登録機能
・ユーザーの登録を行う。
・登録する情報は：ユーザーID、ユーザー名、パスワード、メールアドレス。

#### ③ 投稿機能
・ログインしているユーザーは投稿できる。

・投稿する情報は：タイトル、 メッセージ 。

・タイトル、 メッセージは必ず投稿。

#### ④ 閲覧機能
・ログインしているユーザーは投稿を閲覧できる。

#### ⑤ 詳細 表示 機能

・詳細ページを表示できる。

#### ⑥ 削除機能
・ログインユーザー が投稿した記事 のみ を削除できる。
・内容:日常の感じたことや出来事をメッセージにて投稿し日記のように綴っていくアプリケーションです。
---
![テーブル設計図](/assets/0f90e1dc85bb9b73fe0f4a4fc4e0bf43.png) 


![画面遷移図](/assets/1ef0bde87cc9610eb351e3bc0ad93174.png) 
---

## 企画背景
ServletとJSPを学習し、そのアウトプットとして作成しました。
現在はSpring bootの開発を目標にしておりJavaのWeb開発の根源であるServletを理解しWeb開発の理解を深め、Spring bootの開発に役立てればと思い作成しました。