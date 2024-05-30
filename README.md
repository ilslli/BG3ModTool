# BG3ModTool
博德之门3MOD汉化工具
# 前言
欢迎使用我的程序，这个程序可以帮助你更快的完成MOD翻译工作且获得较好的效果，当然，这个程序目前也有一些缺陷，如果我有时间我会尝试解决它

我编写这个程序的原因是在翻译MOD的过程中发现效率太低并且质量不高，使用百度等翻译软件的效果太差了，后来发现AI翻译的文本更加符合世界观，但由于我们无法控制AI的输出而且调用API可能需要一些小钱钱，所以想了个笨办法让我们能用上免费的AI

> [!WARNING]
> **这个程序没有解包.pak文件和转译.loca文件的能力，请下载[LSLib](https://github.com/Norbyte/lslib/releases)处理文件！**
> 
如果我有时间我会尝试让它实现这些功能的 :confused: ~~这可能会在很久以后~~

# 介绍
让我来介绍一下我的程序
![Snipaste_2024-05-30_21-31-00](https://github.com/ilslli/BG3ModTool/assets/138840275/49ac4558-a385-48c3-a3da-459605b0ceeb)

这是主界面，让我们简单看一下它的运行流程（如果加载不出来没关系，我会把它放到文件里）


https://github.com/ilslli/BG3ModTool/assets/138840275/e2978178-86a9-40fd-b6a8-c054e46de932

如你所见，它非常的蠢，但这是我能想到比较好的办法，如果你有更好的办法可以告诉我 :relaxed:

具体功能解释请看Wiki页面
- 半自动AI翻译

它可以读取xml文件里的英文文本，并将其复制到你的剪贴板上，首先按下**CTRL+V**并将其发送给AI，然后**按住鼠标左键**选中AI翻译的结果然后按下**CTRL+C**，它就自动粘贴保存到你的文件里了，如果你不想翻译当前选中 的文本可以按**空格**跳过
不断重复这一流程~~这很枯燥~~就可以得到一个翻译完成的xml文件

> [!TIP]
> **在发给AI前给AI设置一个翻译语境更好哦**，如：接下来进行英文翻译，世界观是西方奇幻世界，类似博得之门3，不需要具体解释，只要翻译内容

- 全自动翻译
  在默认模式下翻译模式为全自动翻译，要使用这个功能需要先申请一个[百度翻译API](https://api.fanyi.baidu.com/)的**ID与密钥**，如果不知道如何申请可以Bing一下，百度翻译每个月能免费翻译五万个字符
  
> [!WARNING]
> 注意：由于百度翻译API接口不能频繁调用，只能支持**1秒**翻译一条文本，所以速度会比较慢！

- 创建完整工程文件夹


