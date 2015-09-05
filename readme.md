## 注意
本項目使用 GPL v3 協議。改編者請注意開源並使用相同協議。
本人輕度執行 Apache 關於文檔的標準，卽，對修改的內容做出說明。索引的修正多記錄在 https://github.com/821/Acorns 中，此處主要記錄圖片的處理。

## 緣起
中文博大精深，但辭書的質量卻不好恭維，需要多看多查。由於目前中文辭書普遍缺乏電子化，而 OCR 的質量又不可能很高，能對照原書的意義就非常重大了。
本項目儘量多收權威級辭書，讓每個字詞都能輕鬆找到多種解釋，讓人能夠快速把握字詞的大致意義和用法。同時，本項目衹使用「字頭—頁碼—原書圖像」的形式，確保與直接查書的一致性，這樣不但引用方便，而且也能最大限度降低錯誤率。

## 模式
考慮到版權問題，本項目衹放出檢索文件，原書圖片衹存在於文檔的介紹中。文檔會記錄圖片材料的來源、處理方式、缺憾等。
每部辭書都有頁面導航，比如康煕字典，輸入 kx1111 ，則得其第 1111 頁；輸入 KXI001 ，則得其索引頁第一頁（但不是所有辭書都有索引）。爲了方便翻頁，每一頁也都有前後導航。

## 原則
低損。儘量重現原書之貌。
開放。全部給源碼。
有序。記錄材料源頭和有損處理過程，保證流傳有序。

## 歷史
最初構想： 2011 年。
實際動工： 2013 年 8 月。
重新整理： 2015 年 8 月。

## 子目
（按照辭書初版的出版日期排序。）

### 康煕字典 (kxzd)
圖像：中華書局 2010 版（同文書局版之影本，附現代檢字表） 04h pdg ， ssid: 12622261 。對原圖放大一倍、糾斜、裁邊並轉爲單色 tif 。處理後圖片總體積從 988MB 縮至 366MB 。
索引： kx2ucs.txt ，見 https://github.com/cjkvi/cjkvi-dict/ 。
康煕字典版本太多，中華書局影印了同文書局版，並添加了現代索引，是當下比較常用的版本。

### 中文大辭典 (ecl)
圖像：中文大辭典 04h pdg ， ssid: 12230963 等。對原圖放大一倍、糾斜、裁邊並轉爲單色 tif 。
索引： http://bbs.xueleku.com/forum.php?mod=viewthread&tid=369962 。順序按頁碼排了，但是最初順序還是丟失了。
中文大辭典的圖像版主要有三個版本，本版， ssid 爲 11598492 等的 02h pdg ，臺灣任眞掃描的 jpg ，其餘基本上是這三個版本經有損轉換而成。 02h pdg 太模糊，任眞版分辨率並不高且頁面較亂，故取本版。

### 漢語大字典 (hydzd)
圖像：漢語大字典第二版 04h pdg （第九卷索引爲 02h ）， ssid: 12621612 等。對原圖放大一倍、糾斜、裁邊並轉爲單色 tif 。處理後圖片總體積從 2.1GB 縮至 948MB 。
索引： http://bbs.unispim.com/forum.php?mod=redirect&goto=findpost&ptid=31606&pid=121595 。 Unicode 所缺字原作 X ，現作「缺字」。爲了便於檢閱，這些缺字統合在了一起。

### 故訓匯纂 (gxhz)
圖像：故訓匯纂 02h pdg ， ssid: 11208070 。對原圖糾斜、裁邊。圖像體積變化不大，從 409 MB 減少至 406MB 。
索引： http://bbs.xueleku.com/forum.php?mod=viewthread&tid=369962 。由於該文件給出了每個字的順序，因而得以按原順序重排。
SS 原圖的淸晰度不夠， 13263942 的 2007 大字版很淸晰，但僅有上冊且沒有文本索引。