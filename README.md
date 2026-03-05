# WebP Batch Converter

[English](#english) | [繁體中文](#繁體中文)

<h2 id="english">English</h2>

A browser-based tool for converting JPG and PNG images to WebP format. The conversion runs entirely on the client side, meaning files are processed locally and never uploaded to any external server.

### Features

* **Client-side processing:** Uses HTML5 Canvas for image conversion.
* **Bulk import:** Supports dragging and dropping multiple files or selecting entire directories.
* **Direct output:** Saves converted files directly to a local folder via the File System Access API.
* **ZIP export fallback:** Bundles all images into a single ZIP file for browsers that do not support direct folder writing.
* **Theme toggle:** Includes dark and light modes with local storage persistence.

### Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript
* [JSZip](https://stuk.github.io/jszip/)

### Usage

1. Open `index.html` in Chrome or Edge.
2. Drag images or folders into the drop zone.
3. Set the desired WebP quality.
4. Choose to save directly to a folder or download as a ZIP file.

<br>

<h2 id="繁體中文">繁體中文</h2>

這是一個純前端的 JPG 與 PNG 轉 WebP 工具。所有轉換程序都在使用者的瀏覽器本地執行，無須後端伺服器，圖片檔案不會外流。

### 特點

* **本地端處理：** 利用 HTML5 Canvas 轉換圖片格式。
* **批量匯入：** 支援拖曳多個檔案或完整資料夾。
* **直接輸出：** 透過 File System Access API 直接將檔案存入本地指定資料夾。
* **ZIP 打包：** 若瀏覽器不支援直接寫入，可將所有圖片打包成單一 ZIP 檔下載。
* **主題切換：** 內建深色與淺色主題，並自動記錄使用者偏好。

### 技術摘要

* HTML5
* CSS3
* 原生 JavaScript
* [JSZip](https://stuk.github.io/jszip/)

### 使用方法

1. 使用 Chrome 或 Edge 開啟 `index.html`。
2. 將圖片或資料夾拖曳至畫面中的轉換區。
3. 調整 WebP 壓縮品質參數。
4. 點擊儲存至資料夾或下載 ZIP 檔完成匯出。
