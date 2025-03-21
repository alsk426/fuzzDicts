# fuzzDicts
Web Pentesting Fuzz 字典,一个就够了。


## log 

20190801：合并了一个[r35tart](https://github.com/r35tart/RW_Password)师傅整理的很好的“强弱口令”字典（即看起来很复杂，单但实际上很多人在用的密码）

20190615：合并了一个[国外的字典](https://github.com/emadshanab/WordLists-20111129) 感觉分类有点乱 考完试再重新整理一下咯。


* [参数Fuzz字典](#参数fuzz字典)
* [Xss Fuzz字典](#xss-fuzz字典)
* [用户名字典](#用户名字典)
* [密码字典](#密码字典)
* [目录字典](#目录字典)
* [sql-fuzz字典](#sql-fuzz字典)
* [ssrf-fuzz字典](#ssrf-fuzz字典)
* [XXE字典](#XXE字典)
* [ctf字典](#ctf字典)
* [Api字典](#Api字典)
* [路由器后台字典](#路由器后台字典)
* [文件后缀Fuzz](#文件后缀Fuzz)
* [js文件字典](#js文件字典)



工具推荐：[burpsuite](https://portswigger.net/burp/),[sqlmap](https://github.com/sqlmapproject/sqlmap),[xssfork](https://github.com/bsmali4/xssfork),[Wfuzz](https://github.com/xmendez/wfuzz/),[webdirscan](https://github.com/TuuuNya/webdirscan)

如果有什么的好字典或是建议欢迎提交issue给我。


## [参数Fuzz字典](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/paramDict)

```
https://github.com/TheKingOfDuck/fuzzDicts/blob/master/paramDict/parameter.txt
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/parameter.jpg)



采集自`ThinkPHP`,`yii2`,`phphub`,`Zblog`,`DiscuzX`,`WordPress`等常见PHP框架/CMS。

使用技巧：如http://127.0.0.1/1.php ,视为可疑文件，进行fuzz param 选择GET,POST AND (POST JSON) AND (GET Route) AND cookie param


## [Xss Fuzz字典](https://github.com/TheKingOfDuck/easyXssPayload/blob/master/easyXssPayload.txt)

```
https://github.com/TheKingOfDuck/easyXssPayload/blob/master/easyXssPayload.txt
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/xss.jpg)

采集自`github`。

## [用户名字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/userNameDict)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/userNameDict
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/username.jpg)


## [密码字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/passwordDict)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/passwordDict
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/password.jpg)

## [目录字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/directoryDicts)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/directoryDicts
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/directory.jpg)


## [SQL Fuzz字典](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/sqlDict/sql.txt)

```
https://github.com/TheKingOfDuck/fuzzDicts/blob/master/sqlDict/sql.txt
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/sql.jpg)


## [ssrf fuzz字典](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/ssrfDicts)

```
https://github.com/TheKingOfDuck/fuzzDicts/blob/master/ssrfDicts
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/ssrf.jpg)

由[\xeb\xfe](https://github.com/doge-dog)师傅提供。

## [XXE字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/XXEDicts)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/XXEDicts
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/xxe.jpg)

收集自百度。

## [ctf字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/ctfDict)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/ctfDict
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/ctfDict/ctf-wscan/1.gif)

收集自百度[侵删]。


## [Api字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/apiDict)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/apiDict/api.txt
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/api.jpg)

钟馗采集的代码写得很cxk 我真弟弟。。。

## [路由器后台字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/routerDicts)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/routerDicts/pass.txt
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/router.jpg)

## [文件后缀Fuzz](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/uploadFileExtDicts)

```
https://github.com/TheKingOfDuck/fuzzDicts/tree/master/uploadFileExtDicts
```

![CoolCat](https://github.com/TheKingOfDuck/fuzzDicts/blob/master/images/fileExt.png)

采集自https://github.com/c0ny1/upload-fuzz-dic-builder


## [js文件字典](https://github.com/TheKingOfDuck/fuzzDicts/tree/master/js)

采集自:https://github.com/7dog7/bottleneckOsmosis




