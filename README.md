# 議席圖譜

世界國會的互動圓形席次圖。右上角可搜尋及切換 198 個國家與議會選項。每個圓點代表一席。

## 發布網站

在儲存庫的 **Settings → Pages**，將 **Source** 設為 **Deploy from a branch**，選擇 **main** 和 **/(root)**，然後按 **Save**。

## 更新公開席次

1. 在網站切換國家並點選「編輯席次」，調整總席次、政黨名稱、席數及代表顏色。
2. 按「套用預覽」，檢查圖表後下載席次 JSON。
3. 使用有儲存庫寫入權限的 GitHub 帳號，把下載的檔案上傳至 `main` 根目錄並提交。保留原始檔名，例如 `seats-JP.json`。GitHub Pages 完成更新後，訪客即可讀取新資料。

頁面以各國獨立的 JSON 檔載入已發布設定。尚無檔案的國家會顯示空白狀態，臺灣則預設載入有標示的示範資料。

國家名錄參考 [IPU](https://www.ipu.org/national-parliaments)，旗幟來自 [FlagCDN](https://flagcdn.com/)。
