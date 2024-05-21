主樣式CSS 文件: bb-template.css 、 style-starter.css (因為當時有參考其他模板因此有兩個)

字型: "Roboto", "sans-serif" ==> 引用自Google Font 匯入bb-template.css、開頭複製首頁的引用即可

logo圖片:projectB&B/logo

icon:首頁使用fontawesome,進入DashBoard後使用的icon放在:projectB&B/assests/icon

navbar顏色:
background:linear-gradient(to right top, rgb(246,222,136)
20%, rgb(242,128,128) 80%)
==>雙色漸層，漸層方向為項右上漸層

漸層色重點: 
在CSS中，漸變實際上是一個圖像值，而不是顏色值。
所以撰寫時必須使用 background-image或background(background能繼承所有background屬性的指令)，不能直接使用 background-color

其他常用輔色色票:
淡橘:#F1E0CD
深橘:#F6A185
淺灰:F0F0F0
黑咖:#A2998D
