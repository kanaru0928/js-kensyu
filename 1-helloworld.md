---
marp: true
theme: theme411
class: slides
paginate: true
---
<!--
_class: title
_paginate: false
-->

# team411研修資料
## 項目1. Hello, world

---
<!--
class: slides
-->
# プログラミングとは
**コンピュータに対する命令**を書くこと。

```js
load JIntMainRet1
store IntRet
jump Int
JIntMainRet1: jump IntMainRet1
IntMainRet1: load Ret
store MainA
store IntAddArgX
load JIntMainRet2
store IntRet
```

---
# プログラミングのルール
## 順次
- 上から順番に実行される
## 分岐
- 実行する命令を分岐させる
- ex. ruby, JSの`if`文
## 繰り返し
- 命令を繰り返す
- ex. rubyの`while`文

---
# Hello world
## HTMLを使う方法
1. `index.html`と`script.js`を同じディレクトリに配置 
2. `index.html`に以下を記入(コピペOK)
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="script.js"></script>
  <title>研修</title>
</head>
<body>
</body>
</html>
```

---
# Hello world

3. `script.js`に以下を記入
```js
console.log("Hello world");
```
4. `index.html`をブラウザで開いてF12キーを押す
1. 検証ツールのConsoleタブを開いて結果を確認

---
# Hello world
## AtCoderのコードテスト

