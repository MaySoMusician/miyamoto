# 勤怠管理bot - 宮本さん

Google Apps Scriptで書かれた、Slack用勤怠管理Bot。

Slackで下記の様につぶやくと、宮本さんがGoogle Spreadsheetに記録してくれます。

## 会話例
- おはようございます ← 現在時刻で出勤
- おはようございます 12:00 ← 指定時刻で出勤
- 12:00に出勤しました ← 指定時刻で出勤
- お疲れ様でした ← 現在時刻で退勤
- お疲れ様でした 20:00 ← 指定時刻で退勤
- 20時に退勤しました ← 指定時刻で退勤
- 明日はお休みです ← 休暇申請
- 10/1はお休みです ← 休暇申請
- 明日のお休みを取り消します ← 休暇申請取り消し
- 明日はやっぱり出勤します ← 休暇申請取り消し

- 誰がいる？ ← 出勤中のリスト
- 誰がお休み？ ← 休暇中のリスト
- 9/21は誰がお休み？ ← 指定日の休暇リスト

## 設置方法