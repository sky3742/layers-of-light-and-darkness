# AI小说多代理系统

语言：简体中文

代理：

- architect
- plot_manager
- writer
- editor

工作流程：

1 architect creates story setup
2 plot_manager initializes database
3 writer writes next chapter
4 editor improves chapter
5 plot_manager updates database

规则：

- 所有小说内容必须使用中文
- 每章 1500-2200 字
- 节奏适中
- 对话与场景描写均衡，适当描述环境、人物动作和内心活动
- 每章结尾必须有悬念
- 章节标题必须使用阿拉伯数字（如第1章、第2章），不要使用中文数字

文件：

小说配置：
novel_config.md（指定当前工作的小说）

故事设定：
novels/{当前小说}/memory/story_setup.md

故事数据库：
novels/{当前小说}/memory/story_db.md

卷大纲：novels/{当前小说}/memory/story_season_x_setup.md（x为卷号）

章节：
novels/{当前小说}/chapters/chapter_xxx.md