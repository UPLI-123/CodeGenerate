# 代码生成工具开发时间线以及遇到的问题以及解决方案

## 1. 2025年3月26日

>
>
>创建`GitHub`项目，方便后续的更新和维护。
>
>* `clone`项目时出现`Recv failure Connection was reset`的问题。
>
>  >
>  >
>  >这个问题通常时网络连接问题或者是代理设置不正确导致的。
>  >
>  >**取消代理**
>  >
>  >```yaml
>  >git config --global --unset http.proxy 
>  >git config --global --unset https.proxy
>  >```
>  >
>  >**克隆语句**
>  >
>  >```yaml
>  >git clone https://github.com/UPLI-123/CodeGenerate.git
>  >```
>
>初步打算使用的技术栈
>
>* 前端：`Vue3`
>* 后端：`Spring Boot3`
>* 单体项目，然后进行部署。
>