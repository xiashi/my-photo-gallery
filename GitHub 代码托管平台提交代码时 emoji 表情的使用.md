**执行 git commit 时使用 emoji 为本次提交打上一个 标签， 使得此次 commit 的主要工作得以凸现，也能够使得其在整个提交历史中易于区分与查找，添加了 emoji 表情的提交记录真的能包含很多有用信息，阅读体验非常棒。
但是，emoji 表情在提交代码的时候也不能乱用，否则容易造成误解。因此开源项目 gitmoji 专门规定了在 GitHub 提交代码时应当遵循的emoji 规范。**

[gitmoji | 提交消息的表情符号指南](https://gitmoji.carloscuesta.me/)

commit 格式
git commit 时，提交信息遵循以下格式：
==:emoji1: :emoji2: 提交信息主体==

初次提交示例：
==git commit -m ":tada: fisrt commit"==

### emoji 指南

|emoji|	emoji 代码|	commit 说明|
|:--:|:--:|:--:|
|🎨 (调色板)|	:art:	|改进代码结构/代码格式|
|⚡️(闪电)	|:zap:	|提高性能|
|🔥 (火焰)|	:fire:|	移除代码或文件|
|🐛 (bug)	|:bug:	|修复 bug|
|🚑 (急救车)|	:ambulance:	|重要补丁|
|✨ (火花)	|:sparkles:	|引入新功能|
|📝 (备忘录)|	:memo:	|撰写文档|
|🚀 (火箭)	|:rocket:|	部署功能|
|💄 (口红)	|:lipstick:	|更新 UI 和样式文件|
|🎉 (庆祝)	|:tada:	|初次提交|
|✅ (白色复选框)	 |:white_check_mark:|更新测试|
|🔒 (锁)	|:lock:	|修复安全问题|
|🍎 (苹果)|	:apple:	|修复 macOS 下的问题|
|🐧 (企鹅)|	:penguin:|	修复 Linux 下的问题|
|🏁 (旗帜)|	:checkered_flag:|	修复 Windows 下的问题|
|🤖 (机器人)| :robot: | 在Android上修复问题|
|🍏 (苹果)| :green_apple: | 在iOS上修复问题|
|🔖 (书签)|	:bookmark:	|发行/版本标签|
|🚨 (警车灯)|	:rotating_light:|	移除 linter 警告|
|🚧 (施工)|	:construction:	|工作进行中|
|💚 (绿心)|	:green_heart:|	修复 CI 构建问题|
|⬇️ (下降箭头)|	:arrow_down:|	降级依赖|
|⬆️ (上升箭头)|	:arrow_up:|	升级依赖|
|📌 (固定器)|	:pushpin:|	将依赖项固定到特定版本。|
|👷 (工人)|	:construction_worker:|	添加 CI 构建系统|
|📈 (上升趋势图)|	:chart_with_upwards_trend:|	添加分析或跟踪代码|
|♻️ (循环)|	:recycle:|	重构代码|
|🔨 (锤子)	|:hammer:|	重大重构|
|➕ (加号)	|:heavy_plus_sign:	|增加一个依赖|
|➖ (减号)	|:heavy_minus_sign:	|减少一个依赖|
|🐳 (鲸鱼)	|:whale:|	Docker 相关工作|
|🔧 (扳手)	|:wrench:|	修改配置文件|
|🌐 (地球)|	:globe_with_meridians:|	国际化与本地化|
|✏️ (铅笔)	|:pencil2:	|修复错别字|
|👌 (OK手势)|	:ok_hand:|	由于代码审查更改而更新代码|
|💩|:poop:|编写需要改进的错误代码|
|⏪|:rewind:|还原更改|
|🔀|:twisted_rightwards_arrows:|合并分支机构|
|📦|:package:|更新编译的文件或软件包|
|👽|:alien:|由于外部API的更改而更新了代码|
|🚚|:truck:|移动或重命名文件|
|📄|:page_facing_up:|添加或更新许可证|
|💥|:boom:|引入重大变化|
|🍱|:bento:|添加或更新资产|
|♿️|:wheelchair:|改善可访问性|
|💡|:bulb:|记录源代码|
|🍻|:beers:|醉酒地编写代码|
|💬|:speech_balloon:|更新文本和文字|
|🗃|:card_file_box:|执行数据库相关的更改|
|🔊|:loud_sound:|添加日志|
|🔇|:mute:|删除日志|
|👥|:busts_in_silhouette:|正在添加贡献者|
|🚸|:children_crossing:|改善用户体验/可用性|
|🏗|:building_construction:|进行架构更改|
|📱|:iphone:|致力于响应式设计|
|🤡|:clown_face:|嘲笑的东西|
|🥚|:egg:|添加一个复活节彩蛋|
|🙈|:see_no_evil:|添加或更新.gitignore文件|
|📸|:camera_flash:|添加或更新快照|
|⚗|:alembic:|尝试新事物|
|🔍|:mag:|改善SEO|
|☸️|:wheel_of_dharma:|关于Kubernetes的工作|
|🏷️ |:label:|添加或更新类型（Flow，TypeScript）|



 





