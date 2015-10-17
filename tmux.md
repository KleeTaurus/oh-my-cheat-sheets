# Tmux 小抄大全

### 目录

1. [会话](#sessions)
2. [窗口](#windows)
3. [面板](#panels)
4. [复制模式](#copy-mode)
5. [其他](#misc)
6. [帮助](#help)

### 会话

命令 | 说明
---- | ----
`$ tmux` | 开启一个新会话
`$ tmux new -s mysession` | 开启一个名称为 `mysession` 的新会话
`$ tmux kill-ses -t mysession` | 结束名称为 `mysession` 的会话
`Ctrl` + `b` `$` | 为当前会话重新命名
`Ctrl` + `b` `d` | 断开当前会话
`Ctrl` + `b` `(` | 切换至前一个会话
`Ctrl` + `b` `)` | 切换至后一个会话
`$ tmux a` | 连接到最近断开的会话中
`$ tmux a -t mysession` | 连接到名称为 `mysession` 的会话中
`$ tmux ls` 或 `Ctrl` + `b` + `s` | 显示会话列表

### 窗口

命令 | 说明
---- | ----
`Ctrl` + `b` `c` | 创建一个新窗口
`Ctrl` + `b` `,` | 重新命名当前窗口
`Ctrl` + `b` `&` | 关闭当前窗口
`Ctrl` + `b` `p` | 切换至前一个窗口 
`Ctrl` + `b` `n` | 切换至后一个窗口
`Ctrl` + `b` `0` ... `9` | 跳转到指定窗口, `0` .. `9` 为窗口编号 (窗口编号从 `0` 开始)
`Ctrl` + `b` `:swap-window -s 2 -t 1` | 重新调整 window 的显示顺序, 将窗口 2 和 1 的顺序对调

### 面板

命令 | 说明
---- | ----

### 复制模式

### 杂项

### 帮助
