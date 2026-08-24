# 2026-08-24 週貼文素材

- 風格：幽默風（ISO 週數 35，35 mod 4 = 3）
- `caption.txt`：本週 Facebook 貼文文案
- `image.png`：本週搭配圖片

## 圖片來源

改用 repo 內本地素材，不再呼叫外部圖片生成 API。

- 圖庫：`assets/`（目前僅 1 張：`spcflooringfbpost.png`）
- 選圖規則：週數 mod 圖庫圖片數量 → 35 mod 1 = 0 → 選中 `spcflooringfbpost.png`
- 已複製為本資料夾的 `image.png`

備註：本次執行順便整理了 repo 結構——先前根目錄下有一個誤建的空白 `assets`
檔案（非資料夾）與一張放錯位置的 `spcflooringfbpost.png`（原本在 repo 根目
錄），這次已改為建立正確的 `assets/` 資料夾並將圖片移入其中，之後排程可持續
從 `assets/` 挑圖使用。

## 先前狀態（已解決）

上一次執行時因環境出站網路白名單阻擋，無法呼叫 Pollinations.ai 產生圖片
（403 Forbidden），因此當時沒有產出圖片。這次已改用本地素材，問題已解決。
