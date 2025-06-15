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
    font-size: **80px**;
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
# DAIGAKU WORK AI Meetup
**2025.06.18 大学業務×生成AI活用**

---

<!-- _class: two-column -->
# 自己紹介　(森木銀河)

<div class="two-column">
<div class="column-left">

元大学職員。2023年以降は大学組織における生成AI活用の第一人者として急速に頭角を現し、全国の大学等で講演、研修、コンサルティングを精力的に行う。

「AIとヒトをつなぐ」をミッションに掲げ、大学職員の能力開発を支援する「プロンプトガイドP4Us」や内省支援AIエージェント等のツール開発も手掛ける。

</div>
<div class="column-right">

<img src="./.images/image.png" alt="代表者写真">
<p>@pogohopper8</p>

</div>
</div>

---

# 本日のアジェンダ

1. **イベント概要**
2. **対象者について**
3. **タイムスケジュール**
4. **主催コミュニティ紹介**

---

# イベント概要
### 大学業務に生成AIを活用したい職員必見！
- **目的**: 大学業務における生成AI活用の最前線を共有
- **背景**: 大学運営の高度化・複雑化への対応
- **内容**: AI技術の最新動向と実践事例の紹介
- **形式**: オンライン開催（Google Meet）
- **定員**: 100名（満員の場合はYouTube配信）

---

# 対象者について
### どなたでもご参加いただけます
- **大学・高等教育機関の教職員**
  - 教育、研究、事務、情報システム部門
- **DX推進に関心のある方**
  - 業務効率化を検討中の大学関係者
- **生成AI活用に興味のある方**
  - 最新動向や事例を学びたい方
- **情報交換を希望される方**
  - 他大学の取り組みに関心がある方

---

# タイムスケジュール
### 17:00-18:30 充実の90分プログラム

| 時間 | 内容 | 登壇者 |
|------|------|--------|
| 17:00-17:10 | オープニング・コミュニティ紹介 | - |
| 17:10-17:25 | 講演1 | 岡崎浩二さん（キャリアボット） |
| 17:25-17:40 | DX担当だからできるAI推進戦略 | 高橋侑暉さん（金沢大学） |
| 17:40-17:55 | 講演3 | 鈴木翔太さん（東北大学） |
| 17:55-18:10 | LT発表 | 白鳥成彦さん（東京都市大学） |
| 18:10-18:30 | 質疑応答・クロージング | - |

---

<!-- _class: two-column -->
# 主催コミュニティ紹介

<div class="two-column">
<div class="column-left">

### SEPAL - 生成AI×大学業務コミュニティ
- **代表者**: 森木銀河
- **コンセプト**: 生成AI×大学業務の情報交換・価値創出
- **活動内容**: ゆるやかなコミュニティ運営
- **参加方法**: イベント後にDiscordサーバ招待予定

**みなさまのご参加をお待ちしております！**

</div>
<div class="column-right">

![コミュニティロゴ](./.images/logo.png)

</div>
</div>

---

# 代表者からのメッセージ
### プロンプトエンジニアリングについて思うこと

- **ChatGPTの登場はAIを人類の共通言語に押し上げた**
  - プロンプトエンジニアリング特有の価値は手続き的知識にしかない
  - その生死や良し悪しは取るに足らないのではないか

---

# 拡大解釈への懸念
### ツールと戦略は別物

- **プロンプトエンジニアリングの過度な拡大解釈は避けるべき**
  - 「AIという強力な思考ツールを使いこなすための、人間の根源的な知的能力そのもの」まで拡大すると...
  - 従来の知的生産活動がラップされて分かりづらくなる

- **例えば**: レーシングカーの運転技術 ≠ レーシングドライバーが練る戦略

---

# デモンストレーション
### Cursor Background Agent の紹介

**実際にCursor Background Agentを使ったデモをお見せします**

- リアルタイムでのコード生成
- 開発プロセスの効率化
- 実践的な活用方法 