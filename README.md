## 酷狗音乐API接口整理

>基于酷狗音乐整理的音乐API接口数据

### 音乐新歌榜

__说明:__ 获取新歌曲榜单

__必选参数:__
`page`: json

__接口地址:__ `http://m.kugou.com/?json=true`



###  音乐排行榜

__说明:__ 获取音乐排行榜

__必选参数:__

__接口地址:__ `http://m.kugou.com/rank/list&json=true`

__返回数据__


###  排行版分类歌曲列表

__说明:__ 获取音乐排行榜

__必选参数:__
`rankid` 排行榜分类下id
`json` 返回类型


__接口地址:__ `http://m.kugou.com/rank/info/?rankid=8888&page=1&json=true`

__返回数据__


###  音乐歌单

__说明:__ 获取音乐排行榜

__必选参数:__


__接口地址:__ `http://m.kugou.com/plist/index&json=true`

__返回数据__

###  歌单下的音乐列表

__说明:__ 获取 歌单下的音乐列表，需要添加  `specialid`


__必选参数:__
`specialid` 125032

__接口地址:__ `http://m.kugou.com/plist/list/125032?json=true`

__返回数据__


### 歌手分类

__说明:__ 获取 歌手分类


__必选参数:__

`无`
__接口地址:__ `http://m.kugou.com/singer/class&json=true`


### 歌手分类下面的歌手列表

__说明:__ 获取 歌手分类

__必选参数:__

`classid` 

__接口地址:__ `http://m.kugou.com/singer/list/88?json=true`


### 歌手信息

__说明:__ 获取 歌手分类

__必选参数:__

`singerid` : 歌手id  3060 

__接口地址:__ `http://m.kugou.com//singer/info/3060&json=true`




