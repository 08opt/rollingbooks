rollingbooks
============

滚去背单词的英语开放课程

##文件布局规范

1. 课程放在同一个子目录下
2. 每个课程目录下是包含的具体课文文件夹和清单文件
3. 清单文件描述课程名称，课时和课程描述
4. 课文文件夹下content.md是课文文件，请使用markdown编写
5. 课文文件夹下meta.son是课文元信息，请填写课文名称(type和words已经废弃)


##课文内容规范

1. markdown描述
2. 不能引入css，js
3. 可以插入视频，链接等


###文件样板

meta.json

```
{
  "title" : "胡安·恩利克斯：令人吃惊的新科技",
  "type"  : "markdown",
  "words" : []
}
```

manifest.json

```
{
  "name":         "新概念第四册",
  "tasks":        10,
  "desc":         "新概念第四册的课文"
}
```
