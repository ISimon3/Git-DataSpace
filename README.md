# Git 数据空间：私有云密码管家


![image](https://github.com/ISimon3/Git-DataSpace/blob/main/example1.0.6.jpg)
---
## ✨ 核心功能与特色
###  1. 数据安全与自主掌控
###  2. 全面的密码管理功能
###  3. 强大的密码辅助工具
###  4. 高效的浏览与操作
###  5. 便捷的云同步机制
###  6. 个性化与易用性
---
## ✨ 使用说明
### 进入 GitHub Token 页面 
打开链接：https://github.com/settings/personal-access-tokens → 点击 “Fine-grained tokens” → 然后点击 “Generate new token”
### 填写基本信息 Token 名称（例如：PasswordSyncToken）
过期时间（建议设置一个月或三个月，后续可续）
### 选择要访问的仓库
仅选一个私有仓库（建议只选一个）,点击 “Repository access” 选择你想要用来存储加密文件的仓库
### 设置仓库权限（最关键部分）
在 “Repository permissions” 中，找到：
Contents → 设置为 Read and write
其他权限保持为 No access
这一步确保你只给了该 Token “读写文件内容”的权限，而没有授予删除代码、操作 PR、管理部署等危险权限。
### 确认生成,点击底部 “Generate token”
成功后会跳出一次性显示的 token，（例如：ghp_xxxxxxxxxxxxxxxx）,请立刻复制保存！
