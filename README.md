# MSOE
1. 游標點擊可以移動
2. 計算midi音高 (this.miditone inside class / MSOE.miditone outside class)
3. 更正節拍計算方式(基礎拍子會隨拍子定義的分母改變)
4. 增加聲部功能，可以新增、刪除、交換順序 (w 新增 shift+w 刪除 r 指定要交換的第一個聲部 shift+r 當前聲部與被指定過的交換位置) (1~6 切換編輯的聲部)
5. 增加調整譜號功能 (q 啟動調整譜號模式 1~4 譜號模式下更換譜號: treble alto tenor bass)
6. 增加預覽模式(無游標及不可編輯) (e 切換)
7. 修正一些class權限的bug
8. 現在打和弦時可以升降最後一個輸入的note的key，放開shift後不可再修改
9. 更改游標顯示，現在游標會隨著Dstate改變，讓使用者在調整節拍時更直覺
10. 現在使用"s"或"a"分合音符時，是對游標前兩個音符作用
11. 新增啟動瀏覽器列印樂譜(可以另存成pdf) (t 使用)
