# [WMF 发行说明概述](releasenotes.md)

# [安装详细信息](requirements.md)

# [产品兼容性状态](productincompat.md)

# [反馈](feedback.md)

# [由 WMF 5.0 启用的方案]()
## [Just Enough Administration (JEA)](jea_overview.md)
### [创建并连接到 JEA 终结点](jea_endpoint.md)
### [JEA 报告](jea_report.md)

## [使用 PowerShell 类创建自定义类型](class_overview.md)
### [定义自定义类型](class_newtype.md)
### [声明基类](class_base.md)
### [声明已实现的接口](class_interface.md)
### [调用基类构造函数](class_baseconstructor.md)
### [调用基类方法](class_basemethod.md)

## [PowerShell 脚本调试中的改进](debug_overview.md)

## [Desired State Configuration (DSC) 中的改进](dsc_improvements.md)
### [配置]()
#### [指定跨节点依赖关系](dsc_waitfor.md)
#### [已加密 MOF](dsc_encryptedmof.md)
#### [DSC 配置的帮助支持](dsc_confighelp.md)
#### [使用 PowerShell ISE 创作改进](dsc_authoring.md)
#### [配置中完全相同的重复资源的限额](dsc_identicalduplicate.md)
#### [Import-DscResource 关键字支持 -moduleversion 参数](dsc_importdscresource.md)
#### [对 Configuration 关键字的 WOW64 支持](dsc_wow64.md)
### [资源]()
#### [基于类的 DSC 资源](dsc_classbasedresource.md)
#### [DSC 资源脚本调试](dsc_resourcedebugging.md)
#### [对 DSC 资源的自动 RunAs 支持](dsc_runas.md)
#### [对 DSC 资源的并行版本控制支持](dsc_sxsresource.md)
#### [新的随机资源](dsc_newresources.md)
### [本地 Configuration Manager]()
#### [使用多个配置片段配置节点](dsc_partialconfig.md)
##### [对混合 RefreshMode 的支持](dsc_partialconfig_mixedmode.md)
#### [使用新的属性配置 DSC 引擎](dsc_metaconfiguration.md)
#### [关于 LCM 状态的详细信息](dsc_lcmstate.md)
#### [RefreshMode 和 ConfigurationMode 的频率无需是彼此的倍数](dsc_freqnomultiple.md)
#### [RefreshMode 属性的附加值](dsc_refreshmode.md)
### [Cmdlet]()
#### [关于配置状态的详细信息](dsc_getconfigurationstatus.md)
#### [Test-DscConfiguration cmdlet 支持引用配置](dsc_testconfiguration.md)
#### [直接访问 DSC 资源方法](dsc_directaccess.md)
#### [传递配置文档而不应用](dsc_publishconfig.md)
#### [删除 DSC 文档](dsc_removeconfigdoc.md)
#### [统一且一致的状态和状态表示形式](dsc_statestatus.md)
#### [Set-DscLocalConfigurationManager cmdlet 支持 -force 参数](dsc_setdsclcm.md)
### [请求模式]()
#### [DSC 配置的按需请求](dsc_updateconfig.md)
#### [节点和配置 ID 的分隔](dsc_nodeid.md)
#### [配置、资源和报告存储库的分隔](dsc_repository.md)
#### [向中央位置报告配置状态](dsc_reporting.md)

## [审核使用脚本和日志记录的 PowerShell 使用情况](audit_overview.md)
### [增强的脚本选项](audit_transcript.md)
### [脚本跟踪和日志记录](audit_script.md)
### [加密消息语法 (CMS) cmdlet](audit_cms.md)

## [使用 PackageManagement 进行软件发现、安装和盘存](oneget_overview.md)
### [PackageManagement Cmdlet](oneget_cmdlets.md)

## [使用 PowerShellGet 进行 PowerShell 模块发现、安装和盘存](psget_module_overview.md)
### [注册 PowerShell 存储库](psget_psrepository.md)
### [PowerShell 5.0 或更高版本上的并行版本支持](psget_modulesxsinstall.md)
### [模块依赖项的安装](psget_moduledependency.md)
### [用于模块管理的 PowerShellGet Cmdlet](psget_modulecmdlets.md)

## [使用 PowerShellGet 进行 PowerShell 脚本发现、安装和管理](psget_script_overview.md)
### [用于脚本管理的 PowerShellGet cmdlet](psget_scriptcmdlets.md)

## [根据社区反馈的新增和更新的 cmdlet ](feedback_cmdlets.md)
### [使用项 cmdlet 的符号链接](feedback_symbolic.md)
### [存档 cmdlet](feedback_archive.md)
### [剪贴板 cmdlet](feedback_clipboard.md)
### [Convert-String](feedback_convertstring.md)
### [提取和分析字符串外的结构化对象](feedback_convertfromString.md)
### [Format-Hex](feedback_formathex.md)
### [NoNewLine 参数](feedback_nonewline.md)
### [New-TemporaryFile](feedback_tempfile.md)
### [New-Guid](feedback_newguid.md)
### [Get-ChildItem 具有 -Depth 参数](feedback_getchilditem.md)
### [对 FileInfo 对象的更新](feedback_fileinfo.md)
### [对声明版本范围的模块支持（1.* 等）](feedback_moduleversionranges.md)

## [信息流](informationstream_overview.md)

## [基于 OData 终结点生成 PowerShell Cmdlet](odata_overview.md)

## [PowerShell 网络交换机管理](networkswitch_overview.md)

## [软件清单日志记录 (SIL)](sil_overview.md)

# [已知问题和限制](limitation_overview.md)
## [Desired State Configuration (DSC) 已知问题](limitation_dsc.md)


<!--HONumber=May16_HO4-->


