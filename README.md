
## Source Code
* Module [GitHub](https://github.com/Zackptg5/Audio-Modification-Library)

＃音频修改支持库
AudModLib是能让Magisk中已安装的多个音频模块协调运作的框架。[了解更多](https://forum.xda-developers.com/apps/magisk/mod-audio-modification-library-t3745466)

##更新日志
### v1.8  -  7.20.2018
*修复icewizard始终显示错误
*添加用patch_cfgs函数替换库和效果的功能（-r）
*将pre_processing patch_cfgs选项更改为-q
*修复代理效果的错误
*使用xml文件修复与osp的错误
*修正squareound错误

### v1.7.2  -  7.2.2018
*更新了冰向导补丁
*删除osp而不是注释掉

### v1.7.1  -  6.27.2018
*使用osp_detect修复错误 - 现在应修补所有cfgs

### v1.7  -  6.19.2018
*增加了对mixer_gains，audio_device和sapa_feature xml文件的支持
*为自定义AML脚本添加了RUNONCE选项 - 允许它们只运行一次而不是每个音频cfg文件。如果您的mod没有cfg补丁，请使用此选项
*添加了COUNT变量。自定义AML脚本可以使用它来确定脚本运行的次数。如果你的mod有cfg补丁和其他音频文件补丁，请使用此选项
*修复了卸载文件恢复的旧bug
*修复了启动脚本的错误
*删除需要使用patch_cfgs函数指定文件 - 确保为此更新aml.sh脚本
*添加了aninur squareound

### v1.6.2  -  6.15.2018
*修复了混合库/效果
*修正了acp的错误

### v1.6.1  -  6.15.2018
*修复了xml文件的错误

### v1.6  -  6.14.2018
* Redid修补后端 - 非常感谢Rezmir99 @ xda-developers
*完全集成的aml.sh功能 - 用户现在可以像在AudioModificationLibrary.sh脚本中那样使用patch_cfgs函数和LIBDIR变量 - 请参阅支持线程获取指令

### v1.5.7  -  4.26.2018
*新增功能，以让其能在magisk目录的根目录中导入任何带有“.aml.sh”文件的音频模块

### v1.5.6  -  4.12.2018
* 为有单独分区的设备做修复
* misc修复

### v1.5.5  -  4.12.2018
* osp_detect修复

### v1.5.4  -  4.08.2018
*动态效果移除 修复

### v1.5.3  -  4.07.2018
* V4A修复

### v1.5.2  -  4.07.2018
*支持 V4A
*使用动态效果消除

### v1.5.1  -  3.30.2018
*修复效果消失

### v1.5  -  3.28.2018
*添加声音和dha效果去除（一些三星设备需要）
*从ACP mod而不是静态补丁中拉出ACP补丁
*精细调整osp补丁

### v1.4.8  -  3.22.2018
*用重做ACP替换了ubdr

### v1.4.7  -  3.1.2018
*添加Oreo支持接口

### v1.4.6  -  3.1.2018
*修复了sauron的lib目录问题

### v1.4.5  -  2.25.2018
*修复部分有单独分区的引导模式相关文件
*添加了更多策略文件的检测

### v1.4.4  -  2.16.2018
*修复文件中存在空行的处理逻辑
*修复xml文件中关于music_helper / sa3d的项目

### v1.4.3  -  2.14.2018
*修复osp用于适配htc和其他一些独特的设备
*移除Verdor cfg的创建 - 不需要

### v1.4.2  -  2.12.2018
*更多osp修复

### v1.4.1  -  2.9.2018
*尝试修复osp
*为三星设备添加了sa3d移除功能

### v1.4  -  2.9.2018
*修正了osp错误

### v1.3  -  2.8.2018
*修复了output_session_processing补丁的问题

### v1.2  -  2.7.2018
*修正了janky引导模式的一些东西
*修复了在引导模式中无法对音频模块进行卸载或升级

### v1.1  -  2.6.2018
*修复了xml文件
*各种 修复/改进

### v1.0  -  2.5.2018
* 首次发布

＃＃ 源代码
*模块 [GitHub](https://github.com/Zackptg5/Audio-Modification-Library)