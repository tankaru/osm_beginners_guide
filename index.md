お店の情報を登録しよう! OpenStreetMapはじめてガイド
======

**みんなでテイクアウトMAP**は、みんなで編集できるみんなの地図**[OpenStreetMap](https://www.openstreetmap.org/)**のデータに基づいています。

地元のお店やお気に入りのお店の情報が不足していたり間違っていたりしたら、だれでも変更することができます。お店自体が登録されていなくても、今すぐ登録することができます。一般的なWebブラウザで簡単にできますので、ぜひこの機会にOpenStreetMapを編集してみませんか?
OpenStreetMapを編集するにはアカウントを持っている必要があります。アカウントは誰でも作成することができます。


* [OpenStreetMapのアカウントを**持っている**方はこちらからスタート](#register)
* [OpenStreetMapのアカウントを**持っていない**方はこちらからスタート](#login)

アカウントの作成<a name="register"></a>
------
OpenStreetMapのアカウントをお持ちでない方は、[ユーザ登録ページ](https://www.openstreetmap.org/user/)で登録を行ってください。メールアドレスや表示名 (OpenStreetMap上で表示されるあなたの名前です) を入力すると、登録したメールアドレス宛にメールが届きますので、メールの内容に従って登録を完了させてください。

![ユーザー登録](img/register.png "ユーザー登録")

その他のSNSなど外部アカウントとの連携も可能ですので、 (TODO: 参考ページ)

ログイン<a name="login"></a>
------
すでにOpenStreetMapのアカウントをお持ちの場合は、[ログインページ](https://www.openstreetmap.org/login)からログインします。

![ログイン](img/login.png "ログイン")

編集する
------
お店のある地域にズームインします。

地図を動かしながらズームインしていくこともできます。
![地図が表示されます](img/map_japan.png "地図が表示されます")

左上の検索ボックスに住所や駅名などを入れると検索できます。
![地名で検索](img/map_search.png "地名で検索")

お店のあるエリアが表示されたらいよいよ編集開始です。画面のいちばん上にある「編集」を選びます。初めてでもすぐに使える「iD (ブラウザー内エディター) で編集」を選びます。

![編集開始](img/select_editor.png "編集開始")

ブラウザー内エディター「iD」が起動します。起動には少し時間がかかる場合があります。起動が完了すると、航空写真の上に道路や建物や施設の情報が表示されます。

![オンラインエディタiD](img/id.png "オンラインエディタiD")

![オンラインエディタiD](img/zoom.png "オンラインエディタiD")
地図の右に表示される「+」「-」ボタンを使い、店舗を追加したい位置に向かってズームしたら、編集準備完了です。

* [**お店自体を登録する**ところからスタートする場合](#add)
* [**お店の情報を編集する**場合](#edit)

新しいお店を登録<a name="add"></a>
------
画面上のメニューから「ポイント」を選びます。
![「ポイント」を選択(img/add_point.png "「ポイント」を選択")

カーソルが十字に変わるので、追加したい地点を地図上でクリックします。
追加する位置はお店の中心部に相当する位置を目安にしてください。
![ピンを追加](img/add_pin.png "ピンを追加")

白いピンが立ち、赤く点滅し、左に地物 (地図上のモノのことをこう呼びます) の種類を選択する画面が現れますので、追加したいお店の種類を選んでください。
地物の種類はたくさんありますので、虫眼鏡アイコンのあるテキストボックスで絞り込むのがおすすめです。


![「レストラン」の検索](img/search_type.png "「レストラン」を検索")

![「レストラン」の場合](img/add_restaurant.png "「レストラン」の場合")

どれに分類するか曖昧な場合は、あまり悩まずに最も近そうなものを選べばOKです。よく使われる分類は以下のようなものがあります。

* レストラン : 食事のできるお店。
* ファストフード : すばやく食事を済ませることができる比較的低価格なお店。ハンバーガーやピザなど、細かい分類もあります。
* 喫茶店 : ノンアルコールの飲み物がメインのカフェなど。
* 居酒屋 : お酒と食べ物を提供するお店。
* バー : お酒をメインとするお店。

![「レストラン」の場合](img/add_restaurant.png "「レストラン」の場合")

選択したいお店の種類がグレーで表示され、「ポイントが非表示となっています。ズームインして有効化してください。」と表示される場合、ズームが足りません。地図の右にある「+」「-」ボタンでズームインしてください。
![TODO](img/restaurant_unavailable.png "TODO")

「名称」の欄に、お店の名前を記入します。
![TODO](img/input_name.png "TODO")

お店の情報を編集する<a name="edit"></a>
------
お店をクリックします。

OpenStreetMapでは、お店の色々な情報を登録することができます。
たとえば営業時間や料理のジャンル、そしてテイクアウトやデリバリーの情報などなど。

![TODO](img/add_tag.png "TODO")

「可能」「不可能」「持ち帰りのみ」の選択肢が表示されますので、該当するものを選んでください。
![TODO](img/input_takeaway_value.png "TODO")

これで「このお店はお持ち帰りが可能」という情報が入力できました。
![TODO](img/input_takeaway_value_done.png "TODO")

配達の可否も同様に入力することができます。こちらはチェックボックスで選択する方式になっています。

![TODO](img/input_delivery_value.png "TODO")

![TODO](img/input_delivery_value_done.png "TODO")


コミット
------
うまく編集できましたか? この時点ではまだ、変更した内容はOpenStreetMapに反映されていません。
**コミット**することによって、全世界に向けて情報を発信することができます。

画面右上の「コミット」をクリックします。
![TODO](img/commit.png "TODO")

コミットする際には、「何を変更したのか」を「コミットメッセージ」として添えます。
![TODO](img/commit_message.png "TODO")

この内容でOK! と思ったら、「アップロード」をクリック。これで変更内容がOpenStreetMapのサーバに送信され、しばらくすると全世界に公開されます。そのうちみんなでテイクアウトMAPにも反映されます。おめでとうございます! OpenStreetMapデビューに成功です!

OpenStreetMapにもっと参加したいと思ったら
------
ここでは、お店をひとつ追加したり、お店のお持ち帰りや配達の情報を記入したりする方法を紹介しました。
OpenStreetMapの情報を編集する人のことを**マッパー**といいます。お店をひとつ編集したらあなたはマッパーとして世界デビューを果たしたことになります。

TODO