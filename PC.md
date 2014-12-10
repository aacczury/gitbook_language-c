# 單機

<br />MinGW
<br />[http://sourceforge.net/projects/mingw/files/latest/download?source=files](http://sourceforge.net/projects/mingw/files/latest/download?source=files)

<br />![Install](http://i.imgur.com/LvzdZ3m.png)
<br />載好以後就開始安裝 Install->Continue->開始裝->Continue

<br />![Install](http://i.imgur.com/vUcUo03.png)
<br />跳出這個視窗後，點mingw32-gcc-g++前面的框框->選Mark for Installation
<br />然後點左上角的Installation->Apply Changes->Apply->開始裝->Close

<br />![bin](http://i.imgur.com/VThNL6U.png)
<br />裝好以後再**C:\MinGW\bin**(如果沒改預設路徑的話)裡面就會長這樣

<br />![PC](http://i.imgur.com/lRTzsni.png)
<br />**我的電腦**右鍵->**內容**

<br />![Env](http://i.imgur.com/Ug1PyR1.png)
<br />**進階系統設定**->**環境變數**

<br />![Path](http://i.imgur.com/qpppTed.png)
<br />下面**系統變數**的地方找到**Path**->**編輯**->把 **C:\MinGW\bin;** 貼在最前面->**確定**->**確定**->**確定**

<br />![cmd](http://i.imgur.com/FNQX9iJ.png)
<br />按**Win+R**叫出執行(或是去**開始**慢慢找)->打**cmd**->**確定**

<br />![gcc](http://i.imgur.com/5uKq5mS.png)
<br />打gcc，如果有跑出gcc: fatal error....就是安裝成功了

