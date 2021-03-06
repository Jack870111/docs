﻿# &lt;stl:container&gt; 容器

```html
<stl:container channelIndex="栏目索引" channelName="栏目名称" parent="父栏目" upLevel="上级栏目的级别" topLevel="从首页向下的栏目级别" context="所处上下文"></stl:container>
```

## 说明

通过 stl:container 标签在模板中定义容器，切换上下文。

上下文是指系统解析 StL 标签时的默认数据，详情请参考[切换上下文](/context)。

&lt;stl:container&gt; 标签需要嵌套 HTML 标签或者 STL 标签，否则系统将忽略此标签。

## 解析

如果使用 &lt;stl:container&gt; 元素，系统将在指定上下文情景下对嵌套的标签进行解析。

{stl:container} 实体无效，系统将解析此实体为空字符串。

## 属性

| 属性                                                 | 说明                 |
| ---------------------------------------------------- | -------------------- |
| [channelIndex](container/attributes?id=channelIndex) | 栏目索引             |
| [channelName](container/attributes?id=channelName)   | 栏目名称             |
| [parent](container/attributes?id=parent)             | 父栏目               |
| [upLevel](container/attributes?id=upLevel)           | 上级栏目的级别       |
| [topLevel](container/attributes?id=topLevel)         | 从首页向下的栏目级别 |
| [context](container/attributes?id=context)           | 所处上下文           |

<!-- done -->