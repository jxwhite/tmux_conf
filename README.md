# ln -s -f /Users/xxx/xxx/.tmux.conf ~/.tmux.conf

# 外部命令
## tmux new -s sess1 创建一个名为sess1的会话
## tmux new -s sess1 -n win1 创建一个名为sess1的会话并把第一个窗口名命名为win1
## tmux ls 查看所有后台运行的会话
## tmux a -t sess1 连接到一个名为sess1的会话
## tmux a 默认进入到第一个会话
## tmux kill-session -t sess1 关闭名为sess1的会话
## tmux kill-server 关闭服务器，所有的会话都会被关闭



# 内部快捷键
## 第一命令键 `
## 第二命令键 ctrl+a

- **cmd->d**          分离会话，将会话切到后台
- **cmd->r**          重载配置文件~/.tmux.conf
- **cmd->ctrl+l**     清除window中的所有panel和清屏
- **cmd->ctrl+c**     创建新session
- **cmd->ctrl+f**     切换session（以名字）
- **cmd->c**          创建新window
- **cmd->,**          为当前window命名
- **cmd->ctrl+n**     上一个window
- **cmd->n**          下一个window
- **cmd->w**          列出所有window列表
- **cmd->t**          在window中显示时间
- **cmd->tab**        在最后使用的两个window间切换
- **cmd->0..9**       根据编号选择window
- **cmd->&**          关闭当前window，有确认提示
- **cmd->\\**         当前pane竖向一分为二
- **cmd->]**          当前pane横向一分为二
- **cmd->h j k l**    切换pane
- **cmd->小键盘上下左右**   切换pane
- **cmd->o**          循环切换pane
- **cmd->H I J K**    调整pane大小
- **cmd-><**          交换pane
- **cmd->>**          交换pane
- **cmd->+**          将当前pane最大化，再将使用恢复
- **cmd->SPACE**      循环使用pane的几个布局
- **cmd->q**          短暂显示每个pane编号
- **cmd->x**          关闭当前pane，有确认提示
- **cmd->m**          开启、关闭鼠标支持
- **cmd->U**          launches Urlview (if available)
- **cmd->F**          launches Facebook PathPicker (if available)
- **cmd->Enter**      进入拷贝模式，在拷贝模式下有以下操作：
    1. v 进入 选择/虚拟模式
    2. C-v toggles between blockwise visual mode and visual mode
    3. H jumps to the start of line
    4. L jumps to the end of line
    5. y copies the selection to the top paste-buffer
    6. Escape cancels the current operation
- **cmd->b**          列出粘贴缓冲区列表
- **cmd->p**          从粘贴缓冲区的最近一条取出来并粘贴
- **cmd->P**          从粘贴缓冲区中选择一条并粘贴
- **cmd->:**          进入命令模式