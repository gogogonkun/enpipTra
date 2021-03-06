# 議事録(設計)
---
## ヘッダー
|項目|内容|
|:--:|:--:|
| 日時 | 2016/11/2 15:00 ~ 16:20|
| 参加者 | 長内、風間、山田、佐々木、工藤 |
| 欠席者 | 加藤 |
| 会議種別 | デモについての共有、画面イメージの詳細設計 |
| 場所 | はこだて未来大学、室蘭工業大学、岩手県立大学 |

---
## 目次
1. [デモについて](#anchar1)
2. [画面・機能設計の詳細化](#anchar2)
4. [利用ツール](#anchar3)
5. [その他特記事項](#anchar4)
6. [次回の予定](#anchar5)

### 今日の成果物
- 画面イメージ　URL : https://github.com/enpit2016fun/pbl_e/blob/documents/ScreenLayout/

---

## <div id="anchar1"/>デモについて<font color = "red">*</font>
- 端末
	- Nexus7, 9 (タブレット端末)
- 11月4日用
	- ポリコムの画面越しに実機を見せる形で発表
- 中間?最終発表
	- 岩手県立大学でデモ用動画を撮影
	- 40 ~ 50人程度が部屋内にいる前提（圧倒的に人が足りないのでビーコンを人に見立てて行う可能性あり）
	

## <div id="anchar2"/>画面・機能設計の詳細化<font color = "red">*</font>
- プロフィール表示画面
	- 基本項目表示：名前，国籍などなど（facebookから取得）
	- 個別項目表示（facebookから取得できる項目の中に無いもの）
	- 一言コメント表示
	- 会うのは何度目か表示
	- 位置情報表示（ビーコンを使用する場合）
	
- プロフィール編集画面
	- 一言コメント編集
	- 顔写真変更
	- 公開範囲の設定（表示，非表示）
	  特定の相手への非公開設定まではしない
	  
- 近くのユーザ一覧表示画面
	- zoomバー
		- どの程度の距離まで画面に表示するのかを指定（縮尺設定のような）
	 	- 画面に表示される人の数が多くなるにつれてアイコンを小さくする　
			- 画面表示がごちゃごちゃするのを防止するため
	- プロフィール画面への遷移
		- 画面上アイコンをタップした場合
	- プロフィールが類似している人（共通の趣味とか）を可視化
		- 画面上アイコンの色を変化させる
	 
- 過去に会ったユーザ一覧表示画面
	- リストで表示(DBから一覧を取得)
	- ソート，絞り込み
	
- サイドメニュー(左から出てくるやつ)
	- 各表示画面への遷移
	- 近くのユーザ一覧表示画面で表示する人のフィルター設定（仮）
		- 例：「野球」が好きな人だけ表示したい・・・・
	  
- 各画面共通項目
	- 一言コメントのポスト（あったらいいな・・・くらいな感じ）
	
※画面ベースでのやることなので，「別の場所で再会したときに通知」のような機能もありますが，上記には含めてません・・・

## <div id="anchar3"/>利用言語・開発環境<font color = "red">*</font>
- 言語
	- Java

## <div id="anchar4"/>利用ツール<font color = "red">*</font>
- プロジェクト管理、バージョン管理、タスク管理
	- GitHub  

## <div id="anchar5"/>次回の予定
- 開発の分担決め
- デモ
- デモプログラムの共有（チーム内）
- 個人作業
	- タスクの細分化

