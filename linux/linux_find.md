## 指定檔名搜尋

```
若要在目前的目錄底下，找尋檔案名稱為 secret 的檔案，可以使用：
find .(/) -name secret
執行後，find 會列出所有檔名是 secret 的檔案列表。
```

##範例
```
lab@29d4cf5af0ab:~$ find / -name secret
find: '/proc/tty/driver': Permission denied
find: '/proc/1/task/1/fd': Permission denied
find: '/proc/1/task/1/fdinfo': Permission denied
find: '/proc/1/task/1/ns': Permission denied
find: '/proc/1/fd': Permission denied
/opt/secret
```

## 指定目錄下指定檔案名稱搜尋

```
./gtwang/gtwang.txt
在 /home 目錄底下，找尋檔案名稱為 gtwang.txt 的檔案：

find /home -name gtwang.txt
輸出為

/home/gtwang/gtwang/gtwang.txt

在 /home 目錄底下，不分英文大小寫，找尋檔案名稱為 gtwang.txt 的檔案：

find /home -iname gtwang.txt

輸出為

/home/gtwang/gtwang/GTWang.txt
/home/gtwang/gtwang/GTWANG.TXT
/home/gtwang/gtwang/gtwang.txt
```
