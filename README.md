### 標準出力と標準エラー出力をファイルに追記する
```
./test.sh 1>>log.txt 2>&1
```

$ cat test.sh
```
#!/bin/sh

composer update
```

2>&1 標準エラー出力を標準出力へ
1>>[FILE] ファイルへ**追記**
