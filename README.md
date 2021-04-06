# flmaker
## 概要
ファイルを簡単にたくさん作成するためのツール
## 動作確認
Mac
ruby 2.7.2
## インストール
- git cloneあるいはコピペでflmakerというファイルを作り、``~/bin``あたりに配置し、権限を付与する
## 使用方法
引数 (1: 出力パス, 2: ファイル名, 3: 繰り返し数)
```
$ ruby flmaker ./ abc 6
$ ls
abc0		abc1		abc2		abc3		abc4		abc5
```

or (1: ファイル名, 2: 繰り返し数) 
```
$ ruby flmaker abc 6
$ ls
abc0		abc1		abc2		abc3		abc4		abc5
```

or (1: 繰り返し数)
```
$ flmaker 30
$ ls
0	10	12	14	16	18	2	21	23	25	27	29	4	6	8
1	11	13	15	17	19	20	22	24	26	28	3	5	7	9
```
