# 咒泉鄉的桃園三結義 · 正典

《三國演義》第一回的娘溺泉改寫，Larch 視覺小說。這個 repo 是它的**正典資料集**：
哪些取自原著、哪些我們改了、哪些是我們自己編的，以及哪些圖真的是正典。

**網站：<https://yazelin.github.io/larch-taoyuan-canon/>**

玩：<https://larch.ink/play/market/2375b478-10c0-4b52-8ff6-239e57162c64>

## 這裡的東西是產生出來的

不要直接改這個 repo。來源在私有的 `larch-taoyuan`：

- 文字 → `canon/canon.md`
- 版型 → `canon/layout.py`
- 組裝 → `canon/build_site.py`
- 素材清單 → `canon/assets.py`（從線上版子反推）
- 規則檢查 → `canon/canoncheck.py`

改完跑 `python3 canon/publish.py push`。

授權見 [LICENSE.md](LICENSE.md)（CC BY-NC 4.0）。
