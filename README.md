# artop_examples_learning

本项目已迁移至[coding.net](https://nescar.coding.net/p/artop_examples_learning)（2019/9/10）

## 说明

本项目用于Artop官方例程的学习，主要修改内容为添加注释。

| 序号 | 组员 | 子项目 |
| ---- | ---- | ------ |
|1  | 宋超超 |`org.artop.aal.examples.actions`<br>`org.artop.aal.examples.autosar412.viatra.query`<br>`org.artop.aal.examples.extender` |
|2  | 徐帅 |`org.artop.aal.examples.common` <br>`org.artop.aal.examples.common.ui`<br>`org.artop.aal.examples.explorer`|
|3  | 孙怡琳 |`org.artop.aal.examples.diagrams.componenttype21`<br>`org.artop.aal.examples.standalone`|
|4  | 张宗煜 |`org.artop.aal.examples.diagrams.componenttype3x`<br>`org.artop.aal.examples.newwizards`|
|5  | 胡婧 |`org.artop.aal.examples.converter` <br>`org.artop.aal.examples.editor`|
|6  | 张晨 |`org.artop.demonstrator`<br>`org.artop.demonstrator.cheatsheets`<br>`org.artop.demonstrator.intro`|

## 使用
### GIT

组内成员分工学习本项目，不可以越界修改别人的子工程，不然会造成版本混乱。push代码之前，先进行pull，保持和master相同。

```bash
# 1.pull 项目
## 保证和master的HEAD相同
$ git pull

# 2.push项目
## 2.1.添加要push的文件
## eg.$ git add . 
$ git add [FILE_NAME]
## 2.2.评论
## eg.$ git commit -m "finish artop-learning"
$ git commit -m "[COMMIT]"
## 2.3 push项目
$ git push
```

### 环境
| 名称 | 环境 | 版本 |
| ---- | ---- | ------ |
|IDE  | Eclipse_RCP |2018-12（即4.10） |
|Eclipse Target Platform  | 4.10.target |4.10 |

开发Artop应用之前需要[配置](https://github.com/NESCAR/artop_examples_learning/blob/master/eclipse_conf_intro.md)Eclipse的Target Platfrom。

## 资源
1.[《Eclipse插件开发》张鹏](https://pan.baidu.com/s/1nKCw2EyOBFlNe3MDMpZyMw)  提取码：z8k3

2.[《Eclipse插件开发》源码](https://pan.baidu.com/s/1GtelhpO2mfvIMDNJ1FkDbQ)  提取码：0j5l 

3.[ Eclipse 插件开发笔记](http://neyzoter.cn/wiki/EclipsePluginDev/)

## 联系

Email:songchaochao@zju.edu.cn
