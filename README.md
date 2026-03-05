# WebP Converter

[English](#english) | [繁體中文](#繁體中文)

<h2 id="english">English</h2>

A browser-based tool to batch convert JPG and PNG images to WebP. It runs entirely on the client side, ensuring privacy and fast processing without any server uploads.

### Features
* Local conversion using HTML5 Canvas and WebAssembly.
* Drag and drop support for files and folders.
* Direct folder output (via File System Access API) or ZIP download.
* Built-in i18n (English, Traditional Chinese, Japanese, Korean).
* Dark and light theme toggle.

### Tech Stack
* Vanilla JavaScript
* HTML5 / CSS3
* [JSZip](https://stuk.github.io/jszip/)
* [@jsquash/webp](https://github.com/jamsinclair/jSquash)

### Usage
Simply open `index.html` in a modern browser like Chrome or Edge. Drag your images into the dropzone, adjust the quality slider, and choose your export method.

<h2 id="繁體中文">繁體中文</h2>

這是一個純前端的圖片轉檔工具，用於將 JPG 和 PNG 批量轉換為 WebP 格式。所有處理都在瀏覽器本地完成，不依賴後端，無須擔心圖片外流。

### 功能特點
* 使用 HTML5 Canvas 與 WebAssembly 進行本地轉檔。
* 支援直接拖曳多個檔案或整個資料夾。
* 支援直接寫入本機資料夾 (需瀏覽器支援 File System Access API)，或打包成 ZIP 下載。
* 內建繁體中文、英文、日文與韓文，支援自動偵測切換。
* 支援深色與淺色主題。

### 開發技術
* 原生 JavaScript
* HTML5 / CSS3
* [JSZip](https://stuk.github.io/jszip/)
* [@jsquash/webp](https://github.com/jamsinclair/jSquash)

### 使用方式
使用 Chrome 或 Edge 直接開啟 `index.html` 即可運行。將圖片拖曳至網頁中，調整品質滑桿後，選擇要直接存入資料夾或下載 ZIP 檔。
