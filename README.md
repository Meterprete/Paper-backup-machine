# 写在最前面
这是我的第一个read_me,我怀着激动的心情写下了这篇read_me。真有象征意义。
# Paper-backup-machine功能说明：
这个项目可以让论文狗们一键将论文上传到自己的腾讯微云——无需手动进行任何登录操作。
# 程序使用流程
1.下载Paper_backup_machine.zip到电脑的任一位置，然后解压到同一文件夹里。
2.将你需要保存的论文改名为“需要保存的论文.docx” ，放到D盘根目录下
3.点击backup_machine.exe，这时候会跳出一个浏览器：
  浏览器里的任何东西全都不要手动操作！
  浏览器里的任何东西全都不要手动操作！
  浏览器里的任何东西全都不要手动操作！（重要的事情说三遍）
  出现任何情况都要控制住自己的手，不要在浏览器里点。我的程序都把情况预想到了，请信任程序，所有的东西都在程序的黑框框里按照提示一步一步操作就好。除非程序正式报错，不然请等待，会好的。祝备份愉快！
4.好用的话转到作者主页，给作者点个star(这步可选，哈哈)

# 程序注意事项（必读！）：
## 关于压缩包里两个exe文件：（如果你想使用我的工具的话，你需要且只需要下载这两个）
1.backup_machine.exe和Handle_upload_dialoge.exe这两个文件都需要下载。使用的时候点击backup_machine.exe这一个程序就好，另一个程序是被调用的。backup_machine.exe会自动调用H文件。
2.这两个程序下载到哪里都没关系，但是要注意：
    backup_machine.exe一定要和Handle_upload_dialoge.exe文件放在一起！且Handle_upload_dialoge.exe不能改文件名！
    backup_machine.exe一定要和Handle_upload_dialoge.exe文件放在一起！且Handle_upload_dialoge.exe不能改文件名！
    backup_machine.exe一定要和Handle_upload_dialoge.exe文件放在一起！且Handle_upload_dialoge.exe不能改文件名！（重要的事情说三遍）
  不然程序运行到上传文件那一步一定会出问题。
  back开头的程序名你随便改
## 关于你需要保存的那篇论文：
1.存放位置：请务必将你需要备份的论文放在D盘根目录下，这样程序才能正常调用。也就是说只能是D:\下面，不能是其他盘，也不能是D盘下面的某个文件夹下。这是目前技术原因（AutoIT无法动态接收脚本）。
2.论文命名：一定要命名为：“需要保存的论文.docx”  一个字都不能错 \笑哭···
  这还是因为上面提到的那个编程语言自身的局限，也就是某种技术原因。我知道这里操作起来稍有点不方便，小弟在这里抱歉了，各位客官忍一忍吧hhh之后技术提升后应该会改进的。
## 假如防火墙想要删除程序——不允许！
1.防火墙那个一定不要信任他（“他”指防火墙），信任我的程序就好。然后要是杀毒软件说其中一个文件是木马的话也请不要信，如果被删的话恢复它。这个在我电脑上就被腾讯管家删过。但其实只是一个AutoIT写的用来和上传对话框交互的只有4行程序的代码。我的所有源代码都可以放到项目里供你看，因此这个不用太担心。（而且咱目前想写也写不出木马呀···）
## 程序可能报错的点
1.按照目前我的测试，程序如果报错的话可能的点就最开始登录浏览器的时候。如果浏览器长时间没有加载出登录界面的话，程序就会报错。
解决方法：关闭程序和浏览器，重开
  
# 写在最后面
这是我的第一个read_me,我怀着激动的心情一字一字下了这篇read_me。也算是我的第一个项目吧。真有象征意义。
之前就有朋友说要做项目，前几天和小蒋的交流正式启发了我在github上上传自己的项目——哈哈，姑且算是个小的吧，毕竟完成了一套完整的功能。我发现写项目和写代码自己用还真是有点不一样。本来自己写着玩的话只要自己能用就好，不需要提示语也不担心报错，一次失败了把程序再重开就好，反正能写出来就很好了；现在变成项目的话为了让大家用需要修改了好多功能，也需要考虑更友好的交互，因此需要做很多改进，比如增加了一些提示语和函数，考虑并测试了很多可能出错的地方然后进行异常判断，甚至还增加了一个更仿真的user-agent来企图骗过腾讯微云。我也是学到了，hh。希望这个程序能让大家用得开心！
