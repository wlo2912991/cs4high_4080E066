# 完成底下linux指令的測試報告

## cd
```
https://hungwei0331.pixnet.net/blog/post/351125458-linux---cd%E6%8C%87%E4%BB%A4%28%E5%88%87%E6%8F%9B%E5%B7%A5%E4%BD%9C%E7%9B%AE%E9%8C%84%29

cd為Change Directory的縮寫, 是用來變換工作目錄的指令。

目錄的表示方式可以使用絕對路徑與相對路徑。

語法：cd [options] [dir]

 

1. 切換工作路徑

 cd /home/username/Desktop

2. 切換至使用者家目錄

#cd ~username or #cd ~ 等同於 #cd /home/username

3. 回到家目錄 /*不加上任何路徑，也是回到自己家目錄*/

# cd

4. 回上一層目錄

# cd ..

5. 絕對路徑寫法 /*指定要前往的完整路徑名稱*/

# cd /Desktop/folder1

6. 相對路徑寫法 /* 相對路徑的寫法，由/Desktop/folder1切換至/Desktop/folder2*/

# cd ../folder2

```
```
root@kali:/bin# ls
'['
 0trace.sh
 2to3-2.7
 411toppm
 7z
 7za
 7zr
```

## pwd
```
https://hungwei0331.pixnet.net/blog/post/352643434-linux---pwd%E6%8C%87%E4%BB%A4

pwd為print name of current/working directory的縮寫

顧名思義pwd用於顯示目前所在目錄的指令,

想要知道目前所在的目錄，可以輸入pwd即可：

1. 列出目前的工作目錄:

#pwd

2. 顯示出實際的工作目錄，而非連結檔本身的目錄名

#pwd -P

3. 目錄連接鏈結時，輸出連接路徑

#pwd -L
```
```
root@kali:~# pwd
/root
```
## cat 
```
https://charleslin74.pixnet.net/blog/post/419873500
名稱：cat
　　使用權限：所有使用者
　　使用方式：cat [-AbeEnstTuv] [--help] [--version] fileName
　　說明：把檔案串連接後傳到基本輸出（螢幕或加 > fileName 到另一個檔案）
　　參數：
　　-n 或 --number 由 1 開始對所有輸出的行數編號
　　-b 或 --number-nonblank 和 -n 相似，只不過對於空白行不編號
　　-s 或 --squeeze-blank 當遇到有連續兩行以上的空白行，就代換為一行的空白行
　　-v 或 --show-nonprinting
```
```

```

## ls
```

-a 顯示所有文件及目錄 (ls內定將文件名或目錄名稱開頭為"."的視為隱藏檔，不會列出)
-l 除文件名稱外，亦將文件型態、權限、擁有者、文件大小等資訊詳細列出
-r 將文件以相反次序顯示(原定依英文字母次序)
-t 將文件依建立時間之先後次序列出
-A 同 -a ，但不列出 "." (目前目錄) 及 ".." (父目錄)
-F 在列出的文件名稱後加一符號；例如可執行檔則加 "*", 目錄則加 "/"
-R 若目錄下有文件，則以下之文件亦皆依序列出

```
```
root@kali:/# ls
0     dev   initrd.img      lib32   lost+found  opt   run   sys  var
bin   etc   initrd.img.old  lib64   media       proc  sbin  tmp  vmlinuz
boot  home  lib             libx32  mnt         root  srv   usr  vmlinuz.old
```
top
ps
ping



## 作業一:說明liunx 上述的目錄結構
### 建目錄 mkdir 與刪除目錄 rmdir

目錄===directory===dir
 ```
 root@kali:/# mkdir ksu
root@kali:/# cd ksu
root@kali:/ksu# pwd
/ksu
```

