## pdfファイルを組む方法

ネットにあるmdファイルのuriをymlファイルに設定することで、対象mdファイルが組まれる

```javascript
title: 使用方法
subContentItemList:
 - !!map
  title: 各種コンテンツを組む方法
  subContentItemList:
   - !!map
      title: ③pdfコンテンツを組む（URIを設定する）
      uri: https://github.com/hfjlb/Nothing/raw/master/xx.pdf
```

### githubにあるpdfファイルを組む前提条件

                
1. 当該ファイルがpublicとなっていること
2. uriに設定されるuriがrawファイルのuriとなること

### raw uriの取得方法

下記のpptxファイルを例として

```
https://github.com/hfjlb/Nothing/blob/master/xx.pdf
```

blobをrawに書き換えて
下記のuriがraw uriとなる

```
https://github.com/hfjlb/Nothing/raw/master/xx.pdf
```

