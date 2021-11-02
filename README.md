# 🎯HMOSHomePage
* 这是一款适用于手机/平板的浏览器主页（兼容pc端浏览器，如edge、chrome、hwbrowser）
* 图标主要来源于“Pure轻雨”图标包，部分改自官方LOGO
* 本人非专业开发者，业余时间“改”出来的“主页”，若有大佬愿意帮忙优化代码，可以通过邮箱联系我
# 💎功能介绍
* 自定义搜索引擎
* 自定义图标颜色、每行书签图标数量
* 自定义壁纸、LOGO、LOGO高度以及LOGO点击/长按功能
* 自定义主页搜索栏样式(细圆、方正)
* 自定义搜索历史是否保存
* 自定义夜间模式（手动、跟随浏览器、定时）
* 支持开启/关闭书签增加
* 支持备份数据(可加密后再导出数据)
* 支持搜索页面进行搜索引擎快速切换
* 添加书签时支持自动获取网站favicon
* 设置页支持检查版本更新(以github版本为标准)
* 搜索栏/书签支持http、https、ftp、file类URL转跳（file类型URL仅支持本地主页）
# 🌐相关地址
* 在线使用地址(GithubPage可能会被墙)：https://icedwatermelonjuice.github.io/HMOSHomePage
* 备用在线地址(国内地址访问较慢)：https://gem-hp.rth.app
* CRX插件版下载：https://github.com/IcedWatermelonJuice/HMOSHomePage/releases
* Github仓库：https://github.com/IcedWatermelonJuice/HMOSHomePage
# 🌹开源致谢
* 原项目名称：quarkHomePage(H5仿夸克浏览器主页)
* 原项目作者：liumingye(刘明野)
* 原仓库地址：https://gitee.com/liumingye/quarkHomePage
# 📪联系方式
* Email：gem_xl@petalmail.com
# 📕更新日志
<版本 1.18>
* 增加主页数据加密/解密功能。现在在导出数据时将提示是否加密主页数据。加密主页数据后，有助于保护数据安全，防止数据泄露或被串改。(PS:加密后主页数据可以通过airportal快速跨端传输)
* 增加了搜索引擎快速切换工具栏显示/隐藏设置。

<版本 1.17>
* 增加搜索引擎快速切换工具栏。现在可以在搜索页面-搜索栏正上方进行搜索引擎快切。注意若要修改自定义搜索引擎，请前往设置。
* 设置页，在搜索引擎中选择自定义，如果已有自定义搜索引擎，则将在弹出的对话框中作为默认值。
* 修复了夜间模式下，书签修改/增加页面中，自动获取图标按钮未适配夜间模式的问题
* 修复了首页书签增加按钮错位的问题

<版本 1.16>
* 自动获取图标支持书签修改页

<版本 1.15>
* 增加了自动获取图标功能。现在添加书签时候可以通过自动获取图标来添加书签图标。(获取失败时，请多次尝试。如果多次尝试均失败，可能是书签url不正确、对方网站拒绝访问favicon.ico或者favicon.ico文件不存在)

<版本 1.14>
* 修复了“整体位置”设置的bug
* 修复了crx版无法查看版本号的bug
* 现在恢复数据将提示是否覆盖原书签数据。选择确定覆盖原书签数据，选择取消将不覆盖原书签数据，新书签数据将接在原书签数据之后
* 新增书签修改功能。长按书签将出现修改图标，点击可以修改书签数据

<版本 1.13>
* 增加了一个“整体位置”设置，可用于设置主页主体部分上下位置
* 主页默认书签更改，增加了“扫一扫”等多个书签

<版本 1.12>
* 修复了LOGO高度设置丢失的问题
* 优化了高度设置、自动夜间模式、设置点击/长按LOGO功能冲突检测的反应速度
* 设置功能缺失检测功能添加对LOGO隐藏的判别

<版本 1.11>
* 设置页增加了“LOGO高度”设置功能(Tips:当高度为0时，LOGO将隐藏)

<版本 1.10>
* 精选页增加了“抖音热搜榜”。由于采用抖音官方接口，解析速度比较慢。如果点击榜单跳转后，看不到东西，请关闭广告拦截类插件或浏览器自带的广告拦截功能
* 精选页常用类，增加了SleasyFork脚本网站入口，增加了CrxSoSo插件网站入口，并调整修改了部分入口位置以及入口图标。
* 优化了自动夜间模式逻辑代码，现在夜间模式自动切换的速度更快了


<版本 1.9>
* 增加了“添加主页书签”功能，可以手动开启或关闭主页书签添加功能
* 增加了“图标数量”设置，可以自定义首页书签每行图标数量

<版本 1.8>
* 修改了精选页“热搜榜”替换来源，并改名为“微博热搜榜”，“知乎热榜”替换来源，改名为“知乎热搜榜”
* 修改了设置页的文字说明
* 增加了“自动夜间模式（用户定时）”功能，可以定时开启夜间模式而不是简单的跟随浏览器
* 当启用“自动夜间模式（跟随浏览器）”时，将屏蔽“夜间模式”与“自动夜间模式（用户定时）”两个选项；当启用“自动夜间模式（用户定时）”时，将屏蔽“夜间模式”与“自动夜间模式（跟随浏览器）”两个选项
* 针对via浏览器，屏蔽无法使用的“自动夜间模式（跟随浏览器）”功能
* 修改默认设置。现在将根据via浏览器、x浏览器、其他浏览器（如chromium内核浏览器）的不同，拥有不同的默认设置，体验更佳

<版本 1.7>
* 设置“关于”增加版本检测功能
* 修复了PC端Edge浏览器LOGO功能设置选项中，有时候会出现“打开书签”选项的BUG

<版本 1.6>
* 增加“点击/长按LOGO”功能设置，可以在打开书签（由于chromium内核限制，书签功能仅Via浏览器和X浏览器可用，其他浏览器意屏蔽该选项）、打开设置、打开精选，三者任选（LOGO功能和书签至少要有一个为设置）
* 修改默认设置：Via浏览器和X浏览器，点击LOGO打开书签，长按LOGO进入设置；其他浏览器，点击LOGO打开精选，长按LOGO进入设置

<版本 1.5>
* 修复了本地主页时，设置页无法通过点击Github/Gitee转跳网页的BUG
* LOGO长按/点击逻辑调整，从而适配PC端：对于Via浏览器和X浏览器，点击可以打开书签，长按可以打开设置；对于其他浏览器如Kiwi浏览器，点击长按均为打开设置页
* 设置页描述性文字修改，整体UI略微改动
 
<版本 1.4>
* 修改设置页（Github与Gitee跳转暂仅支持非本地主页，正在抓紧修复中）
* 新增“恢复默认书签和设置”功能
* “导入/导出主页数据”功能在原本正常“书签”数据基础上，额外支持“设置”数据

<版本 1.3>
* 默认LOGO适配夜间模式
* 新增“自动夜间模式”功能，可跟随浏览器夜间模式（默认开启）。支持PC端Edge浏览器，移动端Kiwi浏览器、X浏览器。暂不支持移动端Via浏览器、华为浏览器、Alook浏览器。其他浏览器效果未知。

<版本 1.2>
* 书签、搜索栏支持“file:///”类型本地URL(本地主页时可用)

<版本 1.1>
* 修改首页默认书签
* 精选页面调整修改

<版本 1.0>
* 修改默认设置：搜索引擎默认为“百度”，搜索栏样式默认为“细圆”，历史记录默认为“不记录”
* 修改首页LOGO，采用华为“HarmonyOS”官方LOGO图标
