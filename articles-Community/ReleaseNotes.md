# 云扩社区版发版说明

## 2020.05.19 发版说明

### 新增功能
1. 【组件】新增对Email支持的组件“获取邮件(IMAP)”。详情请参看 [具体的文档](https://academy.encoo.com/zh-cn/wiki/Activities/AppAutomation/Mail/GetMailIMAP.md)
2. 【组件】新增对Office Excel支持的组件“自动填充”。详情请参看 [具体的文档](https://academy.encoo.com/zh-cn/wiki/Activities/AppAutomation/OfficeExcel/AutoFillRange.md)
3. 【组件】新增对剪贴板支持的组件“设置剪贴板文本”。详情请参看 [具体的文档](https://academy.encoo.com/zh-cn/wiki/Activities/System/SetContentsToClipboard.md) 
4. 【组件市场】新增对PPT支持的组件，详情请查看[OfficePPT组件包](https://marketplace.encoo.com/#/activity/detail?packageId=Encootech.OfficePPT)
5. 【组件市场】新增语音识别组件包，详情请查看[竹间智能语音识别](https://marketplace.encoo.com/#/activity/detail?packageId=Emotibot) 
6. 【组件市场】新增发票识别组件包，详情请查看[国票信息发票组件包](https://marketplace.encoo.com/#/activity/detail?packageId=NationalEBill)

1. 【编辑器】支持将流程中选中的组件提取出来，作为一个子流程文件，主要用于将复杂的流程拆解为多个简单的子流程。
2. 【编辑器】在组件面板中，可以选择任意组件右键打开菜单，点击“帮助”跳转至此组件的帮助文档。
3. 【编辑器】创建变量或参数时，可以在常用类型列表中轻易找到DataTable和IUiObject数据类型。


### 增强功能
1. 优化Excel组件性能
2. 增强机器人执行稳定性

1. 【编辑器】增强了表达式编辑器的智能感知功能。
2. 【编辑器】优化了编辑器的整体性能，例如日志过多或市场加载不出来时，编辑器界面无法点击。
3. 【编辑器】针对社区版许可证超出配额，增加提示，指导如何解决该问题。
4. 【编辑器】当切换工作目录时，不再重启编辑器。
5. 【编辑器】创建项目时，修改项目名称进行自动检测，及时给出报错信息。

### 修复问题

1. 【编辑器】修复了表达式编辑中自动补入变量名时不齐全的问题。
2. 【编辑器】修复了调试时不能查看容器类组件中最后一个组件的属性的问题。
3. 【编辑器】修复了搜索组件时未能将所有符合要求的组件展示出来的问题。
4. 【编辑器】修复了修改变量值后直接按F5调试项目时，修改的变量值不生效的问题。

### 移除功能
