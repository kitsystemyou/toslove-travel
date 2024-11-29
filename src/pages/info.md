---
title: Markdown page example
---

# 旅程

```mermaid
sequenceDiagram
    participant ty as 東京駅

    box White 新潟
    participant e as 越後駅
    participant o as その他(?)
    participant y as トラスブ湯沢
    end
    
    opt 1日目(11/30)
    ty ->> e: 10時56分発 新幹線 12:08着
    e -->> e: 昼食とか
    e ->> y: 14時45分発 シャトルバス🚌 15時00分着
    note over y: 🔺チェックイン可能 15~21時
    y -->>y: くつろぐ♨
    end

    opt 2日目(12/1)
    note over y: 🔺チェックアウト 11時まで 
    y ->> e: 11時10分発 シャトルバス 🚌 11時20分着
    e ->> o: ？？
    o -->> e: 戻る
    e ->> ty: 17時16分発 新幹線 18時40分着
    end

```

# その他資料

- [公式サイト](https://www.its-kenpo.or.jp/shisetsu/hoyou/chokuei/toslove_yuzawa/index.html)
- [パンフレット](https://www.its-kenpo.or.jp/documents/shisetsu/hoyou/chokuei/toslove_yuzawa/tos_yuzawa_pamph.pdf)
- [シャトルバス](https://www.its-kenpo.or.jp/documents/shisetsu/hoyou/chokuei/toslove_yuzawa/bus20240401.pdf)