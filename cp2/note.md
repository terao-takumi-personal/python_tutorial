インタプリタ起動


1. 直接コマンド上にコードを書いて実行

```shell
python3 -c 'import sys; print(sys.argv[1])' 'hello world'
```
この場合`sys.argv[0]`は"-c"になる。

2. ファイル実行
```shell
python3 cp2/main.py "hello world"
```

3. 対話モード

`python3`で起動

`>>>`が一次プロンプト
`...`が二次プロンプト
二次プロンプトとは、インデントや閉じ括弧が発生するような状況のときに出る。

終了は^Dか`exit()`を実行する。
