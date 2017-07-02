Title: Pyslvs 手冊：介面
Date: 2017-07-02 21:00
Category: 2016bg2
Tags: pyslvs-manual-sphinx
Author: 40323230

介面
===

主畫面的上方為功能表列 (Menu bar)、右側為畫布 (Canvas)；左方則有各式功能的分頁欄 (Tab widgets)。

功能表列涵蓋大部分的功能，然而一些有關各項目的細部操作，則必須在對應的分頁欄中選取或設定。以下小節將為主畫面中不同區域的功能名稱做簡單的介紹。

功能表列 (Menu bar)
---

功能表列中根據不同的功能分類，如下：

+ 檔案 (File)

    建立新的工作簿、開啟既有的工作簿、參考範例，或是不同檔案格式的匯入與匯出功能。
    
    另外還有調整視窗縮放的指令，而功能表列在全螢幕模式仍會顯示。
    
+ 編輯 (Edit)

    復原與重做功能、一些輔助編輯機構節點的指令。
    
+ 繪製 (Draw)

    建立、編輯、刪除機構實體的功能，還有更新當前座標至原始座標的指令。
    
+ 模擬 (Simulation)

    建立、編輯、刪除機構約束的功能。
    
+ 路徑 (Path)

    路徑追蹤功能的相關指令與顯示設定。
    
+ 選項 (Options)

    檢視方式調整以及工作簿相關資訊。
    
+ 說明 (Help)

    本套件的相關網站與套件資訊。

功能表列中的功能都有對應的快捷鍵，參考如下：

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#ccc;}
.tg td{font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#fff;}
.tg th{font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#ccc;color:#333;background-color:#f0f0f0;}
.tg .tg-yw4l{vertical-align:top}
</style>
<table class="tg">
<tr>
<th class="tg-yw4l">熱鍵</th>
<th class="tg-yw4l">功能</th>
</tr>
<tr>
<td class="tg-yw4l">F1</td>
<td class="tg-yw4l">關於 Pyslvs</td>
</tr>
<tr>
<td class="tg-yw4l">F2</td>
<td class="tg-yw4l">新增 - 節點</td>
</tr>
<tr>
<td class="tg-yw4l">F3</td>
<td class="tg-yw4l">新增 - 連桿</td>
</tr>
<tr>
<td class="tg-yw4l">F4</td>
<td class="tg-yw4l">新增 - 固定鍊</td>
</tr>
<tr>
<td class="tg-yw4l">F5</td>
<td class="tg-yw4l">設置 - 驅動軸</td>
</tr>
<tr>
<td class="tg-yw4l">F6</td>
<td class="tg-yw4l">設置 - 滑塊</td>
</tr>
<tr>
<td class="tg-yw4l">F7</td>
<td class="tg-yw4l">設置 - 伸縮桿</td>
</tr>
<tr>
<td class="tg-yw4l">F10</td>
<td class="tg-yw4l">顯示 / 隱藏 - 節點標記</td>
</tr>
<tr>
<td class="tg-yw4l">F11</td>
<td class="tg-yw4l">顯示 / 隱藏 - 尺寸標註</td>
</tr>
<tr>
<td class="tg-yw4l">Shift + F1</td>
<td class="tg-yw4l">全螢幕</td>
</tr>
<tr>
<td class="tg-yw4l">Shift + F2</td>
<td class="tg-yw4l">還原視窗</td>
</tr>
<tr>
<td class="tg-yw4l">Space</td>
<td class="tg-yw4l">縮放畫布至合適大小</td>
</tr>
<tr>
<td class="tg-yw4l">Esc</td>
<td class="tg-yw4l">關閉所有面板</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + N</td>
<td class="tg-yw4l">新建工作簿</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + O</td>
<td class="tg-yw4l">載入工作簿</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + S</td>
<td class="tg-yw4l">儲存工作簿</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + Shift + S</td>
<td class="tg-yw4l">另存工作簿</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + Q</td>
<td class="tg-yw4l">離開 Pyslvs</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + Z</td>
<td class="tg-yw4l">復原指令</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + Shift + Z</td>
<td class="tg-yw4l">重做指令</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + F</td>
<td class="tg-yw4l">節點關聯</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + R</td>
<td class="tg-yw4l">取代節點</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + B</td>
<td class="tg-yw4l">批次移動</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + 3</td>
<td class="tg-yw4l">Solvespace 3D 模型格式</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + 2</td>
<td class="tg-yw4l">Solvespace 2D 草圖格式</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + D</td>
<td class="tg-yw4l">DXF 2D 模型格式</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + Shift + D</td>
<td class="tg-yw4l">DXF 2D 草圖格式</td>
</tr>
<tr>
<td class="tg-yw4l">Ctrl + P</td>
<td class="tg-yw4l">圖片格式</td>
</tr>
</table>

畫布 (Canvas)
---

工作簿中的機構樣貌會呈現在畫布中。

畫布下方為導覽列，提供瀏覽提示、縮放等級、縮放畫布至合適大小的功能，另外也會顯示工作簿的機構自由度。

瀏覽提示圖示將會顯示進階的滑鼠操作，可以幫助您更快地調整檢視的視角：

* Ctrl + 滑鼠雙擊：將畫布原點移動至滑鼠位置。

* Ctrl + 滑鼠按住（可拖動）：將畫布原點移動至滑鼠位置。

* 滑鼠滾輪或中鍵拖曳：平移。

* 滑鼠滾輪滾動：縮放大小。

* Alt + 滑鼠雙擊：快速加入一個普通節點。

* 滑鼠中鍵雙擊或 Space 鍵：縮放畫布至合適大小。

畫布的滑鼠右鍵選單則可以快速加入普通節點和固定節點。