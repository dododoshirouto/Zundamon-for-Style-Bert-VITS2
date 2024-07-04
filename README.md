# Zundamon-for-Style-Bert-VITS2
Style-Bert-VITS2を用いたずんだもんの音声モデルです。

### 作成経緯

Style-Bert-VITS2を用いて、自然なイントネーションのずんだもん解説動画を作ろうと思ったが、
[東北ずん子・ずんだもんプロジェクト 公式 マルチモーダルデータベース](https://zunko.jp/multimodal_dev/login.php)の音声データは声優さんが読み上げているものであり、
VOICEVOX独特のイントネーションを表現しようと作成しました。
また、語尾を「のだ」にしたデータを作成し学習させているので、「のだ」調の文章をより自然に読み上げられるようになっていると思います。

### プロジェクト内容

ROHAN：モーラバランス型日本語コーパス 4600文のうち、最初の200文をVOICEVOXで作成しました。
その際、語尾を「のだ」に変換して利用しています。

- 学習結果ファイル
- 学習に使った中間ファイル
- 学習に使ったwavファイル
- wavの作成に使ったvoicevoxプロジェクトファイルと台本データ

### 関連ツール

#### Style-Bert-VITS2
音声を合成するやつ

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=litagin02&repo=Style-Bert-VITS2)](https://github.com/litagin02/Style-Bert-VITS2)

#### VOICE VOX
ずんだもんとかをしゃべらせるやつ

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=VOICEVOX&repo=voicevox)](https://github.com/VOICEVOX/voicevox)

#### ROHAN：モーラバランス型日本語コーパス
学習用音声データにもちいる台本

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=mmorise&repo=rohan4600)](https://github.com/mmorise/rohan4600)



### タグ
[（ず・ω・きょ）](https://zunko.jp/guideline.html)
