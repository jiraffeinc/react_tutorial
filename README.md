## 課題内容
### 1.Intro To React
https://reactjs.org/tutorial/tutorial.html  
上記をGoogle Chromeで動作するものを作成

- [ ] Google Chromeで動作

### 2.Intro To React仕様追加
- [ ] 1.Display the location for each move in the format (col, row) in the move history list.
- [ ] 2.Bold the currently selected item in the move list.
- [ ] 3.Rewrite Board to use two loops to make the squares instead of hardcoding them.
- [ ] 4.Add a toggle button that lets you sort the moves in either ascending or descending order.
- [ ] 5.When someone wins, highlight the three squares that caused the win.

### 3.更に仕様追加
要件が満たされていれば、UI設計などはお任せします。  
設定画面などに適時モーダルやreact-routerなどを使用すると面白いかもしれません。

#### 1.リファクタリング
- [ ] ・クラス毎にファイルを分割してES Moduleでロードする形にしてみましょう

#### 2.マスを選択可能に
- [ ] ・3マスから5マスに変更してみましょう
- [ ] ・スタート前に3マスか5マスか選べるようにしてみましょう

#### 3.CPU対戦
- [ ] ・CPUプレイヤーと対戦できるようにして見ましょう
- [ ] 　・CPUプレイヤーは自分のターンにランダムで空いてるマスを埋めます
- [ ] ・スタート時にCPU対戦か、2プレイヤー対戦か選べるようにしてみましょう
- [ ] 　・余力があったら、自分のターンに列が空いている、もしくは自分が取っていて勝率の高いマスを埋めるなど、CPUの思考ロジックを賢くしてみましょう（後回しでOKです

#### 4.対局履歴を記録・閲覧可能にする
- [ ] ・対局終了時に履歴を記録
- [ ] 　・対局終了は勝者決定 or 引き分け
- [ ] ・1回の対局履歴をリスト表示
- [ ] 　・日時、勝者をリスト表示
- [ ] ・対局履歴を選択し、閲覧ボタンを押下でその対局履歴を表示
- [ ] ・対局履歴をlocal storgeを利用して永続化

#### 5.state管理をfluxアーキテクチャにする
- [ ] ・stateの管理を[redux](https://github.com/reactjs/redux)などのfluxアーキテクチャに載せ替えてみましょう

## ツッコミやPR募集中です！！
