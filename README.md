# funBIZ.Bank.SinoPac
# 永豐銀行豐收款線上金流說明

SinoPac- funBIZ Example

此專案內容包含永豐豐收款(funBIZ)內信用卡支付與行動支付初步Demo介紹。

Required

1.適合具有一定程式開發能力，使用NET/PHP/Java等開發技術的工程人員使用。

2.了解https的request及response格式與過程，對Json格式有所了解與掌握。

3.請至 https://developer.sinopac.com/e-pay.html  填寫相關聯繫方式，專人聯繫後進行申請豐收款測試環境。

Overview

請確認您開發前已從永豐技術客服 得到以下重要串接資料

(1) 商店代號 (ShopNo)：識別商戶專用代號 。

(2) Hash值 (四組 )：產出安全簽章及訊息加密用獨立參數 。

(3) X-KEY：有限時效性之API認證憑證資訊 。

(4) Sample code：目前提供.NET/PHP範例於永豐官方測試站內下載參考。

--------------------------------------------------------------------------

取得完整測試環境後可進行下列金流服務測試：

1.OrderCreate
可建立下列收款管道的金流訂單：虛擬帳號/信用卡/行動支付/LinePay。

2.OrderMaintain
對於訂單資訊進行維護。

3.OrderQuery
對於付款/未付款訂單進行查詢。

4.OrderPayQuery
主動式接收付款成功資訊。

5.BillQuery 
交易對帳檔查詢服務。

6.OrderBack
若有PCIDSS的公司戶可進行刷卡頁自建串接。

7.LinePayOrderQuer
一站式查詢各通路金流收款狀況。

--------------------------------------------------------------------------

# 信用卡 for SinoPacfunBIZ 

![信用卡交易](https://github.com/SinoPacBK/funBIZ.Bank.SinoPac/assets/121604028/0ddb0e98-a5b7-4a64-b3d6-df27ab312d81)

Required

1.適合具有一定程式開發能力，使用NET/PHP/Java等開發技術的工程人員使用。

2.了解https的request及response格式與過程，對Json格式有所了解與掌握。

3.請至 https://developer.sinopac.com/e-pay.html 填寫相關聯繫方式，專人聯繫後進行申請豐收款測試環境。

Overview

請確認您開發前已從永豐技術客服 得到以下重要串接資料

(1) 商店代號 (ShopNo)：識別商戶專用代號 。

(2) Hash值 (四組 )：產出安全簽章及訊息加密用獨立參數 。

(3) X-KEY：有限時效性之API認證憑證資訊 。

(4) Sample code：目前提供.NET/PHP範例於永豐官方測試站內下載參考。

--------------------------------------------------------------------------

# 行動支付 for SinoPacfunBIZ 

![行動支付](https://github.com/SinoPacBK/funBIZ.Bank.SinoPac/assets/121604028/ba1be9a7-5ebf-4d59-99e1-ca6762b200de)

Required

1.適合具有一定程式開發能力，使用NET/PHP/Java等開發技術的工程人員使用。

2.了解https的request及response格式與過程，對Json格式有所了解與掌握。

3.請至 https://developer.sinopac.com/e-pay.html 填寫相關聯繫方式，專人聯繫後進行申請豐收款測試環境。


Overview

請確認您開發前已從永豐技術客服 得到以下重要串接資料

(1) 商店代號 (ShopNo)：識別商戶專用代號 。

(2) Hash值 (四組 )：產出安全簽章及訊息加密用獨立參數 。

(3) X-KEY：有限時效性之API認證憑證資訊 。

(4) Sample code：目前提供.NET/PHP範例於永豐官方測試站內下載參考。

