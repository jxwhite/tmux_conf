ln -s -f .tmux.conf ~/.tmux.conf

第一命令键 `
第二命令键 ctrl+a

cmd->r          重载配置文件~/.tmux.conf
cmd->ctrl+l     清除window中的所有panel和清屏
cmd->ctrl+c     创建新session
cmd->ctrl+f     切换session（以名字）
cmd->ctrl+n     上一个window
cmd->n          下一个window
cmd->tab        在最后使用的两个window间切换
cmd-> \         当前pane竖向一分为二
cmd->]          当前pane横向一分为二
cmd-> h j k l   切换pane
cmd-> H I J K   调整pane大小
cmd-><          交换pane
cmd->>          交换pane
cmd->+          将当前pane最大化，再将使用恢复
cmd->m          开启、关闭鼠标支持
cmd->U          launches Urlview (if available)
cmd->F          launches Facebook PathPicker (if available)
cmd->Enter      进入拷贝模式，在拷贝模式下有以下操作：
    v 进入 选择/虚拟模式
    C-v toggles between blockwise visual mode and visual mode
    H jumps to the start of line
    L jumps to the end of line
    y copies the selection to the top paste-buffer
    Escape cancels the current operation
cmd->b          列出粘贴缓冲区列表
cmd->p          从粘贴缓冲区的最近一条取出来并粘贴
cmd->P          从粘贴缓冲区中选择一条并粘贴