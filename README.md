
# 20181213
```
/* prog10_2, 指標變數的宣告 */
#include <stdio.h> 
#include <stdlib.h>
int main(void)
{
   int *ptr,d=100,num=20,c=33;	/* 宣告變數num與指標變數ptr */

   ptr=&num;			/* 將num的位址設給指標ptr存放 */
   printf("num=%d, &num=%p\n",num,&num); 
   printf("*ptr=%d, ptr=%p, &ptr=%p\n",*ptr,ptr,&ptr); 
   printf("c=%d, c的位址=%p\n",c,&c); 
   printf("d=%d, d的位址=%p\n",d,&d); 
   system("pause");
   return 0;
}
```
```
假如 c存放的位址是000000000062FE3C
請問你 
[1]d的位址為何?
[2]num的位址為何?
[3]ptr的位址為何?
```



# 20181018作業
```
完成Python教科書Ch 1.9的閱讀與練習
完成Python教科書Ch 1作業:十題以上(放在你的github)
```
```
完成Python教科書Ch 2作業:2.1+2.5(放在你的github)
ex2.2
ex2.11
ex2.18
完成Python教科書Ch 2作業:2.5+2.6+2.7+2.21(放在你的github)
```
```
完成Python教科書Ch 3作業:3.8-3.11(放在你的github)
```
# C
```
runoob
```

# 參考書
```
C語言教學手冊（四版）（附1光碟）
作者： 洪維恩  
出版社：旗標 
https://www.books.com.tw/products/0010360466
```
```
Python程式設計入門指南
Introduction to Programming Using Python
作者： Y. Daniel Liang  

譯者： 蔡明志
出版社：碁峰 
https://www.books.com.tw/products/0010719771
```
# C 程式設計入門
```
參考書
實用 C 語言程式設計入門
作者： 施威銘研究室  
出版社：旗標  
出版日期：2018/06/15

第 1 章 認識 C 語言
1-1 本章簡介
1-2 上機實作：與 C 語言的第一次接觸
1-2-1 接觸 C 語言：從零開始
1-2-2 輸出第一行字

1-3 C 語言的基本輸出入和程式架構
1-3-1 main(void) 是什麼意思
1-3-2 標頭檔 #include <...> 淺說
1-3-3 程式的分段：使用大括號 {} 與分號

1-4 程式的註解與編排
1-4-1 適時的分行：便於整篇程式的閱讀
1-4-2 程式碼內縮：表現出程式的層次感
1-4-3 善用註解：幫助了解程式
1-4-4 使用區塊註解
1-5 如何讓 C 語言程式變成可以執行

第 2 章 常數與變數
2-1 本章簡介
2-2 定義常數
2-2-1 用 #define 定義常數
2-2-2 定義常數不可更改其值

2-3 變數的資料型別
2-3-1 資料型別的類型與長度
2-3-2 資料型別的修飾字
2-3-3 數值發生溢位的情況

2-4 變數命名的原則與習慣
2-4-1 變數命名的合法性
2-4-2 變數命名的習慣

2-5 宣告變數
2-5-1 宣告變數的語法
2-5-2 宣告變數的位置
2-5-3 指定變數的值
2-5-4 兩個變數的值互相交換
2-5-5 宣告變數的修飾詞 - const

2-6 變數的資料型別轉換
2-6-1 整數轉成浮點數
2-6-2 浮點數轉成整數
2-6-3 字元和數字間的轉換
2-6-4 大寫字母轉成小寫字母

第 3 章 基本輸出與輸入函式
3-1 本章簡介

3-2 格式化輸出
3-2-1 以不同進位制控制符號顯示
3-2-2 以科學符號表示法顯示

3-3 輸出格式可用的參數
3-3-1 指定輸出的固定寬度
3-3-2 指定輸出寬度時加上正負符號
3-3-3 讓輸出的數值向左靠齊
3-3-4 組合多個參數輸出

3-4 使用跳脫序列控制輸出
3-4-1 刪除、歸位、跳格跳脫序列
3-4-2 輸出單、雙引號與反斜線的跳脫序列
3-4-3 輸出到此為止的結束跳脫序列

3-5 輸入與輸出單一字元的函式
3-5-1 輸入、輸出字元：getchar()、putchar() 函式
3-5-2 不用按Enter 鍵輸入字元：getche()、getch() 函式

3-6 使用輸入數值函式scanf()
3-6-1 scanf() 函式的用法
3-6-2 輸入的數值與指定的格式要相符
3-6-3 避免讀入Tab、Space、Enter 鍵

第 4 章 運算子、運算元與算式
4-1 本章簡介
4-2 算式的結構

4-3 運算子的優先權
4-3-1 運算子與運算元結合的優先權
4-3-2 運算子優先權相同時的結合性順序

4-4 算術運算子
4-5 括號運算子
4-6 關係運算子
4-7 邏輯運算子
4-8 指定運算子與複合指定運算子
4-9 遞增與遞減運算子

4-10 綜合練習
4-10-1 溫度轉換：攝氏轉華氏
4-10-2 遊樂場換幣機程式
4-10-3 判斷輸入的是否為英文字母
4-10-4 計算整數的階乘

第 5 章 條件判斷式
5-1 本章簡介
5-2 if 條件判斷
5-3 if-else 條件判斷
5-4 if-else if 條件判斷
5-5 if 巢狀條件判斷
5-6 switch-case 條件判斷
5-7 三運算元條件判斷式 ?：

5-8 綜合練習
5-8-1 將Ch05_07.c 改用「switch-case」與「? :」取代
5-8-2 輸入月份與日期，用if-else 與switch-case 查星座
5-8-3 用if-else 與 ? : 將輸入的3 個數字做大小排序

第 6 章 迴圈控制
6-1 本章簡介

6-2 執行指定次數的for 迴圈
6-2-1 改變控制算式的遞增量或遞減量
6-2-2 for 迴圈允許超過一組算式
6-2-3 巢狀for 迴圈

6-3 預先判斷是否執行的while 迴圈
6-3-1 利用while 迴圈猜數字
6-3-2 利用while 迴圈算最大公因數

6-4 後設條件判斷的do-while 迴圈

6-5 無限迴圈
6-5-1 for 無限迴圈的用法
6-5-2 while 無限迴圈的用法

6-6 直接跳出迴圈的break、continue 與goto
6-6-1 跳出一層迴圈可使用break
6-6-2 立刻跳到迴圈開頭的continue
6-6-3 強迫跳到指定標籤名的goto

6-7 綜合練習
6-7-1 輸出英文字母金字塔
6-7-2 找出2~200 之間的所有質數
6-7-3 計算指定正整數的階乘

第 7 章 自訂函式
7-1 本章簡介
7-2 宣告函式的寫法與位置

7-3 定義自訂函式
7-3-1 計算絕對值的自訂函式
7-3-2 計算BMI 的自訂函式
7-3-3 找出質數的自訂函式
7-3-4 計算幾次方的自訂函式
7-3-5 計算度量衡轉換的自訂函式
7-3-6 從自訂函式呼叫另一個自訂函式

7-4 遞迴函式
7-4-1 跌入萬丈深淵的無窮遞迴
7-4-2 利用遞迴算最大公因數
7-4-3 利用遞迴算因數分解
7-4-4 利用遞迴算費氏數列
7-4-5 利用遞迴算正整數的階乘
7-4-6 利用遞迴搬河內塔圓盤

第 8 章 巨集
8-1 本章簡介
8-2 定義巨集與放的位置
8-3 無引數的巨集取代算式
8-4 有引數的巨集取代算式
8-5 多個引數的巨集與條件判斷的巨集
8-6 將算式做為巨集的引數

第 9 章 前置處理
9-1 本章簡介
9-2 將標頭檔含括進程式
9-2-1 內建的標頭檔
9-2-2 自己寫的標頭檔
9-3 條件編譯
9-3-1 條件編譯指令 #ifndef、#endif 的用法
9-3-2 條件編譯指令 #ifdef、#else、#endif 的用法
9-3-3 條件編譯指令 #if、#elif、#endif 的用法

第 10 章 陣列
10-1 本章簡介
10-2 一維陣列
10-2-1 宣告一維陣列
10-2-2 宣告陣列時設定初值與改變初值
10-2-3 執行過程指定陣列的數值
10-3 二維陣列
10-3-1 指定二維陣列的初值
10-3-2 執行過程指定二維陣列的數值
10-4 多維陣列
10-5 陣列在函式間的傳遞
10-5-1 傳遞一維陣列
10-5-2 傳遞二維陣列
10-5-3 傳遞陣列是傳遞記憶體位址

第 11 章 字串
11-1 本章簡介
11-2 字元陣列與字串的差異
11-3 宣告字串與設定初值
11-3-1 輸出字串要用%s 控制符號
11-3-2 用字元陣列的方式設定初值
11-4 由鍵盤讀取字串與從螢幕輸出字串
11-4-1 使用scanf() 讀取字串的方法
11-4-2 使用gets() 讀取字串，puts() 輸出字串
11-5 處理字串的函式
11-5-1 複製字串：strcpy() 函式
11-5-2 複製局部字串：strncpy() 函式
11-5-3 算出字串真正的長度：strlen() 函式
11-5-4 比對兩個字串是否完全相符：strcmp() 函式
11-5-5 比對兩字串前面部份是否相符：strncmp() 函式
11-5-6 完整串接兩個字串：strcat() 函式
11-5-7 串接指定字元的字串：strncat() 函式
11-6 字串陣列
11-6-1 輸出字串陣列的初值
11-6-2 讀取、比對字串陣列中的字串

第 12 章 指標
12-1 本章簡介
12-2 記憶體位址
12-3 指標的基本用法
12-3-1 指標佔的記憶體大小與位址
12-3-2 改變指標指向的數值
12-3-3 改變指標指向的變數
12-4 指標與陣列
12-4-1 用指標讀取字串
12-4-2 用指標讀取二維陣列
12-4-3 指標陣列：每個陣列元素都是指標
12-5 指標與函式
12-5-1 傳址呼叫
12-5-2 函式可以傳回指標位址
12-6 雙重指標（指向指標的指標）
12-7 指標與動態記憶體配置
12-8 未指定資料型別的void 指標
12-9 使用指標的好處

第 13 章 變數等級
13-1 本章簡介
13-2 變數的視野與生命期
13-3 內部變數
13-3-1 宣告內部變數，有無auto 都可以
13-3-2 內部變數生命期結束，就被釋放
13-4 外部變數
13-4-1 到處都可用到的外部變數
13-4-2 內部、外部變數名稱相同的優先順序
13-4-3 擴展外部變數視野的extern 用法
13-4-4 跨檔案取用外部變數的extern 用法
13-5 內部靜態變數與外部靜態變數
13-6 暫存器變數

第 14 章 檢驗輸入的資料
14-1 本章簡介
14-2 檢驗英文字母與數字
14-2-1 檢驗字元為英文字母與數字：isalnum() 函式
14-2-2 檢驗字元或數字：isalpha()、isdigit() 函式
14-3 檢驗 ASCII 字元
14-3-1 檢驗 ASCII 字元：isascii()、iscntrl()、isspace() 函式
14-3-2 檢驗大小寫英文字母：isupper()、islower() 函式
14-3-3 檢驗非英數字空格的可列印字元：ispunct() 函式

第 15 章 結構體、共用體、別名、列舉
15-1 本章簡介
15-2 結構體
15-2-1 宣告結構體變數與設定初值
15-2-2 宣告結構體同時宣告結構體變數
15-2-3 結構體中還可以有結構體成員
15-3 結構體變數陣列
15-4 將結構體宣告為指標變數
15-5 將結構體變數傳給函式
15-5-1 傳遞結構體引數的函式原型宣告
15-5-2 結構體變數的傳值呼叫
15-5-3 結構體變數的傳址呼叫
15-6 共用體
15-7 共用體與結構體組合使用
15-8 別名
15-9 列舉

第 16 章 檔案處理
16-1 本章簡介
16-2 檔案讀寫的觀念
16-3 開啟與關閉檔案
16-3-1 開啟檔案：fopen() 函式
16-3-2 關閉檔案：fclose() 函式
16-4 讀取檔案資料
16-4-1 讀取檔案的字元與字串：fgetc()、fgets() 函式
16-4-2 讀取格式化資料：fscanf() 函式
16-4-3 利用正規表示式處理逗點分隔的字串
16-5 寫入檔案資料
16-5-1 將字元與字串寫入檔案：fputc()、fputs() 函式
16-5-2 依格式寫入檔案：fprintf() 函式
16-6 隨機式檔案讀寫
16-6-1 找出指標位置與讓指標回到檔頭：ftell()、rewind() 函式
16-6-2 移動指標並讀取資料：fseek()、fread() 函式
16-6-3 將指定大小的資料寫入檔案：fwrite() 函式

附錄 A ASCII 碼表
附錄 B 使用 Dev-C++
B-1 下載與安裝 Dev-C++
B-2 執行範例程式
B-2-1 開啟 C 程式檔
B-2-2 編譯、連結、執行程式
B-2-3 單獨執行程式
B-3 在 Dev-C++ 中建立新程式檔
B-4 在 Dev-C++ 中建立新專案

附錄 C Dev-C++ 除錯功能
C-1 以逐步執行的方式觀察程式
C-1-1 建立中斷點
C-1-2 逐步執行程式
C-2 使用監看功能
C-2-1 新增監看式
C-2-2 檢視變數值
```
# Python
```
Python程式設計入門指南
Introduction to Programming Using Python
作者： Y. Daniel Liang  

譯者： 蔡明志
出版社：碁峰 
https://www.books.com.tw/products/0010719771
```

```
```
```
```
