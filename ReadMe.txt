来源 taskbar project (https://github.com/phuslu/taskbar)
感谢其作者@phuslu

下载 https://github.com/yuanlixg/taskbar/archive/master.zip
然后用 vc6 打开 taskbar.dsw, 点"编译"得到 taskbar.exe
此时的 taskbar.exe 是 cmd.exe 的一个外壳
用 reshack/exesope 修改 taskbar.exe 的图标资源和字符串资源就能得到自定义的任意 console 程序的外壳了
比如 goagent.exe

环境变量 VISIBLE 设定初始是否可见, 未定义或为 0 时隐藏窗口
环境变量 MEMORY_LIMIT 设定内存限制, 未定义或为 0 时不限制
