dby Shafa A Probosari



Training Session 1[https://drive.google.com/file/d/19ER5FZV7p3mHNjpikg3CilPqANM8IXOs/view?usp=sharing](https://drive.google.com/file/d/19ER5FZV7p3mHNjpikg3CilPqANM8IXOs/view?usp=sharing)


* Metric Dashboard 


* Campaign Creation (Push Notification & In-App) 


* Segment creation 


* Help Center 


* MoEngage Academy



![](images/storage/MoEngage_Training_Part_1.mp4)

Training Session 2[https://drive.google.com/file/d/1eVh9YAlWuLdf4r68Y8qL1m66Owsp3jMs/view?usp=sharing](https://drive.google.com/file/d/1eVh9YAlWuLdf4r68Y8qL1m66Owsp3jMs/view?usp=sharing)


* Analytics



![](images/storage/MoEngage_Training_Part_2.mp4)

General guidelines for number of characters  **General guidelines for number of characters**  allowed for each platform are: ([https://help.moengage.com/hc/en-us/articles/208735856-Create-scheduled-push](https://help.moengage.com/hc/en-us/articles/208735856-Create-scheduled-push) )


* Android - Between 450-650 characters


* iOS - Between 150-230 characters



For best response to push (Anroid and iOS), we recommend


* Text with Image - Title: 25 characters, Message Body: 45 characters


* Text Only - Title: 25 characters, Message Body: between 60-65 characters


* Payload size for Anroid should be less than 4KB



For best response to Push Amp+ (Anroid), we recommend


* Title: Less than 50 characters


* Message: Less than 128 characters


* Image: Dimension should be 984±15 px X 450± 15 px.


* Payload size for Push Amp+ should be less than 3KB





Using External URL as Campaign Action

|  **OS**  |  **Click Action**  |  **Viewer Result**  |  **Format Link**  | 
|  --- |  --- |  --- |  --- | 
|  **Android**  | Deeplink | Webview | KUNCIEMOE://kuncie.co.id/promo&type=url&destination={URL}&external=no&flag=moe | 
|  |  | Browser(open app and browser at the same time) | KUNCIEMOE://kuncie.co.id/promo&type=url&destination={URL}&external=yes&flag=moe | 
|  |  | Browser(seamless without opening the app) |  **_Direcly put the URL link_**  | 
|  **iOS**  | Deeplink | Webview | OLD: KUNCIEMOE://kuncie.co.id/inappbrowser&type=url&destination={URL}&active=true NEW: KUNCIEMOE://kuncie.co.id/promo&type=url&destination={URL}&external=no&flag=moe | 
|  | Richlanding | Browser(seamless without opening the app) |  **_Direcly put the URL link_**  | 



Deeplink Format

|  **Deeplink to…**  |  **Format Link**  |  **Status**  | 
|  --- |  --- |  --- | 
|  **General/ Dynamic link**  | [https://app.adjust.com/j243hjn?deeplink=kunciemoe%3A%2F%2Fkuncie.co.id%2F](https://app.adjust.com/j243hjn?deeplink=kunciemoe%3A%2F%2Fkuncie.co.id%2F) | Ready to use | 
|  **Mentor**  | OLD: KUNCIEMOE://kuncie.co.id/mentor&type=mentor&mentorId={id}&active=true NEW: KUNCIEMOE://kuncie.co.id/promo&type=mentor&mentorId={id}&external=no&flag=moe | Ready to use | 
|  **Module**  | OLD: KUNCIEMOE://kuncie.co.id/module&type=module&moduleId={id}&active=true NEW: KUNCIEMOE://kuncie.co.id/promo&type=module&moduleId={id}&external=no&flag=moe | Ready to use | 
|  **ContentBite**  | KUNCIEMOE://kuncie.co.id/promo&type=content&contentBiteId={id}&moduleId={id}&external=no&flag=moe | Ready to use | 
|  **Chat on ContentBite**  | OLD: KUNCIEMOE://kuncie.co.id/chat&type=chat&channelId={id}&active=true NEW: KUNCIEMOE://kuncie.co.id/promo&type=chat&channelId={id}&external=yes&flag=moe | Ready to use | 
|  **Referral**  | OLD: KUNCIEMOE://kuncie.co.id/referral&type=referral&active=true NEW: KUNCIEMOE://kuncie.co.id/promo&type=referral&external=no&flag=moe | Ready to use | 





*****

[[category.storage-team]] 
[[category.confluence]] 
