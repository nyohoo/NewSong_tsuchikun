# リリース通知くん -お気に入りアーティストの新曲お知らせBot-

## サービス概要
「学生時代に推しだったアーティストのアルバム最近全然追えてないなぁ・・・」　
ーー　こんな悩みをお持ちのあなた！　日々、忙しく過ごしているとなかなか情報をアーティストの活動を追いかけるのって大変ですよね
本サービスでは、LINE通知を利用し、事前に登録したお気に入りアーティストの新曲リリース情報をいち早くお知らせいたします！

## 想定しているサービスの流れ
1. SpotifyAPIを利用して、ユーザーにお気に入りのアーティストを登録してもらいます。
1. User情報に登録アーティストを紐づけて保存しておきます
1. 定期実行の処理で、登録したアーティストの新曲のリリース日付が現在日付と一致しているか確認
1. 一致していた場合は新曲リリースありと判断し、LINEBOTにて通知をユーザーに送信

