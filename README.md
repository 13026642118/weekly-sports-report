# Personal Weekly Sports Report#个人每周体育报告个人每周体育报告#个人每周体育报告个人每周体育报告#个人每周体育报告#个人每周体育报告个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告#个人每周体育报告

Auto-generated from Coros training data.由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。由Coros训练数据自动生成。


阶段一：Coros MCP 认证
调用 coros__get_help() 确认可用工具
coros__authenticate_coros() 完成认证（邮箱+密码）
设置每20小时自动续期的 cron 任务
阶段二：拉取数据
coros__list_activities() 获取 5/17-5/23 活动列表 → 3天8次训练
coros__get_daily_metrics() 拉取 HRV/RHR/疲劳指数趋势
尝试 coros__get_sleep_data()（睡眠数据需 mobile API 额外认证，跳过）
阶段三：Markdown 周报
搜索主流运动 App 周报风格（Strava/Keep/Apple Fitness）
你选了 A+C 混合风格（数据仪表盘 + 专业训练日志）
生成 Markdown 版本，发送到飞书
阶段四：转为 HTML
你说要 HTML 格式，要求「创意且避免 AI 通用风格」
