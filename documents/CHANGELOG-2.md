******
### 版本历史 - 2.x
******
# v2.0.2
###### 2021/02/11
* `提示` 需要留意v2.0.1的项目更新功能可用性  
  · tools文件夹的项目部署工具 (可用)  
  · 配置工具的"从服务器还原" (可用)  
  · 配置工具的"关于"或"Snackbar" (故障)  
  · 项目运行结果展示时的更新悬浮窗 (故障)  
* `修复` 配置工具及Floaty结果的自动更新功能无效的问题
* `修复` 排行榜页面列表结尾的好友可能被跳过检查的问题
* `修复` 配置工具从列表选择应用时的数据筛选错误
* `修复` 高版本安卓设备可能无法判断系统应用的问题
* `优化` 增加主账户头像本地样本尺寸检测以防止尺寸越界

# v2.0.1
###### 2021/02/08 - 项目结构变更 谨慎升级
* `新增` 自动检查更新功能/版本忽略功能及相关配置
* `新增` 排行榜页面的控件滑动策略及相关配置
* `新增` 运行结果展示支持版本更新提示及定时任务信息展示
* `修复` 好友森林动态列表未就绪导致页面判断失效的问题 _[`issue #423`](https://github.com/SuperMonster003/Ant-Forest/issues/423)_ _[`#420`](https://github.com/SuperMonster003/Ant-Forest/issues/420)_ _[`#418`](https://github.com/SuperMonster003/Ant-Forest/issues/418)_ _[`#416`](https://github.com/SuperMonster003/Ant-Forest/issues/416)_
* `修复` 好友森林动态列表未就绪导致能量罩信息获取失败的问题 _[`issue #425`](https://github.com/SuperMonster003/Ant-Forest/issues/425)_
* `修复` 解锁模块覆盖全局require方法后可能导致的功能异常
* `修复` 解锁模块加载外部模块方法的路径匹配错误
* `修复` 找能量向导遮罩导致主页能量球识别失效的问题
* `修复` 执行过程中能量罩倒计时失效后依然触发黑名单的问题
* `修复` 本地备份完成后可能导致本地备份配置信息丢失的问题
* `优化` 移除帮收功能相关的全部功能及配置选项
* `优化` 移除排行榜底部控件图片相关方法以提升兼容性
* `优化` 移除参数调整提示避免自动定时任务无法正常运行的情况
* `优化` 部分imagesx方法提供压缩等级参数以降低OOM出现概率
* `提示` 解锁功能配置工具暂时被移除 (将在后续版本恢复)