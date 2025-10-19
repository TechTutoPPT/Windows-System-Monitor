[![](https://github.com/TechTutoPPT/Windows-System-Monitor/blob/main/IMG_8403.PNG)](https://youtu.be/ZPCOMcJlm68)

評估電腦是否運作正常, 最直觀的方法就是查看電腦各裝置的運作情況, 例如CPU佔用比率是否長期維持在高水平, 
記憶體是否顯示容量不足, 磁碟是否長期處於高強度運轉, 平時網絡是否有不尋常的流量等等.

要查看以上資訊最簡單的方法就是執行Windows內置的工作管理員, 透過按下Ctrl+Shift+Esc便能打開, 再於效能頁去查看各裝置的運作情況,
亦可透過另一方法, 以快捷鍵Win+G去啟動Game Bar功能, 於效能頁亦有相關資訊.

但我覺得以上操作還是不夠直觀, 尤其現今很多平板電腦或筆電竟然將硬碟運作的指示燈都刪減掉, 很多時在安裝, 移除或更新軟件的跑碼過程中
畫面會停在一個位置, 長期不動, 究竟是正常運作中還是遇上錯誤呢程序已終止呢? 這時如果能看到硬碟是正在讀寫中便能比較易作出評估, 
為此我安裝上以下這個簡單的硬碟運作指示燈工具:
先到官網下載DiskLED:
```
https://helgeklein.com/free-tools/diskled
```
將它解壓, 複製內裡的DiskLED.exe檔案, 再按下Win+R輸入shell:startup以打開Windows啟動應用資料夾, 然後於資料夾右鍵貼上捷徑便完成安裝.
現在雙擊這捷徑於右下角的系統匣中會顯示DiskLED圖示, 如果圖示被隱藏, 可透過右鍵工作列設定>系統匣圖示>其他系統匣圖示, 將Hard disk activity LED設為開啟.

除了顯示硬碟運作情況外, 如你還想直觀查看例如CPU, RAM及網絡等資訊, 我會介紹TrafficMonitor這工具:
先到官網下載TrafficMonitor:
```
https://github.com/zhongyang219/TrafficMonitor
```
又是將它解壓, 複製內裡的TrafficMonitor.exe檔案, 再按下Win+R輸入shell:startup以打開Windows啟動應用資料夾, 然後於資料夾右鍵貼上捷徑便完成安裝.
雙擊這捷徑便會顯示TrafficMonitor介面, 現時只有網絡流量資訊, 右鍵它點選顯示更多資訊便會有CPU及RAM的資訊, 現在你可將它拖移到喜歡位置
並將它設為是否最上層顯示及鎖定視窗位置.

