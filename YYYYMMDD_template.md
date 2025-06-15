---
marp: true
theme: freud
footer: 'Copyright (C) gmoriki, All Rights Reserved.'
paginate: true
# header: '<img src="./.images/logo.png" alt="logo" style="float: right;">'
style: |
  section {
    font-family: 'Hiragino Sans', 'Noto Sans CJK JP', sans-serif;
    font-size: 28px;
    background-repeat: no-repeat;
    padding-left: 80px;
    padding-right: 60px;
  }
  table {
    font-size: 0.8em;
  }
  header {
    text-align: right;
    padding: 5px;
  }
  header img {
    max-height: 120px;
  }
  /* 表紙ページの背景 */
  section.cover {
    background-image: url("./.images/background.png");
    background-position: right bottom;
    background-size: 100%;
    background-repeat: no-repeat;
  }
  /* 表紙の見出しとサブタイトルは中央配置 */
  section.cover h1 {
    font-size: 56px;
    text-align: center;
    position: static;
    margin-top: 0;
    margin-bottom: 20px;
  }
  section.cover p {
    text-align: center;
    font-size: 32px;
  }
  /* 通常スライドの見出しは絶対位置固定 */
  h1 {
    font-size: 42px;
    position: absolute;
    top: 100px;
    left: 80px;
    right: 60px;
  }
  h2 {
    font-size: 36px;
  }
  img {
    max-height: 450px;
    display: block;
    margin: 0 auto;
  }
  /* 2段組レイアウト */
  .two-column {
    display: flex;
    gap: 40px;
    align-items: center;
    min-height: 400px;
  }
  .column-left {
    flex: 1;
  }
  .column-right {
    flex: 1;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .column-right p {
    margin-top: 15px;
    font-size: 24px;
    color: #666;
  }
  .column-right img {
    max-height: 350px;
    max-width: 100%;
  }
---

<!-- _class: cover -->
# タイトル
**YYYY.MM.DD hogehoge**

---

# 本日のアジェンダ

1. **あああ**
2. **いいい**
3. **ううう**

---

# あああ
### hogehoge
- aaa
- bbb

---

# いいい
### hogehoge
- aaa
- bbb

---

# ううう
### hogehoge
- aaa
- bbb