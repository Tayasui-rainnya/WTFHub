# WTFHub  GitHub 离谱事件收集
**GitHub 大概是最大的冷笑话平台**

相关资源待补充

---

## 事件目录 📚

### 事件#001：  你们是把***打包了吗？
**事件标签**：`腾讯` `版本号` `吐槽`

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

