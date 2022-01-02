# 很好用的开源安卓软件

个人收集的实用、良心开源安卓软件，最初发布于酷安。今后更新重心转移至git仓库：

- Github主仓库：[oh-my-foss-android](https://github.com/OliverLew/oh-my-foss-android)
- Gitee同步仓库：[oh-my-foss-android](https://gitee.com/lewinat0r/oh-my-foss-android)

酷安应用集链接（需要移动端app）：

- 应用：[很好用的开源软件](https://www.coolapk.com/album/28666843)
- 游戏：[开源游戏](https://www.coolapk.com/album/28747360)

若要推荐，可以通过issue或酷安应用集评论，当然我可能当时不会添加，但我会留意。

应用集强调我自己的使用体验，而不是单纯的展示链接，意在读者能更好地提前了解软件的特点。正因此，本文遵循[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)版权协议，如需转载等，详见文末。

## 选择条件

- **主观体验**：该列表不追求大而全，只是将我自己使用（过）的好软件列出来。
- **干净简约**：界面漂亮，赏心悦目。
- **专一轻量**：功能适中（足够），不臃肿。
- **受众广泛**：目标用户多，适合一般人。
- **积极维护**：源代码持续更新。这一定程度上代表更少的bug和更好的兼容性，也说明开发者的用心和负责。

## 分类

- [应用商店](#应用商店)
- [互联网](#互联网)
- [多媒体](#多媒体)
- [日常工具](#日常工具)
- [学习办公](#学习办公)
- [内容获取](#内容获取)
- [系统工具](#系统工具)
- [极客工具](#极客工具)
- [社交平台](#社交平台)
- [游戏](#游戏)
- [Lineage OS自带](#Lineage-OS自带)

### 应用商店

[F-Droid](https://f-droid.org)是著名的开源安卓软件平台，其客户端提供软件的安装。F-Droid官方源会从源代码编译独立的安装文件，因此可检验软件中的不安全以及非开源因素，使得F-Droid上的软件保证很高的安全性和开源性。

建议安装其中一个F-Droid客户端。

- [F-Droid](https://gitlab.com/fdroid/fdroidclient)
  [[F-Droid](https://f-droid.org/en/packages/org.fdroid.fdroid)]

  F-Droid官方客户端。虽是正统，但功能和界面并不是最好的，没什么值得表扬的。

- [Driod-ify](https://github.com/Iamlooker/Droid-ify)
  [[F-Droid](https://f-droid.org/en/packages/com.looker.droidify)]

  F-Droid第三方客户端，基于foxy droid（见下）。后者不怎么维护了，因此有人修复bug、更新界面后发布了这个款app。目前使用起来不会有什么区别，日后可能会有新功能加入。

  更新：0.3版本加入了root👽静默安装，好耶！可以取代foxy了。

  更新：又加入了大量的内置仓库，可以不用导入了。

- [Foxy Droid](https://github.com/kitsunyan/foxy-droid)
  [[F-Droid](https://f-droid.org/en/packages/nya.kitsunyan.foxydroid)]

  F-Droid第三方客户端，这个很简洁，只有1M多，我一直用作官方客户端的替代品。
  缺点是无法自动和批量安装，每次会弹出安装窗口。基本功能尚可用，但长时间不更新了，更推荐上面Droid-ify。

- [Aurora Droid](https://gitlab.com/AuroraOSS/auroradroid)
  [[F-Droid](https://f-droid.org/en/packages/com.aurora.adroid)]
  [[网站](https://auroraoss.com/)]

  F-Droid第三方客户端，有root的话可以一键更新/安装。

- [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore)
  [[F-Droid](https://f-droid.org/en/packages/com.aurora.store)]

  谷歌商店第三方客户端。在不安装谷歌框架的情况下，可以用这个安装谷歌商店的软件。它会用一个临时账号帮你下载，因此不会向谷歌暴露自己的个人信息。

### 互联网

- [Fennec F-Droid](https://github.com/mozilla-mobile/fenix)
  [[F-Droid](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/)]

  著名的火狐浏览器的更纯净开源版本，去除了其中的闭源成分。Fennec原意是“[耳廓狐](https://baike.baidu.com/item/耳廓狐)”，根据百科这是最小的犬类动物，取名还是很有寓意的。

  基础源代码还是Mozilla的，但应该是F-Droid平台自己编译，所以只能从这边安装。

- [K-9 Mail](https://github.com/k9mail/k-9)
  [[F-Droid](https://f-droid.org/en/packages/com.fsck.k9/)]
  [[网站](https://k9mail.app/)]

  最著名的开源邮件客户端，支持多账号，选项很丰富。最近两年UI改进显著，越来越好用了。

  他们的网站是我见过开源软件里做的最好看的之一。

### 多媒体

- [VLC](https://www.videolan.org/vlc/download-android.html)
  [[F-Droid](https://f-droid.org/en/packages/org.videolan.vlc/)]
  [[网站](https://www.videolan.org/vlc/download-android.html)]

  多媒体播放器，开源最佳之一，和电脑端一样功能强大，界面也很漂亮。

- [Nova Video Player](https://github.com/nova-video-player/aos-AVP)
  [[F-Droid](https://f-droid.org/en/packages/org.courville.nova/)]

  视频播放器，作为VLC的补充。Nova有类似于Plex的功能，可以管理视频库，显示封面，联网获取信息等。还有电视模式，可以作为家庭影院的开源方案。个人经验通过SFTP播放视频加载网速比VLC快好几倍。

- [mpv-android](https://github.com/mpv-android/mpv-android)
  [[F-Droid](https://f-droid.org/en/packages/is.xyz.mpv/)]

  Linux平台很出名的播放软件，以UI简洁(lòu)著称。安卓版本并非官方开发，所以就更简洁(lòu)了😢。总体上不如VLC和Nova，但继承了桌面端的可定制性，可以编辑配置文件改变选项和快捷键。

- [Vinyl](https://github.com/AdrienPoupa/VinylMusicPlayer)
  [[F-Droid](https://f-droid.org/en/packages/com.poupa.vinylmusicplayer/)]

  很轻量且干净的音乐播放器。可能是开发难度低，F-Droid上太多音乐软件了。搜"music"关键词，最近更新的都比较好，恕不一一列举。

  列表最后面有个lineage OS自带音乐播放器，和这个超级像，更加精简。

- [FreeDCam](https://github.com/KillerInk/FreeDcam)
  [[F-Droid](https://f-droid.org/en/packages/troop.com.freedcam)]

  相机软件。我觉得这个和Open Camera是开源相机中最好的两个，功能比较全面。当然这个全面是指对任何摄像头都适用的功能，如广角畸变修正、4合1像素再拆成4像素等就不灵了。作为通用相机软件，已经很不错了。

- [Open Camera](https://sourceforge.net/p/opencamera/code)
  [[F-Droid](https://f-droid.org/en/packages/net.sourceforge.opencamera/)]
  [[网站](https://opencamera.org.uk/)]

  比较强大的相机软件。但是界面很丑，开发减缓，感觉开发者逐渐有点无心无力。（不过，最近更新了1.49.1。）

- [Photon Camera](https://github.com/eszdman/PhotonCamera)

  很神奇的相机软件。在LineageOS下，其它相机软件照片质量奇差，涂抹到细节全失。偏偏它的照片质量堪比官方OS下的自带相机。另外，像夜景模式、超像素的支持也都有。在功能上是吊打上面两位和LineageOS自带相机的。

  但问题是，这个相机界面目前bug满满，主要是打开和切换界面都要等半分钟到一分钟。有[一个issue](https://github.com/eszdman/PhotonCamera/issues/54)说它在扫描所有照片，但不知到是不是所有长时间不相应的原因。

  另外，这款软件可能不是默认支持所有设备的，但没找到它支持设备的条件。

- [Photok](https://github.com/leonlatsch/Photok)
  [[F-Droid](https://f-droid.org/en/packages/dev.leonlatsch.photok/)]

  加密相册，选入应用集时正在积极开发，大量功能将要加入。

- [Pocket Paint](https://github.com/Catrobat/Paintroid)
  [[F-Droid](https://f-droid.org/en/packages/org.catrobat.paintroid/)]

  随便画点啥，功能比较全，甚至还有图层，界面也简洁漂亮。

### 日常工具

- [OSMAnd~](https://github.com/osmandapp/Osmand)
  [[F-Droid](https://f-droid.org/en/packages/net.osmand.plus/)]
  [[网站](https://osmand.net/)]

  OpenStreetMap地图。因为数据都是用户自己贡献的，所以越偏僻的地方数据越少。如果在大城市，可以尝试一下，基本的浏览和导航功能还是可以用的。

  请在F-Droid平台安装，那边的开发者在源代码的基础上，去掉了其中的付费页面，编译了OSMAnd+的所有功能。这在谷歌苹果亚马逊的商店都收费至少20刀。

  OSM能做到的功能实际很多，国内地图能记录的信息OSM基本都可以，比如多层建筑、公交地铁线路，但要贡献者自己学会怎么编辑。

- [几何天气](https://github.com/WangDaYeeeeee/GeometricWeather)
  [[F-Droid](https://f-droid.org/en/packages/wangdaye.com.geometricweather/)]

  用过最好的天气软件之一，媲美很多国内安卓系统的自带天气。

- [Pluvia Weather](https://github.com/SpicyChair/pluvia_weather_flutter)
  [[F-Droid](https://f-droid.org/en/packages/com.spicychair.weather/)]

  不错的天气软件，界面相当漂亮，但是使用OpenWeatherMap貌似国内连接很慢，预报也不一定准确。

- [EnRecipes](https://github.com/vishnuraghavb/EnRecipes)
  [[F-Droid](https://f-droid.org/en/packages/com.vishnuraghav.EnRecipes/)]

  菜谱。选这个主要因为这种小功能的软件做的这么精致太难得。但是，这个它没有在线菜谱，只能用户自己录入，就很鸡肋了。希望能建立一个在线菜谱，或与已有的进行合作，用户对其进行丰富，才有实用性。

- [Noice](https://github.com/ashutoshgngwr/noice)
  [[F-Droid](https://f-droid.org/en/packages/com.github.ashutoshgngwr.noice/)]
  [[网站](https://ashutosh.blog/noice/)]

  播放噪音/自然声音。内置各种共30+种声音，可以自由组合，设置每一种声音的音量，保存为预设。

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

- [Ruler](https://github.com/congshengwu/Ruler)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ruler.csw)]

  很简单的屏幕直尺，默认可能有误差，但好在可以校准，没准什么时候可以应急。

### 学习办公

- [Collabora Office](https://www.collaboraoffice.com/)
  [[独立源](https://www.collaboraoffice.com/releases-en/collabora-office-on-mobiles-supporting-password-protected-documents-and-available-on-f-droid/)]
  [[网站](https://www.collaboraoffice.com)]

  LibreOffice的安卓适配版，可以实现大多数的文档查看，还有实验性的编辑功能。这个应该是最好的开源office组件了（但依然不够好）。

  需要F-Droid加入第三方源（链接见上），就可以方便地安装更新。

- [OpenDocument Reader](https://github.com/TomTasche/OpenDocument.droid)
  [[F-Droid](https://f-droid.org/en/packages/at.tomtasche.reader)]

  功能很弱的文档查看软件，貌似主要解析文档里的内容，文档的格式就很……怎么说，显示地很朴素😅。几乎没有编辑功能。

- [Markor](https://github.com/gsantner/markor)
  [[F-Droid](https://f-droid.org/en/packages/net.gsantner.markor/)]
  [[网站](https://gsantner.net/project/markor.html?source=fdroid)]

  笔记软件，使用markdown语法。

  这个对于很多人并不是最优选择，但是我喜欢它直接对本地的纯文本文件进行编辑，而不是保存为其他的格式。这样我可以自行管理markdown文件，包括同步到电脑上，用其他编辑器去编辑。

  这样不需要软件实现跨平台❎，而是通过文件格式进行跨平台。☑️

- [Notally](https://github.com/OmGodse/Notally)
  [[F-Droid](https://f-droid.org/en/packages/com.omgodse.notally/)]

  极简又漂亮的笔记应用，只能输入纯文字，有少许加粗斜体等格式。

- [OpenScan](https://github.com/Ethereal-Developers-Inc/OpenScan)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ethereal.openscan)]

  文档扫描。和大家想的一样，可以拍照、裁切、再合成一个文档，可以导出为PDF。功能完整，比如有再次裁切（只能再切小）、调整顺序、颜色优化（灰阶或黑白）、分享等等。

  相比之下，我试过的其它开源扫描软件就太差了，上面功能大量缺失，我觉得缺一不可。

- [QuickDic](https://github.com/rdoeffinger/Dictionary)
  [[F-Droid](https://f-droid.org/en/packages/de.reimardoeffinger.quickdic/)]

  词典软件。怎么说呢，一言难尽啊，开源的词典真的没找到很好用的。这个QuickDic可以下载很多中词典文件，但基本是多语种互译。查词的时候把所有词显示出来，查哪个滚动到哪个。

- [Wikipedia](https://github.com/wikimedia/apps-android-wikipedia)
  [[F-Droid](https://f-droid.org/en/packages/org.wikipedia/)]
  [[网站](https://www.mediawiki.org/wiki/Wikimedia_Apps)]

  维基百科官方客户端，只有10M，很小巧但五脏俱全。Wikipedia在平台建设上确实遥遥领先，希望国内同行快点幡然醒悟。

- [Sky Map](https://github.com/sky-map-team/stardroid)
  [[F-Droid](https://f-droid.org/en/packages/com.google.android.stardroid/)]

  星图软件，让你上知天文。借助重力感应，把手机指向天空就可以方便对照天上的星是什么名字。当然其他功能就不多了。

  虽然在更新，但是界面比较落后，数据貌似也不多。

- [DeepL](https://github.com/sakusaku3939/DeepLAndroid)
  [[F-Droid](https://f-droid.org/en/packages/com.example.deeplviewer/)]

  翻译软件。基于深度学习的翻译引擎，这个是把网页版包装成了一个轻量的应用。重要的是，可以在选取文字后的弹出菜单里选择DeepL进行翻译。

- [Unit Converter Ultimate](https://github.com/physphil/UnitConverterUltimate)
  [[F-Droid](https://www.f-droid.org/packages/com.physphil.android.unitconverterultimate/)]

  单位转换工具，非常全面，除了常见的长度、面积、重量等基础物理单位，还有汇率、存储单位等。

### 内容获取

这类软件没有自带内容或既定来源，用户自行加入“源”获取在线内容。

- [Feeder](https://gitlab.com/spacecowboy/Feeder)
  [[F-Droid](https://f-droid.org/en/packages/com.example.deeplviewer/)]

  RSS订阅软件，这类软件没有太令我满意的，这个就算比较好的了。

  国内没有什么开源的新闻阅读软件，但是有很多资讯平台有RSS订阅。因此Feeder可以成为一个非常纯粹的新闻阅读软件，没有任何交互，像看报纸一样地阅读📰。

- [FastoTVLite](https://github.com/fastogt/fastotvlite_mobile)

  IPTV客户端，可以从网络串流观看电视节目，大家可以自行从网上搜集IPTV资源，添加至播放器中，就可以播放了。

- [Transistor](https://github.com/y20k/transistor)
  [[F-Droid](https://f-droid.org/en/packages/org.y20k.transistor/)]

  收音机。只不过这个是从网络串流的，不是真正的调频收音机，原因是很多硬件不支持了（手机自带收音机也逐渐消失）。好处是你可以听外地的频道，默认的搜索引擎可以添加上千个国内外频道。

- [Legado(阅读)](https://github.com/gedoor/legado)
  [[F-Droid](https://apt.izzysoft.de/fdroid/index/apk/io.legado.app.release)]
  [[网站](https://www.legado.top)]

  电子书阅读软件。不提供内置书源，需要用户自行寻找后导入，提高了自由度，也让软件本身更加纯净。

### 系统工具

- [Material Files](https://github.com/zhanghai/MaterialFiles)
  [[F-Droid](https://f-droid.org/en/packages/me.zhanghai.android.files/)]

  文件管理器，非常漂亮，基本的功能都有。

- [Pdf Viewer Plus](https://github.com/JavaCafe01/PdfViewer)
  [[F-Droid](https://f-droid.org/en/packages/me.zhanghai.android.files)]

  PDF阅读器，开源的同类软件UI都不怎么样，这个算是很好的了，期待和谷歌PDF阅读器差不多的开源版本出现。

- [同文输入法](https://github.com/osfans/trime)
  [[F-Droid](https://f-droid.org/en/packages/com.osfans.trime/)]

  F-Droid上甚至是开源软件中唯一一个中文输入法，基于配置文件，定制性相当恐怖😱，你喜欢的样子它都有。
  配置文件对上手是一个门槛，需要自行下载配置文件导入。

  本以为两年不更新了，结果又有新版本了（指v3.2.0版本与上一个版本相隔3年多）。一个开源软件突然恢复维护是一件令人感到幸福的事情。

- [Seafile](https://github.com/haiwen/seadroid)
  [[F-Droid](https://f-droid.org/en/packages/com.seafile.seadroid2/)]
  [[网站](https://www.seafile.com/home/)]

  文件同步/网盘客户端。是国内开发的，需要自己搭服务器。我们学校用它做了一个box，访问起来很方便：）

- [Download Navi](https://github.com/TachibanaGeneralLaboratories/download-navi)
  [[F-Droid](https://www.seafile.com/home/)]

  功能强大的下载器，可以多段加速，分享下载链接就可以选择下载。

- [GPSTest](https://github.com/barbeau/gpstest)
  [[F-Droid](https://f-droid.org/en/packages/com.tachibana.downloader/)]

  显示GPS信息，非常丰富，可以看到五种全球定位系统的卫星位置、自己的经纬度、海拔还有速度等等。

- [OAndBackupX](https://github.com/machiav3lli/oandbackupx)
  [[F-Droid](https://f-droid.org/en/packages/com.android.gpstest.osmdroid/)]

  备份软件，可以备份任何东西，需要root。

- [Password Store](https://github.com/android-password-store/Android-Password-Store)
  [[F-Droid](https://f-droid.org/en/packages/dev.msfjarvis.aps/)]

  密码管理和自动填充软件。要先了解Linux平台上的[password store](https://www.passwordstore.org/)才能用，这个是安卓客户端。

  特点是利用git管理加密的密码文件，利用gpg加密解密，password store本身只是一个小脚本，调用git和gpg。因而可以选择GitHub私人仓库+password store的超轻量开源方案，而非托管在统一的服务器上，这很Unix。

- [AN2Linux](https://github.com/rootkiwi/an2linuxclient)
  [[F-Droid](https://f-droid.org/en/packages/kiwi.root.an2linuxclient/)]
  [[网站](https://github.com/rootkiwi/an2linuxserver/)]

  通知同步软件，将手机上的通知推送到Linux电脑上，可以通过WiFi、蓝牙或者移动数据。我只试过WiFi，不知道另两个体验如何。

- [Call Recorder](https://gitlab.com/axet/android-call-recorder)
  [[F-Droid](https://f-droid.org/en/packages/com.github.axet.callrecorder)]

  电话自动录音，非本土化系统中很实用，搭配Magisk模块可以成为系统应用。

- [andOTP](https://github.com/andOTP/andOTP)
  [[F-Droid](https://f-droid.org/en/packages/org.shadowice.flocke.andotp/)]

  双重验证（2FA）或者一次性密码（OTP）客户端，就是很多网站登录时出于安全性设置的6位数动态验证码。

- [Aegis](https://github.com/beemdevelopment/Aegis)
  [[F-Droid](https://f-droid.org/en/packages/com.beemdevelopment.aegis/)]

  和andOTP类似，是一款双重验证码客户端。相比起来，这款界面更简洁、符合质感设计，其它方面大同小异。

- [KDE Connect](https://github.com/KDE/kdeconnect-android)
  [[F-Droid](https://f-droid.org/packages/org.kde.kdeconnect_tp/)]

  很强大的连接PC和手机的工具。可以分享文件或文本、同步通知、运行命令和远程控制等等。需要Linux系统上安装相应的pc端软件，常见的如KDE官方的[kdeconnect](https://kdeconnect.kde.org/)和适配GNOME的[GSConnect](https://github.com/GSConnect/gnome-shell-extension-gsconnect)。

  KDE团队做的很好的一点是，他们将KDE Connect前后端分离开了，真正支撑底层功能的部分实现为一种协议，可以独立于图形界面部分运行。这样在非KDE环境，便可以用其它的软件，如我在使用的[mconnect](https://github.com/grimpy/mconnect)，就是没有图形界面，只有命令行接口，但如果你想要的基本功能都具备，可以很灵活而不受桌面环境限制。

### 极客工具

我并不想分一个“开发类”，这里的软件并不是面向开发者的，而是喜欢折腾的用户。这也符合最开始制订的”受众广泛“要求。

- [Magisk](https://github.com/topjohnwu/Magisk)
  [[F-Droid](https://f-droid.org/en/packages/com.topjohnwu.magisk/)]
  [[网站](https://topjohnwu.github.io/Magisk/install.html)]

  著名的面具，需要电脑端配合安装，可以提供root和修改系统行为的模块。
  不过，不是刚需的话，不建议使用。我使用Lineage OS，因此微信和支付宝的指纹无法正常调用，便使用一些面具模块解决。

  附简要安装步骤（不是手把手指导，请见官方网站）：

  1. 电脑：获取系统镜像，提取boot.img文件，导入手机存储；
  2. 手机：使用Magisk安卓软件为boot.img打补丁，具体是“Magisk安装” 》“选择并修补一个文件”，选择boot.img文件，修补后导出`magisk_patched_***.img`至电脑；
  3. 电脑：准备adb工具，重启手机至fastboot，在终端执行`fastboot flash magisk_patched_***.img`。

  是不是很简单啊？

  再说一句，Magisk并没有提供每一种机型的下载。所以上面的过程对所有机型适用，耗时的步骤是获取boot.img文件，但这保证几乎任何机型都完美适配。

- [Editor](https://github.com/billthefarmer/editor)
  [[F-Droid](https://topjohnwu.github.io/Magisk/install.html)]

  轻量的文本编辑器，很小很小的软件还有语法高亮，吹爆它。

  一个问题是，一般只能打开安卓识别为纯文本的文件，连yaml都不行。除非文件管理器能强行作为文本打开。GitHub有好几个issue提到，但作者坚决把锅甩给安卓和文件管理器，感觉作者有开发“洁癖”。

- [Acode](https://github.com/deadlyjack/Acode)
  [[F-Droid](https://f-droid.org/en/packages/com.foxdebug.acode/)]
  [[网站](https://acode.foxdebug.com/)]

  更高级的文本/代码编辑器。从截图上看，Acode可能更适合在平板等大屏设备上进行更专业的编辑工作，类似于VS Code等软件。

- [ConnectBot](https://github.com/connectbot/connectbot)
  [[F-Droid](https://f-droid.org/en/packages/org.connectbot/)]

  Ssh客户端，很好用。在维护但很久没有新版本了。我校阅了所有的翻译，希望将来有更新。

  2021.10.25：更新啦。

- [TermOne Plus](https://gitlab.com/termapps/termoneplus)
  [[F-Droid](https://f-droid.org/packages/com.termoneplus/)]

  终端应用。有些系统中会禁用系统自带的安卓终端，所以想要在安卓上执行命令行操作，可以尝试这款应用。

- [AVNC](https://github.com/gujjwal00/avnc)
  [[F-Droid](https://f-droid.org/en/packages/com.gaurav.avnc/)]

  简单但不简陋的VNC客户端。可以通过手势实现不同的鼠标控制事件，因此是很实用的。

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

- [F-Droid Build Status](https://codeberg.org/pstorch/F-Droid_Build_Status)
  [[F-Droid](https://f-droid.org/en/packages/de.storchp.fdroidbuildstatus)]

  可以查看F-Droid软件编译状态。F-Droid平台所有软件都严格在他们的服务器上编译，这是和其他任何接受直接上传编译好安装包的应用商店最大的不同。也因此要等待编译，一般要几天时间，用这个就可以看新版本编译完成没有。

- [Revolution IRC](https://github.com/MCMrARM/revolution-irc)
  [[F-Droid](https://f-droid.org/en/packages/io.mrarm.irc/)]

  安卓最佳IRC客户端，有用IRC的老伙伴估计也已经知道了。界面整洁，功能全面。可以在后台一直保持连接。

- [OpenKeychain](https://github.com/open-keychain/open-keychain)
  [[F-Droid](https://f-droid.org/en/packages/org.sufficientlysecure.keychain/)]
  [[网站](https://www.openkeychain.org/)]

  PGP锁钥管理，我是搭配password store使用，提供解锁密钥。此外还有很多软件可以使用它。

### 社交平台

- [Telegram FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)
  [[F-Droid](https://f-droid.org/en/packages/org.telegram.messenger/)]
  [[网站](https://telegram.org/)]

  最常用的开源（只有前端开源）聊天（即时通信）软件。

  该F-Droid版本去除原版所包含的谷歌服务在内的一些闭源成分。

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
- [pxview](https://github.com/alphasp/pxview)

  都是Pixiv客户端，做的也都不错，最后面这个更新不是很频繁了。

- [Hendroid](https://github.com/Nonononoki/Hendroid)
  [[F-Droid](https://f-droid.org/en/packages/org.nonononoki.hendroid/)]

  奇怪漫画网站的客户端，可以下载漫画

### 游戏

- [Lemuroid](https://github.com/Swordfish90/Lemuroid)
  [[F-Droid](https://f-droid.org/en/packages/com.swordfish.lemuroid/)]

  很强大的游戏机模拟器，支持任天堂、索尼等20多款经典游戏机的模拟，Nintendo、GBA、PSP都没问题。你只要下载一个游戏ROM，扔到指定文件夹，就可以玩了，简直良心神器！

  一个软件给手机游戏带来无限可能，可以找回童年，或者把丢掉的童年找回来！

- [Antimine](https://github.com/lucasnlm/antimine-android)
  [[F-Droid](https://f-droid.org/en/packages/dev.lucanlm.antimine/)]

  很棒的扫雷游戏，界面漂亮，操作直观。

- [Mindustry](https://github.com/Anuken/Mindustry)
  [[F-Droid](https://f-droid.org/en/packages/io.anuke.mindustry/)]
  [[网站](https://anuke.itch.io/mindustry)]

  非常精良的塔防游戏。Mindustry比一般的塔防要复杂，比如要采各种矿、建立资源运输管道供给防御工事、开发科技树，敌人自由走动。有点像即时策略了（好像就是），可玩性max。

  注：目前由于F-Droid服务器编译环境不兼容，软件版本卡在了主版本5。

- [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon)
  [[F-Droid](https://f-droid.org/en/packages/com.shatteredpixel.shatteredpixeldungeon/)]
  [[网站](https://shatteredpixel.com/)]

  Roguelike类地牢探险游戏，自己玩过感觉有难度。画面是像素风格的，很精致。现在更新非常频繁，发布了1.0版本，质量有保证。

- [Minetest](https://github.com/minetest/minetest)
  [[F-Droid](https://f-droid.org/en/packages/net.minetest.minetest/)]
  [[网站](https://www.minetest.net/)]

  类似Minecraft的开源沙盘游戏，可玩性很高。我没怎么玩过，应该要搭配下面的模块管理，默认好像真的只有沙盘。

- [Minetest Mods](https://github.com/rubenwardy/mtmods4android)
  [[F-Droid](https://f-droid.org/en/packages/com.rubenwardy.minetestmodmanager/)]
  [[网站](https://rubenwardy.com/mtmods4android/)]

  管理Minetest模块

- [SuperTuxKart](https://github.com/supertuxkart/stk-code)
  [[F-Droid](https://f-droid.org/en/packages/org.supertuxkart.stk/)]
  [[网站](https://supertuxkart.net/Main_Page)]

  大名鼎鼎的开源赛车游戏。游戏画面是卡通风格，有很多的跑道、赛车和道具，多种游戏模式。很适合休闲时玩一玩。

- [UnCiv](https://github.com/yairm210/UnCiv)
  [[F-Droid](https://f-droid.org/en/packages/com.unciv.app/)]

  简化的文明5，有各种国家、职业、建筑，丰富的科技树。作者是试图还原文明5的游戏功能的，界面则抽象化了，这也使得游戏体积很小。没玩过文明5的我表示入手很痛苦😅。

- [Pixel Wheels](https://github.com/agateau/pixelwheels)
  [[F-Droid](https://f-droid.org/en/packages/com.agateau.tinywheels.android/)]
  [[网站](https://agateau.com/projects/pixelwheels/)]

  顶部视角的赛车游戏，像素风格，游戏节奏快。因为不是第一视角，感觉操作有点违反直觉啊，转弯程度不容易控制，但熟悉了之后还蛮好玩的。

  我贡献了中文翻译，不用谢。

- [Andor's Trail](https://github.com/AndorsTrailRelease/andors-trail)
  [[F-Droid](https://f-droid.org/en/packages/xyz.deepdaikon.xeonjia/)]
  [[网站](https://andorstrail.com/)]

  任务驱动的RPG游戏，就是那种升级加技能点买装备打怪兽的游戏。游戏其实还在持续完善，地图还没做完，所以有一部分故事线和任务都是断的。不过目前的部分已经可以玩几个星期了。还有问题是大部分对话是英文，中文翻译的很少。

  时隔好久，又看了一眼git仓库。你猜怎么着，它一小时前更新版本(v0.7.14)了，巧不巧！这个版本有很多人（包括我）更新的翻译，但是依然剩下59%的内容没有翻译。游戏里这些人话可真多。

- [Xeonjia](https://gitlab.com/DeepDaikon/Xeonjia)
  [[F-Droid](https://f-droid.org/en/packages/xyz.deepdaikon.xeonjia/)]

  一个“滑冰”的探险游戏，即在冰上行走不会停，这很大程度影响了角色的行走策略。没错，这又是像素风格的界面。

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

- [DCTimer](https://github.com/MeigenChou/DCTimer-Android)

  这不是游戏，是魔方速拧计时软件，功能相当丰富，生成打乱几乎支持所有比赛类别，还有数据分析等。网页端还有个csTimer，都是开源的。

- [Anuto TD](https://github.com/reloZid/android-anuto)
  [[F-Droid](https://f-droid.org/en/packages/ch.logixisland.anuto/)]

  塔防游戏，界面元素都是作者手画的，作者自认为很丑，因而得名。游戏并不是很优秀，单位比较少，画面粗糙，敌人多了加速会很卡。但是我一度很上瘾。

### Lineage OS自带

- Lineage OS 自带的音乐软件，基于开源的Eleven，基本功能都到位了，我就没有再用第三方音乐软件

- Lineage OS 自带相机。这类第三方相机软件（这是相对于手机原系统来说的）都有一个缺陷，就是无法很好地利用硬件，比如无法利用一分四的超像素，没有延长曝光的超级夜景模式，等等。不过在软件上做的已经很不错，还集成了二维码扫描，不用装单独的二维码扫描软件了。

- Lineage OS 自带文件管理器。界面非常质感设计，很好看。

  功能少而精：整理不同类型的文件，比如会将所有含图片的子文件夹并排，将音乐按歌手-唱片分类（不需要手动建立文件夹），筛选大文件，等等。

- 安卓自带终端，需在开发者选项中开启。这个终端很简单，几乎没有选项，就是单纯地执行命令。这不就是终端的功能吗？

## 相似集合

以下一些集合也列举了很多安卓开源软件

- [Awesome Android Apps](https://github.com/LinuxCafeFederation/awesome-android)

- [Android FOSS](https://github.com/offa/android-foss)

- [Cool FOSS Android Apps](https://github.com/albertomosconi/foss-apps)

## 版权

版权声明：本文为 [Lu Xu](https://github.com/OliverLew) 原创，依据 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 许可证进行授权，转载请附上出处链接及本声明。

原文链接：https://github.com/OliverLew/oh-my-foss-android
