# Millénaire 日本語化Mod

現状，wikiにある通り，[公式の日本語訳](https://www.millenaire.org/translations)は進捗が芳しくないです．  
8.1.0へ更新されたことによって多言語と比較しても更に低くなっています．  
そこで，なるべく日本語でも楽しめるよう翻訳作業を進めようと思います．

## 導入方法

違和感のあった既存の日本語訳も一部変更していますので，用途に合わせてインストール先を変更して下さい．

まずは，リリースより **[Millenaire_JapaneseTranslation.zip](https://github.com/takuzoo3868/millenaire_JapaneseTranslationMod/releases/latest)** をダウンロードします．

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

## 備考

特に設定の必要はないはずですが，再起動しても日本語で表示されない場合は`mods/millenaire`にある`config.txt`の中身を以下のように書き換えます．

```
language=ja
```

文字コードは`UTF-8`，改行コードは`LF`で統一しています．

宗教や歴史要素が強いため，おかしな日本語がありましたらISSUEへ起票願います．

## スクリーンショット

TBA

## 更新履歴
2020/9/24 Ver8.1.0対応中 [gap ja_jp: 63%]  
村のクエスト，トラベルブックの基本的な表示

2020/9/20 Ver8.1.0対応スタート [gap ja_jp: 59%]  
一般的な表示(strings.txt, ja_jp.lang)，アイテムリスト，ヘルプ改善

2018/2/15 Ver7.1.2対応スタート [gap ja_jp: 54%]  
一般的な表示(strings.txt)，ヘルプ，ノルマン(buildings,reputation,sentence,strings)，クエスト関連
