# play-dl (Forked Version)

このリポジトリは、以下のフォークを基にしたものです：

- 元リポジトリ: [play-dl/play-dl](https://github.com/play-dl/play-dl)
- フォーク元: [YuzuZensai/play-dl-test](https://github.com/YuzuZensai/play-dl-test)

## 背景

`play-dl`公式では、YouTube側の仕様変更に迅速に対応できない状況が発生しており、有志の方が修正版をフォークとして提供しています。このリポジトリはそのフォークを元に作成されたもので、**npmから簡単にインストールできるようにする**ために公開しています。

## インストール方法

以下のコマンドを使用して、このリポジトリのバージョンを直接インストールできます：

```bash
npm install git+https://github.com/yuyutti/play-dl.git
```

## 特徴

- 元の `play-dl` と同様の機能を提供します。
- **インポート文を変更する必要がありません**。
  
  ```javascript
  const play = require('play-dl');
  ```
  または
  ```javascript
  import play from 'play-dl';
  ```
  と記述すれば動作します。

## 注意事項

このリポジトリは修正版をnpmで入れやすくするためのフォーク版であり、公式リポジトリとは異なることにご注意ください。また、このリポジトリが今後のYouTube仕様変更に対応できる保証はありません。

## ライセンス

元の `play-dl` のライセンスに準じます。