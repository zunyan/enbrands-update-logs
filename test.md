## 用户的大概使用流程（设想）
1. <a style="color:red">云积分</a>为<a style="color:red">宝洁</a>开发一个可视化的编辑器
2. <a style="color:red">宝洁</a>运营通过该编辑器进行店铺首页装修操作
3. <a style="color:red">宝洁</a>运营保存装修结果
4. <a style="color:red">宝洁</a>运营确认发布装修内容
5. 后台根据编辑内容执行编译，生成weex文件
6. 后台将编译好的weex文件推往淘宝/天猫，由淘宝/天猫完成审核部署
7. 发布完成

## 上述流程内，需要明确的问题
1. 如何在weex中调用的各类平台端接口，包括宝贝列表，分类列表
2. 步奏6的具体实施情况
3. <a style="color:red">云积分</a>这边，能进行的装修操作有哪些（视口范围）
4. 装修操作均在<a style="color:red">云积分</a>侧完成，可能需要提供性能测试的相关指标

另，PPT中提到部分定位楼层，使用的是外部承接页 ，类iframe的方式接入会不会有风险

## 装修模块设想
1. 图片链接 - 可以选择外链，或者页面内模块的位置
![Alt text](http://enbrands-2.oss-cn-shanghai.aliyuncs.com/r-%E9%94%9A%E7%82%B9%E5%BC%8F%E9%93%BE%E6%8E%A5.png)
2. 隐藏型导航模块 - 模块在正常情况下不可见，只有移出视口时才可见
![Alt text](http://enbrands-2.oss-cn-shanghai.aliyuncs.com/r-%E9%9A%90%E8%97%8F%E5%BC%8F%E5%AF%BC%E8%88%AA.png)
3. 其他相关模块 - 这些模块与现装修模块一致，















