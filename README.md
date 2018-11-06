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
- [ ] 1.マスを選択可能に
- [ ] ・3マスから5マスに変更してみましょう
- [ ] ・スタート前に3マスか5マスか選べるようにしてみましょう
- [ ] 　・新規対局ボタン押下時にマスの数を選択するダイアログを表示

- [ ] 2.リファクタ＆stateのFlux管理
- [ ] ・クラス毎にファイルを分割してES Moduleでロードする形にしてみましょう
- [ ] ・stateの管理をreduxなどのfluxアーキテクチャに載せ替えてみましょう　https://github.com/reactjs/redux  (これが一番難易度高めので後回しでもOKです)

- [ ] 3.CPU対戦
- [ ] ・CPUプレイヤーと対戦できるようにして見ましょう
- [ ] 　・CPUプレイヤーは自分のターンにランダムで空いてるマスを埋めます
- [ ] ・スタート時にCPU対戦か、2プレイヤー対戦か選べるようにしてみましょう
- [ ] 　・↑ ができたら、自分のターンに列が空いている、もしくは自分が取っていて勝率の高いマスを埋めるなど、CPUの思考ロジックを賢くしてみましょう

- [ ] 4.対局履歴を記録・閲覧可能にする
- [ ] ・新規対局ボタンを追加(ボタン押下時に対戦終了であればリスト化)
- [ ] 　・対局終了は勝者決定 or 引き分け（リストがのlengthが9）
- [ ] ・1回の対局履歴をリスト表示
- [ ] 　・シーケンス、日時、勝者をリスト表示
- [ ] ・対局履歴を選択し、閲覧ボタンを押下でその対局履歴を表示
- [ ] 　・対局履歴閲覧時には変更不可に
- [ ] ・対局履歴をlocal storgeを利用して永続化