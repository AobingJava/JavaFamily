> 点赞再看，养成习惯，微信搜索【**三太子敖丙**】我所有文章都在这里，本文 **GitHub** [https://github.com/JavaFamily](https://github.com/AobingJava/JavaFamily) 已收录，有一线大厂面试完整考点。

昨天群里被的人文怎么破解，晚上洗完澡睡觉正准备睡觉的时候，米豆吵醒了我，说他的idea炸了。

![](https://tva1.sinaimg.cn/large/0082zybply1gbrmpzffcrj30xc0cktc0.jpg)

于是我让他搜我在公司写的破解文档，这个文档已经造福了很多同事了，我痛定思痛，觉得造福一下你们，但是我先说明，大家有能力的还是支持下正版，我只是觉得这个钱拿去洗脚香一点。

## 开始破解

今天破解的方法很简单，jar包破解的，先下载Jar包。

![](https://tva1.sinaimg.cn/large/006tNbRwly1gb36h9dmpfj30ys0emwi2.jpg)

 破解包使用方法:

 0. 先下载压缩包解压后得到jetbrains-agent.jar，把它放到你认为合适的文件夹内。

    公众号回复【**idea**】获取网盘链接。

 1. 启动你的IDE，如果上来就需要注册，选择：试用（Evaluate for free）进入IDE

 2. 点击你要注册的IDE菜单："Configure" 或 "Help" -> "Edit Custom VM Options ..."
    如果提示是否要创建文件，请点"Yes"。

 3. 在打开的vmoptions编辑窗口末行添加：-javaagent:/absolute/path/to/jetbrains-agent.jar
    一定要自己确认好路径(不要使用中文路径)，**填错会导致IDE打不开**！！！最好使用绝对路径。
    一个vmoptions内只能有一个-javaagent参数。

 4. ![](https://tva1.sinaimg.cn/large/006tNbRwly1gb36vup3pcj318i08eaax.jpg)示例:
    mac:      -javaagent:/Users/neo/jetbrains-agent.jar
    linux:    -javaagent:/home/neo/jetbrains-agent.jar
    windows:  -javaagent:C:\Users\neo\jetbrains-agent.jar

    **注**：如果还是填错了，我帮你找到了目录：

    ### Windows

    All the files are located under this directory by default:

    - **Windows Vista, 7, 8, 10:**

    ```
    <SYSTEM DRIVE>\Users\<USER ACCOUNT NAME>\.<PRODUCT><VERSION>
    ```

    - **Windows XP:**

    ```
    <SYSTEM DRIVE>\Documents and Settings\<USER ACCOUNT NAME>\.<PRODUCT><VERSION>
    ```

    ### Mac OS X

    - **Configuration (idea.config.path):**

    ```
    ~/Library/Preferences/<PRODUCT><VERSION>
    ```

    - **Caches (idea.system.path):**

    ```
    ~/Library/Caches/<PRODUCT><VERSION>
    ```

    - **Plugins (idea.plugins.path):**

    ```
    ~/Library/Application Support/<PRODUCT><VERSION>
    ```

    - **Logs (idea.log.path):**

    ```
    ~/Library/Logs/<PRODUCT><VERSION>
    ```

    找到对应的系统idea安装目录，我的是mac，直接去这个目录 ~/Library/Preferences/<PRODUCT><VERSION>

    ![](https://tva1.sinaimg.cn/large/006tNbRwly1gb36so0twvj30kg084jsa.jpg)

    进去就能直接看到那个idea.vmoptions然后简单，vim打开输入正确的地址就好了

    **暖男提示**：一定要写对，有的路径你看着是对的，有的有空格啥的，三歪就是这样，告诉我路径没错，结果有空格，写错是启动不了的。

 5. 重启你的IDE。

 6. 点击IDE菜单 "Help" -> "Register..." 或 "Configure" -> "Manage License..."
    支持两种注册方式：License server 和 Activation code:
    1). 选择License server方式，地址填入：http://jetbrains-license-server （应该会自动填上）
        或者点击按钮："Discover Server"来自动填充地址。
    2). 选择**Activation code**方式**离线**激活，请使用：ACTIVATION_CODE.txt 内的注册码激活
        如果激活窗口一直弹出（error 1653219），请去hosts文件里移除jetbrains相关的项目
        如果你需要自定义License name，请访问：https://zhile.io/custom-license.html

    **注意**：第一种方法偶尔会失效，你用第二种一样的，记得一定要**离线**

 本项目在最新2019.3上测试通过。

 IDE升级会从旧版本导入以上设置，导入配置后可能提示未注册（因为刚导入的vmoptions未生效），直接重启IDE即可，无需其他操作。

## 知识产权说明

中美达成初步“经贸协定”，我国将对知识产权立法更加的严格。

在民事诉讼中，知识产权侵权将由原先的“谁主张谁举证”改为“举证责任倒置”，由被告提供自己不构成侵权的证据。

在刑事责任中，原先知识产权犯罪为结果犯，造成损失才够罪，经贸协定会让知识产权犯罪变为行为犯，只要有违法行为就可能够罪。

行政上，对于销售假冒商品和盗版商品的电子平台，会被吊销经营许可证。

## 警告

 本项目只做学习研究之用，不得用于商业用途！

 若资金允许，请点击 [https://www.jetbrains.com/idea/buy/] 购买正版，谢谢合作！

 学生凭学生证可免费申请 [https://sales.jetbrains.com/hc/zh-cn/articles/207154369-学生授权申请方式] 正版授权！

 创业公司可5折购买 [https://www.jetbrains.com/shop/eform/startup] 正版授权！

开源项目也可以去官网申请一年的免费使用，到期续费就好了，我就是用的这个：

![](https://tva1.sinaimg.cn/large/0082zybply1gbrn1n0mi0j31cq0lkth8.jpg)

暖不暖你说了算，我们下篇文章见：目测是索引，我还用了新的GIF动图方式，以后可能搭配视频。

放个图预告下：

![](https://tva1.sinaimg.cn/large/0082zybply1gbrn3gpcfwg309m04i43b.gif)



持续更新，未完待续......

**白嫖不好，创作不易，**各位的支持和认可（**求点赞**），就是我创作的最大动力，我们下篇文章见！

敖丙 | 文  【原创】

如果本篇博客有任何错误，请批评指教，不胜感激 ！

------

> 文章每周持续更新，可以微信搜索「 **三太子敖丙** 」第一时间阅读和催更（比博客早一到两篇哟），本文 **GitHub** [https://github.com/JavaFamily](https://github.com/AobingJava/JavaFamily) 已经收录，有一线大厂面试完整考点，欢迎Star和完善，我们一起有点东西。

![](https://tva1.sinaimg.cn/large/0082zybply1gbs8wjbex8j30m80rkgpi.jpg)

你知道的越多，你不知道的越多