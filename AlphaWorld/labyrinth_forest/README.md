頭顱副本計畫
------

## 資料夾結構

- collections: 掉落物的「集合」。只使用**權重**作為該集合物品掉落的比例。
- probabilities: 機率表，調用 collections。使用**機率**來決定掉落指定集合掉落的可能性。
- entities: 生物掉落的戰利品表，調用 probabilities。使用**條件**來決定是否掉落物品。指定給生物的戰利品表，通常就是這裡面的檔案。
- chests: 開箱子的戰利品表，調用 probabilities。使用**條件**來決定是否掉落物品。指定給生物的戰利品表，通常就是這裡面的檔案。