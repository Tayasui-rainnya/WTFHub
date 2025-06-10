# WTFHub  GitHub 离谱事件收集
**GitHub 大概是最大的冷笑话平台**

相关资源待补充

---

## 事件目录 📚

### 事件#001：  你们是把***打包了吗？
**事件标签**：`腾讯` `版本号`

<details>
<summary>**事件概述**</summary>

某开发者在issue中对`tencentcloud-sdk-nodejs`的吐槽，直指其100M+的离谱体积和反人类设计：

> "你们是把马化腾他妈的骨灰盒打包了吗？"  
> —— 当看到`node_modules`里85M的腾讯云SDK时

**魔幻操作一览**：
- 将`test/`、`examples/`、双份CHANGELOG（这玩意一个有5M？）打包进生产环境SDK
- 版本号从`4.0.1`直接飙到`4.0.1021`（这他妈是脑子想出来的？）


相关链接：[https://github.com/TencentCloud/tencentcloud-sdk-nodejs/issues/160](https://github.com/TencentCloud/tencentcloud-sdk-nodejs/issues/160)

</details>

---

### 事件#002：向项目提交公司内部代码  
**事件标签**：`Git操作事故` `理直气壮`

<details>
<summary>**事件概述**</summary>

某程序员将公司敏感数据（含logo、pem文件、版权信息等）提交至开源项目（[Dify](https://github.com/langgenius/dify/)）PR，面对维权律师函时急了：


- 通过公司邮箱群发辱骂邮件：  
  > "发你妈的律师函，傻逼！"  
  > —— 发件人署名"销售数据异常预警"

- 操作迷踪：
  1. 修改该项目 logo 等等一系列定制化内容（想做盗版？）
  2. 向该项目提交修改后内容，提了接近100个 commit？？？
  3. 企业邮箱官方认证的"职场情绪管理失败案例"

相关链接：[https://github.com/langgenius/dify/pull/16819](https://github.com/langgenius/dify/pull/16819)
![image](https://暂缺)

</details>

---

### 事件#003： 把 GitHub Issue 当成许愿池
**事件标签**：`华为` 

<details>
<summary>**事件概述**</summary>

一位开发者向微软 Visual Studio Code 的官方仓库提交了一个 Issue，内容简单明了、言简意赅，堪称“一行程序改变世界”的典范：

  > "Support Harmony Next PC"  
  > —— issue #249326

此举好比在佛祖面前许愿要一个女朋友，直接引爆了社区，并以光速被官方拒绝。

**魔幻操作一览**：
- **用最少的字，许最大的愿**：只用四个英文单词，就向全球最大的代码编辑器提出了适配一个全新PC生态的宏伟请求。
- **社区“热情”超乎想象**：该 Issue 收获了超过 1200 个“👎”。
- **官方光速拒绝**：在社区“热烈讨论”的同时，VS Code 维护者默默地给该 Issue 贴上了 `invalid` (无效) 标签，并以 `not planned` (没计划) 的状态光速关闭，终结了这场闹剧。

PS：截止该事件发生时，华为自己的 IDE DevEco Studio 也没有支持鸿蒙 Next PC。

相关链接：[https://github.com/microsoft/vscode/issues/249326](https://github.com/microsoft/vscode/issues/249326)
![image](https://暂缺)

</details>

---

### 事件#004： 少活十年
**事件标签**：`微信` `文档`

<details>
<summary>**事件概述**</summary>

开发者 @to-explore-future 在尝试接入`wechatpay-java` SDK时，因其反人类的文档（微信老传统了），发出了“能让我少活10年”的愤怒咆哮，并喜提“血压飙升”debuff。

  > "接个微信支付 能让我少活10年 我血压一下子上来了"  
  > —— to-explore-future    opened on Feb 3

**事件内容**：
- 开发者在接入`wechatpay-java` SDK时，遇到了文档不清晰的问题。
- 缺乏简单易懂的示例代码，导致开发者在理解和使用SDK时遇到困难。
- 微信也不是第一次因为垃圾文档被骂了，为啥不改呢？

相关链接：[https://github.com/wechatpay-apiv3/wechatpay-java/issues/338](https://github.com/wechatpay-apiv3/wechatpay-java/issues/338)

</details>

---

## 贡献指南 🤝  
欢迎提交更多离谱事件，需满足：  
✅ 基于GitHub公开可验证的原始记录  
✅ 附上事件编号（按顺序递增）  

**提交格式**：  
```markdown
### 事件#003：[事件标题]
**标签**：`标签1` `标签2`  
<details>  
<summary>概述</summary>  
[事件描述+高能截图/引用]
相关链接：[placeholder](placeholder)

</details>
```

---

## 免责声明 🛡️  
本项目仅收录公开可查的 GitHub 事件，内容真实性由原始链接背书。

---

**LICENSE**：MIT License

