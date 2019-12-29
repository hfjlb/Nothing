## mdファイルを組む方法

ネットにあるmdファイルのuriをymlファイルに設定することで、対象mdファイルが組まれる

```javascript
title: 使用方法
subContentItemList:
 - !!map
  title: 各種コンテンツを組む方法
  subContentItemList:
   - !!map
      title: ①mdコンテンツを組む（URIを設定する）
      uri: https://raw.githubusercontent.com/apollographql/apollo-client/master/docs/source/api/react-apollo.md

```

### githubにあるmdファイルを組む前提条件

                
1. 当該ファイルがpublicとなっていること
2. uriに設定されるuriがrawファイルのuriとなること

### raw uriの取得方法

下記添付画像の「Raw」ボタンをクリックして、ブラウザのUriをコピーする


![Image text](https://github.com/hfjlb/Nothing/blob/master/sample/raw.png?raw=true)

