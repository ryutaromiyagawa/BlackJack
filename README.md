ブラックジャックゲームをオブジェクト指向を使って実装

## ルール

・実行開始時、ディーラーとプレイヤー全員に２枚ずつカードが配られる
・最大３人までのプレイヤーでプレイすることが可能（ディーラーと合わせて合計４人）
・増えたプレイヤーはCPUが自動的に操作
・自分のカードの合計値が21に近づくよう、カードを追加するか、追加しないかを決める
・カードの合計値が21を超えてしまった時点で、その場で負けが確定する
・プレイヤーはカードの合計値が21を超えない限り、好きなだけカードを追加できる
・ディーラーはカードの合計値が17を超えるまでカードを追加する

各カードの点数は次のように決まっています。
・2から9までは、書かれている数の通りの点数
・10,J,Q,Kは10点
・Aは1点あるいは11点として、手の点数が最大となる方で数える

## 静的解析

以下の静的解析を実施しております。
・PHP_CodeSniffer
・PHPStan
・PHPMD
・PHPUnit
