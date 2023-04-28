# 很好用的开源安卓软件

个人收集的实用、良心开源安卓软件。

## 基本信息

- **仓库**：
  [Github主仓库](https://github.com/oliverlew/oh-my-foss-android)，
  [Gitee同步仓库](https://gitee.com/lewinat0r/oh-my-foss-android)。
- **特点**：强调使用体验，希望读者能更好地提前了解软件的特点。
- **推荐**：软件推荐，欢迎提交issue或PR。
- **历史**：软件增删等变更请查看git提交历史。
- **版权**：本文遵循[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)版权协议发表。如需转载等，需要符合要求，如该版权要求只能以相同许可协议传播（SA）、需要明确说明作者和来源（BY）。版权声明见文末。


## 选择条件

- **主观体验**：该列表不追求大而全，只是将我自己使用（过）的好软件列出来。
- **干净简约**：界面漂亮，赏心悦目。
- **专一轻量**：功能适中（足够），不臃肿。
- **受众广泛**：目标用户多，适合一般人。
- **积极维护**：源代码持续更新。这一定程度上代表更少的bug和更好的兼容性，也说明开发者的用心和负责。

## 分类

请使用Github/Gitee自带的目录导航功能。

### 应用商店

#### F-Droid 客户端

[F-Droid](https://f-droid.org)是著名的开源安卓软件平台，其客户端提供软件的安装。F-Droid官方源会从源代码编译独立的安装文件，因此可检验软件中的不安全以及非开源因素，使得F-Droid上的软件保证很高的安全性和开源性。

还存在IzzyOnDroid等第三方F-Droid仓库。如果熟悉Linux的用户，会很了解这个概念，即只增加一个软件来源，但保持和F-Droid官方源软件相同的安装方式。这些第三方仓库丰富了软件的数量，提供更及时的更新，也一定程度放宽了采纳标准。

建议安装其中一个F-Droid客户端。

- [F-Droid](https://gitlab.com/fdroid/fdroidclient)
  [[F-Droid](https://f-droid.org/en/packages/org.fdroid.fdroid)]

  F-Droid官方客户端。虽是正统，但功能和界面并不是最好的，没什么值得表扬的。

- [Neo-Store](https://github.com/NeoApplications/Neo-Store)
  [[F-Droid](https://f-droid.org/en/packages/com.machiav3lli.fdroid)]

  Neo Store是基于Droid-ify（见下）的F-Droid客户端。界面风格有较大改动，个人认为更规范了，这里指对于质感设计的应用更加美观和符合直觉，相比之下，Droid-ify可能更加像一个没有设计能力的程序员随意为之的作品。

  曾经取代/继承了Droid-ify，并入[Neo系列应用](https://github.com/NeoApplications/)。但是后来Droid-ify原作者因个人原因，选择不再参与Neo Store的开发，自己继续维护之前的Droid-ify代码。因此，现在两个项目都是正在维护的。

- [Driod-ify](https://github.com/Iamlooker/Droid-ify)
  [[F-Droid](https://f-droid.org/en/packages/com.looker.droidify)]

  F-Droid第三方客户端，基于foxy droid（见下）。后者不怎么维护了，因此有人修复bug、更新界面后发布了这个款app。目前使用起来不会有什么区别，日后可能会有新功能加入。在质感设计的风格上，应该是使用了第3代的设计语言，即有更多的圆角元素等特点。

  更新：0.3版本加入了root👽静默安装，好耶！可以取代foxy了。

  更新：又加入了大量的内置仓库，可以不用导入了。

- ~~[Foxy Droid](https://github.com/kitsunyan/foxy-droid)~~
  [[F-Droid](https://f-droid.org/en/packages/nya.kitsunyan.foxydroid)]

  长时间不更新了，推荐上面Droid-ify和Neo-Store。

  F-Droid第三方客户端，这个很简洁，只有1M多，基本功能尚可用，我一直用作官方客户端的替代品。
  缺点是无法自动和批量安装，每次会弹出安装窗口。

- [Aurora Droid](https://gitlab.com/AuroraOSS/auroradroid)
  [[F-Droid](https://f-droid.org/en/packages/com.aurora.adroid)]
  [[网站](https://auroraoss.com/)]

  F-Droid第三方客户端，有root的话可以一键更新/安装。

#### 谷歌商店第三方客户端

谷歌商店能提供远多于F-Droid的安卓应用，但一般情况下，只能在安装谷歌服务框架的机器上使用。以下客户端能打破这个限制，无需任何依赖地运行在任何安卓手机上。

- [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore)
  [[F-Droid](https://f-droid.org/en/packages/com.aurora.store)]

  谷歌商店第三方客户端。在不安装谷歌框架的情况下，可以用这个安装谷歌商店的软件。它会用一个临时账号帮你下载，因此不会向谷歌暴露自己的个人信息。

### 互联网

#### 浏览器

- [Fennec F-Droid](https://github.com/mozilla-mobile/fenix)
  [[F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/)]

  著名的火狐浏览器的更纯净开源版本，去除了其中的闭源成分。Fennec原意是“[耳廓狐](https://baike.baidu.com/item/耳廓狐)”，根据百科这是最小的犬类动物，取名还是很有寓意的。

  基础源代码还是Mozilla的，但应该是F-Droid平台自己编译，所以只能从这边安装。

#### 邮件

- [K-9 Mail](https://github.com/k9mail/k-9)
  [[F-Droid](https://f-droid.org/en/packages/com.fsck.k9/)]
  [[网站](https://k9mail.app/)]

  最著名的开源邮件客户端，支持多账号，选项很丰富。最近两年UI改进显著，越来越好用了。

  他们的网站是我见过开源软件里做的最好看的之一。

#### 内容获取

这类软件没有自带内容或既定来源，用户自行加入“源”获取在线内容。

- [Feeder](https://gitlab.com/spacecowboy/Feeder)
  [[F-Droid](https://f-droid.org/en/packages/com.example.deeplviewer/)]

  RSS订阅软件，这类软件没有太令我满意的，这个就算比较好的了。

  国内没有什么开源的新闻阅读软件，但是有很多资讯平台有RSS订阅。因此Feeder可以成为一个非常纯粹的新闻阅读软件，没有任何交互，像看报纸一样地阅读📰。

- [FastoTVLite](https://github.com/fastogt/fastotvlite_mobile)

  IPTV客户端，可以从网络串流观看电视节目，大家可以自行从网上搜集IPTV资源，添加至播放器中，就可以播放了。

- [Transistor](https://codeberg.org/y20k/transistor)
  [[F-Droid](https://f-droid.org/en/packages/org.y20k.transistor/)]

  收音机。只不过这个是从网络串流的，不是真正的调频收音机，原因是很多硬件不支持了（也可以从手机自带收音机逐渐消失这一点看出来）。好处是你可以听外地的频道，默认的搜索引擎可以添加上千个国内外频道。

- [URL Radio](https://github.com/jamal2362/URL-Radio)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.jamal2367.urlradio)]

  另一个收音机应用，应该基于Transistor。不太清楚与后者有什么不同，Transistor也没有放弃维护。

- [Legado(阅读)](https://github.com/gedoor/legado)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/io.legado.app.release)]
  [[网站](https://www.legado.top)]

  电子书阅读软件。不提供内置书源，需要用户自行寻找后导入，提高了自由度，也让软件本身更加纯净。

- [Shosetsu(书)](https://gitlab.com/shosetsuorg/shosetsu)
  [[F-Droid](https://f-droid.org/packages/app.shosetsu.android.fdroid)]

  小说阅读软件。这个内置了一些下载源。我没有读过里面的小说，但是比较喜欢这种形式的软件。

- [Myne](https://github.com/Pool-Of-Tears/Myne)
  [[F-Droid](https://f-droid.org/en/packages/com.starry.myne/)]

  电子书下载与阅读。从一个固定的源下载电子书，都是一些经典书籍，一般是版权过期进入公共领域的书，很不错的软件。

### 多媒体

#### 视频播放器

- [VLC](https://www.videolan.org/vlc/download-android.html)
  [[F-Droid](https://f-droid.org/en/packages/org.videolan.vlc/)]
  [[网站](https://www.videolan.org/vlc/download-android.html)]

  多媒体播放器，开源最佳之一，和电脑端一样功能强大，界面也很漂亮。

- [Nova Video Player](https://github.com/nova-video-player/aos-AVP)
  [[F-Droid](https://f-droid.org/en/packages/org.courville.nova/)]

  视频播放器，作为VLC的补充。Nova有类似于Plex的功能，可以管理视频库，显示封面，联网获取信息等。还有电视模式，可以作为家庭影院的开源方案。个人体验通过SFTP播放视频加载网速比VLC快好几倍（你要问为什么是SFTP，因为我用Linux）。

- [mpv-android](https://github.com/mpv-android/mpv-android)
  [[F-Droid](https://f-droid.org/en/packages/is.xyz.mpv/)]

  基于Linux平台很出名的播放软件MPV，以UI简洁(lòu)著称。安卓版本并非官方开发，所以就更简洁(lòu)了😢。总体上不如VLC和Nova，但继承了桌面端的可定制性，可以编辑配置文件改变选项和快捷键。

- [Kore](https://github.com/xbmc/Kore)
  [[F-Droid](https://f-droid.org/en/packages/org.xbmc.kore/)]

  Kodi官方遥控器应用（**Ko**di **re**mote）。前者是非常棒的开源家庭影院应用，用来播放本地或远程的多媒体文件。

#### 音乐播放

- [Vinyl](https://github.com/AdrienPoupa/VinylMusicPlayer)
  [[F-Droid](https://f-droid.org/en/packages/com.poupa.vinylmusicplayer/)]

  很轻量且干净的音乐播放器。可能是开发难度低，F-Droid上太多音乐软件了。搜"music"关键词，最近更新的都比较好，恕不一一列举。基于[Phonograph](https://github.com/kabouzeid/Phonograph)，后者很早停止维护了，但是却是很经典的质感设计音乐播放器，值得怀念。

  列表最后面有个lineage OS自带音乐播放器，和这个超级像，更加精简。

- [Phonograph Plus](https://github.com/chr56/Phonograph_Plus)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/player.phonograph.plus)]

  也是Phonograph正在积极维护的fork，在逐渐增加功能，中短期应该不会放弃。

- [Mpd](https://github.com/MusicPlayerDaemon/MPD/)
  [[F-Droid](https://f-droid.org/en/packages/org.musicpd/)]

  前后端分离的音乐播放应用。这个属于极客范畴了，本身不携带控制界面，并且实用性也不如正常的音乐播放器。Linux用户或许用过，至少我是很喜欢的（是说喜欢Linux桌面的使用情景，安卓上的使用体验是很糟的）。

- [M.A.L.P.](https://gitlab.com/gateship-one/malp)
  [[F-Droid](https://f-droid.org/en/packages/org.gateshipone.malp/)]

  上述Mpd的前端。可以控制安卓手机自己的Mpd，也可以连接到电脑上的Mpd。

#### 绘画

- [Pocket Paint](https://github.com/Catrobat/Paintroid)
  [[F-Droid](https://f-droid.org/en/packages/org.catrobat.paintroid/)]

  随便画点啥，功能比较全，甚至还有图层，界面也简洁漂亮。

- [PixaPencil](https://github.com/therealbluepandabear/PixaPencil)
  [[F-Droid](https://f-droid.org/en/packages/com.therealbluepandabear.pixapencil/)]

  **警告**：已经停止开发。

  自称“第一的开源像素绘画应用”，大概相当于windows上的绘图，貌似要功能更丰富一些。

#### 相机

- Aperture

  Lineage OS 20 自带相机应用。相较之前自带的Snap（版本19之前）和AOSP原生相机（版本19），界面更加漂亮，功能更加丰富，可以说接近手机原系统中的相机应用了。

  有了这个（当然前提是你在用LineageOS），我自认为可以不再考虑下面几个开源方案。
  此外，只有Gcam可以在功能和质量上好于Aperture，但与系统的集成却很差。不在乎成像质量的，使用这个自带应用就行。

  之前的描述依然适用，复制如下：

  这类第三方相机软件（这是相对于手机原系统来说的）都有一个缺陷，就是无法很好地利用硬件，比如无法利用一分四的超像素，没有延长曝光的超级夜景模式，等等。
  不过在软件上做的已经很不错，还集成了二维码扫描，不用装单独的二维码扫描软件了。

- [FreeDCam](https://github.com/KillerInk/FreeDcam)
  [[F-Droid](https://f-droid.org/en/packages/troop.com.freedcam)]

  相机软件。我觉得这个和Open Camera是开源相机中最好的两个，功能比较全面。当然这个全面是指对任何摄像头都适用的功能，如广角畸变修正、4合1像素再拆成4像素等就不灵了。作为通用相机软件，已经很不错了。

- [Open Camera](https://sourceforge.net/p/opencamera/code)
  [[F-Droid](https://f-droid.org/en/packages/net.sourceforge.opencamera/)]
  [[网站](https://opencamera.org.uk/)]

  比较强大的相机软件。但是界面很丑，开发减缓，感觉开发者逐渐有点无心无力。（不过，最近更新了1.49.1。）

- [Photon Camera](https://github.com/eszdman/PhotonCamera)

  很神奇的相机软件。在LineageOS下，其它相机软件照片质量奇差，涂抹到细节全失。偏偏Photon Camera的照片质量堪比官方OS下的自带相机。另外，像夜景模式、超像素的支持也都有。在功能上是吊打上面两位和LineageOS自带相机的。

  更新：这一段的问题应该已经解决，我尝试编译了最新的git仓库代码，没有长时间卡顿了，不过没有新版本发布。在此前，打开和切换界面都等数十秒长。有[一个issue](https://github.com/eszdman/PhotonCamera/issues/54)说它在扫描设备上所有的照片，不知是不是长时间不响应的原因。

  另外，这款软件可能不是默认支持所有设备的，但没找到它支持设备的条件（源代码里有支持列表）。

- [Gcam-Services-Provider](https://github.com/lukaspieper/Gcam-Services-Provider)
  [[F-Droid](https://f-droid.org/en/packages/de.lukaspieper.gcam.services/)]

  这个本身不是相机软件，但安装后允许用户安装Gcam，即谷歌相机。也就是说，这个解决方案其实并不是开源的，不过却是最完美的。

  大家可以到[Gcam的网站](https://www.celsoazevedo.com/files/android/google-camera/links/)寻找自己机型的适配版本和配置文件，简单安装即可。据我自己体验，Gcam的照片质量远超开源方案，可以说能补足第三方ROM最大的短板，完全可以考虑。

### 日常工具

#### 地图

- [OSMAnd~](https://github.com/osmandapp/Osmand)
  [[F-Droid](https://f-droid.org/en/packages/net.osmand.plus/)]
  [[网站](https://osmand.net/)]

  OpenStreetMap地图。因为数据都是用户自己贡献的，所以越偏僻的地方数据越少。如果在大城市，可以尝试一下，基本的浏览和导航功能还是可以用的。

  请在F-Droid平台安装，那边的开发者在源代码的基础上，去掉了其中的付费页面，编译了OSMAnd+的所有功能。这在谷歌苹果亚马逊的商店都收费至少20刀。

  OSM能做到的功能实际很多，国内地图能记录的信息OSM基本都可以，比如多层建筑、公交地铁线路，但要贡献者自己学会怎么编辑。

#### 天气

- [几何天气](https://github.com/WangDaYeeeeee/GeometricWeather)
  [[F-Droid](https://f-droid.org/en/packages/wangdaye.com.geometricweather/)]

  用过最好的天气软件之一，媲美很多国内安卓系统的自带天气。

- [Pluvia Weather](https://github.com/SpicyChair/pluvia_weather_flutter)
  [[F-Droid](https://f-droid.org/en/packages/com.spicychair.weather/)]

  不错的天气软件，界面相当漂亮，但是使用的OpenWeatherMap貌似国内连接很慢，预报也不一定准确。

#### 自我管理

- [Tasks](https://github.com/tasks/tasks)
  [[F-Droid](https://f-droid.org/en/packages/org.tasks/)]
  [[网站](https://tasks.org/)]

  待办列表管理，应该是同类最佳之一了。

- [Loop Habit Tracker](https://github.com/iSoron/uhabits)
  [[F-Droid](https://f-droid.org/en/packages/org.isoron.uhabits/)]

  制定规划，帮你监督，习惯养成利器。可以记录你每天计划完成的进度，做出统计，定时提醒。

- [Feeel](https://gitlab.com/enjoyingfoss/feeel)
  [[F-Droid](https://f-droid.org/en/packages/com.enjoyingfoss.feeel/)]

  锻炼规划。一个锻炼方案可以设定多个锻炼项目和时长，指导你完成锻炼。界面很漂亮，运动时每个项目有倒计时，内置的几个锻炼项目有根据真实照片抽象化的姿势展示。

- [Did I Take My Meds?](https://github.com/CorruptedArk/did-i-take-my-meds)
  [[F-droid](https://f-droid.org/en/packages/dev.corruptedark.diditakemymeds)]

  监督用药。可以增添用药条目，指定数量，它会提醒你吃药，以及记录过往用药。虽然是新软件，但是目前的功能已经很不错了。

#### 小工具

- [Ruler](https://github.com/congshengwu/Ruler)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ruler.csw)]

  **警告**：源代码貌似没了。

  很简单的屏幕直尺，默认可能有误差，但好在可以校准，没准什么时候可以应急。

- [Compass](https://github.com/Kr0oked/Compass)
  [[F-Droid](https://f-droid.org/en/packages/danielmeek32.compass)]

  指南针。

#### 自然声音

- [Noice](https://github.com/ashutoshgngwr/noice)
  [[F-Droid](https://f-droid.org/en/packages/com.github.ashutoshgngwr.noice/)]
  [[网站](https://ashutosh.blog/noice/)]

  播放噪音/自然声音。内置各种共30+种声音，可以自由组合，设置每一种声音的音量，保存为预设。

### 学习办公

#### 办公套件

- [Collabora Office](https://www.collaboraoffice.com/)
  [[独立源](https://www.collaboraoffice.com/releases-en/collabora-office-on-mobiles-supporting-password-protected-documents-and-available-on-f-droid/)]
  [[网站](https://www.collaboraoffice.com)]

  LibreOffice的安卓适配版，可以实现大多数的文档查看，还有实验性的编辑功能。这个应该是最好的开源office组件了（但依然不够好）。

  需要F-Droid加入第三方源（链接见上），就可以方便地安装更新。

- [OpenDocument Reader](https://github.com/TomTasche/OpenDocument.droid)
  [[F-Droid](https://f-droid.org/en/packages/at.tomtasche.reader)]

  功能很弱的文档查看软件，貌似主要解析文档里的内容，文档的格式就很……怎么说，显示地很朴素😅。几乎没有编辑功能。

#### 笔记

- [Markor](https://github.com/gsantner/markor)
  [[F-Droid](https://f-droid.org/en/packages/net.gsantner.markor/)]
  [[网站](https://gsantner.net/project/markor.html?source=fdroid)]

  笔记软件，使用markdown语法。

  这个对于很多人并不是最优选择，但是我喜欢它直接对本地的纯文本文件进行编辑，而不是保存为其他的格式。这样我可以自行管理markdown文件，包括同步到电脑上，用其他编辑器去编辑。

  这样不需要软件实现跨平台❎，而是通过文件格式进行跨平台。☑️

- [Notally](https://github.com/OmGodse/Notally)
  [[F-Droid](https://f-droid.org/en/packages/com.omgodse.notally/)]

  极简又漂亮的笔记应用，只能输入纯文字，有少许加粗斜体等格式。

- [Saber](https://github.com/adil192/saber)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.adilhanney.saber)]

  不多见的开源手写笔记软件。我没有安卓平板，不知道实际体验如何。

#### 文档

- [OpenScan](https://github.com/Ethereal-Developers-Inc/OpenScan)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ethereal.openscan)]

  文档扫描。和大家想的一样，可以拍照、裁切、再合成一个文档，可以导出为PDF。功能完整，比如有再次裁切（只能再切小）、调整顺序、颜色优化（灰阶或黑白）、分享等等。

  相比之下，我试过的其它开源扫描软件就太差了，上面功能大量缺失，我觉得缺一不可。

- [Pdf Viewer Plus](https://github.com/JavaCafe01/PdfViewer)
  [[F-Droid](https://f-droid.org/en/packages/me.zhanghai.android.files)]

  **警告**：已停止开发，建议用下面的MJ PDF Reader。

  PDF阅读器，开源的同类软件UI都不怎么样，这个算是很好的了，期待和谷歌PDF阅读器差不多的开源版本出现。

- [MJ PDF Reader](https://gitlab.com/mudlej_android/mj_pdf_reader)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.gitlab.mudlej.MjPdfReader)]

  基于上述Pdf Viewer Plus的PDF阅读器。由于前者很久无维护，所以这个项目做了大量重构与适配工作，修复了一些问题，增加一些功能。总体来说解决了之前项目的一些痛点，值得一用。

- [Librera Reader](https://github.com/foobnix/LibreraReader)
  [[F-Droid](https://f-droid.org/en/packages/com.foobnix.pro.pdf.reader/)]
  [[网站](https://librera.mobi/)]

  一个电子书的阅读与管理软件。其实开源安卓应用中很少具有管理文档的功能，这个软件就填补了空缺。

  界面虽然看起来很过时，但是整个应用的功能还是很成熟的，这个应该更重要一些。

#### 词典翻译

- [Aard2](https://github.com/itkach/aard2-android)
  [[F-Droid](https://f-droid.org/en/packages/itkach.aard2/)]

  还是不错的词典软件，支持很多词典，可以在官网找到相应下载链接。可惜作者不愿意将界面更新为早已成为主流的质感设计（见此[issue](https://github.com/itkach/aard2-android/issues/72)），因此界面很老旧。

- [QuickDic](https://github.com/rdoeffinger/Dictionary)
  [[F-Droid](https://f-droid.org/en/packages/de.reimardoeffinger.quickdic/)]

  词典软件。怎么说呢，一言难尽啊，开源的词典真的没找到很好用的。这个QuickDic可以下载很多中词典文件，但基本是多语种互译。查词的时候把所有词显示出来，查哪个滚动到哪个。

- [DeepL](https://github.com/sakusaku3939/DeepLAndroid)
  [[F-Droid](https://f-droid.org/en/packages/com.example.deeplviewer/)]

  翻译软件。基于深度学习的翻译引擎，这个是把网页版包装成了一个轻量的应用。重要的是，可以在选取文字后的弹出菜单里选择DeepL进行翻译。

#### 数学工具

- [microMathematics Plus](https://github.com/mkulesh/microMathematics)
  [[F-Droid](https://f-droid.org/en/packages/com.mkulesh.micromath.plus/)]

  掌上CAS。极为强大的计算机代数系统（CAS），函数、微积分、作图等应有尽有。采用了最近越来越常见的笔记本（notebook）的形式，输入和输出都可以保留下来，作图会内置显示等。陪你度过大学不是梦。

#### 百科

- [Wikipedia](https://github.com/wikimedia/apps-android-wikipedia)
  [[F-Droid](https://f-droid.org/en/packages/org.wikipedia/)]
  [[网站](https://www.mediawiki.org/wiki/Wikimedia_Apps)]

  维基百科官方客户端，只有10M，很小巧但五脏俱全。Wikipedia在平台建设上确实遥遥领先，希望国内同行快点幡然醒悟。

#### 星图

- [Sky Map](https://github.com/sky-map-team/stardroid)
  [[F-Droid](https://f-droid.org/en/packages/com.google.android.stardroid/)]

  星图软件，让你上知天文。借助重力感应，把手机指向天空就可以方便对照天上的星是什么名字。当然其他功能就不多了。

  虽然在更新，但是界面比较落后，数据貌似也不多。

- [Stellarium](https://www.stellarium-labs.com/stellarium-mobile-plus/)

  大名鼎鼎的Stellarium，最近桌面端发布了1.0版本，才反应过来它也是开源的。但是只能在其他应用商店下载。专业性上即便在商业软件中也算极为优秀。

#### 单位转换

- [Unit Converter Ultimate](https://github.com/physphil/UnitConverterUltimate)
  [[F-Droid](https://www.f-droid.org/packages/com.physphil.android.unitconverterultimate/)]

  单位转换工具，非常全面，除了常见的长度、面积、重量等基础物理单位，还有汇率、存储单位等。

### 系统工具

#### 文件管理

- [Material Files](https://github.com/zhanghai/MaterialFiles)
  [[F-Droid](https://f-droid.org/en/packages/me.zhanghai.android.files/)]

  文件管理器，非常漂亮，基本的功能都有。

- [Disk Usage](https://github.com/IvanVolosyuk/diskusage)
  [[F-Droid](https://f-droid.org/en/packages/com.google.android.diskusage/)]

  磁盘占用分析，类似于Windows的SpaceSniffer，类Unix的du，显示手机上磁盘占用情况。

  这类开源应用实在没有更“现代”的选择了，界面比较落后，好在这个软件依然完美运行，源代码也在维护。根据最新半个月（2022.04）的提交消息来看，有超级多的代码更新，可能会有新版本？

#### 文件同步

- [Seafile](https://github.com/haiwen/seadroid)
  [[F-Droid](https://f-droid.org/en/packages/com.seafile.seadroid2/)]
  [[网站](https://www.seafile.com/home/)]

  文件同步/网盘客户端。是国内开发的，需要自己搭服务器。我们学校用它做了一个box，访问起来很方便：）

#### 文件加密

- [DroidFS](https://forge.chapril.org/hardcoresushi/DroidFS)
  [[F-Droid](https://f-droid.org/en/packages/sushi.hardcore.droidfs/)]

  加密存储文件。

- [Photok](https://github.com/leonlatsch/Photok)
  [[F-Droid](https://f-droid.org/en/packages/dev.leonlatsch.photok/)]

  加密相册，选入应用集时正在积极开发，大量功能将要加入。

- [Anemo](https://github.com/2bllw8/anemo)
  [[F-Droid](https://f-droid.org/en/packages/exe.bbllw8.anemo)]

  首先说明，这个并不是文件加密软件，但是应该可以满足部分需要这类应用的用户需求。

  我们可以使用Anemo将文件存入这个应用的私有本地空间。Anemo会隐藏这些文件，但用户可以选择临时开启，就可以从文件管理器的侧边栏看到入口。在15分钟无访问后，入口会再次隐藏。整个过程并未加密。

#### 输入法

- [Unexpected Keyboard](https://github.com/Julow/Unexpected-Keyboard)
  [[F-Droid](https://f-droid.org/en/packages/juloo.keyboard2/)

  非常轻量的输入法（目前版本不到200kB），专为程序员、极客人群设计，终端搭配神器。在较常见的4行键位基础上，通过在每一个键向四个角滑动的操作，触发其他的按键。

  重点是，这款键盘默认操作体验十分顺手（此处@Trime）。如果之前在用Hacker's keyboard的，可以换这个了。

- [Fcitx5-Android](https://github.com/fcitx5-android/fcitx5-android)

  在它出现之前，开源的安卓拼音输入法应该只有同文输入法（见下）。而Fcitx（小企鹅）的加入，可以说解决了很多人（包括我）的痛点。我用了一段时间，感觉已经无缝替换掉了Gboard。

  Fcitx输入法的特点就是对小白用户友好，和谷歌的Gboard很像，很多界面元素和交互体验的设计应该直接借鉴了后者。这是个好事，相比之下，同文输入法就给我带来了了不少的操作负体验。两款软件就体现了友好度和定制性的权衡。

  在用户界面和体验上，Fcitx已经很成熟了。即便目前的版本还是0.0.3（表示还不稳定）。想安装即用的，绝对推荐。想要强大定制性的，则推荐下方的同文输入法。

- [同文输入法](https://github.com/osfans/trime)
  [[F-Droid](https://f-droid.org/en/packages/com.osfans.trime/)]

  ~~F-Droid上甚至是开源软件中唯一一个中文拼音输入法。~~（有新选手加入，见上fcitx）同文输入法就像其桌面版一样，基于配置文件，定制性相当恐怖😱，你喜欢的样子它都有。
  配置文件对上手是一个门槛，需要自行下载配置文件导入。

  本以为两年不更新了，结果又有新版本了（指v3.2.0版本与上一个版本相隔3年多）。一个开源软件突然恢复维护是一件令人感到幸福的事情。

- [笔划输入法](https://github.com/stroke-input/stroke-input-android)
  [[F-Droid](https://f-droid.org/en/packages/io.github.yawnoc.strokeinput/)]

  很简单的笔划输入法，虽然平时不用，但感觉可用性是不差的。容错性稍稍差了一些，所有笔划都要严格归入横、竖、撇、捺和折5种，判断错误就找不到字了。

#### 下载管理

- [Download Navi](https://github.com/TachibanaGeneralLaboratories/download-navi)
  [[F-Droid](https://www.seafile.com/home/)]

  功能强大的下载器，可以多段加速，分享下载链接就可以选择下载。

#### 卫星定位

- [GPSTest](https://github.com/barbeau/gpstest)
  [[F-Droid](https://f-droid.org/en/packages/com.tachibana.downloader/)]

  显示GPS信息，非常丰富，可以看到五种全球定位系统的卫星位置、自己的经纬度、海拔还有速度等等。

#### 备份

- [Neo Backup](https://github.com/NeoApplications/Neo-Backup)
  [[F-Droid](https://f-droid.org/en/packages/com.android.gpstest.osmdroid/)]

  备份软件（之前名称为OAndBackupX），可以备份任何东西，需要root。

#### 电话录音

- [Call Recorder](https://gitlab.com/axet/android-call-recorder)
  [[F-Droid](https://f-droid.org/en/packages/com.github.axet.callrecorder)]

  电话自动录音，非本土化系统中很实用，搭配Magisk模块可以成为系统应用。

#### 密码

- [Password Store](https://github.com/android-password-store/Android-Password-Store)
  [[F-Droid](https://f-droid.org/en/packages/dev.msfjarvis.aps/)]

  密码管理和自动填充软件。要先了解Linux平台上的[password store](https://www.passwordstore.org/)才能用，这个是安卓客户端。

  password store本身只是一个小脚本，调用git管理gpg加密的密码文件，这个安卓版也是类似。因而可以选择GitHub私人仓库+password store的超轻量开源方案，而非托管在统一的服务器上，这很Unix。

- [andOTP](https://github.com/andOTP/andOTP)
  [[F-Droid](https://f-droid.org/en/packages/org.shadowice.flocke.andotp/)]

  **警告**：已不再维护。

  双重验证（2FA）或者一次性密码（OTP）客户端，就是很多网站登录时出于安全性设置的6位数动态验证码。

- [Aegis](https://github.com/beemdevelopment/Aegis)
  [[F-Droid](https://f-droid.org/en/packages/com.beemdevelopment.aegis/)]

  和andOTP类似，是一款双重验证码客户端。相比起来，这款界面更简洁、符合质感设计，其它方面大同小异。

- [OpenKeychain](https://github.com/open-keychain/open-keychain)
  [[F-Droid](https://f-droid.org/en/packages/org.sufficientlysecure.keychain/)]
  [[网站](https://www.openkeychain.org/)]

  PGP锁钥管理，我是搭配password store使用，提供解锁密钥。此外还有很多软件可以使用它。

#### 电脑连接

- [AN2Linux](https://github.com/rootkiwi/an2linuxclient)
  [[F-Droid](https://f-droid.org/en/packages/kiwi.root.an2linuxclient/)]
  [[网站](https://github.com/rootkiwi/an2linuxserver/)]

  **警告**：已不再维护。建议使用下面的A2LN。

  通知同步软件，将手机上的通知推送到Linux电脑上，可以通过WiFi、蓝牙或者移动数据。我只试过WiFi，不知道另两个体验如何。

- [A2LN](https://github.com/patri9ck/a2ln-app)
  [[F-Droid](https://f-droid.org/en/packages/dev.patri9ck.a2ln)]

  与上面的AN2Linux类似，说明见上。

- [KDE Connect](https://github.com/KDE/kdeconnect-android)
  [[F-Droid](https://f-droid.org/packages/org.kde.kdeconnect_tp/)]

  很强大的连接PC和手机的工具。可以分享文件或文本、同步通知、运行命令和远程控制等等。需要Linux系统上安装相应的pc端软件，常见的如KDE官方的[kdeconnect](https://kdeconnect.kde.org/)和适配GNOME的[GSConnect](https://github.com/GSConnect/gnome-shell-extension-gsconnect)。

  KDE团队做的很好的一点是，他们将KDE Connect前后端分离开了，真正支撑底层功能的部分实现为一种协议，可以独立于图形界面部分运行。这样在非KDE环境，便可以用其它的软件，如我在使用的[mconnect](https://github.com/grimpy/mconnect)，就是没有图形界面，只有命令行接口，但如果你想要的基本功能都具备，可以很灵活而不受桌面环境限制。

#### 手机安全

- [Hypatia](https://gitlab.com/divested-mobile/hypatia)
  [[F-Droid](https://f-droid.org/en/packages/us.spotco.malwarescanner/)]

  自称安卓第一款恶意软件扫描应用。不过，既然都用开源软件了，这个的意义就没那么大了，除非用户依然想胡乱下载其他的东西。

#### 系统清理

- [LTE Cleaner](https://github.com/TheRedSpy15/LTECleanerFOSS)
  [[F-Droid](https://f-droid.org/en/packages/theredspy15.ltecleanerfoss/)]

  系统清理软件。这个并不是很强大，它只负责清理日志（Log）、临时文件（Temporary）和空文件夹（Empty）。但是聊胜于无。

#### 传感器

- [Phyphox](https://github.com/phyphox/phyphox-android)
  [[F-Droid](https://f-droid.org/en/packages/de.rwth_aachen.phyphox/)]
  [[网站](https://phyphox.org)]

  显示手机传感器信息，以及利用手机完成一些小实验。这个应用是亚琛大学的老师学生设计开发。可以使手机变身成为一个小的物理实验室，进行光学、声学和力学实验。

#### 系统美化

- [Doodle](https://github.com/patzly/doodle-android)
  [[F-Droid](https://f-droid.org/en/packages/xyz.zedler.patrick.doodle/)]
  [[网站](https://patrickzedler.com/doodle/)]

  质感设计风格的动态壁纸，具有自动暗色模式和省电动画等特点。喜欢抽象、简约风格的可以试一试。

### 极客工具

我并不想分一个“开发类”，这里的软件并不是面向开发者的，而是喜欢折腾的用户。这也符合最开始制订的”受众广泛“要求。

#### Root工具

- [Magisk](https://github.com/topjohnwu/Magisk)
  [[F-Droid](https://f-droid.org/en/packages/com.topjohnwu.magisk/)]
  [[网站](https://topjohnwu.github.io/Magisk/install.html)]

  著名的面具，需要电脑端配合安装，可以提供root和修改系统行为的模块。
  不过，不是刚需的话，不建议使用。我使用Lineage OS，因此微信和支付宝的指纹无法正常调用，便使用一些面具模块解决。

  Magisk并没有提供每一种机型的下载，所以其安装过程对所有机型适用。

#### 文本编辑

- [Editor](https://github.com/billthefarmer/editor)
  [[F-Droid](https://topjohnwu.github.io/Magisk/install.html)]

  轻量的文本编辑器，很小很小的软件还有语法高亮，吹爆它。

  一个问题是，一般只能打开安卓识别为纯文本的文件，连yaml都不行。除非文件管理器能强行作为文本打开。GitHub有好几个issue提到，但作者坚决把锅甩给安卓和文件管理器，感觉作者有开发“洁癖”。

- [Acode](https://github.com/deadlyjack/Acode)
  [[F-Droid](https://f-droid.org/en/packages/com.foxdebug.acode/)]
  [[网站](https://acode.foxdebug.com/)]

  更高级的文本/代码编辑器。从截图上看，Acode可能更适合在平板等大屏设备上进行更专业的编辑工作，类似于VS Code等软件。

#### 远程连接

- [ConnectBot](https://github.com/connectbot/connectbot)
  [[F-Droid](https://f-droid.org/en/packages/org.connectbot/)]

  Ssh客户端，很好用。在维护但很久没有新版本了。我校阅了所有的翻译，希望将来有更新。

  2021.10.25：更新啦。

- [AVNC](https://github.com/gujjwal00/avnc)
  [[F-Droid](https://f-droid.org/en/packages/com.gaurav.avnc/)]

  简单但不简陋的VNC客户端。可以通过手势实现不同的鼠标控制事件，因此是很实用的。

- [WADB](https://github.com/RikkaApps/WADB)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/moe.haruue.wadb)]

  无线ADB，需要root。虽然安卓在开发者选项中也可以开启“无线调试”，但这里开启的端口是随机的，明显是出于安全考虑。如果你所在网络没有那么危险，这款应用可以在固定的、也是默认的5555端口开启无线调试，因此电脑使用adb时无需输入端口信息即可连接。

#### 终端

- [TermOne Plus](https://gitlab.com/termapps/termoneplus)
  [[F-Droid](https://f-droid.org/packages/com.termoneplus/)]

  终端应用。有些系统中会禁用系统自带的安卓终端，所以想要在安卓上执行命令行操作，可以尝试这款应用。

#### Git及平台客户端

- [OctoDroid](https://github.com/slapperwan/gh4a)
  [[F-Droid](https://f-droid.org/en/packages/com.gh4a/)]

  GitHub客户端，对GitHub各项功能支持比较全面（指reaction表情、通知等细节都有），但是开发比较迟缓了。

- [GitFox](https://gitlab.com/terrakok/gitlab-client)
  [[F-Droid](https://f-droid.org/en/packages/com.gitlab.terrakok.gitfox/)]

  GitLab客户端，有点简洁，功能不多。GitLab可以自主搭建服务器，因此支持登录其他服务器。

- [GitTouch](https://github.com/git-touch/git-touch)
  [[F-Droid](https://f-droid.org/en/packages/io.github.pd4d10.gittouch/)]

  很多git托管平台的客户端，比如GitHub，GitLab等。注意不是git客户端，没发现很好的git客户端。

- [MGit](https://github.com/maks/MGit)
  [[F-Droid](https://f-droid.org/en/packages/com.manichord.mgit/)]
  [[网站](https://manichord.com/projects/mgit.html)]

  不太好的git客户端里不太差的一个。在维护，但很久不发布新版本，界面也很古老，是Android 4时代的界面。

#### F-Droid状态

- [F-Droid Build Status](https://codeberg.org/pstorch/F-Droid_Build_Status)
  [[F-Droid](https://f-droid.org/en/packages/de.storchp.fdroidbuildstatus)]

  可以查看F-Droid软件编译状态。F-Droid平台所有软件都严格在他们的服务器上编译，这是和其他任何接受直接上传编译好安装包的应用商店最大的不同。也因此要等待编译，一般要几天时间，用这个就可以看新版本编译完成没有。

### 社交聊天

#### 聊天软件

更学究的讲，这一类软件叫做“即时通信”（Instant messaging）。

- [Telegram FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)
  [[F-Droid](https://f-droid.org/en/packages/org.telegram.messenger/)]
  [[网站](https://telegram.org/)]

  最常用的开源（只有前端开源）聊天（即时通信）软件。

  该F-Droid版本去除原版所包含的谷歌服务在内的一些闭源成分。

- [Revolution IRC](https://github.com/MCMrARM/revolution-irc)
  [[F-Droid](https://f-droid.org/en/packages/io.mrarm.irc/)]

  **警告**：已经很长时间没有更新了。

  安卓（不一定）最佳IRC客户端，有用IRC的老伙伴估计也已经知道了。界面整洁，功能全面。可以在后台一直保持连接。

- [Goguma](https://git.sr.ht/~emersion/goguma)
  [[F-Droid](https://f-droid.org/en/packages/fr.emersion.goguma/)]
  [[网站](https://sr.ht/~emersion/goguma)]

  更加现代化的IRC客户端，支持很多IRCv3的新标准。坏消息是，很多主流IRC服务器基本不支持IRCv3特性（手动斜眼）。

#### 社交平台

- [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit)
  [[F-Droid](https://f-droid.org/en/packages/ml.docilealligator.infinityforreddit/)]

  Reddit客户端，F-Droid上有好几个Reddit客户端，这个是我最喜欢的

- [Glider](https://github.com/Mosc/Glider)
  [[F-Droid](https://f-droid.org/en/packages/nl.viter.glider/)]

  著名面向IT领域的资讯平台hacker news的客户端，很精巧，用起来很顺手

- [Showly](https://github.com/michaldrabik/Showly-2.0)

  Trakt客户端，归纳自己看的电影和电视剧，精确到集的进度管理，有追剧提醒，随时同步。美剧党神器。

- [RedReader](https://github.com/QuantumBadger/RedReader)
  [[F-Droid](https://f-droid.org/en/packages/org.quantumbadger.redreader/)]

  Reddit客户端，很简洁轻量。我个人更喜欢Infinity和Slide

- [Twidere X](https://github.com/TwidereProject/TwidereX-Android)
  [[F-Droid](https://f-droid.org/en/packages/com.twidere.twiderex/)]
  [[网站](https://x.twidere.com/)]

  Twitter客户端，开源中最佳，没有之一

- [NewPipe](https://github.com/TeamNewPipe/NewPipe)
  [[F-Droid](https://f-droid.org/en/packages/org.schabi.newpipe/)]
  [[网站](https://newpipe.net/)]

  注重隐私的YouTube客户端，不能登陆，只能看，不过非常好用

- [Fritter](https://github.com/jonjomckay/fritter)
  [[F-Droid](https://f-droid.org/en/packages/com.jonjomckay.fritter/)]

  类似于NewPipe之于YouTube，Fritter是Twitter的无登录客户端，所有数据都在本地

- [Shaft](https://github.com/CeuiLiSA/Pixiv-Shaft)
- [pixez](https://github.com/Notsfsssf/pixez-flutter)

  都是Pixiv客户端，做的也都不错。

- [Hendroid](https://github.com/Nonononoki/Hendroid)
  [[F-Droid](https://f-droid.org/en/packages/org.nonononoki.hendroid/)]

  奇怪漫画网站的客户端，可以下载漫画

### 游戏

#### 模拟器

- [Lemuroid](https://github.com/Swordfish90/Lemuroid)
  [[F-Droid](https://f-droid.org/en/packages/com.swordfish.lemuroid/)]

  很强大的游戏机模拟器，支持任天堂、索尼等20多款经典游戏机的模拟，Nintendo、GBA、PSP都没问题。你只要下载一个游戏ROM，扔到指定文件夹，就可以玩了，简直良心神器！

  一个软件给手机游戏带来无限可能，可以找回童年，或者把丢掉的童年找回来！

#### 休闲益智

- [Antimine](https://github.com/lucasnlm/antimine-android)
  [[F-Droid](https://f-droid.org/en/packages/dev.lucanlm.antimine/)]

  很棒的扫雷游戏，界面漂亮，操作直观。

- [TriPeaks](https://github.com/mimoguz/tripeaks-gdx)
  [[F-Droid](https://f-droid.org/en/packages/ogz.tripeaks/)]

  像素风格的纸牌游戏，很简单，只有这一种游戏，加进来是因为界面很精致。

- [Apple Flinger](https://gitlab.com/ar-/apple-flinger)
  [[F-Droid](https://f-droid.org/en/packages/ogz.tripeaks/)]

  类似愤怒的小鸟，画面很精致。但是关卡太少了，不过瘾，也不更新了。

- [Sudoku](https://github.com/SecUSo/privacy-friendly-sudoku)
  [[F-Droid](https://f-droid.org/en/packages/org.secuso.privacyfriendlysudoku)]

  数独，F-Droid有几个数独游戏，这个用户体验是很好的。还有[另一个](https://github.com/ogarcia/opensudoku)，但是自带只有90个离线关卡，此外只能下载导入。

- [2048](https://github.com/andstatus/game2048)
  [[F-Droid](https://f-droid.org/en/packages/org.andstatus.game2048/)]

  目前维护最积极的2048。

- [Blockinger](https://github.com/vocollapse/Blockinger)
  [[F-Droid](https://f-droid.org/en/packages/org.blockinger.game/)]

  俄罗斯方块。很久很久很久没更新了，但是还可以用。即便很老，但玩起来很顺手，反应灵敏，比较严格的经典规则，我认为高手也能玩的很舒服。也比较无奈，竟然没有较新的开源俄罗斯方块。

  小提示：可以用上面的Lemuroid下载Nintendo原版ROM（1991年）玩原汁原味的俄罗斯方块。不过可能有点延迟，不灵敏。

- [Falling Lightblocks](https://github.com/MrStahlfelge/lightblocks)

  经推荐发现的另一款开源俄罗斯方块，更加新一些。操作体验上与Blockinger不同，支持手势操作，有过渡动画。有一些新版俄罗斯方块的操作，比如hold。

  但这个不是完全开源，它可以连接非开源的服务器，（可选择？）上传游戏全程操作，和登录谷歌账号进行同步。

- [Lichess](https://github.com/lichess-org/lichobile)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/org.lichess.mobileapp)]

  在线国际象棋对弈应用。这方面真的希望国内做出一些比较开放的棋类对弈平台，给开源应用提供一些可能性。

- [Puzzles](https://github.com/chrisboyle/sgtpuzzles)
  [[F-Droid](https://f-droid.org/en/packages/name.boyle.chris.sgtpuzzles/)]

  40款益智小游戏合集，包含扫雷等，想费一费脑细胞的可以试试。

#### 塔防

- [Mindustry](https://github.com/Anuken/Mindustry)
  [[F-Droid](https://f-droid.org/en/packages/io.anuke.mindustry/)]
  [[网站](https://anuke.itch.io/mindustry)]

  非常精良的塔防游戏。Mindustry比一般的塔防要复杂，比如要采各种矿、建立资源运输管道供给防御工事、开发科技树，敌人自由走动。有点像即时策略了（好像就是），可玩性max。

  注：目前由于F-Droid服务器编译环境不兼容，软件版本卡在了主版本5。

- [Anuto TD](https://github.com/reloZid/android-anuto)
  [[F-Droid](https://f-droid.org/en/packages/ch.logixisland.anuto/)]

  塔防游戏，界面元素都是作者手画的，作者自认为很丑，因而得名。游戏并不是很优秀，单位比较少，画面粗糙，敌人多了加速会很卡。但是我一度很上瘾。

#### 探险

- [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon)
  [[F-Droid](https://f-droid.org/en/packages/com.shatteredpixel.shatteredpixeldungeon/)]
  [[网站](https://shatteredpixel.com/)]

  Roguelike类地牢探险游戏，自己玩过感觉有难度。画面是像素风格的，很精致。现在更新非常频繁，发布了1.0版本，质量有保证。

- [Andor's Trail](https://github.com/AndorsTrailRelease/andors-trail)
  [[F-Droid](https://f-droid.org/en/packages/xyz.deepdaikon.xeonjia/)]
  [[网站](https://andorstrail.com/)]

  任务驱动的RPG游戏，就是那种升级加技能点买装备打怪兽的游戏。游戏其实还在持续完善，地图还没做完，所以有一部分故事线和任务都是断的。不过目前的部分已经可以玩几个星期了。还有问题是大部分对话是英文，中文翻译的很少。

  时隔好久，又看了一眼git仓库。你猜怎么着，它一小时前更新版本(v0.7.14)了，巧不巧！这个版本有很多人（包括我）更新的翻译，但是依然剩下59%的内容没有翻译。游戏里这些人话可真多。

- [Xeonjia](https://gitlab.com/DeepDaikon/Xeonjia)
  [[F-Droid](https://f-droid.org/en/packages/xyz.deepdaikon.xeonjia/)]

  一个“滑冰”的探险游戏，即在冰上行走不会停，这很大程度影响了角色的行走策略。没错，这又是像素风格的界面。

#### 沙盒

- [Minetest](https://github.com/minetest/minetest)
  [[F-Droid](https://f-droid.org/en/packages/net.minetest.minetest/)]
  [[网站](https://www.minetest.net/)]

  类似Minecraft的开源沙盘游戏，可玩性很高。我没怎么玩过，应该添加一些模块，默认好像真的只有沙盘。

#### 赛车

- [SuperTuxKart](https://github.com/supertuxkart/stk-code)
  [[F-Droid](https://f-droid.org/en/packages/org.supertuxkart.stk/)]
  [[网站](https://supertuxkart.net/Main_Page)]

  大名鼎鼎的开源赛车游戏。游戏画面是卡通风格，有很多的跑道、赛车和道具，多种游戏模式。很适合休闲时玩一玩。

- [Pixel Wheels](https://github.com/agateau/pixelwheels)
  [[F-Droid](https://f-droid.org/en/packages/com.agateau.tinywheels.android/)]
  [[网站](https://agateau.com/projects/pixelwheels/)]

  顶部视角的赛车游戏，像素风格，游戏节奏快。因为不是第一视角，感觉操作有点违反直觉啊，转弯程度不容易控制，但熟悉了之后还蛮好玩的。

  我贡献了中文翻译，不用谢。

#### 策略

- [UnCiv](https://github.com/yairm210/UnCiv)
  [[F-Droid](https://f-droid.org/en/packages/com.unciv.app/)]

  简化的文明5，有各种国家、职业、建筑，丰富的科技树。作者是试图还原文明5的游戏功能的，界面则抽象化了，这也使得游戏体积很小。没玩过文明5的我表示入手很痛苦😅。

#### 魔方

- [DCTimer](https://github.com/MeigenChou/DCTimer-Android)

  这不是游戏，是魔方速拧计时软件，功能相当丰富，生成打乱几乎支持所有比赛类别，还有数据分析等。网页端还有个csTimer，都是开源的。

### Lineage OS自带

- Lineage OS 自带的音乐软件，基于开源的Eleven，基本功能都到位了，我就没有再用第三方音乐软件

- Lineage OS 自带文件管理器。界面非常质感设计，很好看。

  功能少而精：整理不同类型的文件，比如会将所有含图片的子文件夹并排，将音乐按歌手-唱片分类（不需要手动建立文件夹），筛选大文件，等等。

- 安卓自带终端，需在开发者选项中开启。这个终端很简单，几乎没有选项，就是单纯地执行命令。这不就是终端的功能吗？

## 相似集合

以下一些集合也列举了很多安卓开源软件

- [Awesome Android Apps](https://github.com/LinuxCafeFederation/awesome-android)

- [Android FOSS](https://github.com/offa/android-foss)

- [Cool FOSS Android Apps](https://github.com/albertomosconi/foss-apps)

- [Awesome Android Apps](https://github.com/Psyhackological/AAA) （另一个）

## 版权

版权声明：本文为 [Lu Xu](https://github.com/OliverLew) 原创，依据 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 许可证进行授权，转载请附上出处链接及本声明。

原文链接：https://github.com/OliverLew/oh-my-foss-android
