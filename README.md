# Auto_tinder_swipe
ブログ（http://healuniv.hatenablog.jp/entry/2017/12/05/210430）で紹介した自動右スワイプ用のコードを少し書き換えたもの．

## 使い方
Facebook ID, トークンの取得およびpynderパッケージのインストールを終わってる前提で話を進めます．

- your_fb_idとyour_fb_tokenを自分のFacebook ID，アクセストークンに書き換える
- 課金ユーザの場合，19行目の終了条件を
```
if counter==10000:
```
に書き換える
- 以下のコマンドを実行する．
```
python auto_tinder.py
```
- コードが回るまでコーヒーでも飲んで待ってましょう．

## 注意事項
アクセストークンの取得について，今後現在の手法が使えなくなる可能性は大いにあります．その時は色々試行錯誤してみて下さい．
