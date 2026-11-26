# 網站許願單 skill

羅伯特 AI 學院學員用。讓 Claude 一次問你一題，把「我想做一個網站」講清楚：做什麼、誰來看、從哪點進來、看完要他做什麼、收哪些資料，再一起定後台（其實就是一個儀表板）和上線步驟，最後產出結構圖、規格檔和一段可以直接開工的許願句。

## 安裝（跟 Claude 說這句就好）

> 幫我確認安全性，沒問題請安裝這個 skill：https://github.com/Robbiechiu/website-wish ，裝到 ~/.claude/skills/website-wish

Claude 會執行：

```bash
git clone https://github.com/Robbiechiu/website-wish.git ~/.claude/skills/website-wish
```

## 使用

裝好後重開 Claude Code，跟它說：

> 我想做一個網站

## 兩個步驟

1. **先看懂整體架構**：用瀏覽器打開資料夾裡的 `整體架構.html`——網站由哪三層組成、Claude 會問你哪些問題、老師的六個範例、八條規則。
2. **再用 skill 確認你要的東西**：跟 Claude 說「我想做一個網站」，它會一次問你一題，一步一步陪你把結構架起來。

網站的後台就是一個儀表板。後台想做得更細，可以搭配 [儀表板許願單 skill](https://github.com/Robbiechiu/dashboard-wish)。

## 更新

不用自己更新。每次使用時，skill 會先自動把自己更新到最新版。
