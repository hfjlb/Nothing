# YAMLファイル編集方法

## Content Listの編集

フォマット：yaml
コンテンツ形式：md、pdf、ppt、docx、youtube video、mp4

```javascript
title: 使用方法
subContentItemList:
 - !!map
  title: まとめ
  uri: http://xxxx
 - !!map
  title: 各種コンテンツを組む方法
  subContentItemList:
   - !!map
      title: ①mdコンテンツを組む（URIを設定する）
      uri: https://raw.githubusercontent.com/apollographql/apollo-client/master/docs/source/api/react-apollo.md
   - !!map
      title: ②pptコンテンツを組む（URIを設定する）
      uri: https://github.com/hfjlb/Nothing/blob/master/xx.pptx?raw=true
   - !!map
      title: ③pptコンテンツを組む（URIを設定する）
      uri: https://github.com/hfjlb/Nothing/raw/master/xx.pdf
   - !!map
    title: ④mdファイル中に、videoを埋める方法
    uri: https://raw.githubusercontent.com/hfjlb/Nothing/master/video%20in%20md.md
   - !!map
    title: ⑤mp4コンテンツを組む（URIを設定する）
    uri: https://media.w3.org/2010/05/sintel/trailer_hd.mp4
   - !!map
    title: ⑥youtube4コンテンツを組む
    uri: 2g811Eo7K8U.youtube
```

