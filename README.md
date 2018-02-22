# RubyOmikuji
おみくじ

## 処理
randメソッドを使用して1 ～ 6のランダムな数字を使って、おみくじの結果を出力します。

## コード
```
omikuji = rand(1..6)
if omikuji == 1
  puts "大吉"
elsif omikuji == 2
  puts "中吉"
elsif omikuji == 3
  puts "小吉"
elsif omikuji == 4
  puts "吉"
elsif omikuji == 5
  puts "凶"
elsif omikuji == 6
  puts "大凶"
end
```

## 出力例  
```
中吉
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
