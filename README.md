# nijika
ぼっち・ざ・ろっく！のキャラクター伊地知虹夏ちゃんをWebページ上にばらまく。

### サンプル

https://mtsml.github.io/nijika/

![sample](https://user-images.githubusercontent.com/50922910/212523316-826f1ccd-f74b-457b-8125-692e3fbf40b8.png)

### 導入

WebアプリやHTMLを認識するブログなどに以下を記載。

```html
<div id="root" style="position: relative;"></div>
<script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<script src="https://unpkg.com/interactjs/dist/interact.min.js"></script>
<script type="text/babel">
    <!-- ここにminifyしたjavascriptを置く -->
</script>
```

画像パスを差し替える必要があるため

- `<img>`の`src`を画像を格納しているパスへ
- `ITEM`の画像識別子を対応する値へ

それぞれ変更する。ブログの場合は画像をアップロードしてURLを得ればよい。
