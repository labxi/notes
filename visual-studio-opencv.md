---
description: 安裝、環境設置、遭遇問題及其解決方式。
---

# OpenCV + Visual Studio \(安裝、環境設定\)

## 安裝環境 :

{% hint style="info" %}
作業系統：Windows 10 專業版 \(64 bit\)

軟體版本：「opencv-3.4.2-vc14\_vc15」和「Visual Studio 2015 professional」
{% endhint %}

## OpenCV 

　　OpenCV \(Open Source Computer Vision Library\) 是一個跨平台的電腦視覺庫，可以在商業和研究領域中免費使用，用以開發所有與圖像處理相關的應用程式。

程式下載：[https://opencv.org/releases.html](https://opencv.org/releases.html)

## Step 1 : 執行 OpenCV 的自動解壓縮安裝程式

![](.gitbook/assets/cv001.jpg)

## Step 2 : 自動解壓縮

![](.gitbook/assets/cv002.jpg)

## Step 3 : 解壓縮完成

![](.gitbook/assets/cv003.jpg)

## Step 4 : 在 \[檔案總管\]中的 \[本機\] 或 \[電腦\] 按右鍵，再點選 \[內容\(R\)\]

![](.gitbook/assets/cv004.jpg)

## Step 5 : 點選 \[進階系統設定\]

![](.gitbook/assets/cv005.jpg)

## Step 6 : 點選 \[環境變數\]

![](.gitbook/assets/cv006.jpg)

## Step 7 : 設定 \[系統變數\(S\)\] 中的 Path

![](.gitbook/assets/cv007.jpg)

## Step 8 : 直接新增OpenCV的路徑

![&#x53EF;&#x9EDE;&#x9078; \[&#x65B0;&#x589E;N\] &#x6216;&#x76F4;&#x63A5;&#x9375;&#x5165;&#x300C;C:\opencv\build\x64\vc15\bin&#x300D;](.gitbook/assets/cv009.jpg)

{% hint style="info" %}
「x64」適用於 64 bit 作業系統，若為 32 bit 作業系統則使用「x32」。

「vc15」適用於 Visual Studio 2017 \(編譯器 vc15\)、但用於 VS 2015 尚未遇到問題。

「vc14」適用於 Visual Studio 2015 \(編譯器 vc14\)。
{% endhint %}

## Visual Studio

　　微軟推出的程式開發工具集，以下將以安裝 Visual Studio 2015 professional 的 Visual C++ 為例。倘若無此軟體，可自微軟下載「Visual Studio Community」\(Visual Studio 的免費版本\)，安裝過程大同小異。所有個人開發人員都可以使用 Visual Studio Community 創作自己的免費或付費應用程式，但要注意的是，30天後需要以 Microsoft 帳戶 \(免費申請\) 登入後，才能繼續使用。

Visual Studio Community程式下載：[https://visualstudio.microsoft.com/zh-hant/free-developer-offers/](https://visualstudio.microsoft.com/zh-hant/free-developer-offers/)

## Step 1 : 執行安裝程式

![&#x672A;&#x8207;&#x7DB2;&#x8DEF;&#x9023;&#x7DDA;&#x6642;&#x5C07;&#x51FA;&#x73FE;&#x8B66;&#x544A;&#xFF0C;&#x53EF;&#x9EDE;&#x9078; \[&#x7E7C;&#x7E8C;\(N\)\] &#x8DF3;&#x904E;](.gitbook/assets/vs001.jpg)

## Step 2 : 選擇自訂安裝

![](.gitbook/assets/vs002.jpg)

{% hint style="info" %}
由於 Visual Studio 2015 的編譯器為 vc14，安裝資料夾預設為 Microsoft Visual Studio 14.0
{% endhint %}

## Step 3 : 可視情況選擇所需功能

![](.gitbook/assets/vs003.jpg)

## Step 4 : 在程式語言中，選擇 Visual C++

![](.gitbook/assets/vs004.jpg)

## Step 5 : 確認選取的功能後，點選安裝

![](.gitbook/assets/vs005.jpg)

## Step 6 : 安裝中

![](.gitbook/assets/vs006.jpg)

## Step 7 : 安裝完成，點選 \[啟動\] 開啟 Visual Studio

![](.gitbook/assets/vs007.jpg)

## Step 8 : 可點選 \[不是現在，以後再說\] 略過登入

![](.gitbook/assets/vs008.jpg)

## Step 9 : 點選 \[啟動 Visual Studio\]

![](.gitbook/assets/vs009.jpg)

## Step 10 : 等候首次使用的準備工作

![](.gitbook/assets/vs010.jpg)

## Step 11 : 進入 Visual Studio 起始頁

![](.gitbook/assets/vs011.jpg)

## Step 12 : 新增專案

![&#x6A94;&#x6848;\(F\) -&amp;gt; &#x65B0;&#x589E;\(N\) -&amp;gt; &#x5C08;&#x6848;\(P\)](.gitbook/assets/vs012.jpg)

## Step 13 : 開啟 Visual C++ 的空專案

![Visual C++ -&amp;gt; &#x4E00;&#x822C; -&amp;gt; &#x7A7A;&#x5C08;&#x6848; -&amp;gt; &#x78BA;&#x5B9A;](.gitbook/assets/vs013.jpg)

## Step 14 : 設定屬性

![&#x5728; Project1 &#x6309;&#x53F3;&#x9375; -&amp;gt; &#x5C6C;&#x6027;\(R\)](.gitbook/assets/vs014.jpg)

## Step 15 : 點選 \[組態管理員\(O\)\]

![](.gitbook/assets/vs015.jpg)

## Step 16 : 若作業系統為 64 bit，請選擇 x64

![](.gitbook/assets/vs016.jpg)

## Step 17 : 確認無誤後，點選 \[關閉\]

![](.gitbook/assets/vs017.jpg)

## Step 18 : 設定 \[Include 目錄\]

![VC++ &#x76EE;&#x9304; -&amp;gt; Include &#x76EE;&#x9304; -&amp;gt; &#x4E0B;&#x62C9;&#x5F0F;&#x9078;&#x55AE;&#x5143;&#x4EF6;](.gitbook/assets/vs018.jpg)

## Step 19 : 點選 &lt;編輯...&gt;

![](.gitbook/assets/vs019.jpg)

## Step 20 : 新增一行路徑

![](.gitbook/assets/vs020.jpg)

## Step 21 : 鍵入 opencv 的 include 路徑

![&#x65B0;&#x589E;&#x8DEF;&#x5F91;&#x300C;C:\opencv\build\include&#x300D;](.gitbook/assets/vs021.jpg)

## Step 22 : 設定 \[程式庫目錄\]

![](.gitbook/assets/vs022.jpg)

## Step 23 : 鍵入 opencv 的 lib 路徑

![&#x65B0;&#x589E;&#x8DEF;&#x5F91;&#x300C;C:\opencv\build\x64\vc15\lib&#x300D;](.gitbook/assets/vs023.jpg)

## Step 24 : 確認是否設定完成

![](.gitbook/assets/vs024.jpg)

## Step 25 : 設定相依性

![&#x9023;&#x7D50;&#x5668; -&amp;gt; &#x8F38;&#x5165; -&amp;gt; &#x5176;&#x4ED6;&#x76F8;&#x4F9D;&#x6027; -&amp;gt; &#x4E0B;&#x62C9;&#x5F0F;&#x9078;&#x55AE;&#x5143;&#x4EF6; -&amp;gt; &amp;lt;&#x7DE8;&#x8F2F;...&amp;gt;](.gitbook/assets/vs025.jpg)

## Step 26 : 確認 OpenCV 的 lib 檔名

![](.gitbook/assets/vs026.jpg)

## Step 27 : 將 lib 檔名\(含副檔名\)鍵入輸入框

![](.gitbook/assets/vs027.jpg)

## Step 28 : 新增項目

![&#x5728;\[&#x539F;&#x59CB;&#x7A0B;&#x5F0F;&#x6A94;\]&#x6309;&#x53F3;&#x9375; -&amp;gt; &#x52A0;&#x5165;\(D\) -&amp;gt; &#x65B0;&#x589E;&#x9805;&#x76EE;\(W\)](.gitbook/assets/vs028.jpg)

## Step 29 : 選擇 Visual C++ 的 C++檔\(.cpp\)

![](.gitbook/assets/vs029.jpg)

## Step 30 : 鍵入程式碼

![&#x4F9D;&#x60C5;&#x6CC1;&#x8ABF;&#x6574;&#x5716;&#x6A94;&#x8DEF;&#x5F91;](.gitbook/assets/vs030.jpg)

{% hint style="info" %}
waitKey\(0\)的w須小寫
{% endhint %}

## Step 31 : 點選 \[本機Windows偵測工具\] 執行及偵錯

![](.gitbook/assets/vs031.jpg)

## Step 32 : 出現圖片即代表成功

![](.gitbook/assets/vs032.jpg)

## Step 33 : 加入另一個 .cpp 檔案

![&#x5728;&#x539F;&#x59CB;&#x7A0B;&#x5F0F;&#x6A94;&#x6309;&#x53F3;&#x9375; -&amp;gt; &#x73FE;&#x6709;&#x9805;&#x76EE;\(G\) -&amp;gt; &#x52A0;&#x5165;\(D\)](.gitbook/assets/vs033.jpg)

## Step 34 : 選擇欲加入的 .cpp 檔案

![](.gitbook/assets/vs034.jpg)

## Step 35 : 在 \[原始程式檔\] 中可看到成功加入的 .cpp 檔

![](.gitbook/assets/vs035.jpg)

## Step 36 : 全選並註解

![](.gitbook/assets/vs036.jpg)

{% hint style="info" %}
目的是為了避免同時執行 Sample1.cpp 及 Source.cpp。
{% endhint %}

## Step 37 : 每行皆自動加上「//」

![](.gitbook/assets/vs037.jpg)

## Step 38 : 選擇 Sample1.cpp

![](.gitbook/assets/vs038.jpg)

## Step 39 : 修改圖檔路徑

![&#x300C;&#x8B80;&#x5716;&#x8207;&#x51FA;&#x5716;&#x300D;&#x9700;&#x8A3B;&#x89E3;&#x6216;&#x4E7E;&#x8106;&#x522A;&#x9664;&#xFF0C;&#x4E26;&#x4E14;&#x78BA;&#x8A8D;&#x5716;&#x6A94;&#x8DEF;&#x5F91;&#x662F;&#x5426;&#x7121;&#x8AA4;](.gitbook/assets/vs039.jpg)

## Step 40 : 點選 \[本機 Windows 偵測工具\] -&gt; \[是\]

![](.gitbook/assets/vs040.jpg)

## Step 41 : 成功顯示兩個圖檔

![](.gitbook/assets/vs041.jpg)

## 操作過程中曾遇到的錯誤\(1\) : 

![](.gitbook/assets/error01-1.jpg)

![](.gitbook/assets/error01-2.jpg)

{% hint style="info" %}
OpenCV的路徑未正確加入系統的環境變數。
{% endhint %}

## 操作過程中曾遇到的錯誤\(2\) : 

![](.gitbook/assets/error02.jpg)

{% hint style="info" %}
WaitKey\(0\)中的「W」應為小寫「w」。
{% endhint %}

## 操作過程中曾遇到的錯誤\(3\) : 

![](.gitbook/assets/error03.jpg)

{% hint style="info" %}
圖檔路徑需為絕對路徑，如：「C:\\lena.jpg」。
{% endhint %}

