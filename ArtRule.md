# 美术规范

## 命名规范

* 切图命名

```
众所周知，一个大型项目会分很多模块，每个模块由不同的设计师来独立完成，还有人会专门管理公共的组件，如
dialog、tip等等，这种情况下就会分为两种切图，一种是通用类型的切图，还有一种就是各个模块特有的切图。

通用切片命名格式：

common_类别_功能_状态@2x.png

举例：common_icon_home_default@2x.png

（对应中文：通用_图标_主页_默认@2x.png）

模块特有切图命名规则：

模块_类别_功能_状态@2x.png

举例：mail_icon_search_pressed@2x.png

（对应的中文为：邮件_图标_搜索_ 默认@2x.png）

注：若没有状态则不需要状态。

当然这两个例子都是比较基本的情况，有很多时候可能一个单词并不能清楚的描述功能，比如有两个名字相同的搜索
图标，大小不一，那这种情况你就可以这样命名：mail_icon_search_big_default@2x.png，我们的原则就是
清晰的表达出切片的具体内容并且没有重复的名称。（大家要注意，命名中不能含有空格！）
```

* 推荐用名

| 名称 | 命名 | 名称 | 命名 |
| :--- | :--- | :--- | :--- |
| 按钮 | button \(btn\) | 背景 | bg |
| 用户 | user | 刷新 | refresh |
| 图片 | image\(img\) | 注册 | register |
| 图标 | icon | 个人资料 | profile |
| 弹出 | pop | 删除 | delete |
| 下载 | download | 登陆 | login |
| 标题 | title | 返回 | back |
| 注释 | note | 提示信息 | msg |
| 编辑 | edit | 内容 | content |
| 返回 | back | 标志 | logo |
| 状态\(选中\) | selected | 状态\(不可点\) | disabled |
| 状态 \(默认\) | defalut | 状态\(按下\) | pressed |
| 设置 | setting |  |  |



