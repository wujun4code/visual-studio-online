#  Visual Studio Online CI 使用分享

<!-- toc -->

## 适用人群

- 你是程序员/测试/SA/QA/产品经理
- 你不习惯 Travis CI 的用户体验
- 你需要友好的 UI 操作来制定测试/发布流程
- 你对微软的产品不排斥
- 你的代码是跨平台的编译到各种环境下


## 注册和登录以及初始化
访问 [https://visualstudio.microsoft.com/](https://visualstudio.microsoft.com/) 注册或者直接登录你的微软账号(hotmail/outlook邮箱都可以)。

然后你会看见如下界面：

![image](https://user-images.githubusercontent.com/5119542/44890228-0b900200-ad0c-11e8-91de-e3a3b106193d.png)

接下来你需要创建一个组织

- 组织里面包含了多个项目 - 对应的就是 Github 多个 repo
- 每一个项目都可以创建多个自动化测试的 Build 和 Release
- 每一个组织默认免费可以有 5 个成员（包括创建者自身）和 240 分钟的云端 CI 运行时间

创建组织的时候输入一些必要的字段，比如二级域名，`myapp.visualstudio.com` 这个就是你以后访问的组织域名。

![image](https://user-images.githubusercontent.com/5119542/44890510-2adb5f00-ad0d-11e8-938b-f76018ae9472.png)


接着需要创建一个项目 `MyBlog`:

![image](https://user-images.githubusercontent.com/5119542/44890584-74c44500-ad0d-11e8-85ce-857db5aa21e7.png)



## 只写代码，master 合并之后自动发布

如果你的项目是开源的，并且托管在 Github



## 自动化测试

## 运行结果邮件/聊天频道通知