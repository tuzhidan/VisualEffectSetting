# VisualEffectSetting
Set Windows VisualEffects by command,and apply realtime

# depends
编译依赖boost库，按教程编译好boost库之后在项目中设置后保存：
1、项目->项目属性->VC++目录->包含目录:最后添加D:\bin\boost_1_77_0\（我本机路径）
2、项目->项目属性->链接器->附加库目录：输入D:\bin\boost_1_77_0\stage\lib;（我本机路径）

# useage
VisualEffectSetting.exe [option] args
         list : list current setting options.
         get : get current setting as parameters.
         set : set visual effects by parameters.need to args
                 arg 1:setting options (0 - 3)
                 arg 2:selected options.eg: 01000100001000000
       
VisualEffectSetting.exe set 1 00
VisualEffectSetting.exe set 2 00
VisualEffectSetting.exe set 3 01000100001000000

# screenshot
![useage-1](https://user-images.githubusercontent.com/4006912/156282146-d95844b1-fda1-491e-b729-cb154f9c293f.png)

