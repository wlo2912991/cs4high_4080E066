說明底下程式執行結果

# For 迴圈(loop)
```
for name in ['orange', 'apple']:
	print(name)
  
 答案:orange
      apple

```

```
for index in range(0, 6):
	print(index)
  
  從0開始 數六次
  0 1 2 3 4 5

```

### 程式設計題
```
使用For 迴圈(loop)計算1+2+3+.....100
sum=0
for index in range(1,100):
    sum += index
print(sum)   //總和

sum=0
for index in range(1,100):
    sum += index
    print(sum)   //過程
```

```
使用For 迴圈(loop)計算1+3+5+7.....+99

sum=0
for index in range(1,100,2):
    sum += index
print(sum)

```
```
使用For 迴圈(loop)計算1*3*5*7.....*99
sum=1
for index in range(1,100,2):
    sum *= index
print(sum)

```
# while 迴圈(loop)




### 程式設計題
```
使用while 迴圈(loop)計算1+2+3+.....100
sum=0
index=0
while index < 100 :
    index += 1
    sum += index
print(sum)
```
```
使用while 迴圈(loop)計算1+3+5+7.....+99

sum=1
index=1
while index < 99 :
    index += 2
    sum += index
print(sum)
```

```
使用while 迴圈(loop)計算1*3*5*7.....*99
sum=1
index=1
while index < 99 :
    index += 2
    sum *= index
print(sum)
```
