---
title:  MSFT_DSCLocalConfigurationManager 类的 EnableDebugConfiguration 方法
ms.date:  2016-05-16
keywords:  powershell,DSC
description:  
ms.topic:  article
author:  eslesar
manager:  dongill
ms.prod:  powershell
---


# MSFT_DSCLocalConfigurationManager 类的 EnableDebugConfiguration 方法

启用 DSC 资源调试。

语法
------

```mof
uint32 EnableDebugConfiguration(
  [in] boolean BreakAll
);
```

参数
----------

*BreakAll* \[in\]  
在资源脚本中的每一行设置断点。

## 返回值
------------

如果成功，则返回零；否则返回错误代码。

## 备注

这是一种静态方法。

## 要求
------------
>**MOF：** DscCore.mof

>**命名空间**：Root\Microsoft\Windows\DesiredStateConfiguration


## 另请参阅


[**MSFT_DSCLocalConfigurationManager**](msft-dsclocalconfigurationmanager.md)
 

 





<!--HONumber=May16_HO3-->


