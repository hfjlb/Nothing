## mdファイルにvideoを埋める方法

ネットにあるvideoをmdファイルに埋める方法


### youtubeの場合

下記のようのタッグをmdファイルに埋めることとなる。

```
[![](http://img.youtube.com/vi/6A5EpqqDOdk/0.jpg)](http://www.youtube.com/watch?v=6A5EpqqDOdk "")

```
[![](http://img.youtube.com/vi/6A5EpqqDOdk/0.jpg)](http://www.youtube.com/watch?v=6A5EpqqDOdk "")

6A5EpqqDOdkはvideo idのため、置き換えてください。


### youtube以外、mp4の場合

下記のように、タッグを埋めることとなる。

```
<video width="320" height="240" controls>
  <source src="https://media.w3.org/2010/05/sintel/trailer_hd.mp4" type="video/mp4">
</video>
```
<video width="320" height="240" controls>
  <source src="https://media.w3.org/2010/05/sintel/trailer_hd.mp4" type="video/mp4">
</video>

src部はvideoのuriとなるため、置き換えるひつようがある

