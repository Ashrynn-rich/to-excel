# to-excel：PDF／圖片轉 Excel

把 PDF（文字型或掃描型）與圖片（JPG、PNG 等）中的表格內容，轉成可編輯的表格，並能複製貼到 Excel 或下載為 .xlsx。

- 所有處理都在瀏覽器裡完成，**檔案不會上傳到任何伺服器**。
- 文字型 PDF 直接讀取文字；圖片與掃描 PDF 以內建的離線文字辨識（PaddleOCR PP-OCRv5 為主，Tesseract 為後備；繁體中文＋英文）處理，辨識結果請務必人工核對。
- 純靜態網頁，無需安裝。

## 使用
開啟頁面，把檔案拖進去，檢查表格，按「複製」或「下載 Excel」。

## 授權與第三方元件
- [pdf.js](https://github.com/mozilla/pdf.js)（Apache-2.0）
- [SheetJS Community Edition](https://github.com/SheetJS/sheetjs)（Apache-2.0）
- [tesseract.js](https://github.com/naptha/tesseract.js)（Apache-2.0）與 Tesseract 訓練資料（Apache-2.0）
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) PP-OCRv5 文字辨識模型（Apache-2.0）
- [ONNX Runtime Web](https://github.com/microsoft/onnxruntime)（MIT）

授權文字見 `vendor/` 內各資料夾。
