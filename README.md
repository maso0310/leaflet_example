# Leaflet.js 學習範例程式碼

這是一個循序漸進的 Leaflet.js 學習專案，包含了從基礎地圖建立到進階功能的 HTML 範例檔案。每個檔案（`DAY_XX.html`）都專注於一個或多個特定的主題，旨在展示 Leaflet 的各種功能。

## 參考資料

本專案中的範例程式碼主要參考自 **塔塔墨** 的 [iThome 鐵人賽系列文章](https://ithelp.ithome.com.tw/m/users/20112552/ironman/2074)：
-   Leaflet.js 從零開始

## 如何使用

1.  Clone 或下載此專案。
2.  直接在網頁瀏覽器中開啟任何一個 `DAY_XX.html` 檔案即可看到效果。
3.  由於地圖圖資與函式庫是透過 CDN 載入，請確保在開啟檔案時有網路連線。

## 範例檔案說明

以下是每個範例檔案的內容摘要：

### `DAY_01.html`: 基礎地圖

-   **核心功能**: 初始化一個 Leaflet 地圖，設定中心點、縮放層級，並加入一個 OpenStreetMap 圖層。這是使用 Leaflet 的第一步。

### `DAY_02.html`: 地圖操作

-   **核心功能**: 示範 `setView`, `setZoom`, `zoomIn/Out`, `fitBounds`, `panTo`, `flyTo` 等常用的地圖視圖控制方法。

### `DAY_03.html`: 向量圖層與圖層控制器

-   **核心功能**: 加入線 (`L.polyline`)、面 (`L.polygon`) 向量圖層。
-   **進階功能**: 使用 `L.control.layers` 來建立一個可以切換不同底圖與覆蓋圖層的控制器。

### `DAY_05.html`: 標記 (Marker) 與彈出視窗 (Popup)

-   **核心功能**: 建立可拖曳的 Marker，並為其綁定 `bindPopup` (點擊後顯示) 和 `bindTooltip` (滑鼠懸浮顯示)。

### `DAY_06.html`: 圖片、影片與 WMS 圖層

-   **核心功能**: 示範如何在特定地理範圍上疊加圖片 (`L.imageOverlay`)、影片 (`L.videoOverlay`)。
-   **進階功能**: 介紹如何串接 WMS (Web Map Service) 服務 (`L.tileLayer.wms`)。

### `DAY_07.html`: 更多向量圖層

-   **核心功能**: 示範 `L.circleMarker` (半徑單位為像素) 以及如何繪製具有孔洞的多邊形 (`L.polygon`)。

### `DAY_08.html`: 向量圖層樣式

-   **核心功能**: 如何為向量圖層（如 `L.rectangle`）定義一個樣式物件，來設定顏色、透明度、邊框等外觀。

### `DAY_09.html`: 圖層群組與自訂圖層

-   **核心功能**: 使用 `L.layerGroup` 和 `L.featureGroup` 來管理多個圖層，並對群組進行統一操作。
-   **進階功能**: 示範如何透過繼承 `L.GridLayer` 來建立自訂的網格圖層，例如顯示圖磚座標。

### `DAY_10.html`: 工具類與自訂圖示

-   **核心功能**: 介紹 `L.latLng`, `L.point` 等工具類別，並示範如何使用 `L.icon` (圖片) 和 `L.divIcon` (CSS) 來自訂 Marker 圖示。

### `DAY_11.html`: 地圖控制項

-   **核心功能**: 客製化內建的控制項，包含縮放 (`L.control.zoom`)、屬性 (`L.control.attribution`)、圖層 (`L.control.layers`) 和比例尺 (`L.control.scale`)。

### `DAY_12.html`: 工具函式

-   **核心功能**: 介紹 `L.Browser` 瀏覽器偵測與 `L.transformation` 座標轉換等不常直接使用但很實用的工具函式。

### `DAY_13.html`: DOM 工具類

-   **核心功能**: 示範 `L.PosAnimation` (控制 DOM 位置動畫) 和 `L.Draggable` (讓 DOM 元素可拖曳) 等與 DOM 元素互動的進階功能。

<br><br>
====================================<br>
如果喜歡這個教學內容<br>
歡迎訂閱Youtube頻道<br>
[Maso的萬事屋](https://www.youtube.com/playlist?list=PLG4d6NSc7_l5-GjYiCdYa7H5Wsz0oQA7U)<br>
或加LINE私下交流 LINE ID: mastermaso<br>
![LOGO](https://yt3.ggpht.com/ytc/AKedOLR7I7tw_IxwJRgso1sT4paNu2s6_4hMw2goyDdrYQ=s88-c-k-c0x00ffffff-no-rj)<br>


====================================<br>