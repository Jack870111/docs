### 问题

为什么发布的mp4前台无法播放？

### 答案

有时候我们需要把一些特殊类型的文件发布到IIS站点上，供用户访问和下载，但直接把文件放上去是不行的，访问时会提示“HTTP 错误 404.3 - Not Found”错误，这时就需要配置站点的MIME类型。

**解决方法：**

打开IIS管理器，找到相应站点，然后在中间的窗口中找到“MIME类型”并双击，点击右侧窗口中的操作“添加”，文件扩展名填写 “.mp4” ，MIME类型填写 “application/mp4”。添加完了再访问网页正常是能播放mp4文件了。