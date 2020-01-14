# scaffold-cli
scaffold-cli
 create spa fastly

# 命令
scaffold init template-name project-name  根据远程模板，初始化一个项目(远程模板可配置)
scaffold config set <key> <value> 修改配置信息
scaffold config get [<key>] 查看配置信息
scaffold --version 查看当前版本号
scaffold -h

eg：
scaffold init react-scaffold  my


#开发环境
1启动项目
npm run watch
2开发过程中为了方便调试，在当前的目录下执行npm link ，将 scaffold 命令链接到全局环境。
npm link


#dependencies
babel-cli/babel-env: 语法转换
commander: 命令行工具
download-git-repo: 用来下载远程模板
ini: 格式转换
inquirer: 交互式命令行工具
ora: 显示loading动画
chalk: 修改控制台输出内容样式
log-symbols: 显示出 √ 或 × 等的图标


