﻿# &lt;stl:count&gt; 展示数值

```html
<stl:count type="需要获取值的类型" channelIndex="栏目索引" channelName="栏目名称" upLevel="上级栏目的级别" topLevel="从首页向下的栏目级别" scope="内容范围" since="时间段"></stl:count>
```

## 说明

通过 stl:count 标签在模板中展示统计数字

标签 &lt;stl:count&gt; 用于展示相关数值，如栏目数目、内容数目等。

属性 channelIndex、channelName、upLevel 以及 topLevel 用于指定统计的栏目，如果不设置默认将统计当前栏目或内容的数据。
属性 scope 用于指定统计范围，默认为仅统计当前栏目或内容的相关数据。
属性 type 用于设置展示数值的类型。
属性 since 用于指定时间段，系统将只展示这段时间内的统计数据。since 属性格式为"数字+日期符号"，如"1y"、"3m"、"10d"或"16h"，分别代表一年、三个月、十天及十六个小时。

&lt;stl:count&gt; 标签对应的实体为{stl:count}。

## 属性

| 属性                                             | 说明                 |
| ------------------------------------------------ | -------------------- |
| [type](count/attributes?id=type)                 | 需要获取值的类型     |
| [channelIndex](count/attributes?id=channelIndex) | 栏目索引             |
| [channelName](count/attributes?id=channelName)   | 栏目名称             |
| [upLevel](count/attributes?id=upLevel)           | 上级栏目的级别       |
| [topLevel](count/attributes?id=topLevel)         | 从首页向下的栏目级别 |
| [scope](count/attributes?id=scope)               | 内容范围             |
| [since](count/attributes?id=since)               | 时间段               |