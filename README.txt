電子書簡介

1.這本電子書的頁數 ?
共有25頁，但是會依照玩家所回答的答案來決定跳轉頁數，因此，每次遊玩只會看到10頁而已。

2.這本書主要在做什麼 ?
這本書主要是用來測試玩家比較喜歡Python還是C語言(但絕對不要相信XD)，第0頁的部分則是我的自我介紹，而最後兩頁是我參與Sprout2020前半段課程的心得。

3.這本電子書如何操作 ?
依照"enter command:"底下的按鍵指示進行操作即可。

4.這本電子書有什麼功能 ?
僅有最基本規定的5個功能QQ
goto：跳轉到指定的頁面
exit：離開電子書（結束程式）
Qsave：將目前這一頁存檔
Qload：回到先前Qsave存檔的頁面
Search：在這一頁的文字內容中，搜尋特定的字串

5.我是如何完成這本電子書與我的想法 ?
//code的部分
exit：
因為想不到有什麼方法可以結束程式(如果用break的話好像會爆掉QQ)，所以是上網google的。
Qsave & Qload : 
先設一個save變數來存取當前的頁碼，再運用講師已經寫好的PrintPage函數進行輸出。
goto : 
運用<cstring>函數的功能，先將"goto 頁數"拆成"goto"與"頁數"。然後先判斷此指令是否為goto，如果是，再判斷頁數，並運用PrintPage函數進行輸出。
search : 
此部分的code是我認為5個指定指令中最難的，也是我想最久的部分。最後我想出的解法是運用for迴圈，並且將欲收尋的字元與電子書內容的字元進行一一的比對。但這時就產生了一個問題，當兩字串的第一個字元一樣，但後面的字元不盡相同時，程式也會認為那串字串是你所欲收尋的字串。因此，為了避免這種情況發生，我想到一個方式，就是設一個t_or_f變數，當兩字元相等時，t_or_f就加1，不等時則不變，最後再判斷t_or_f是否與欲收尋字串的字串長度相等(因為只要字串中有一個字與欲收尋字串不一樣，t_or_f就不會與欲收尋字串的字串長度相等)。
//電子書內容的部分
image : 
下載https://www.asciiart.eu/裡面的ascii art圖，再依據電子書當頁的text加一些文字或小修改圖片。
(include與import的圖是運用線上的文字轉ascii art的轉換器。網址 : http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)
text :
內容皆為自己所想的(所以絕對不要相信裡面的分析結果XD)。
而會有這個想法則是因為自己本身也會一點點點的Python，然後剛好又碰到有同學一直在猶豫到底要學Python還是C語言，於是我就決定要寫用這個主題來呈現我的大作業，順便幫助她XD (?
(最後...我的英文真的不太好...所以如果有很多錯字或文法錯誤還請講師多多包涵...QAQ)

