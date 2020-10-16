# Millénaire 日本語化Mod

現状，wikiにある通り，[公式の日本語訳](https://www.millenaire.org/translations)は進捗が芳しくないです．

8.1.0へ更新されたことによって他言語と比較しても更に低くなっています...

そこで，なるべく日本語でもMillénaireを楽しめるよう，このプロジェクトを開始しました．

## 導入方法

違和感のあった既存の日本語訳も一部変更していますので，用途に合わせてインストール先を変更して下さい．

まずは，リリースより **[Millenaire_JapaneseTranslation.zip](https://github.com/takuzoo3868/millenaire_JapaneseTranslationMod/releases/latest)** をダウンロードします．

### ステップ①

- 本コンテンツの日本語翻訳へ上書きする方

ダウンロードしたzipを解凍し，`languages/ja`の中身を以下のフォルダへ上書き保存．

```
  ...(省略).../mods/millenaire/languages/ja
```

- デフォルトの日本語訳は変更したくない方

ダウンロードしたzipを解凍し，`languages`を以下のフォルダへコピーします．

```
  ...(省略).../mods/millenaire-custom
```

### ステップ②

「アイテム名」や「進捗」などマイクラ本体と関わる箇所は`languages/ja`の中にある`ja_jp.lang`へ纏まっています．

このファイルについてはMOD本体(jarファイル)の中身を上書きする必要があります．

`mods/millenaire-8.1.0.jar`を7zipなどで開いて，以下のフォルダへ`ja_jp.lang`をコピーします．

```
  ...(省略).../mods/millenaire-8.1.0.jar/assets/millenaire/lang
```

## 備考

特に設定の必要はないはずですが，再起動しても日本語で表示されない場合は

`mods/millenaire`にある`config.txt`の中身を以下のように書き換えます．

```
language=ja
```

文字コードは`UTF-8`，改行コードは`LF`で統一しています．

宗教や歴史要素が強いため，おかしな日本語がありましたらISSUEへ起票願います．

## 注意事項

全体の翻訳が終わったら，Millénaire翻訳チームへこの日本語化プロジェクトをマージしていただけるかコンタクト予定です．

## スクリーンショット

![travelbook](https://imgur.com/i4X0N8U.png)

![panel](https://imgur.com/0ojtnb2.png)

![help](https://imgur.com/aXoJ835.png)

![dialogue](https://imgur.com/LXaD6CO.png)

## 更新履歴

#### 2020/10/17 Ver8.1.0対応中 [gap ja_jp: 95%]

- 交易ヘルプ修正，旅の書，マヤ，セルジューク

#### 2020/10/13 Ver8.1.0対応中 [gap ja_jp: 85%]

- 時代背景を考慮した用語修正，イヌイット，日本

#### 2020/10/11 Ver8.1.0対応中 [gap ja_jp: 79%]

- 儀式表示の修正，インド(buildings,dialogues,reputation,sentences,strings,travelbook)，一部用語の統一

#### 2020/10/06 Ver8.1.0対応中 [gap ja_jp: 75%]

- その他表示内容の修正，ビザンティン(dialogues,sentences,travelbook)

#### 2020/10/02 Ver8.1.0対応中 [gap ja_jp: 72%]

- パネル表示の修正，ビザンティン(buildings,reputation,strings)，ノルマン(dialogues,travelbook)，苦行者の報告書

#### 2020/9/24 Ver8.1.0対応中 [gap ja_jp: 63%]

- 村のクエスト，旅の書の基本的な表示

#### 2020/9/20 Ver8.1.0対応スタート [gap ja_jp: 59%]

- 一般的な表示(strings.txt, ja_jp.lang)，アイテムリスト，ヘルプ改善

#### 2018/2/15 Ver7.1.2対応スタート [gap ja_jp: 54%]

- 一般的な表示(strings.txt)，ヘルプ，ノルマン(buildings,reputation,sentence,strings)，クエスト関連
