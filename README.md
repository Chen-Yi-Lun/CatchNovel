# 網路小說擷取
使用C#爬蟲擷取網路小說並輸出成HTML檔案，利用Edge瀏覽器的大聲朗讀功能變成有聲小說
## 目的
  因為使用Microsoft Edge大聲朗讀功能，在有附加廣告的網站會影響其功能(嚴重間斷、夾雜開頭與結尾文字)，所以利用C#爬蟲將其內容擷錄並匯出成HTML方便使用大聲朗讀功能。
## 軟體介面
![](https://github.com/Chen-Yi-Lun/CatchNovel/blob/main/1.JPG?raw=true)
 ⬆圖一
## 使用方法
1. 將Release資料夾下載(若有疑慮可以將[網路文字小說擷取]資料夾下載自行編譯)
1. 點擊Release資料夾內的網路小說文字擷取.exe檔案即可看到上圖介面
1. 找小說可以按左上功能輸入書名或點擊參考網站自己尋找
1. 找到某小說後請點擊該小說的某一章節(參考下方圖二)
1. 複製該章節URL至小說章節網址後面的輸入項
1. 依據需求可點擊是否一次擷取後20篇章(若不足20則有幾章擷幾章)後點擊搜尋(一次擷取20章要稍微等一下，因為有設定延遲，畢竟人家網站也要營運)
1. 一段時間後下方欄位會出現文字代表成功了，此時可以按匯出，或點擊語音進行閱聽。
1. 今天主要目的是使用Microsoft Edge的大聲朗讀，所以按匯出，成功後跳訊息，在桌面上會出現Novel.html.
1. 使用Edge瀏覽器開啟並按右鍵大聲朗讀即可一次聽取多章小說。
## 擷圖
<img src="https://github.com/Chen-Yi-Lun/CatchNovel/blob/main/3.JPG?raw=true"  width="700" height="300">

 ⬆圖二  點擊該小說某的章回後複製其網址
 
<img src="https://github.com/Chen-Yi-Lun/CatchNovel/blob/main/2.jpg?raw=true"  width="700" height="300">

 ⬆圖三  匯出後點擊桌面Novel.html，使用Edge瀏覽器打開按右鍵即可使用大聲朗讀功能，使其變成有聲書。

