# EX.9
## 說明
```
int main() {
    int n, sum = 0;  
    cin >> n;
```
在main函數中，定義兩個整型變量n和sum，n用於存儲輸入的正整數，sum用於存儲可被3整除的數值之和，初始化為0，並使用cin語句將輸入的值存儲在n中。  
```
for (int i = 1; i <= n; i++) {
if (i % 3 == 0) {sum += i;}}
```
使用for循環來遍1到N之間的每一個數。循環i從1開始，每次增加1，直到i等於N。在循環中，使用if判斷i是否能被3整除。如果是，則將i加入到總和sum中。
