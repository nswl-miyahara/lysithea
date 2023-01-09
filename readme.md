# 勤怠自動入力＆チェックツール

## セットアップ

1. 「Script Auto Runner」のインストール
> https://chrome.google.com/webstore/detail/scriptautorunner/gpgjofmpmjjopcogjgdldidobhmjmdbm?hl=ja

2. Scriptの設定
- Chrome拡張機能 > ScriptAutoRunner > オプション  
![image](https://user-images.githubusercontent.com/121376398/211330489-57b8712c-7d4b-4cd6-a48d-ec85780d6d85.png)
- [こちらのソースコード](https://raw.githubusercontent.com/nswl-miyahara/lysithea/master/dist/index.js)をコピーして、以下にペースト。
![image](https://user-images.githubusercontent.com/121376398/211331256-d52f38ff-0307-4ce3-a934-87a255adbab2.png)

3. リシテアの確認
- フォームが設定されていればOK  
![image](https://user-images.githubusercontent.com/121376398/211332179-4ad9efe2-d20d-40e2-a3e9-cb018ac2ee39.png)

## 使い方
1. 始業時間と終業時間を選択する
2. チェックボックスはテレワークかどうかを選択（テレワークの場合はチェック）
3. 「勤怠入力」ボタンを選択
4. 始終業時間、テレワーク（選択した場合のみ）、作番（作業コードと作業時間のみ）が自動で入力される  

## その他
- 残業された場合の休憩時間(30分)は自動で計算されます
- 作番は自身で選択して下さい
