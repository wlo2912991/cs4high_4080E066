
# base64 編碼

```
用法：base64 [選項]... [文件]
使用 Base64 編碼/解碼文件或標準輸入輸出。

  -d, --decode 解碼數據
  -i, --ignore-garbag 解碼時忽略非字母字符
  -w, --wrap=字符數 在指定的字符數後自動換行(默認為76)，0 為禁用自動換行

      --help 顯示此幫助信息並退出
      --version 顯示版本信息並退出

如果沒有指定文件，或者文件為"-"，則從標準輸入讀取。
```

## 範例

```
lab@29d4cf5af0ab:~$ base64 -d base64.txt
BreakALLCTF{XvXeVX5Ae9FwnYmDV2jU}l
```
