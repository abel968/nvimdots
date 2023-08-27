| 场景  | 快捷键xxxxxx  | 命令                                 | 说明                                                                                                                         |
| ----- | ------------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| 默认  | Y             | y$                                   |                                                                                                                              |
|       | D             | d$                                   |                                                                                                                              |
|       | \<C-q\>       | :wq                                  |                                                                                                                              |
|       | i \| \<C-b\>  | \<Left\>                             |                                                                                                                              |
|       | i \| \<C-f\>  | \<Right\>                            |                                                                                                                              |
|       | i \| \<C-a\>  | \<Home\>                             |                                                                                                                              |
|       | i \| \<C-e\>  | \<End\>                              |                                                                                                                              |
|       | i \| \<C-d\>  | \<Del\>                              |                                                                                                                              |
|       | i \| \<C-h\>  | \<BS\>                               |                                                                                                                              |
|       | v \| J        | :m '>+1<CR>gv=gv                     | 向上移动一行                                                                                                                 |
|       | v \| K        | :m '>-2<CR>gv=gv                     | 向下移动一行                                                                                                                 |
|       | v \| >        | >gv                                  | 向右缩进                                                                                                                     |
|       | v \| <        | <gv                                  | 向左缩进                                                                                                                     |
| 窗口  | <A-[>         | :vertical resize -5                  |                                                                                                                              |
|       | <A-]>         | :vertical resize +5                  |                                                                                                                              |
|       | \<A-:\>       | :resize -2                           |                                                                                                                              |
|       | <A-'>         | :resize +2                           |                                                                                                                              |
|       | \<A-q\>       | :BufDel                              |                                                                                                                              |
|       | tn            | :tabnew                              | 新建tab                                                                                                                      |
|       | tk            | :tabnext                             |                                                                                                                              |
|       | tj            | :tabprevious                         |                                                                                                                              |
|       | to            | :tabonly                             |                                                                                                                              |
|       | \<ld\>ss      | :SessionSave                         | 保存Session                                                                                                                  |
|       | \<ld\>sl      | :SessionLoad                         |                                                                                                                              |
|       | \<ld\>sd      | :SessionDelete                       |                                                                                                                              |
|       | \<C-n\>       | :NvimTreeToggle                      | 触发左侧目录树                                                                                                               |
|       | \<ld\>nf      | :NvimTreeFindFile                    | 当前文件在左侧目录树中定位                                                                                                   |
|       | \<ld\>nr      | :NvimTreeRefresh                     | 刷新目录树                                                                                                                   |
|       | \<ld\>u       |                                      | Show undo history                                                                                                            |
|       | \<C-\\\>      |                                      | 下方展示终端                                                                                                                 |
|       | \<A-\\\> / F5 |                                      | 右方展示终端                                                                                                                 |
|       | \<A-d\>       |                                      | 中间展示终端                                                                                                                 |
|       | \<C-p\>       |                                      | 命令面板                                                                                                                     |
| 搜索  | \<ld\>w       | :HopWord                             | 定位单词                                                                                                                     |
|       | \<ld\>j/k     | :HopLine                             | 定位行                                                                                                                       |
|       | \<ld\>c       | :HopChar                             | 定位字母                                                                                                                     |
|       | \<ld\>f...    |                                      | 搜索                                                                                                                         |
| Git   | \<ld\>g       |                                      | 触发lazygit                                                                                                                  |
|       | \<ld\>G       | :Git                                 | git的信息                                                                                                                    |
|       | \<ld\>D       | :DiffviewOpen                        | 打开diff                                                                                                                     |
|       | \<ld\>\<ld\>D | :DiffviewClose                       | 关闭diff                                                                                                                     |
|       | gps           | :G push                              | git push                                                                                                                     |
|       | gpl           | :G pull                              | git pull                                                                                                                     |
| 代码  | \<S-Tab\>     | :za                                  | 折叠代码行                                                                                                                   |
|       | J             | :mzJ`z                               | 当前行与下一行合并                                                                                                           |
|       | \<A-f\>       | :FormatToggle                        | 格式化代码                                                                                                                   |
|       | \<ld\>l...    | :Lspxxx                              | Lsp的一些命令，Info Restart Diagnostic                                                                                       |
|       | \<ld\>ci      | :Lspsaga incoming_calls              | 显示当前代码位置的调用方信息。它展示了调用当前位置代码的函数或方法的调用方位置，即代码从其他位置出发，调用了当前位置的代码。 |
|       | \<ld\>co      | :Lspsaga outgoing_calls              | 显示当前代码位置的调用的目标信息。它展示了当前位置代码调用的函数或方法的目标位置，即代码从当前位置出发，调用了其他代码。     |
|       | go            | :Lspsaga outline                     | 当前文件的代码结构                                                                                                           |
|       | g[            | :Lspsaga diagnostic_jump_prev        | 跳到上一个诊断位置                                                                                                           |
|       | g]            | :Lspsaga diagnostic_jump_next        | 跳到下一个诊断位置                                                                                                           |
|       | gs            |                                      | 展示函数签名                                                                                                                 |
|       | gr            |                                      | 当前文件重命名                                                                                                               |
|       | gR            |                                      | 在当前项目重命名                                                                                                             |
|       | ga            |                                      | code action                                                                                                                  |
|       | gd            |                                      | 查看定义                                                                                                                     |
|       | gD            |                                      | 跳转定义                                                                                                                     |
|       | gh            |                                      | 看引用的地方                                                                                                                 |
|       | K             |                                      | 展示当前函数文档                                                                                                             |
|       | gcc gc        |                                      | 行注释                                                                                                                       |
|       | gbc gb        |                                      | 块注释                                                                                                                       |
|       | gea           | :EasyAlign                           |                                                                                                                              |
|       | \<ld\>r       | :SnipRun                             | Run code by range                                                                                                            |
|       | gt            | :TroubleToggle                       | 展示lsp的诊断信息                                                                                                            |
|       | \<ld\>tr      | :TroubleToggle lsp_references        | lsp: Show lsp reference                                                                                                      |
|       | \<ld\>td      | :TroubleToggle document_diagnostics  |                                                                                                                              |
|       | \<ld\>tw      | :TroubleToggle workspace_diagnostics |                                                                                                                              |
|       | \<ld\>tq      | :TroubleToggle quickfix              |                                                                                                                              |
|       | \<ld\>tl      | :TroubleToggle loclist               |                                                                                                                              |
| Debug | \<ld\>d...    |                                      | debug的一些信息                                                                                                              |
|       | \<ld\>db      |                                      | 根据某个条件设置断点                                                                                                         |
|       | F6            |                                      | Continue                                                                                                                     |
|       | F7            |                                      | Stop                                                                                                                         |
|       | F8            |                                      | 触发断点                                                                                                                     |
|       | F9            |                                      | step into                                                                                                                    |
|       | F10           |                                      | step out                                                                                                                     |
|       | F11           |                                      | step over                                                                                                                    |
| 插件  | \<ld\>p...    | :Lazy                                | Lazy 管理其余插件\n                                                                                                          |
