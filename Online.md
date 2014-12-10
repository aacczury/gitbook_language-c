# 線上

<br />**Koding**
<br />https://koding.com/

<br />![Koding](http://i.imgur.com/llkyl8u.png)
<br />先辦個帳號(Sign Up)~

<br />![Setting](http://i.imgur.com/A5g2AVr.png)
<br />辦好後它會開始設定環境，等它一下

<br />![Init](http://i.imgur.com/n15hatK.png)
<br />設定完以後的初始畫面

<br />![Save](http://i.imgur.com/3y2KF48.png)
<br />打個程式(↓)後存檔(Ctrl+S)，檔名(Filename)打XXXX.c (XXXX可以隨便打)
<br />
```
#include <stdio.h>

int main(){
    printf("Hello World\n");
    return 0;
}
```

<br />![ls](http://i.imgur.com/VOjBbcH.png)
<br />在Terminal(終端機)的地方打ls，他會列出這個資料夾裡面有哪些檔案
<br />可以看到我們有四個資料夾(Applications, Backup, Documents, Web)
<br />兩個檔案(HelloWorld.c, README.md)

<br />![Compile](http://i.imgur.com/9nL5KIO.png)
<br />輸入 gcc -o HelloWorld HelloWorld.c
<br />編譯程式(Compile)，原本的.c檔是人類看得懂的語言(和一堆0跟1比起來)，要把它轉換成電腦看得懂的語言(一堆0跟1)
<br />gcc: C語言的編譯器(Compiler) (白話講就是一種翻譯機)
<br />gcc -o <執行檔的名字> <程式碼的名字>

<br />![ls](http://i.imgur.com/Ibm2rMg.png)
<br />ls後可以看到多了一個HelloWorld的執行檔

<br />![run](http://i.imgur.com/b8eNSho.png)
<br />打上./HelloWorld，執行HelloWorld這個程式 (./ 是現在這個資料夾的意思)
<br />它就會印出Hello World了~

