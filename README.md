BT-Search
=========
简洁舒服的BT搜索程序，屌丝必备神器。

###运行环境
* PHP5.3+
* 开启CURL扩展
* 保留30MB以上的硬盘空间
(缓存会占用很多，100PV大概生成20M数据)

###程序特点
低调奢华有内涵 高端大气上档次

###示例网站
URL: https://www.bt-ss.com

###安装说明
将所有文件上传到网站根目录，设置cache目录权限为777，并对config.php进行必要修改。
我的要求不高，大家给我保留个版权就可以了，链接到https://github.com/kslr/BT-Search

###0.3版本更新记录
* 重新设计UI界面（感谢帮我设计的朋友@world,飞鸟）
* 热门关键词数据修改为万达电影数据
* 对抓取进行优化（速度提高50%+）
* 添加移动版界面
* 去除BT下载支持，纯磁力链下载
* 优化缓存部分
* 加入短地址快速分享
* 代码结构调整更加清晰
* 修复翻页BUG
* 修复磁力页错误处理
* 改动较多，其他细节就不一一描述了

###0.21版本更新记录
* 同步更新网站接口

###0.2版本更新记录
* 修复空关键词时的判断错误
* 添加搜索关键词过滤
* 取消访问量统计
* 调整了一部分页面设计
* 把乱七八糟的代码整理了一下
* 使用了独立的配置文件(config)(解决DA固定前缀无法使用)
* 加入了缓存机制，搜索过的关键词将会保留30天(下次点击时秒搜)
* 支持多页码采集

如有任何意见或BUG反馈，请给我发送邮件 kslrwang#gmail.com
