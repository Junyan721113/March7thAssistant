# March7thAssistant Changelog

## v1.3.0

### 新功能
- 支持识别每日实训内容并尝试完成，而不是全部做一遍 [点击查看支持任务](https://github.com/moesnow/March7thAssistant#%E6%AF%8F%E6%97%A5%E5%AE%9E%E8%AE%AD)
- 新增选项每周优先完成三次「历战余响」（默认关闭）
- 副本名称（instance_names）更改为根据副本类型单独设置，同时也会用于“完成1次xxx”的实训任务中
- 移除“使用支援角色”、“强制使用支援角色”、“启用每日拍照”和“启用每日合成/使用 材料/消耗品”配置选项
- 每周模拟宇宙运行前先检查一遍可领取的奖励
### 修复
- 尝试解决低概率下识别副本名称失败
- 彻底解决每日实训是否全部完成检测不可信

## v1.2.6

### 新功能
- 支持更多副本类型：侵蚀隧洞、凝滞虚影、拟造花萼（金）、拟造花萼（赤）
- 设置中的捕获截图功能支持OCR识别文字，可用于复制副本名称

## v1.2.5

### 新功能
- 内置锄大地命令

### 修复
- 开拓力偶尔识别成“1240”而不是“/240”
- 每日实训是否全部完成检测失败

## v1.2.4

### 新功能
- 图形界面支持显示更新日志
- 更新模拟宇宙 [Auto_Simulated_Universe  v5.30](https://github.com/CHNZYX/Auto_Simulated_Universe/tree/f17c5db33a42d7f6e6204cb3e6e83ec2fd208e5e)

### 修复
- 1.3版本的各种UI变化导致的异常

## v1.2.3

### 新功能
- 混沌回忆支持检测每关星数
- 副本名称支持简写，例如【睿治之径】

### 修复
- 偶尔点击速度过快导致领取实训奖励失败
- 鼠标位于屏幕左上角触发安全策略导致点击失效
- 偶尔界面切换速度太慢导致消耗品识别点击位置偏移
- 检测无名勋礼奖励模板图片错误
- 降低部分阈值要求，提高操作成功率
- 移除部分多余的界面检测，提高速度

## v1.2.2

### Features
- feat: add Bailu and Kafka
适配白露和卡芙卡
- feat: forgottenhall support melee character
混沌回忆支持近战角色开怪
- feat: add take_screenshot to gui
图形界面设置中新增捕获截图功能
- feat: add check update to gui
图形界面启动时检测更新
- feat: add tip when start

### Fixes
- fix: use consumables when repeat
消耗品效果未过期导致无法使用
- fix: check_update option not available
更新检测开关不可用
- fix: avoid trailblaze_power overflow
模拟宇宙前后清一次体力避免溢出
- fix: space cause text ocr fail
偶尔会识别出空格导致判断文字失败
- fix: exit function

## v1.2.1

### Features
- feat: auto change team
在打副本和锄大地前可以自动切换队伍
- feat: add submodule Auto_Simulated_Universe
添加模拟宇宙子模块

### Fixes
- fix: switch window problem
游戏窗口偶尔无法切换到前台
- fix: same borrow character
支援角色和原队伍角色相同

## v1.2.0

### Features
- feat: graphical user interface
增加图形用户界面