InvoiceQR_ios 
===
- Author : CookieChou(周秉楠)
- Made in Summer 2018 , IBM Taiwan.
- InvoiceQR_ios is an iOS App for invoice QR code Scanner and using the QR code information to **get the api data from Ministry of Finance, R.O.C. (財政部) .**
- The app is a front-end to realize **Microservices** Architecture of back-end.

Introduction
---
- **Microservices Architecture**
<img src="https://i.imgur.com/qM2hpUf.png" height="600" />
- **What are microservices?**
Microservice architecture is an architectural style that structures an application as a collection of loosely coupled services, which implement business capabilities. The microservice architecture enables the continuous delivery/deployment of large, complex applications. It also enables an organization to evolve its technology stack.

- API GUI Website - Swagger 
![](https://i.imgur.com/6yRIi3E.png)

Demo 
---
- 1. Open the iOS app , enter the Home Page
<img src="https://i.imgur.com/T2xrTPI.jpg" height="600" />
- 2. Grab a electrical invoice , scan the QR code
<img src="https://i.imgur.com/PcpwtjH.jpg" height="600" />
- 3. Alert Dialog : Close Alert , Scan Again , and store the information
<img src="https://i.imgur.com/PcpwtjH.jpg" height="600" />


Installation
---
1. Xcode 10 Download
https://developer.apple.com/xcode/
<img src="https://i.imgur.com/oIsKMr3.jpg" height="600" />
2. Clone the InvoiceQR_ios repository.
``` mac
git clone https://github.com/CookieNotSession/InvoiceQR_ios.git
```
3. Open Xcode
4. Open the QRReader folder
5. Run ViewController.swift

```
1. 目前功能為進入app主頁面，點入QR code Scanner 的Button進入QR code掃描模式
2. 掃完發票後，取得發票號碼前15碼，並串連Get API，可選擇「再掃一次」以及「下一步」
3. 進入儲存發票頁面後，除了show出發票內容，可按下方「儲存發票」按鈕，即可call POST API
```

