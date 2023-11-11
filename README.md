https://www.youtube.com/watch?v=uZ4KZ6zKBn0

參考網站:
jiejin0327/2021-VRDL-HW1-Bird-Images-Classification	https://github.com/jiejin0327/2021-VRDL-HW1-Bird-Images-Classification

遇到的難點:
1.在進行鳥類辨識系統時，發生程式正常執行完畢且無報錯的情況下，沒有如預期output。
解決辦法: 由於沒有報錯，推測並非程式語法方面錯誤，進行多次交叉比對，發現在使用"torch"後，實際上並沒有執行，推測為電腦硬體因素，而後使用colab，程式順利執行，完成model。
2.鳥類辨識系統在colab 可以讀取model，而本地無法讀取。
解決辦法: 推測gpu不符合主流市場，於是將所有程式碼中要求硬體部分的標準改低，並成功本地讀取。
3.django客戶端圖片上傳，實現方法困難。
解決辦法: 利用model格式，將圖片下載到本地，並將其統一格式成jpg，以執行鳥類辨識系統。
