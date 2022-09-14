# feishu_card_builder

飞书官方提供的 [消息卡片搭建工具](https://open.feishu.cn/tool/cardbuilder?from=howtoguide) 需要按照文档配置参数，开发人员能够接受，但是对于使用者来说入门成本略高。

本着简化操作的原则，构建了一个 HTML 页面，组件可拖拽、排序、可视化编辑。

## 样例图

![image-20220914104022059](https://wdj-1252419878.cos.ap-beijing.myqcloud.com/blog/20220914-Rw6dG0.png)

## 快速开始

clone 当前项目本地打开 `feishu_card_builder.html` 即可。

## 组件说明

### 图片组件

图片组件需要自己实现 [飞书图片上传](https://open.feishu.cn/document/uAjLw4CM/ukTMukTMukTM/reference/im-v1/image/create) 服务。未实现的情况下，在新增组件或者排序时可能出现图片组件重置的问题。

### 向我发送预览

需要实现 [飞书批量发送消息](https://open.feishu.cn/document/ukTMukTMukTM/ucDO1EjL3gTNx4yN4UTM) 功能。