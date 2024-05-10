1. HTML結構 (簡短)
創建標題 "Memory Matching Game"。
創建標題區域，中央文字 "Memory Matching Game"。
主要區域包含：4x4遊戲網格、消息顯示區、重啟遊戲按鈕。
在底部，創建頁腳區域，顯示遊戲版本信息。
1. HTML結構 (詳細)
創建一個HTML標題，標題的文字內容為 "Memory Matching Game"，讓用戶可以在瀏覽器的標題欄中看到
在頁面的頂部，創建一個標題區域，區域中央有一個大字體的文字 "Memory Matching Game"，明確告訴用戶這是一個記憶配對遊戲
主要內容區域包含以下元素：
一個4x4的遊戲網格，用於顯示和操作遊戲卡片
一個消息顯示區，用於向用戶展示遊戲的進度和結果
一個重啟遊戲按鈕 (Reset Game)，用戶可以點擊此按鈕來重新開始遊戲
在頁面的底部，創建一個頁腳區域，區域中央有一個小字體的文字，用於顯示遊戲的版本信息 (e.g. v20240503)
2. CSS樣式 (簡短)
為所有元素設定字體為 Arial，文字居中對齊
設定標題和頁腳的背景顏色為灰色，文字顏色為白色
網格顯示為4x4布局，卡片之間有間隙
每張卡片具有翻轉動畫效果，當被翻轉時顯示背面
2. CSS樣式 (詳細)
使用CSS的"font-family"屬性，將所有HTML元素的字體設定為 Arial。同時，使用"text-align"屬性，將所有元素的文字對齊方式設定為居中。
使用"background-color"屬性，設定標題和頁腳區域的背景顏色為灰色(#808080)。並使用"color"屬性，將這兩個區域的文字顏色設定為白色(#FFFFFF)。
使用CSS Grid，設定遊戲網格為4x4的布局。每張卡片都具有等距的間隙，可以通過設定"margin"或"gap"屬性實現。
為每張卡片添加翻轉動畫效果。當卡片被點擊或觸碰時，利用CSS的"transform"和"transition"屬性，使卡片翻轉並顯示背面，背面顯示對應的表情符號。
3. JavaScript邏輯
