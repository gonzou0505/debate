### Memo
- Server 立ち上げ

```bash
$ bundle exec rails s
```

- server シャットダウン

Ctr 押しながらCボタン(ターミナルで)

---

- 囲むやつ
```bash
```

- serverURL

[server](http://localhost:3000/)

- gitの変更

1. command S
2. サイドバーのsource controlを押す
3. changesの＋ボタンを押す
4. messageをかく
5. command押しながらEnter
6. source controlの欄の点三つのやつを押してpushを選択

---

1. config/routes.rbにアクセス
```rb
get 'welcome/index'
```
2. これはwelcomeコントローラーのindexメソッドにとぶ

3. indexメソッドの処理をした後にviewを呼び出す。

viewは`app/views/コントローラー名/メソッド名.html.erb`を呼び出す。

この場合は`app/views/welcome/index.html.erb`

---
- aタグ

```
<a href="URL">表示文字</a>
```

