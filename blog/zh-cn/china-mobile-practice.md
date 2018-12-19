---
hidden: false
title: 浙江移动容器云基于 Dragonfly 的统一文件分发平台生产实践
keywords: dragonfly,china mobile
description: 浙江移动容器云（DCOS）平台以 Dragonfly 为改革“利器”，成功解决了运营商大规模集群场景下分发效率低、成功率低以及网络带宽控制难等问题；并反哺社区，在 Dragonfly 界面功能、生产高可用部署层面对 Dragonfly 进行了升级。
author: 陈远峥, 王淼鑫
date: 2018-12-18
---

# 浙江移动容器云基于 Dragonfly 的统一文件分发平台生产实践

![](https://mmbiz.qpic.cn/mmbiz_png/yvBJb5IiafvmdKLP4zXN2ATCFDNshUUCpESPWoRHOyNb78s6QdTT3hlDTUHpViapNp2QoQibqRHibWk0881YWohQzQ/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

2018 年 11 月， 源于阿里巴巴的云原生镜像分发系统—— Dragonfly 在 KubeCon 上海现场亮相，成为 CNCF 沙箱级别项目（Sandbox Level Project）。

Dragonfly 主要解决以 Kubernetes 为核心的分布式应用编排系统的镜像分发难题。2017 年开源即成为阿里巴巴最为核心的基础设施技术之一。开源一年以来，Dragonfly 已在诸多行业落地。

DCOS 是浙江移动容器云平台，目前在平台式运行的应用系统已有 185 套，包括手机营业厅、CRM 应用等核心系统。**本文将主要介绍浙江移动容器云（DCOS）平台以 Dragonfly 为改革“利器”，成功解决了运营商大规模集群场景下分发效率低、成功率低以及网络带宽控制难等问题；并反哺社区，在 Dragonfly 界面功能、生产高可用部署层面对 Dragonfly 进行了升级。**


[阅读原文](https://mp.weixin.qq.com/s/0PRitK9bqcMr88lOOw5aKQ)
