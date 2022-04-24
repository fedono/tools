## 工作环境配置

> 这里是日常使用的高频工具，tools-2/tools-3 是比较好的工具，但是日常使用并不高频

- git
    - 终端内输入`git`， 会自动确认是否安装`git`，确认即可
    
- 截图软件
    - `AppStore` 中搜索`Xnip`
    
- 修改`Host`
    - [SwitchHosts](https://github.com/oldj/SwitchHosts)
    
- 编写文档
    - [Typora](https://www.typora.io/)
    - [marktext](https://github.com/marktext/marktext)
      - Typora 最好的替代品
    
- 快速打开应用
    - 安装 `Alfred`
    
- 命令行
    - 安装 [zsh](https://ohmyz.sh/#install)，并修改相关快捷键，一般在`/Users/用户名/.oh-my-zsh/oh-my-zsh.sh`中修改
    
- 终端
    - 安装[iTerm2](https://iterm2.com/) 并设置皮肤为`Solarized Dark Higher Contrast`(皮肤需要下载)
    
- 编辑器
    - [webstorm](https://xclient.info/s/web-storm.html)
        > 使用 webstorm 打开当前文件命令 `open -a webstorm .`
        > 在 config/webstorm 有个 configs.zip的文件（有多个这样的文件，随意使用其中一个），在配置 webstorm 的时候使用 file -> manage IDE settings -> import settings 的路径导入这个配置就可以了
        > 
        > [配置官方文档](https://www.jetbrains.com/help/webstorm/tool-windows.html)
        > 长期使用方式参考 [1](https://xclient.info/a/b11e938b-10b5-83bc-7cc7-3012aba930f8.html) | [2](https://zhile.io/2020/11/18/jetbrains-eval-reset-da33a93d.html)
        
    - [vscode](https://code.visualstudio.com/)
        - 需要直接在代码文件内，打开`vscode`，安装`vscode`后，使用`command + shift + p` 输入`shell`，可以看到`在 path 中安装 code 命令`
         点击安装即可，然后在终端切换到代码文件中，使用`code .` 即可使用`vscode`打开当前文件夹
        - 打开后，使用`command + shift + p` 打开面板，选择 `install 'code' command in path`来配置在命令行中使用`code .` 打开当前目录  
        - 主题找到了 [GitHub.github-vscode-theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) 会觉得好一点
    
- 下载工具
    - Motrix(还没试用过)
    > 支持下载 HTTP、FTP、BT、磁力链、百度网盘等资源    
    
- 压缩工具
    - The Unarchiver
    - [Keka](https://www.keka.io/en/)
      
        > 去官网下上下载，在 app store 上要钱
    
- 剪贴板工具
    - [Clipy](https://clipy-app.com/) 
    
      使用 shift + command + space 来在当前窗口打开所有的剪贴历史来复制
    
- 本地保存代码片段剪贴板工具
  - [snippetslab](https://xclient.info/s/snippetslab.html)
    
    > 点击直接复制代码，可以保存日常使用频率较高的如 shell 脚本等，比如登录机器步骤，比如查找当前机器占用较大的文件，比如 SQL 等
  
- 查看 epub 文件
    - [clearview](https://xclient.info/s/clearview.html)    
    - [Clearview X](https://xclient.info/s/clearview-x.html)  clearview 的升级版，更好，两个都下载
    
- 番茄工具
    - [tomato one]  App Store上搜
    - [Timer](https://github.com/michaelvillar/timer-app)
    
- 控制所有软件的声音
    - [Background Music](https://github.com/kyleneideck/BackgroundMusic)
    - [soundsource](https://xclient.info/s/soundsource.html)
    
- 视频
    - [IINA](https://iina.io/)
    
- 桌面取色工具

    - System Color Picker

         (APP Store 上搜)

- 画流程图，日常画架构图

    - [iThoughtsx](https://xclient.info/s/ithoughtsx.html)
        - 这个还真挺好用的，画脑图使用 tab / enter 自动增加，可以分组、注释，箭头这些都有，很方便
    - [whimsical](https://whimsical.com/)  密码使用 chrome 记录了

- [Thor](https://www.macappbox.com/a/609.html) 

    > 通过快捷键来打开某个应用，其实就相当于桌面软件切换工具，这样就不用再使用 command + tab 来打开所有的面板来切换了，既然我的主要应用是 webstorm 和 Chrome，日常在开发中，就设置这两个应用就可以了
    >
    > 这个才是切换应用最好的，也是最快的，还是比 contexts 要好

- [OpenInTerminal](https://github.com/Ji4n1ng/OpenInTerminal)

    - 平常会在 Thor 中设定 option + s 切换到浏览器，option +  x 切换到终端，option + w 切换到编辑器，那么当我们在浏览文件夹的时候，如何快速使用上面三个程序来打开当前文件夹的文件呢

        可能会在终端进行切换，然后使用 open -a webstorm . 来打开，这样就需要多步的操作了

        终极答案当然是 OpenInTerminal 了，设定 ctrl + s / ctrl + x / ctrl +w 快捷键，可以快速使用上面的三个程序来打开当前的文件夹

- [Typinator](https://www.macappbox.com/a/typinator.html)

    自动化插入经常使用的文本和图形，比如在软件内设置了`dt` 然后他会自动的转换成当天的日期这种，可以在 mac 全平台使用

    >  Oh-my-zshell 中有非常多的插件，输入某个命令能够自动对应具体的命令然后执行，这种就比 Typinator 好，因为这个是无感知的，比如使用 git 的时候，直接使用 gcmsg 就是提交信息，这个替换成 git commit -m 就是无感知的，不会在其他地方输入 gcmsg 的时候会替换，但是使用 Typinator 的时候，就会输入命令立即自动替换成其他的命令，就是有感知的

- [DCommander 3.9.1 双窗格文件管理](https://xclient.info/s/dcommander.html)

    目前能找到的最好的文件管理的工具

    - 还有一个 Qspace 好像也很好，在 APP store 中有，需要六十块多钱就是

- Hidden Bar

    隐藏采集栏中的图标，使用过 bartender 和 vanilla，都不如这个免费的好，在 App Store 中搜就有 

- 在桌面上的时间展示

    - zClock Lite 

      > 直接 app store 下载，免费的

      这个就显示在当前桌面的右上角，在每个桌面都会显示，背景透明，比较没有什么倾入性，所以这个会好一点

    - [onTime PRO](https://xclient.info/s/ontime-pro.html)

      这个是一个比较大一点的，显示当前的月份、星期和时间，只会在当前桌面显示，比较有倾入性，占据的比较显眼。还是使用 zClock Lite 吧
      
      > 进入设置里面取消 time 以及 border 的背景透明度，就能和 zClock Lite 一样了，当个备用吧，挺好的，使用外接显示器的时候，显示器放 zClock Lite 然后笔记本使用 onTime Pro 就挺好

- pbcopy （系统自带的）
    - 在命令行中直接将输出内容复制到剪贴中，如 `cat file.text | pbcopy` 则现在可以使用 `ctrl + v` 粘贴了，也可以通过 `pbcopy < file.text` 将`file.text`中的内容复制到剪贴版中
    - 这时候可以通过 pbpaste 来检索内容，如剪贴中有多个内容，通过 `pbpaste name` 就可以检索到含有 `name` 的内容并进行输出到当前窗口中了

- github加速神器，解决github打不开、用户头像无法加载、releases无法上传下载、git-clone、git-pull、git-push失败等问题。

- 练习打字

    >  如何练习编程的手速？ - 韦易笑的回答 - 知乎 https://www.zhihu.com/question/27021761/answer/53323794
    >
    > - 在[dosbox 官网](https://www.dosbox.com/) 下载能够运行 exe 文件的程序
    > - 下载 [tt.exe](http://www.skywind.me/mw/images/e/eb/TT-Dosbox.7z) 打字文件
    >   - 备用下载地址，登录百度网盘->系统和软件 中有一个 TT-Dosbox.7z 文件，里面有 tt.exe 
    > - 安装 dosbox 之后
    >   - 把 tt.exe 放到 ~/{username}/dosbox 文件夹下
    >   - 在 dosbox 中，使用 mount C:  ~/{username}/dosbox
    >     - 也就是将 ~/{username}/dosbox 设置为 C 盘
    >     - Drive C is mounted as local directory /Users/[your username]/dosbox/
    >   - 然后使用 C: tt.exe 打开tt 软件即可
    >   - 参考 https://www.dosbox.com/wiki/DOSBox_and_Mac_OS_X 

    - 

- 上网
    - [1](https://github.com/vpncn/vpncn.github.io) | [1-副本](https://github.com/vpnforchina/vpnforchina.github.io) 
    - [2](https://glados.one/console)    
    - [3](https://lightyearapp.live/zh/pricing?payment=all)
    - [4](http://strongvpn.com/)
    - [5](https://www.fastvpncn.com/expressvpn)
