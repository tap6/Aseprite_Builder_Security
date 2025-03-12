此仓库来源于https://github.com/a1393323447/aseprite-builder 修改。

由ChatGPT4o和ChatGPTo3-mini-high检测是否存在不良步骤（并没有不良步骤），同时将a1393323447/aseprite-builder中使用的https://github.com/a1393323447/fetch-release 直接集成入 a1393323447/aseprite-builder ，避免从其他仓库调用。



# 你应该做什么？

① Fork 这个 repo

② 启用工作Build and release Aseprite流程Actions -- Workflows

③ 点击Action > Build and release Aseprite > run workflow如图所示

![418335212-5174f407-4daf-4e28-996e-5efb4f8751cb](https://github.com/user-attachments/assets/e8fc1c27-1b7e-46a6-a41f-045a2475ca6e)


## 根据Eula：

（b）分配。

您不得将软件产品的副本分发给第三方。可从许可方网站下载的评估版本可以自由分发。

我们需要移除仓库中的产品Releases。

## 常问问题

Windows：未找到 libcrypto-1_1-x64.dll

<img src="https://github.com/user-attachments/assets/0c9e5801-abf2-491b-acaa-aba2c958c493" alt="image" style="zoom: 67%;" />

在 [firedaemon](https://kb.firedaemon.com/support/solutions/articles/4000121705#Download-OpenSSL) 下载openssl-1.1.1w.zip

<img src="https://github.com/user-attachments/assets/9ce7f97b-0bff-47f7-8f0c-580b2682edae" alt="image" style="zoom: 25%;" />

或您可以使用直链，[openssl-1.1.1w.zip](https://download.firedaemon.com/FireDaemon-OpenSSL/openssl-1.1.1w.zip)

解压x64/bin/libcrypto-1_1-x64.dll到openssl-1.1.1w.zip与aseprite.exe
现在 aseprite 应该可以正常工作了
