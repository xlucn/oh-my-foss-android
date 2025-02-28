# 很好用的开源安卓软件

个人收集的实用、良心开源安卓软件。

## 基本信息

- **仓库**：
  [Github 主仓库](https://github.com/xlucn/oh-my-foss-android)，
  [Gitee 同步仓库](https://gitee.com/lewinat0r/oh-my-foss-android)。
- **特点**：强调使用体验，希望读者能更好地提前了解软件的特点。
- **推荐**：软件推荐，欢迎提交 issue 或 PR。他人贡献并且我没有使用过的条目会标注`*`。
- **历史**：软件增删等变更请查看 git 提交历史。
- **版权**：本文遵循 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 版权协议发表。如需转载等，无需征得同意，只需要符合协议要求。例如，该版权要求只能以相同许可协议传播（SA）、需要明确说明作者和来源（BY）。版权声明见文末。


## 选择条件

- **主观体验**：该列表不追求大而全，只是将我自己使用（过）的好软件列出来。
- **干净简约**：界面漂亮，赏心悦目。
- **专一轻量**：功能适中（足够），不臃肿。
- **受众广泛**：目标用户多，适合一般人。
- **积极维护**：源代码持续更新。这一定程度上代表更少的 bug 和更好的兼容性，也说明开发者的用心和负责。

## 分类

请使用 Github/Gitee 自带的目录导航功能。

### 应用商店

#### F-Droid 客户端

[F-Droid](https://f-droid.org) 是著名的开源安卓软件平台，其客户端提供软件的安装。F-Droid 官方源会从源代码编译独立的安装文件，因此可检验软件中的不安全以及非开源因素，使得 F-Droid 上的软件保证很高的安全性和开源性。

还存在 IzzyOnDroid 等第三方 F-Droid 仓库。如果熟悉 Linux 的用户，会很了解这个概念，即只增加一个软件来源，但保持和 F-Droid 官方源软件相同的安装方式。这些第三方仓库丰富了软件的数量，提供更及时的更新，也一定程度放宽了采纳标准。

建议安装其中一个 F-Droid 客户端。

- [F-Droid](https://gitlab.com/fdroid/fdroidclient)
  [[F-Droid](https://f-droid.org/packages/org.fdroid.fdroid)]
- [F-Droid Basic](https://gitlab.com/fdroid/fdroidclient)
  [[F-Droid](https://f-droid.org/packages/org.fdroid.basic)]\*

  <details>

  <summary>F-Droid 官方客户端。</summary><br/>

  虽是正统，但功能和界面并不是最好的，没什么值得表扬的。

  后者升级了 API，在 Android 12 及以上无需特权或 root 即可进行静默更新。缺少一些无关紧要的功能。

  </details>

- [Neo-Store](https://github.com/NeoApplications/Neo-Store)
  [[F-Droid](https://f-droid.org/packages/com.machiav3lli.fdroid)]

  <details>

  <summary>Neo Store 是基于 Droid-ify（见下）的 F-Droid 客户端。</summary><br/>

  界面风格有较大改动，个人认为更规范了，这里指对于质感设计的应用更加美观和符合直觉，相比之下，Droid-ify 可能更加像一个没有设计能力的程序员随意为之的作品。

  曾经取代/继承了 Droid-ify，并入 [Neo 系列应用](https://github.com/NeoApplications/)。但是后来 Droid-ify 原作者因个人原因，选择不再参与 Neo Store 的开发，自己继续维护之前的 Droid-ify 代码。因此，现在两个项目都是正在维护的。

  </details>

- [Driod-ify](https://github.com/Iamlooker/Droid-ify)
  [[F-Droid](https://f-droid.org/packages/com.looker.droidify)]

  <details>

  <summary>F-Droid 第三方客户端，基于 Foxy droid（见下）。</summary><br/>

  后者不怎么维护了，因此有人修复 bug、更新界面后发布了这个款 app。目前使用起来不会有什么区别，日后可能会有新功能加入。在质感设计的风格上，应该是使用了第三代的设计语言，即有更多的圆角元素等特点。

  更新：0.3 版本加入了 root👽 静默安装，好耶！可以取代 Foxy 了。

  更新：又加入了大量的内置仓库，可以不用导入了。

 </details>

<details>

<summary>过时的内容</summary>

- _[Foxy Droid](https://github.com/kitsunyan/foxy-droid)
  [[F-Droid](https://f-droid.org/packages/nya.kitsunyan.foxydroid)]_

  <details>

  _<summary>长时间不更新了，推荐上面 Droid-ify 和 Neo-Store。</summary>_

  **最后更新：20200801。**

  F-Droid 第三方客户端，这个很简洁，只有 1M 多，基本功能尚可用，我一直用作官方客户端的替代品。缺点是无法自动和批量安装，每次会弹出安装窗口。

  </details>

- _[Aurora Droid](https://gitlab.com/AuroraOSS/auroradroid)
  ~~[[F-Droid](https://f-droid.org/packages/com.aurora.adroid)]
  [[网站](https://auroraoss.com/)]~~_

  <details>

  _<summary>F-Droid 第三方客户端，已从官网消失。</summary>_

  **最后更新：20210526 / F-droid 已 404。**

  有 root 的话可以一键更新/安装。

 </details>

</details>

#### 谷歌商店第三方客户端

谷歌商店能提供远多于 F-Droid 的安卓应用，但一般情况下，只能在安装谷歌服务框架的机器上使用。以下客户端能打破这个限制，无需任何依赖地运行在任何安卓手机上。

- [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore)
  [[F-Droid](https://f-droid.org/packages/com.aurora.store)]
  [[网站](https://auroraoss.com/)]

  <details>

  <summary>谷歌商店第三方客户端。</summary><br/>

  在不安装谷歌框架的情况下，可以用这个安装谷歌商店的软件。它会用一个临时账号帮你下载，因此不会向谷歌暴露自己的个人信息。

  </details>

#### 其他

一些应用尚未在任何商店内发布，通过以下应用可跟踪此类应用的更新。

- [Obtainium](https://github.com/ImranR98/Obtainium)
  [[F-Droid](https://f-droid.org/packages/dev.imranr.obtainium.fdroid/)]
  [[网站](https://obtainium.imranr.dev/)]\*

  <details>

  <summary>从源直接获取 Android 应用程序更新。</summary><br/>

  支持的应用源请查看 [Wiki](https://wiki.obtainium.imranr.dev/sources/)，[这里](https://apps.obtainium.imranr.dev/)还有一个 Complex Obtainium Apps 列表。

  有相当一部分应用源和应用并不是开源的，注意甄别。

  </details>

### 互联网

#### 浏览器

- [Fennec F-Droid](https://hg.mozilla.org/mozilla-central/file/tip/mobile/android)
  [[F-Droid](https://f-droid.org/packages/org.mozilla.fennec_fdroid/)]

  <details>

  <summary>著名的火狐浏览器的更纯净开源版本，去除了其中的闭源成分。</summary><br/>

  Fennec 原意是“[耳廓狐](https://zh.wikipedia.org/zh-cn/耳廓狐)”，根据百科这是最小的犬类动物，取名还是很有寓意的。

  基础源代码还是 Mozilla 的，但应该是 F-Droid 平台自己编译，所以只能从这边安装。

  </details>

- [Iceraven Browser](https://github.com/fork-maintainers/iceraven-browser)\*

  <details>

  <summary>另一个强化版火狐浏览器。</summary><br/>

  更长的扩展列表，支持 about:config ，隐私方面应该相当于 Fennec。

  “Iceraven 浏览器结合了 Fenix 的力量和 Fennec 的精神，并向 Netscape Navigator 的伟大传统致敬。”

  </details>

#### 邮件

- [K-9 Mail](https://github.com/thunderbird/thunderbird-android)
  [[F-Droid](https://f-droid.org/packages/com.fsck.k9/)]
  [[网站](https://k9mail.app/)]

  <details>

  <summary>最著名的开源邮件客户端，源代码已迁移到 Thunderbird。</summary><br/>

  支持多账号，选项很丰富。最近两年UI改进显著，越来越好用了。

  他们的网站是我见过开源软件里做的最好看的之一。

  </details>

- [FairEmail](https://github.com/M66B/FairEmail)
  [[F-Droid](https://f-droid.org/packages/eu.faircode.email/)]
  [[网站](https://email.faircode.eu/)]\*

  <details>

  <summary>注重隐私的邮件客户端。</summary><br/>

  **高级版需要付费。**

  XPrivacy 作者 M66B 的作品。

  无数的自定义选项，对隐私的极端保护。（个人只因为 K9 没有黑色小部件而选择了 FairEmail。）

  </details>

#### 内容获取

这类软件没有自带内容或既定来源，用户自行加入“源”获取在线内容。

- [Feeder](https://github.com/spacecowboy/Feeder)
  [[F-Droid](https://f-droid.org/packages/com.nononsenseapps.feeder/)]
  [[网站](https://news.nononsenseapps.com/)]

  <details>

  <summary>RSS 订阅软件。这类软件没有太令我满意的，这个就算比较好的了。</summary><br/>

  国内没有什么开源的新闻阅读软件，但是有很多资讯平台有 RSS 订阅。因此 Feeder 可以成为一个非常纯粹的新闻阅读软件，没有任何交互，像看报纸一样地阅读📰。

  </details>

- [Read You](https://github.com/Ashinch/ReadYou)
  [[F-Droid](https://f-droid.org/packages/me.ash.reader/)]\*

  <details>

  <summary>同 RSS 订阅软件，Material You 设计风格。</summary><br/>

  支持多种订阅方式，定时同步订阅及提醒。

  </details>

- [M3U](https://github.com/oxyroid/M3UAndroid)
  [[F-Droid](https://f-droid.org/packages/com.m3u.androidApp/)]\*

  <!-- [FastoTVLite](https://github.com/fastogt/fastotvlite_mobile)
   这个项目看上去已经死了，名称及官网已变更，源码不更新。-->

  <details>

  <summary>IPTV 客户端，可以从网络串流观看电视节目。</summary><br/>

  大家可以自行从网上搜集 IPTV 资源，添加至播放器中，就可以播放了。

  </details>

- [Transistor(晶体管收音机)](https://codeberg.org/y20k/transistor)
  [[F-Droid](https://f-droid.org/packages/org.y20k.transistor/)]

  <details>

  <summary>网络收音机，频道需要手动搜索后添加。</summary><br/>

  这个是从网络串流的，不是真正的调频收音机，原因是很多硬件不支持了（也可以从手机自带收音机逐渐消失这一点看出来）。好处是你可以听外地的频道，默认的搜索引擎可以添加上千个国内外频道。

  </details>

- [RadioDroid](https://github.com/segler-alex/RadioDroid)
  [[F-Droid](https://f-droid.org/packages/net.programmierecke.radiodroid2/)]
  [[网站](https://www.radio-browser.info/)]\*

  另一个网络收音机，自带频道列表，不需要手动搜索。

- [AntennaPod](https://github.com/AntennaPod/AntennaPod)
  [[F-Droid](https://f-droid.org/packages/de.danoeh.antennapod/)]
  [[网站](https://antennapod.org/)]\*

  Podcast 客户端有很多，这款历史久，开发活跃，功能实而不华。

- [Legado(阅读)](https://github.com/gedoor/legado)
  ~~[[网站](https://www.legado.top)]~~

  <details>

  <summary>电子书阅读软件，不提供内置书源。</summary><br/>

  需要用户自行寻找后导入，提高了自由度，也让软件本身更加纯净。

  </details>

- [Shosetsu(书)](https://gitlab.com/shosetsuorg/shosetsu)
  [[F-Droid](https://f-droid.org/packages/app.shosetsu.android.fdroid)]
  [[网站](https://shosetsu.app/)]

  <details>

  <summary>小说阅读软件，这个内置了一些下载源。</summary><br/>

  我没有读过里面的小说，但是比较喜欢这种形式的软件。

  </details>

- [Myne](https://github.com/Pool-Of-Tears/Myne)
  [[F-Droid](https://f-droid.org/packages/com.starry.myne/)]

  <details>

  <summary>电子书下载与阅读，从一个固定的源下载电子书，都是一些经典书籍。</summary><br/>

  一般是版权过期进入公共领域的书，很不错的软件。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[URL Radio](https://github.com/jamal2362/URL-Radio)~~
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.jamal2367.urlradio)]_

  <details>

  _<summary>另一个收音机应用，已停止开发。</summary>_

  **源码已存档：20241206。**

  应该基于 Transistor。不太清楚与后者有什么不同，Transistor 也没有放弃维护。

  </details>

</details>

#### 追剧管理

- [Showly](https://github.com/michaldrabik/Showly-2.0)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.michaldrabik.showly_oss)]
  [[网站](https://www.showlyapp.com/)]

  <details>

  <summary>Trakt 客户端，归纳自己看的电影和电视剧。</summary><br/>

  精确到集的进度管理，有追剧提醒，随时同步。美剧党神器。

  </details>

- [Episodes](https://github.com/red-coracle/episodes)
  [[F-Droid](https://f-droid.org/packages/com.redcoracle.episodes/)]

  <details>

  <summary>管理自己看过的电视剧，更推荐上边的 Showly。</summary><br/>

  数据来自 TMDB，功能上比较单一。

  </details>

#### BT 客户端

这里是一些 BT 软件的远程客户端，并不是直接在安卓手机上进行 BT 下载的客户端。

- [qbitcontroller](https://github.com/Bartuzen/qBitController)
  [[F-Droid](https://f-droid.org/packages/dev.bartuzen.qbitcontroller)]

  Qbittorrent 的远程控制软件。

- [Tremotesf](https://github.com/equeim/tremotesf-android)
  [[F-Droid](https://f-droid.org/repository/browse/?fdid=org.equeim.tremotesf)]
- [Transmissionic](https://github.com/6c65726f79/Transmissionic)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.sleroy.transmissionic)]

  Transmission 的远程控制软件。

### 多媒体

#### 视频播放

- [VLC](https://www.videolan.org/vlc/download-android.html)
  [[F-Droid](https://f-droid.org/packages/org.videolan.vlc/)]
  [[网站](https://www.videolan.org/vlc/download-android.html)]

  多媒体播放器，开源最佳之一，和电脑端一样功能强大，界面也很漂亮。

- [Nova Video Player](https://github.com/nova-video-player/aos-AVP)
  [[F-Droid](https://f-droid.org/packages/org.courville.nova/)]

  <details>

  <summary>视频播放器，作为 VLC 的补充，有类似于 Plex 的功能。</summary><br/>

  可以管理视频库，显示封面，联网获取信息等。还有电视模式，可以作为家庭影院的开源方案。

  个人体验通过 SFTP 播放视频加载网速比 VLC 快好几倍（你要问为什么是 SFTP，因为我用 Linux）。

  </details>

- [mpv-android](https://github.com/mpv-android/mpv-android)
  [[F-Droid](https://f-droid.org/packages/is.xyz.mpv/)]

  <details>

  <summary>基于 Linux 平台很出名的播放软件 MPV，以 UI 简洁(lòu)著称。</summary><br/>

  安卓版本并非官方开发，所以就更简洁(lòu)了😢。总体上不如 VLC 和 Nova，但继承了桌面端的可定制性，可以编辑配置文件改变选项和快捷键。

  </details>

- [Kore](https://github.com/xbmc/Kore)
  [[F-Droid](https://f-droid.org/packages/org.xbmc.kore/)]
  [[网站](https://kodi.tv/)]

  <details>

  <summary>Kodi 官方遥控器应用（Kodi remote）。</summary><br/>

  前者是非常棒的开源家庭影院应用，用来播放本地或远程的多媒体文件。

  </details>

#### 音乐播放

可能是开发难度低，F-Droid 上太多音乐软件了。搜 "music" 关键词，最近更新的都比较好，恕不一一列举。

- [Vinyl](https://github.com/AdrienPoupa/VinylMusicPlayer)
  [[F-Droid](https://f-droid.org/packages/com.poupa.vinylmusicplayer/)]

  <details>

  <summary>很轻量且干净的音乐播放器，拥有透明小部件。</summary><br/>

  基于 [Phonograph](https://github.com/kabouzeid/Phonograph)，后者很早停止维护了，但是却是很经典的质感设计音乐播放器，值得怀念。

  列表最后面有个 Lineage OS 自带音乐播放器，和这个超级像，更加精简。

  </details>

- [Phonograph Plus](https://github.com/chr56/Phonograph_Plus)
  [[F-Droid](https://f-droid.org/packages/player.phonograph.plus/)]

  也是 Phonograph 正在积极维护的 fork，在逐渐增加功能。

- [Retro Music](https://github.com/RetroMusicPlayer/RetroMusicPlayer)
  [[F-Droid](https://f-droid.org/packages/code.name.monkey.retromusic/)]
  [[网站](https://retromusic.app/)]

  <details>

  <summary>很漂亮的音乐播放软件。F-Droid 版本已移除内购。</summary><br/>

  曾经有一个名为 [Metro](https://github.com/MuntashirAkon/Metro)[[F-Droid](https://f-droid.org/packages/io.github.muntashirakon.Music/)] 的破解版，但前者完全免费后已没有继续开发的必要。

  </details>

- [Vanilla Music](https://github.com/vanilla-music/vanilla)
  [[F-Droid](https://f-droid.org/packages/ch.blinkenlights.android.vanilla/)]
  [[网站](https://vanilla-music.github.io/)]\*

  <details>

  <summary>老牌音乐播放器。</summary><br/>

  从 Reddit 上的反馈来看似乎是开源中为数不多对 .opus 文件支持较好的播放器。

  </details>

- [Mpd](https://github.com/MusicPlayerDaemon/MPD/)
  [[F-Droid](https://f-droid.org/packages/org.musicpd/)]
- [M.A.L.P.](https://gitlab.com/gateship-one/malp)
  [[F-Droid](https://f-droid.org/packages/org.gateshipone.malp/)]

  <details>

  <summary>前后端分离的音乐播放应用。</summary><br/>

  这个属于极客范畴了，本身不携带控制界面，并且实用性也不如正常的音乐播放器。Linux 用户或许用过，至少我是很喜欢的（是说喜欢 Linux 桌面的使用情景，安卓上的使用体验是很糟的）。

  M.A.L.P. 为前端，可以控制安卓手机自己的 Mpd，也可以连接到电脑上的 Mpd。

  </details>

- [Noice](https://github.com/ashutoshgngwr/noice)
  [[F-Droid](https://f-droid.org/packages/com.github.ashutoshgngwr.noice/)]
  [[网站](https://ashutosh.blog/noice/)]

  <details>

  <summary>播放白噪音/自然声音。</summary><br/>

  **有付费内容。**

  内置各种共 30+ 种声音，可以自由组合，设置每一种声音的音量，保存为预设。

  </details>

- [SoundAura](https://github.com/CliffracerMerchant/SoundAura)
  [[F-Droid](https://f-droid.org/packages/com.cliffracertech.soundaura)]

  <details>

  <summary>同时播放多条用户提供的音频。</summary><br/>

  实际上可以完成上边Noice的功能，但软件没有自带任何声音，需要我们自己去下载。

  Issue 中有人推荐了一些“双耳节拍"音频，可以下载尝试：
  - https://orangefreesounds.com/binaural-beats/
  - https://archive.org/details/binaural-beats_201904
  - https://musicalhypnosis.com/royalty-free-binaural-beats/

  </details>

#### 流媒体

- [YAACC](https://github.com/tobexyz/yaacc-code)
  [[F-Droid](https://f-droid.org/packages/de.yaacc/)]\*

  <details>

  <summary>DLNA 服务器/客户端/接收器/控制器。</summary><br/>

  经过迭代已变得基本可用，可部分替代 BubbleUPnP。

  </details>

#### 绘画

- [Pocket Paint](https://github.com/Catrobat/Paintroid)
  [[F-Droid](https://f-droid.org/packages/org.catrobat.paintroid/)]

  随便画点啥，功能比较全，甚至还有图层，界面也简洁漂亮。

- _[PixaPencil](https://github.com/therealbluepandabear/PixaPencil)
  [[F-Droid](https://f-droid.org/packages/com.therealbluepandabear.pixapencil/)]
  [[网站](https://pixapencil.com/)]_

  <details>

  _<summary>自称“第一的开源像素绘画应用”，已易主。</summary>_

  大概相当于 Windows 上的绘图，貌似要功能更丰富一些。

  **警告** ：2024 年 1 月，PixaPencil 易主，并正在用 Flutter 重写，协议从 GNU GPL v3 切换到了 [PixaPencil's EULA](https://github.com/tomdoeslinux/PixaPencil/blob/main/EULA.txt)。[Reddit](https://www.reddit.com/r/Kotlin/comments/1ce6g74/my_first_kotlin_app_pixapencil_the_perfect_app/) 上的自荐，账号已被 ban，声称用 Kotlin 写的，在 Google Play 发布。真是混乱，是否仍旧真正开源自行甄别吧。

  </details>

#### 相机

- [Gcam Services Provider](https://github.com/lukaspieper/Gcam-Services-Provider)
  [[F-Droid (Basic版)](https://f-droid.org/packages/de.lukaspieper.gcam.services/)]
  [[Izzyondroid (Photos版)](https://apt.izzysoft.de/fdroid/index/apk/com.google.android.apps.photos)]

  <details>

  <summary>这个本身不是相机软件，但安装后允许用户安装 Gcam，即谷歌相机。</summary><br/>

  谷歌相机有着其他开源相机软件无法比拟的图像优化，成像质量可以提升好几档。此外，还有夜景模式、全景模式、HDR+ 等很强大的功能。对照片质量敏感的朋友，就不要用下面那些软件了。当然，这个解决方案并不是开源的。如果你不在意的话，这算是最佳方案了。

  （2024.02 更新）后来才搞明白，这个软件有 Basic 和 Photos 两个版本。简单地说，如果系统上有 Google Photos，就用 Basic 版；如果没有，就用 Photos 版。这样可以使用相机界面的“相册”按钮打开系统相册。详见 [Izzyondroid 页面](https://apt.izzysoft.de/fdroid/index/apk/com.google.android.apps.photos)。

  安装此软件后，大家可以到 [Gcam 的网站](https://www.celsoazevedo.com/files/android/google-camera/links/)寻找适配自己机型版本的 Gcam 和配置文件，简单安装即可。

  </details>

- [Aperture](https://github.com/LineageOS/android_packages_apps_Aperture)

  <details>

  <summary>Lineage OS 20 及以上版本自带相机应用。</summary><br/>

  相较之前自带的 Snap（版本19之前）和 AOSP 原生相机（版本19），界面更加漂亮，功能更加丰富，可以说接近手机原系统中的相机应用了。有了这个（当然前提是你在用 Lineage OS），我自认为可以不再考虑下面几个开源方案。

  此外，只有 Gcam 可以在功能和质量上好于 Aperture，但与系统的集成却比较差。不在乎成像质量的，使用这个自带应用就行。

  之前的描述依然适用，复制如下：

  这类第三方相机软件（这是相对于手机原系统来说的）都有一个缺陷，就是无法很好地利用硬件，比如无法利用一分四的超像素，没有延长曝光的超级夜景模式，等等。不过在软件上做的已经很不错，还集成了二维码扫描，不用装单独的二维码扫描软件了。

  </details>

- _[FreeDCam](https://github.com/KillerInk/FreeDcam)
  [[F-Droid](https://f-droid.org/packages/troop.com.freedcam)]_

  <details>

  _<summary>我觉得这个和 Open Camera 是开源相机中最好的两个，功能比较全面。</summary>_

  **最后更新时间：20221020。**

  当然这个全面是指对任何摄像头都适用的功能，如广角畸变修正、4 合 1 像素再拆成 1 像素等就不灵了。作为通用相机软件，已经很不错了。

  </details>

- [Open Camera](https://sourceforge.net/p/opencamera/code)
  [[F-Droid](https://f-droid.org/packages/net.sourceforge.opencamera/)]
  [[网站](https://opencamera.org.uk/)]

  <details>

  <summary>比较强大的相机软件，但是界面很丑。</summary><br/>

  开发减缓，感觉开发者逐渐有点无心无力。（不过，最近更新了 1.53.1。）

  </details>

- [Photon Camera](https://github.com/eszdman/PhotonCamera)

  <details>

  <summary>很神奇的相机软件，照片质量堪比官方 OS 下的自带相机。</summary><br/>

  在 Lineage OS 下，其它相机软件照片质量奇差，涂抹到细节全失。另外，像夜景模式、超像素的支持也都有。在功能上是吊打上面两位和 Lineage OS 自带相机的。

  更新：这一段的问题应该已经解决，我尝试编译了最新的git仓库代码，没有长时间卡顿了，不过没有新版本发布。在此前，打开和切换界面都等数十秒长。有[一个 issue](https://github.com/eszdman/PhotonCamera/issues/54) 说它在扫描设备上所有的照片，不知是不是长时间不响应的原因。

  另外，这款软件可能不是默认支持所有设备的，但没找到它支持设备的条件（源代码里有支持列表）。

  </details>

### 日常工具

#### 地图

- [OSMAnd~](https://github.com/osmandapp/Osmand)
  [[F-Droid](https://f-droid.org/packages/net.osmand.plus/)]
  [[网站](https://osmand.net/)]

  <details>

  <summary>OpenStreetMap 地图。</summary><br/>

  因为数据都是用户自己贡献的，所以越偏僻的地方数据越少。如果在大城市，可以尝试一下，基本的浏览和导航功能还是可以用的。OSM 能做到的功能实际很多，国内地图能记录的信息 OSM 基本都可以，比如多层建筑、公交地铁线路，但要贡献者自己学会怎么编辑。

  请在 F-Droid 平台安装，那边的开发者在源代码的基础上，去掉了其中的付费页面，编译了 OSMAnd+ 的所有功能。这在谷歌苹果亚马逊的商店都收费至少 20 刀。

  </details>

- [Organic Maps](https://github.com/organicmaps/organicmaps)
  [[F-Droid](https://f-droid.org/packages/app.organicmaps/)]
  [[网站](https://organicmaps.app/)]

  <details>

  <summary>基于 OpenStreetMap 数据的离线地图软件。</summary><br/>

  是 Maps.me 的开源复刻，离线的登山、骑行与导航，主打给驴友们做路线规划。

  </details>

- [GPS Logger(GPS记录器 )](https://github.com/mendhak/gpslogger)
  [[F-Droid](https://f-droid.org/packages/com.mendhak.gpslogger/)]
  [[网站](https://gpslogger.app/)]\*

  轻量、省电的 GPS 记录器。

#### 天气

- [Breezy Weather](https://github.com/breezy-weather/breezy-weather)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/org.breezyweather)]
  [[F-Droid](https://f-droid.org/packages/org.breezyweather/)]

  <details>

  <summary>基于几何天气的天气软件，已取代前者。</summary><br/>

  因为几何天气维护停滞，Breezy Weather 应运而生，增加了新的功能、提供商，修复了一些 bug。整体上，就是一款更好的几何天气。

  注意二进制版本之间的区别，F-droid 版本去除了非自由网络来源。

  </details>

- [Pluvia Weather](https://github.com/SpicyChair/pluvia_weather_flutter)

  <details>

  <summary>不错的天气软件，界面相当漂亮。</summary><br/>

  但是使用的 OpenWeatherMap 貌似国内连接很慢，预报也不一定准确。

  更新：早在 2022 年，F-Droid 官方就以检测到 GMS 使用为由下架了这个软件，但是作者并未有意识地使用（见[相关 issue](https://github.com/SpicyChair/pluvia_weather_flutter/issues/56)）。所以现在 F-Droid上 安装不了了。大家可自行判断，或者干脆使用上面的 Breezy Weather。

  </details>

<details>

<summary>过时的内容</summary>

- _[Geometric Weather(几何天气)](https://github.com/WangDaYeeeeee/GeometricWeather)
  ~~[[F-Droid](https://f-droid.org/packages/wangdaye.com.geometricweather/)]~~_

  <details>

  _<summary>开发已经停滞，建议使用 Breezy Weather。</summary>_

  **最后更新时间：20220610 / F-droid 已 404。**

  用过最好的天气软件之一，媲美很多国内安卓系统的自带天气软件。

  </details>

</details>

#### 智能穿戴

- [Gadgetbridge](https://codeberg.org/Freeyourgadget/Gadgetbridge)
  [[F-Droid](https://f-droid.org/app/nodomain.freeyourgadget.gadgetbridge)]
  [[网站](https://gadgetbridge.org/)]

  <details>

  <summary>智能手环/手表的手机客户端。</summary><br/>

  无需官方软件，无需创建账号，即可管理你的手环和查看数据。

  最兼容的是小米、Amazfit 等，华为的很多设备也有较好的支持，目前可以比较好地[支持 112 款设备](https://gadgetbridge.org/gadgets/)。对于较新的设备，其中一些由于协议要求，需要安装一次官方软件并获取密钥，相关操作见[官方文档](https://gadgetbridge.org/basics/pairing/huami-xiaomi-server/)。

  就功能来说，可以操作的功能有：健康数据、通知同步、查看天气、来电处理、音乐控制、运动记录、设定闹钟、查找手机、导航显示等。这些对我来说真的足够了，并且几年前的手环就足以支持，成本极低。截至添加条目时，我已经用了2个月，感觉非常好用，可以替代官方软件。

  </details>

#### 自我管理

- [Tasks](https://github.com/tasks/tasks)
  [[F-Droid](https://f-droid.org/packages/org.tasks/)]
  [[网站](https://tasks.org/)]

  待办列表管理，应该是同类最佳之一了。

- [Loop Habit Tracker(习惯)](https://github.com/iSoron/uhabits)
  [[F-Droid](https://f-droid.org/packages/org.isoron.uhabits/)]

  <details>

  <summary>制定规划，帮你监督，习惯养成利器。</summary><br/>

  可以记录你每天计划完成的进度，做出统计，定时提醒。

  </details>

- [Feeel(家庭锻炼)](https://gitlab.com/enjoyingfoss/feeel)
  [[F-Droid](https://f-droid.org/packages/com.enjoyingfoss.feeel/)]

  <details>

  <summary>锻炼规划。</summary><br/>

  一个锻炼方案可以设定多个锻炼项目和时长，指导你完成锻炼。界面很漂亮，运动时每个项目有倒计时，内置的几个锻炼项目有根据真实照片抽象化的姿势展示。

  </details>

- [Did I Take My Meds?(我吃药了吗？)](https://github.com/CorruptedArk/did-i-take-my-meds)
  [[F-droid](https://f-droid.org/packages/dev.corruptedark.diditakemymeds)]

  <details>

  <summary>监督用药。</summary><br/>

  可以增添用药条目，指定数量，它会提醒你吃药，以及记录过往用药。虽然是新软件，但是目前的功能已经很不错了。

  </details>

- [My Expenses(开支助手)](https://github.com/mtotschnig/MyExpenses)
  [[F-droid](https://f-droid.org/packages/org.totschnig.myexpenses/)]
  [[网站](https://www.myexpenses.mobi/)]\*

  个人理财管理工具。

#### 小工具

- [Tape Measure](https://github.com/SecUSo/privacy-friendly-tape-measure)
  [[F-Droid](https://f-droid.org/packages/org.secuso.privacyfriendlytapemeasure)]
  [[网站](https://secuso.aifb.kit.edu/english/Tape_Measure_and_Ruler.php)]

  <details>

  <summary>屏幕直尺（没跑路的那种）。</summary><br/>

  实际上其主要功能为通过图片中的制定参考物测量其他物体长度，但远远没有苹果手机/平板上的那个功能方便好用。屏幕直尺的校准也不太好，需要你用另一个尺去量屏幕上的一条线，而不是用一张常见的卡片去校准。总之，设计上略显简陋和矛盾，但偶尔应急也没问题。

  </details>

- [GuessIron](https://github.com/mobeil1/GuessIron)
  [[F-Droid](https://www.f-droid.org/zh/packages/de.indie42.guessiron/)]

  <details>

  <summary>更好的屏幕直尺（笑）。</summary><br/>

  可以用另一个尺子、银行卡或者任意你知道长度的物体来校准。

  </details>

- [Compass](https://github.com/Kr0oked/Compass)
  [[F-Droid](https://f-droid.org/packages/danielmeek32.compass)]

  指南针。

- [Trail Sense](https://github.com/kylecorry31/Trail-Sense)
  [[F-Droid](https://f-droid.org/packages/com.kylecorry.trail_sense/)]\*

  <details>

  <summary>野外生存应用，内置大量小工具。</summary><br/>

  手机能做到的/你能想到的功能它几乎都有。

  </details>

- [Audio Spectrum Analyzer](https://github.com/woheller69/audio-analyzer-for-android)
  [[F-Droid](https://f-droid.org/packages/org.woheller69.audio_analyzer_for_android/)]

  声音频谱分析。

- [Bluetooth Remote(蓝牙遥控器)](https://gitlab.com/Atharok/BtRemote)
  [[F-Droid](https://f-droid.org/packages/com.atharok.btremote/)]
  [[网站](https://atharok.gitlab.io/site/projects/bt-remote/)]\*

  <details>

  <summary>顾名思义，有键鼠功能。</summary><br/>

  适合在 TV 系统上临时使用。还比较简陋有点小问题，可以作为Bluetooth Keyboard & Mouse(io.appground.blek)的下位替代。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[Ruler](https://github.com/congshengwu/Ruler)~~
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ruler.csw)]_

  <details>

  _<summary>很简单的屏幕直尺，已删库跑路。</summary>_

  **警告：源码已 404。彻底不算开源软件了。**

  默认可能有误差，但好在可以校准，没准什么时候可以应急。

  </details>

</details>

### 学习办公

#### 办公套件

- [Collabora Office](https://www.collaboraoffice.com/)
  [[独立源](https://www.collaboraoffice.com/releases-en/collabora-office-on-mobiles-supporting-password-protected-documents-and-available-on-f-droid/)]
  [[网站](https://www.collaboraoffice.com)]

  <details>

  <summary>LibreOffice 的安卓适配版。</summary><br/>

  可以实现大多数的文档查看，还有实验性的编辑功能。这个应该是最好的开源 office 组件了（但依然不够好）。

  需要 F-Droid 加入第三方源（链接见上），就可以方便地安装更新。

  </details>

#### 笔记

- [Markor](https://github.com/gsantner/markor)
  [[F-Droid](https://f-droid.org/packages/net.gsantner.markor/)]

  <details>

  <summary>笔记软件，使用 Markdown 语法。</summary><br/>

  这个对于很多人并不是最优选择，但是我喜欢它直接对本地的纯文本文件进行编辑，而不是保存为其他的格式。这样我可以自行管理 Markdown 文件，包括同步到电脑上，用其他编辑器去编辑。

  这样不需要软件实现跨平台❎，而是通过文件格式进行跨平台。☑️

  </details>

- [Notally](https://github.com/OmGodse/Notally)
  [[F-Droid](https://f-droid.org/packages/com.omgodse.notally/)]

  极简又漂亮的笔记应用，只能输入纯文字，有少许加粗斜体等格式。

- [Saber](https://github.com/adil192/saber)
  [[F-Droid](https://f-droid.org/packages/com.adilhanney.saber/)]
  [[网站](https://saber.adil.hanney.org/)]

  <details>

  <summary>不多见的开源手写笔记软件。</summary><br/>

  ~~我没有安卓平板，不知道实际体验如何。~~ 我在两个安卓设备上体验了：一个装了 LineageOS 18 的三星 Note 4（即第三方系统 + 第三方软件），另一个是官方系统的三星 Tab A 9.7。和原装系统下的自带笔记相比，延迟差不多（但本来就很高）,也支持压感。

  想在纯开源的环境下体验手写笔记，在目前 Saber 是一个很不错的选择。

  </details>

#### 文档阅读

- [OpenDocument Reader](https://github.com/TomTasche/OpenDocument.droid)
  [[F-Droid](https://f-droid.org/packages/at.tomtasche.reader)]
  [[网站](https://opendocument.app/)]

  <details>

  <summary>功能很弱的文档查看软件。</summary><br/>

  貌似主要解析文档里的内容，文档的格式就很……怎么说，显示地很朴素😅。几乎没有编辑功能。

  </details>

- [MJ PDF Reader](https://gitlab.com/mudlej_android/mj_pdf_reader)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.gitlab.mudlej.MjPdfReader)]

  <details>

  <summary>基于 Pdf Viewer Plus 的 PDF 阅读器。</summary><br/>

  由于前者很久无维护，所以这个项目做了大量重构与适配工作，修复了一些问题，增加一些功能。总体来说解决了之前项目的一些痛点，值得一用。

  </details>

- [KOReader](https://github.com/koreader/koreader)
  [[F-Droid](https://f-droid.org/packages/org.koreader.launcher.fdroid/)]
  [[网站](https://koreader.rocks/)]

  适用于电子书的著名阅读软件。

- [Librera Reader](https://github.com/foobnix/LibreraReader)
  [[F-Droid](https://f-droid.org/packages/com.foobnix.pro.pdf.reader/)]
  [[网站](https://librera.mobi/)]

  <details>

  <summary>一个电子书的阅读与管理软件。</summary><br/>

  其实开源安卓应用中很少具有管理文档的功能，这个软件就填补了空缺。界面虽然看起来很过时，但是整个应用的功能还是很成熟的，这个应该更重要一些。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[Pdf Viewer Plus](https://github.com/JavaCafe01/PdfViewer)
  [[F-Droid](https://f-droid.org/packages/com.gsnathan.pdfviewer)]~~_

  <details>

  _<summary>已停止开发，建议使用 MJ PDF Reader。</summary>_

  **源码已存档：20240204 / F-droid 已 404。** 

  开源的同类软件 UI 都不怎么样，这个算是很好的了，期待和谷歌 PDF 阅读器差不多的开源版本出现。

  </details>

</details>

#### 文档扫描

- [OSS Document Scanner](https://github.com/Akylas/com.akylas.documentscanner)
  [[IzzyOnDroid](https://apt.izzysoft.de/packages/com.akylas.documentscanner)]

  <details>

  <summary>文档扫描。整体上看，要比 OpenScan 好很多。</summary><br/>

  之前只有下面的 OpenScan 做的不错，但是 2023 年底突然出现了一个更好的 OSS Document Scanner。

  这个软件具有正常的拍照导入或图片导入文档的功能，可以自由地（再次）裁切、调整顺序、20+ 种颜色滤镜。并且，身为颜值党，我很喜欢这个按照质感设计绘制的界面。

  当然这个软件目前正处于初期快速迭代的阶段，后续肯定还会有更多的功能实现和 bug 修复。我贡献了很粗糙的中文翻译，应该会在接下来 1、2 个版本加入。

  </details>

- [OpenScan](https://github.com/Ethereal-Developers-Inc/OpenScan)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.ethereal.openscan)]

  <details>

  <summary>文档扫描。推荐使用上面的 OSS Document Scanner。</summary><br/>

  和大家想的一样，可以拍照、裁切、再合成一个文档，可以导出为 PDF。功能完整，比如有再次裁切（只能再切小）、调整顺序、颜色优化（灰阶或黑白）、分享等等。

  相比之下，我试过的其它开源扫描软件就太差了，上面功能大量缺失，我觉得缺一不可。

  </details>

#### 卡片

- [AnkiDroid](https://github.com/ankidroid/Anki-Android)
  [[F-Droid](https://f-droid.org/repository/browse/?fdid=com.ichi2.anki)]
  [[网站](https://ankidroid.org/)]\*

  <details>

  <summary>跨平台记忆卡软件，可以制作和复习记忆卡。</summary><br/>

  AnkiDroid 根据艾宾浩斯记忆曲线让你按时复习卡片。卡片编辑的功能也非常强大，如可以增加图片、挖空等等，大家可以自行探索。

  </details>

#### 词典翻译

- [Aard2](https://github.com/itkach/aard2-android)
  [[F-Droid](https://f-droid.org/packages/itkach.aard2/)]
  [[网站](https://aarddict.org/)]

  <details>

  <summary>支持很多词典，可以在官网找到相应下载链接。</summary><br/>

  可惜作者不愿意将界面更新为早已成为主流的质感设计（见[此 issue](https://github.com/itkach/aard2-android/issues/72)），因此界面很老旧。

  </details>

- [QuickDic](https://github.com/rdoeffinger/Dictionary)
  [[F-Droid](https://f-droid.org/packages/de.reimardoeffinger.quickdic/)]

  <details>

  <summary>词典软件。</summary><br/>

  怎么说呢，一言难尽啊，开源的词典真的没找到很好用的。这个 QuickDic 可以下载很多中词典文件，但基本是多语种互译。查词的时候把所有词显示出来，查哪个滚动到哪个。

  </details>

- [DeepL](https://github.com/sakusaku3939/DeepLAndroid)
  [[F-Droid](https://f-droid.org/packages/com.example.deeplviewer/)]

  <details>

  <summary>翻译软件，基于深度学习的翻译引擎。</summary><br/>

  这个是把网页版包装成了一个轻量的应用。重要的是，可以在选取文字后的弹出菜单里选择 DeepL 进行翻译。

  </details>

#### 数学工具

- [microMathematics Plus](https://github.com/mkulesh/microMathematics)
  [[F-Droid](https://f-droid.org/packages/com.mkulesh.micromath.plus/)]

  <details>

  <summary>掌上 CAS，极为强大的计算机代数系统。</summary><br/>

  函数、微积分、作图等应有尽有。采用了最近越来越常见的笔记本（notebook）的形式，输入和输出都可以保留下来，作图会内置显示等。陪你度过大学不是梦。

  </details>

#### 百科

- [Wikipedia(维基百科)](https://github.com/wikimedia/apps-android-wikipedia)
  [[F-Droid](https://f-droid.org/packages/org.wikipedia/)]
  [[网站](https://www.mediawiki.org/wiki/Wikimedia_Apps)]

  <details>

  <summary>维基百科官方客户端，只有 10M，很小巧但五脏俱全。</summary><br/>

  Wikipedia 在平台建设上确实遥遥领先，希望国内同行快点幡然醒悟。

  </details>

#### 星图

- [Sky Map](https://github.com/sky-map-team/stardroid)
  [[F-Droid](https://f-droid.org/packages/com.google.android.stardroid/)]
  [[网站](https://sky-map-team.github.io/stardroid/)]

  <details>

  <summary>星图软件，让你上知天文。</summary><br/>

  2023.12 注：更新减缓，推荐用 Stellarium，虽然没有经过 F-Droid/IzzyOnDroid 发布，但也算是开源吧。

  借助重力感应，把手机指向天空就可以方便对照天上的星是什么名字。当然其他功能就不多了。虽然在更新，但是界面比较落后，数据貌似也不多。

  </details>

- [Stellarium](https://github.com/Stellarium/stellarium)
  [[网站](https://www.stellarium-labs.com/stellarium-mobile-plus/)]

  <details>

  <summary>大名鼎鼎的 Stellarium。</summary><br/>

  最近桌面端发布了 1.0 版本，才反应过来它也是开源的。但是只能在其他应用商店下载。专业性上即便在商业软件中也算极为优秀。

  </details>

#### 单位转换

- [Unit Converter Ultimate](https://github.com/physphil/UnitConverterUltimate)
  [[F-Droid](https://www.f-droid.org/packages/com.physphil.android.unitconverterultimate/)]

  <details>

  <summary>单位转换工具，非常全面。</summary><br/>

  除了常见的长度、面积、重量等基础物理单位，还有汇率、存储单位等。

  </details>

### 系统工具

#### 输入法

- [Unexpected Keyboard](https://github.com/Julow/Unexpected-Keyboard)
  [[F-Droid](https://f-droid.org/packages/juloo.keyboard2/)]

  <details>

  <summary>非常轻量的输入法，专为程序员、极客人群设计，终端搭配神器。</summary><br/>

  在较常见的 4 行键位基础上，通过在每一个键向四个角滑动的操作，触发其他的按键。

  重点是，这款键盘默认操作体验十分顺手（此处 @Trime）。如果之前在用 Hacker's keyboard 的，可以换这个了。

  </details>

- [Fcitx5 for Android(小企鹅输入法 5)](https://github.com/fcitx5-android/fcitx5-android)
  [[F-Droid](https://f-droid.org/packages/org.fcitx.fcitx5.android/)]
  [[网站](https://fcitx5-android.github.io/)]

  <details>

  <summary>在它出现之前，开源的安卓拼音输入法应该只有同文输入法（见下）。</summary><br/>

  Fcitx（小企鹅）的加入，可以说解决了很多人（包括我）的痛点。我用了一段时间，感觉已经无缝替换掉了 Gboard。

  Fcitx 输入法的特点就是对小白用户友好，和谷歌的 Gboard 很像，很多界面元素和交互体验的设计应该直接借鉴了后者。这是个好事，相比之下，同文输入法就给我带来了了不少的操作负体验。两款软件就体现了友好度和定制性的权衡。

  在用户界面和体验上，Fcitx 已经很成熟了。即便目前的版本还是 0.0.3（表示还不稳定）。想安装即用的，绝对推荐。想要强大定制性的，则推荐下方的同文输入法。

  </details>

- [Trime(同文输入法)](https://github.com/osfans/trime)
  [[F-Droid](https://f-droid.org/packages/com.osfans.trime/)]

  <details>

  <summary>支持拼音的输入法，基于著名的 RIME 输入法框架。</summary><br/>

  ~~F-Droid 上甚至是开源软件中唯一一个中文拼音输入法~~（有新选手加入，见上 Fcitx5）。同文输入法就像其桌面版一样，基于配置文件，定制性相当恐怖😱，你喜欢的样子它都有。配置文件对上手是一个门槛，需要自行下载配置文件导入。

  本以为两年不更新了，结果又有新版本了（指 v3.2.0 版本与上一个版本相隔3年多）。一个开源软件突然恢复维护是一件令人感到幸福的事情。

  </details>

- [Stroke Input Method(笔划输入法)](https://github.com/stroke-input/stroke-input-android)
  [[F-Droid](https://f-droid.org/packages/io.github.yawnoc.strokeinput/)]

  <details>

  <summary>很简单的笔划输入法，虽然平时不用，但感觉可用性是不差的。</summary><br/>

  容错性稍稍差了一些，所有笔划都要严格归入横、竖、撇、捺和折 5 种，判断错误就找不到字了。

  </details>

#### 文件管理

- [Material Files(质感文件)](https://github.com/zhanghai/MaterialFiles)
  [[F-Droid](https://f-droid.org/packages/me.zhanghai.android.files/)]

  文件管理器，非常漂亮，基本的功能都有。

- [Ghost Commander](https://sourceforge.net/p/ghostcommander/svn/HEAD/tree/)
  [[F-Droid](https://f-droid.org/packages/com.ghostsq.commander/)]
  [[网站](https://sites.google.com/site/ghostcommander1)]\*

  <details>

  <summary>双面板文件管理器，替代 Total Commander。</summary><br/>

  灵感源于两大经典软件：DOS 下的 Norton Commander 和 Linux 下的 Midnight Commander。界面没有跟进质感设计的风格，但也有自己的特色。

  </details>

- [Disk Usage](https://github.com/WhiredPlanck/diskusage)
  [[F-Droid](https://f-droid.org/packages/com.google.android.diskusage/)]

  <details>

  <summary>磁盘占用分析，显示手机上磁盘占用情况。</summary><br/>

  类似于 Windows 的 SpaceSniffer，类 Unix 的 du。

  这类开源应用实在没有更“现代”的选择了，界面比较落后，好在这个软件依然完美运行，源代码也在维护。根据最新半个月（2022.04）的提交消息来看，有超级多的代码更新，可能会有新版本？

  更换了维护者，尚未发布新版本。SD Maid 其实有类似的实现。

  </details>

- [CIFS Documents Provider](https://github.com/wa2c/cifs-documents-provider)
  [[F-Droid](https://f-droid.org/packages/com.wa2c.android.cifsdocumentsprovider/)]\*

  <details>

  <summary>将网络存储挂载到存储访问框架（SAF）。</summary><br/>

  支援 SMB/FTP(S)/SFTP。其他应用只需访问 SAF 便可访问网络存储。

  </details>

#### 文件同步

- [Seafile](https://github.com/haiwen/seadroid)
  [[F-Droid](https://f-droid.org/packages/com.seafile.seadroid2/)]
  [[网站](https://www.seafile.com/home/)]

  <details>

  <summary>文件同步/网盘客户端，是国内开发的，需要自己搭服务器。</summary><br/>

  我们学校用它做了一个 box，访问起来很方便：）

    </details>

- [Syncthing-Fork](https://github.com/Catfriend1/syncthing-android-fdroid)
  [[F-Droid](https://f-droid.org/packages/com.github.catfriend1.syncthingandroid/)]
  [[网站](https://syncthing.net/)]\*

  <details>

  <summary>文件同步软件，支持局域网和在线同步。</summary><br/>

  和 KDE Connect 有同样的缺点，保活做得不是很好，网络环境变化后与其他设备连接可能不及时。个人解决方案是连接 WIFI 后使用 Tasker 自动打开软件一次。

  Syncthing 主项已停止 Android 端开发，只能更换此增强版使用了。

  </details>

#### 文件加密/隐藏

- [DroidFS](https://forge.chapril.org/hardcoresushi/DroidFS)
  [[F-Droid](https://f-droid.org/packages/sushi.hardcore.droidfs/)]

  加密存储文件。

- [Photok](https://github.com/leonlatsch/Photok)
  [[F-Droid](https://f-droid.org/packages/dev.leonlatsch.photok/)]
  [[网站](https://www.producthunt.com/products/photok)]

  <details>

  <summary>加密相册。</summary><br/>

  选入应用集时正在积极开发，大量功能将要加入。

  </details>

- [Anemo](https://github.com/2bllw8/anemo)
  [[F-Droid](https://f-droid.org/packages/exe.bbllw8.anemo)]

  <details>

  <summary>隐藏文件（无加密）。</summary><br/>

  首先说明，这个并不是文件加密软件，但是应该可以满足部分需要这类应用的用户需求。

  我们可以使用 Anemo 将文件存入这个应用的私有本地空间。Anemo 会隐藏这些文件，但用户可以选择临时开启，就可以从文件管理器的侧边栏看到入口。在 15 分钟无访问后，入口会再次隐藏。整个过程并未加密。

  </details>

- [Amarok](https://github.com/deltazefiro/Amarok-Hider)
  [[F-Droid](https://f-droid.org/zh_Hans/packages/deltazero.amarok.foss/)]
  [[网站](https://deltazefiro.github.io/Amarok-doc/)]

  <details>

  <summary>隐藏文件和应用的软件。</summary><br/>

  具体方式根据官方说法是：

  > - Amarok 通过混淆文件名以及文件头部，改名文件并使文件“损坏”无法打开，从而达到隐藏的目的。
  > - Amarok 通过停用应用等方式，使它们在启动器与系统菜单中不可见，从而隐藏应用。

  </details>

#### 文件分享

- [LocalSend](https://github.com/localsend/localsend/)
  [[F-droid](https://f-droid.org/packages/org.localsend.localsend_app)]
  [[网站](https://localsend.org)]

  <details>

  <summary>可以在局域网内多设备间传递文件。</summary><br/>

  官方自己介绍为“开源、跨平台的 AirDrop 替代”。软件会自动搜索局域网内就绪的其他设备，一触即发，无需互联网连接，也无需账号或者提前配对等操作。可以分享文件、文件夹、文本、剪贴板、应用 apk 等，基本没有限制。

  对于 Linux 用户来讲，竞争对手就是 KDE Connect 这类通过配对连接并分享文件的方案了。相比之下，我更喜欢 LocalSend 的操作简洁。当然，KDE Connect 还有通知同步、远程输入等其他功能，也是相当强大和良心的软件。

  </details>

- [open2share](https://github.com/linesoft2/open2share)
  [[F-Droid](https://f-droid.org/packages/top.linesoft.open2share/)]\*

  <details>

  <summary>这是一款可以将“打开文件”转换为“分享文件”的 Android 小工具。</summary><br/>

  用于解决某些 App（读作 weixin）不接入系统文件分享功能导致的各种不便。（不过，在 wx 多选界面点击右下角的邮件小图标，确实是有系统分享的，但不清楚是不是覆盖了所有情形，大家可以试一试。/ wx的多选分享是聊天记录形式，选单中似乎只有能接收文本的目标。）

  </details>

- [Save Copy(保存副本)](https://github.com/RikkaApps/SaveCopy)
  [[Izzyondroid](https://apt.izzysoft.de/fdroid/index/apk/app.rikka.savecopy)]\*

  <details>

  <summary>在打开方式和分享菜单中加入保存副本选项。</summary><br/>

  长久不更新了，但使用没问题。示例：应用内更新时，可选择此选项而不是直接安装，可不授予应用安装权限且保留安装包并手动在文件管理器中安装。

  质感文件具有同样的功能，名为“另存为”。

  </details>

- [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif/tree/HEAD)
  [[F-Droid](https://f-droid.org/packages/com.jarsilio.android.scrambledeggsif/)]\*

  在分享图片前，从图片中删除如设备、日期、地点等 Exif 信息。

- [FFShare](https://github.com/caydey/ffshare)
  [[F-Droid](https://f-droid.org/packages/com.caydey.ffshare/)]\*

  <details>

  <summary>在分享媒体前使用 ffmpeg 压缩文件，可选删除 Exif 信息。</summary><br/>

  Scrambled Exif 增强版。

  </details>

- [Untracker(移除追踪)](https://github.com/zhanghai/Untracker)
  [[F-Droid](https://f-droid.org/packages/me.zhanghai.android.untracker/)]\*

  在分享链接前移除追踪信息，自带规则。

- [Tarnhelm](https://github.com/lz233/Tarnhelm)
  [[F-Droid](https://f-droid.org/packages/cn.ac.lz233.tarnhelm/)]
  [[网站](https://tarnhelm.project.ac.cn/)]\*

  <details>

  <summary>比 Untracker 更好的选择，有自动清理剪切板的能力。</summary><br/>

  可能由于需要规避风险，软件默认不带规则，请手动添加，官网有一些常用规则。

  </details>

#### 下载管理

- [Download Navi](https://github.com/TachibanaGeneralLaboratories/download-navi)
  [[F-Droid](https://f-droid.org/packages/com.tachibana.downloader/)]

  <details>

  <summary>功能强大的下载器，可以多段加速，分享下载链接就可以选择下载。</summary><br/>

  开发似乎已经停滞了，最新版本停留在 2022 年。

  </details>

- [Seal](https://github.com/JunkFood02/Seal)
  [[F-Droid](https://f-droid.org/packages/com.junkfood.seal/)]\*

  基于 yt-dlp 的视频/音频下载器。

#### 备份

- [Neo Backup](https://github.com/NeoApplications/Neo-Backup)
  [[F-Droid](https://f-droid.org/packages/com.machiav3lli.backup/)]

  备份软件（原名 OAndBackupX），可以备份任何东西，需要 root。

#### 密码

- [OpenKeychain](https://github.com/open-keychain/open-keychain)
  [[F-Droid](https://f-droid.org/packages/org.sufficientlysecure.keychain/)]
  [[网站](https://www.openkeychain.org/)]

  <details>

  <summary>PGP 锁钥管理，提供解锁密钥。</summary><br/>

  我是搭配 password store 使用。此外还有很多软件可以使用它。

  </details>

- [KeePassDX](https://github.com/Kunzisoft/KeePassDX)
  [[F-Droid](https://f-droid.org/zh_Hans/packages/com.kunzisoft.keepass.libre/)]
  [[网站](https://www.keepassdx.com/)]\*

  <details>

  <summary>Android 密码管理程序，与  KeePass 及其衍生程序兼容。</summary><br/>

  稍加配置即可做到密码全平台同步，且支持 Material 3 设计语言，界面简洁美观。

  提示：即使 KeePass 支持双重认证，也不应将密码与双重验证码放在一起，否则就失去了双重验证的意义，推荐使用 Aegis 或者 Stratum。

  </details>

- [Aegis](https://github.com/beemdevelopment/Aegis)
  [[F-Droid](https://f-droid.org/packages/com.beemdevelopment.aegis/)]
  [[网站](https://getaegis.app/)]

  双重验证（2FA）客户端，支持 HOTP 和 TOTP。

- [Stratum](https://github.com/stratumauth/app)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.stratumauth.app)]
  [[网站](https://stratumauth.com/)]\*

  <details>

  <summary>双重验证（2FA）客户端，支持 Wear OS 查看验证码。</summary><br/>

  除了 HOTP 和 TOTP，还支持 Mobile-Otp (mOTP)，Steam 和 Yandex。界面简洁美观，原名 Authenticator Pro。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[Password Store](https://github.com/android-password-store/Android-Password-Store)
  [[F-Droid](https://f-droid.org/packages/dev.msfjarvis.aps/)]~~_

  <details>

  _<summary>密码管理和自动填充软件。</summary>_

  **源码已存档：20241015 / F-droid 已 404。**

  要先了解 Linux 平台上的 [password store](https://www.passwordstore.org/) 才能用，这个是安卓客户端。

  password store 本身只是一个小脚本，调用 git 管理 gpg 加密的密码文件，这个安卓版也是类似。因而可以选择 GitHub 私人仓库 + password store 的超轻量开源方案，而非托管在统一的服务器上，这很 Unix。

  </details>

- _~~[andOTP](https://github.com/andOTP/andOTP)
  [[F-Droid](https://f-droid.org/packages/org.shadowice.flocke.andotp/)]~~_

  <details>

  _<summary>双重验证（2FA）或者一次性密码（OTP）客户端。</summary>_

  **源码已存档：20220114 / F-droid 已 404。**

  OTP 就是很多网站登录时出于安全性设置的 6 位数动态验证码。

  </details>

</details>

#### 短信

- [QUIK](https://github.com/octoshrimpy/quik)
  [[F-Droid](https://f-droid.org/packages/dev.octoshrimpy.quik/)]\*

  <details>

  <summary>短信应用，带搜索功能。</summary><br/>

  [QKSMS](https://github.com/moezbhatti/qksms) 的继任者。

  用它是因为 Lineage OS 自带的短信应用没有搜索功能，找上古短信很不方便。

  </details>

#### 电话录音

就我目前简单的调查所知，以 Lineage OS 为例，系统中没有自动通话录音功能。
只有在电话打通后才能手动开始录音。所以，这里列举一些可以开启自动录音的软件。

<details>

<summary>冷知识：</summary><br/>

Lineage OS 中，录音功能按照不同国家的法律对电话录音的规定设置了与否启用。
比如，在地区设置为我国，录音按钮就会显示；而设置在美国，则打电话的时候没有录音按钮。
为此，Lineage OS 团队（亦或是更早的开发者）调研了几乎每一个国家的法律，逐一做出了判断，
相关源代码可见[这里](https://github.com/LineageOS/android_packages_apps_Dialer/blob/lineage-20.0/java/com/android/dialer/callrecord/res/xml/call_record_states.xml)。
其中列举了针对所有国家地区决定开启这项功能与否的理由，并附所参考法律文件的链接，可谓用心良苦。

</details>

- [BCR(Basic Call Recorder)](https://github.com/chenxiaolong/BCR)

  <details>

  <summary>这是一款很简洁、积极开发的通话录音软件，做的非常好。</summary><br/>

  软件只有一个设置界面，只管录音后保存。对于以保存的录音，可以用其他任何方式访问音频文件。
  比如，可以用下面的 BCR-GUI 软件查看和管理这个软件保存的通话录音。是不是有种 UNIX 哲学在里面呀？

  这款软件只能通过 root 安装为系统软件，才能正常使用，所以 F-Droid 平台是没有的。需要通过 Magisk 等方式安装。

  </details>

- [BCR-GUI](https://github.com/nicorac/bcr-gui)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.github.nicorac.bcrgui)]

  <details>

  <summary>上面 BCR 通话录音软件的录音查看软件。</summary><br/>

  因为 BCR 开发者为了降低维护成本、专心只做通话录音工作，
  选择不制作录音管理的界面。因此，有人制作了配套的通话录音查看软件。
  作为 Linux 用户，我对这种决定表示完全理解。

  </details>

- [Call Recorder](https://gitlab.com/axet/android-call-recorder)
  [[F-Droid](https://f-droid.org/packages/com.github.axet.callrecorder)]

  <details>

  <summary>电话自动录音，非本土化系统中很实用。</summary><br/>

  搭配 Magisk 模块可以成为系统应用。

  之前作为第三方应用使用时，经常出现不会触发录音的问题，不知道安装为系统应用能否正常使用。推荐上面的 BCR。

  </details>

#### 应用管理

- [App Manager](https://github.com/MuntashirAkon/AppManager)
  [[F-Droid](https://f-droid.org/packages/io.github.muntashirakon.AppManager/)]
  [[网站](https://muntashirakon.github.io/AppManager/)]\*

  <details>

  <summary>极其强大的应用管理器。</summary><br/>

  称其为最强也不为过。即使只作为查看器，它所展示的应用详细信息也是同类应用中最详尽的。强大的代价是牺牲了易用性，属于极客工具。

  </details>

- [LibChecker](https://github.com/LibChecker/LibChecker)
  [[F-Droid](https://f-droid.org/packages/com.absinthe.libchecker/)]\*

  <details>

  <summary>作为 App Manager 的补充，主要用于查看应用使用的第三方库。</summary><br/>

  似乎同类中只有它能快速筛选 32 位应用，让我能及时用 64 位版本替换掉原先误装的 32 位版本。

  </details>

- [Activity Manager](https://github.com/sdex/ActivityManager)
  [[F-Droid](https://f-droid.org/packages/com.activitymanager/)]\*

  高级的 Activity 和快捷方式启动器。

- [Language Selector](https://github.com/VegaBobo/Language-Selector)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/vegabobo.languageselector)]\*

  <details>

  <summary>更改应用的显示语言，需要 Android 13 + 和 Shizuku。</summary><br/>

  虽然使用条件苛刻，但值得一用。有些应用只有简/繁其中一种翻译，且没有适配 Android 13 新增的在应用设置中选择语言的特性。此应用可对指定应用伪装系统语言，以达到改变应用内语言的目的。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[Anywhere-](https://github.com/zhaobozhen/Anywhere-)~~
  [[网站](https://absinthe.life/Anywhere-Docs/guide/)]\*_

  <details>

  _<summary>更多的快捷方式，已停止开发。</summary>_

  **源码已存档：20240929。**

  将你常用的应用页面（Activity）收集到一个界面并保存，可以在无需经过应用主界面的情况下快速打开。这里页面可以是扫码页面，可以是签到页面，实际上可以是任意软件的几乎任意界面。可玩性高，看你有没有需求了。

  这个软件没有上架 F-Droid 或 Izzyondroid，在酷安也被下架了，截至添加本条目时只能在 Github Releases 或者谷歌商店下载到。

  </details>

</details>

#### 应用冻结

- [Hail(雹)](https://github.com/aistra0528/Hail)
  [[F-Droid](https://f-droid.org/packages/com.aistra.hail)]

  <details>

  <summary>比较实用的应用冻结软件。</summary><br/>

  有很多冻结的途径可选如停用、隐藏和暂停，权限可以通过 Shizuku、root 等方式获取。软件整体质量很高，界面也遵循了最新的质感设计，体验很不错。

  我比较喜欢使用暂停这一方式，主要原因是桌面的图标不会消失，比如在停用后恢复的话桌面图标也没有了。设置自动冻结的选项也比较丰富。如果你有些软件常年不会用，可以冻结了以防这些软件时常在后台有联网、弹广告等活动。

  </details>

- [SuperFreezZ](https://gitlab.com/SuperFreezZ/SuperFreezZ)
  [[F-Droid](https://f-droid.org/packages/superfreeze.tool.android)]
  [[网站](https://superfreezz.gitlab.io/)]

  <details>

  <summary>冻结软件的后台活动，类似于Greenify。</summary><br/>

  开发似乎停滞了。

  它的冻结与上面的“雹”不同，并不是禁用、暂停或者隐藏软件，仅仅是限制软件的后台。Superfreeze 会自动冻结 7 天以上未使用的软件。我不知道怎么评估它的效果，大家不妨自己试一试。

  </details>

#### 系统清理

- [SD Maid SE](https://github.com/d4rken-org/sdmaid-se)
  [[F-Droid](https://f-droid.org/packages/eu.darken.sdmse/)]

  <details>

  <summary>SD Maid 二代。</summary><br/>

  估计很多人都用过 SD Maid，这个是其作者为更高安卓版本重新开发的开源版本。SE 是什么意思作者也[没有给出解释](https://github.com/d4rken-org/sdmaid-se/wiki/FAQ#what-does-the-se-in-sd-maid-se-stand-for)，或可解读为第二版 Second Edition。

  目前版本有各种系统清理选项，还有存储占用分析。已经基本可以替代原版本了。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[LTE Cleaner](https://github.com/TheRedSpy15/LTECleanerFOSS)
  [[F-Droid](https://f-droid.org/packages/theredspy15.ltecleanerfoss/)]~~_

  <details>

  _<summary>系统清理软件，已删库跑路。</summary>_

  **源码已 404 / F-droid 已 404。**

  这个并不是很强大，它只负责清理日志（Log）、临时文件（Temporary）和空文件夹（Empty）。但是聊胜于无。

  </details>

</details>

#### 系统美化

- [Doodle](https://github.com/patzly/doodle-android)
  [[F-Droid](https://f-droid.org/packages/xyz.zedler.patrick.doodle/)]
  [[网站](https://patrickzedler.com/doodle/)]

  <details>

  <summary>质感设计风格的动态壁纸。</summary><br/>

  具有自动暗色模式和省电动画等特点。喜欢抽象、简约风格的可以试一试。

  </details>

- [Iconify](https://github.com/Mahmud0808/Iconify)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/com.drdisagree.iconify)]

  <details>

  <summary>定制系统界面，需要 root。</summary><br/>

  不要被名字骗了，这个软件不仅可以改变图标，还可以修改很多系统界面的图标、颜色、形状和风格。如果用 Linux 的朋友，可以把这个软件所达到的自由度类比为 GTK/Qt 主题。

  </details>

- [Smartspacer](https://github.com/KieronQuinn/Smartspacer)\*

  <details>

  <summary>第三方一目了然（At a Glance）和负一屏。</summary><br/>

  可作为小部件或升级 Pixel 的一目了然功能（需要 Shizuku）。也可直接作为第三方启动器的负一屏（如 Nova Launcher/Neo Launcher）或替换 Google Discover（需要 Xposed）。

  </details>

#### 系统信息

- [CPU Info](https://github.com/kamgurgul/cpu-info)
  [[F-Droid](https://f-droid.org/packages/com.kgurgul.cpuinfo/)]

  展示系统软硬件信息，如 CPU 核心频率等，但并不全面。

#### 手机安全

<details>

<summary>过时的内容</summary>

- _[Hypatia](https://gitlab.com/divested-mobile/hypatia)
  [[F-Droid](https://f-droid.org/packages/us.spotco.malwarescanner/)]_

  <details>

  _<summary>恶意软件扫描应用，已停止开发。</summary>_

  **源码已存档：20241210**

  母项目 DivestOS 终止后，旗下所有项目都停止开发。有人 [fork](https://github.com/MaintainTeam/Hypatia) 了此项目并上架 [IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/org.maintainteam.hypatia/)，希望有人接手开发。

  自称安卓第一款恶意软件扫描应用。不过，既然都用开源软件了，这个的意义就没那么大了，除非用户依然想胡乱下载其他的东西。

  </details>

</details>

#### 电脑连接

- [A2LN](https://github.com/patri9ck/a2ln-app)
  [[F-Droid](https://f-droid.org/packages/dev.patri9ck.a2ln)]
  [[网站](https://patri9ck.dev/a2ln/)]
- _[AN2Linux](https://github.com/rootkiwi/an2linuxclient)
  [[F-Droid](https://f-droid.org/packages/kiwi.root.an2linuxclient/)]
  [[网站](https://github.com/rootkiwi/an2linuxserver/)]_

  <details>

  <summary>通知同步软件，将手机上的通知推送到 Linux 电脑上。</summary><br/>

  可以通过 WiFi、蓝牙或者移动数据。我只试过 WiFi，不知道另两个体验如何。

  后者已不再维护，  **最后更新时间：20210322**。

  </details>

- [KDE Connect](https://github.com/KDE/kdeconnect-android)
  [[F-Droid](https://f-droid.org/packages/org.kde.kdeconnect_tp/)]
  [[网站](https://kdeconnect.kde.org/)]

  <details>

  <summary>很强大的连接 PC 和手机的工具。</summary><br/>

  可以分享文件或文本、同步通知、运行命令和远程控制等等。需要 Linux 系统上安装相应的 PC 端软件，常见的如 KDE 官方的 [Kde Connect](https://kdeconnect.kde.org/) 和适配 GNOME 的 [GSConnect](https://github.com/GSConnect/gnome-shell-extension-gsconnect)。

  KDE 团队做的很好的一点是，他们将 KDE Connect 前后端分离开了，真正支撑底层功能的部分实现为一种协议，可以独立于图形界面部分运行。这样在非 KDE 环境，便可以用其它的软件，如我在使用的 [mconnect](https://github.com/grimpy/mconnect)，就是没有图形界面，只有命令行接口，但如果你想要的基本功能都具备，可以很灵活而不受桌面环境限制。

  </details>

- [Audio Share ](https://github.com/mkckr0/audio-share)
  [[F-Droid](https://f-droid.org/packages/io.github.mkckr0.audio_share_app/)]\*

  使 PC 的声音通过网络在手机上播放，SoundWire 的替代品。

#### 卫星定位

- [GPSTest](https://github.com/barbeau/gpstest)
  [[F-Droid](https://f-droid.org/packages/com.android.gpstest.osmdroid/)]

  <details>

  <summary>显示 GPS 信息，非常丰富。</summary><br/>

  可以看到五种全球定位系统的卫星位置、自己的经纬度、海拔还有速度等等。

  </details>

#### 传感器

- [Phyphox](https://github.com/phyphox/phyphox-android)
  [[F-Droid](https://f-droid.org/packages/de.rwth_aachen.phyphox/)]
  [[网站](https://phyphox.org)]

  <details>

  <summary>显示手机传感器信息，以及利用手机完成一些小实验。</summary><br/>

  这个应用是亚琛大学的老师学生设计开发。可以使手机变身成为一个小的物理实验室，进行光学、声学和力学实验。

  </details>

#### 语音助手

- [Dicio assistant](https://github.com/Stypox/dicio-android)
  [[F-Droid](https://f-droid.org/packages/org.stypox.dicio/)]

- [RHVoice](https://github.com/RHVoice/RHVoice)
  [[F-Droid](https://f-droid.org/packages/com.github.olga_yakovleva.rhvoice.android/)]

  <details>

  <summary>极其简陋、功能不强的语音助手。先给大家泼冷水，以免误会。</summary><br/>

  只有基本的功能，如打开软件、询问天气、简单计算、打电话等等。问题是对中文的支持还没有设置，但不难，需要用配置文件描述触发问题的语句是什么样的，需要提交到官方代码中去。总之，还是不要寄予太高期望，我只是觉得有就值得提一下。

  如果需要听它出声音，还要安装 RHVoice，否则的话只能显示文字。

  </details>

#### 统一推送（[UnifiedPush](https://unifiedpush.org/)）

UnifiedPush 是一套可以让用户选择推送通知方式的规范和工具。[已适配的应用列表。](https://unifiedpush.org/users/apps/)

- [Ntfy](https://github.com/binwiederhier/ntfy-android)
  [[F-Droid](https://f-droid.org/packages/io.heckel.ntfy/)]
  [[网站](https://ntfy.sh/)]

  <details>

  <summary>开源的网络推送服务，可以使用自建服务器。</summary><br/>

  通过一个网络连接，就可以把通知发送到已经配置好的手机上。有非常广泛的应用场景。但是对一般人来说，没有这种刚需，有点鸡肋。

  </details>

- [Sunup](https://codeberg.org/Sunup/android)
  [[F-Droid](https://f-droid.org/packages/org.unifiedpush.distributor.sunup/)]
  [[网站](https://github.com/mozilla-services/autopush-rs)]\*

  <details>

  <summary>基于 Mozilla 推动的 Autopush 网络推送服务。</summary><br/>

  项目刚起步，适配的应用寥寥无几。

  </details>

- [gCompat-UP](https://codeberg.org/UnifiedPush/fcm-distributor)
  [[Izzyondroid](https://apt.izzysoft.de/fdroid/index/apk/org.unifiedpush.distributor.fcm)]\*

  <details>

  <summary>将 UnifiedPush 转化为 FCM（谷歌推送）。</summary><br/>

  使只支持 UnifiedPush 的应用变为可以使用 FCM 推送。

  </details>

### 极客工具

我并不想分一个“开发类”，这里的软件并不是面向开发者的，而是喜欢折腾的用户。这也符合最开始制订的”受众广泛“要求。

#### Root 工具

- [Magisk](https://github.com/topjohnwu/Magisk)
  [[F-Droid](https://f-droid.org/packages/com.topjohnwu.magisk/)]
  [[网站](https://topjohnwu.github.io/Magisk/)]

  <details>

  <summary>  著名的面具，可以提供 root 和修改系统行为的模块。</summary><br/>

  不过，不是刚需的话，不建议使用。我使用 Lineage OS，因此微信和支付宝的指纹无法正常调用，便使用一些面具模块解决。

  Magisk 并没有提供每一种机型的下载，所以其安装过程对所有机型适用。

  </details>

#### 文本编辑

- [Editor](https://github.com/billthefarmer/editor)
  [[F-Droid](https://f-droid.org/packages/org.billthefarmer.editor/)]
  [[网站](https://billthefarmer.github.io/editor/)]

  <details>

  <summary>轻量的文本编辑器，很小很小的软件还有语法高亮，吹爆它。</summary><br/>

  一个问题是，一般只能打开安卓识别为纯文本的文件，连 yaml 都不行。除非文件管理器能强行作为文本打开。GitHub 有好几个 issue 提到，但作者坚决把锅甩给安卓和文件管理器，感觉作者有开发“洁癖”。

  </details>

- [Acode](https://github.com/deadlyjack/Acode)
  [[F-Droid](https://f-droid.org/packages/com.foxdebug.acode/)]
  [[网站](https://acode.foxdebug.com/)]

  <details>

  <summary>更高级的文本/代码编辑器。</summary><br/>

  从截图上看，Acode 可能更适合在平板等大屏设备上进行更专业的编辑工作，类似于 VS Code 等软件。

  </details>

#### 远程连接

- [ConnectBot](https://github.com/connectbot/connectbot)
  [[F-Droid](https://f-droid.org/packages/org.connectbot/)]
  [[网站](https://connectbot.org/)]

  <details>

  <summary>SSH 客户端，很好用。</summary><br/>

  在维护但很久没有新版本了。我校阅了所有的翻译，希望将来有更新。

  2021.10.25：更新啦。

  </details>

- [AVNC](https://github.com/gujjwal00/avnc)
  [[F-Droid](https://f-droid.org/packages/com.gaurav.avnc/)]

  <details>

  <summary>简单但不简陋的 VNC 客户端。</summary><br/>

  可以通过手势实现不同的鼠标控制事件，因此是很实用的。

  </details>

- [RustDesk](https://github.com/rustdesk/rustdesk)
  [[F-Droid](https://f-droid.org/packages/com.carriez.flutter_hbb/)]
  [[网站](https://rustdesk.com/)]

  开源远程桌面应用，开源 TeamViewer 替代方案。

- [WADB](https://github.com/RikkaApps/WADB)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/moe.haruue.wadb)]

  <details>

  <summary>无线 ADB，需要 root。</summary><br/>

  虽然安卓在开发者选项中也可以开启“无线调试”，但这里开启的端口是随机的，明显是出于安全考虑。如果你所在网络没有那么危险，这款应用可以在固定的、也是默认的 5555 端口开启无线调试，因此电脑使用 adb 时无需输入端口信息即可连接。

  </details>

#### 终端

- [TermOne Plus](https://gitlab.com/termapps/termoneplus)
  [[F-Droid](https://f-droid.org/packages/com.termoneplus/)]
  [[网站](https://termoneplus.com/)]

  <details>

  <summary>终端应用。</summary><br/>

  有些系统中会禁用系统自带的安卓终端，所以想要在安卓上执行命令行操作，可以尝试这款应用。

  </details>

- [Termux](https://github.com/termux/termux-app)
  [[F-Droid](https://f-droid.org/packages/com.termux/)]
  [[网站](https://termux.dev/)]\*

  <details>

  <summary>Termux 不仅是一个终端，它还包含了一个完整的生态。</summary><br/>

  Termux 有自己的包管理，你可以像使用任何 Linux 系统一样使用这个终端，安装软件等都是可以的。

  不过，我自己之前没有收纳这个软件，现在经推荐才加入进来，原因就是它并不适合一般用户，明显是为极客用户而生的。更麻烦的是，貌似 Termux 在 Android 12+ [有被系统杀掉进程](https://github.com/termux/termux-app/issues/2366) 的问题，解决这个问题又是需要折腾系统（如果愿意使用 Tasker，这个问题可以使用 [Termux:Tasker](https://f-droid.org/packages/com.termux.tasker/)解决，Lineage OS 20 用此方法在 Termux 中开机启动后自动挂代理，几乎未被系统杀死过。）。总之，我认为想玩 Linux 的话，最佳办法是在真机或虚拟机里安装 Linux 系统，Termux 的使用场景真的比较有限。

  </details>

#### 抓包工具

- [PCAPdroid](https://github.com/emanuele-f/PCAPdroid)
  [[F-Droid](https://f-droid.org/packages/com.emanuelef.remote_capture)]
  [[网站](https://emanuele-f.github.io/PCAPdroid/)]

  Android 抓包工具，可[配合 Wireshark](https://emanuele-f.github.io/PCAPdroid/advanced_features#45-pcapdroid-trailer) 使用。

#### Git及平台客户端

- [OctoDroid](https://github.com/slapperwan/gh4a)
  [[F-Droid](https://f-droid.org/packages/com.gh4a/)]
  [[网站](https://slapperwan.github.io/gh4a/)]

  <details>

  <summary>GitHub 客户端，对 GitHub 各项功能支持比较全面。</summary><br/>

  reaction 表情、通知等细节都有，但是开发比较迟缓了。

  </details>

- _[GitFox](https://gitlab.com/terrakok/gitlab-client)
  [[F-Droid](https://f-droid.org/packages/com.gitlab.terrakok.gitfox/)]_

  <details>

  _<summary>GitLab 客户端，有点简洁，功能不多。</summary>_

  **最后更新时间：20220216。**

  GitLab 可以自主搭建服务器，因此支持登录其他服务器。

  </details>

- _[GitTouch](https://github.com/git-touch/git-touch)
  [[F-Droid](https://f-droid.org/packages/io.github.pd4d10.gittouch/)]_

  <details>

  _<summary>很多 git 托管平台的客户端，比如 GitHub，GitLab 等。</summary>_

  **最后更新时间：20221030。**

  注意不是 git 客户端，没发现很好的 git 客户端。

  </details>

- [MGit](https://github.com/maks/MGit)
  [[F-Droid](https://f-droid.org/packages/com.manichord.mgit/)]
  [[网站](https://manichord.com/projects/mgit.html)]

  <details>

  <summary>不太好的 git 客户端里不太差的一个。</summary><br/>

  在维护，但很久不发布新版本，界面也很古老，是 Android 4 时代的界面。

  </details>

#### F-Droid状态

- [F-Droid Build Status](https://codeberg.org/pstorch/F-Droid_Build_Status)
  [[F-Droid](https://f-droid.org/packages/de.storchp.fdroidbuildstatus)]

  <details>

  <summary>可以查看 F-Droid 软件编译状态。</summary><br/>

  F-Droid 平台所有软件都严格在他们的服务器上编译，这是和其他任何接受直接上传编译好安装包的应用商店最大的不同。也因此要等待编译，一般要几天时间，用这个就可以看新版本编译完成没有。

  </details>

#### 手册

- [Linux Command Library](https://github.com/SimonSchubert/LinuxCommandLibrary)
  [[F-Droid](https://f-droid.org/packages/com.inspiredandroid.linuxcommandbibliotheca/)]
  [[网站](https://linuxcommandlibrary.com/)]

  Linux 相关命令、应用的帮助手册，主要包括大量 man pages。

### 社交聊天

#### 聊天软件

更学究的讲，这一类软件叫做“即时通信”（Instant Messaging）。

- [Telegram FOSS](https://github.com/Telegram-FOSS-Team/Telegram-FOSS)
  [[F-Droid](https://f-droid.org/packages/org.telegram.messenger/)]
  [[网站](https://telegram.org/)]

  <details>

  <summary>最常用的开源（只有前端开源）聊天（即时通信）软件。</summary><br/>

  该 F-Droid 版本去除原版所包含的谷歌服务在内的一些闭源成分。

  </details>

- [Revolution IRC](https://github.com/MCMrARM/revolution-irc)
  [[F-Droid](https://f-droid.org/packages/io.mrarm.irc/)]
  [[网站](https://mrarm.io/)]

  <details>

  <summary>安卓（不一定）最佳 IRC 客户端，有用 IRC 的老伙伴估计也已经知道了。</summary><br/>

  ~~**警告**：已经很长时间没有更新了。~~ 好像有人想接手项目，让我们静观其变。

  界面整洁，功能全面。可以在后台一直保持连接。

  </details>

- [Goguma](https://codeberg.org/emersion/goguma)
  [[F-Droid](https://f-droid.org/packages/fr.emersion.goguma/)]
  [[网站](https://sr.ht/~emersion/goguma)]

  <details>

  <summary>更加现代化的 IRC 客户端，支持很多 IRCv3 的新标准。</summary><br/>

  坏消息是，很多主流 IRC 服务器基本不支持 IRCv3 特性（手动斜眼）。

  </details>

- [Jami](https://git.jami.net/savoirfairelinux/jami-client-android)
  [[F-Droid](https://f-droid.org/packages/cx.ring/)]
  [[网站](https://jami.net/)]\*

  加密聊天软件，支持 UnifiedPush。还可以用作 SIP 客户端。

- [TRIfA](https://github.com/zoff99/ToxAndroidRefImpl)
  [[F-Droid](https://f-droid.org/packages/com.zoffcc.applications.trifa/)]
  [[网站](https://tox.zoff.cc)]\*

  Tox 协议的安卓客户端，不挂后台需要安装 [Tox Notify](https://github.com/zoff99/tox_push_msg_app/) 使用 UnifiedPush 推送。

#### 社交平台

- [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit)
  [[IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/ml.docilealligator.infinityforreddit.patreon)]

  Reddit 客户端，F-Droid 上有好几个 Reddit 客户端，这个是我最喜欢的。

- [RedReader](https://github.com/QuantumBadger/RedReader)
  [[F-Droid](https://f-droid.org/packages/org.quantumbadger.redreader/)]

  Reddit 客户端，很简洁轻量。我个人更喜欢 Infinity 和 Slide。

- [Glider](https://github.com/Mosc/Glider)
  [[F-Droid](https://f-droid.org/packages/nl.viter.glider/)]

  著名面向 IT 领域的资讯平台 hacker news 的客户端，很精巧，用起来很顺手。

- _[Twidere X](https://github.com/TwidereProject/TwidereX-Android)
  ~~[[F-Droid](https://f-droid.org/packages/com.twidere.twiderex/)]~~
  [[网站](https://x.twidere.com/)]_

  <details>

  _<summary>Twitter 客户端，开源中最佳，没有之一。似乎已死。</summary>_

  **最后更新时间：20230524 / F-droid & Google Play 均已 404。**

  </details>

- [Fritter](https://github.com/jonjomckay/fritter)
  ~~[[F-Droid](https://f-droid.org/packages/com.jonjomckay.fritter/)]~~
  [[网站](https://fritter.cc/)]

  <details>

  <summary>Fritter 是 Twitter 的无登录客户端，应用商店均已阵亡。</summary><br/>

  源码尚在维护。

  类似于 NewPipe 之于 YouTube，所有数据都在本地。

  </details>

- [NewPipe](https://github.com/TeamNewPipe/NewPipe)
  [[F-Droid](https://f-droid.org/packages/org.schabi.newpipe/)]
  [[网站](https://newpipe.net/)]

  注重隐私的 YouTube 客户端，不能登陆，只能看，不过非常好用。

- [PipePipe](https://github.com/InfinityLoop1308/PipePipe)
  [[F-Droid](https://f-droid.org/packages/InfinityLoop1309.NewPipeEnhanced/)]
  [[网站](https://pipepipe.dev/)]\*

  <details>

  <summary>基于 Newpipe，同时可以观看其他视频站如 bilibili/niconico。</summary><br/>

  bilibili 无需登录即可播放 1080p 视频。

  </details>

- [Shaft](https://github.com/CeuiLiSA/Pixiv-Shaft)
- [PixEz](https://github.com/Notsfsssf/pixez-flutter)

  都是 Pixiv 客户端，做的也都不错。

- [Hentoid](https://github.com/avluis/Hentoid)
- _~~[Hendroid](https://github.com/Nonononoki/Hendroid)
  [[F-Droid](https://f-droid.org/packages/org.nonononoki.hendroid/)]~~_

  <details>

  _<summary>奇怪漫画网站的客户端，可以下载漫画。</summary>_

  后者是前者的 fork。由于 Hentoid 使用了某个闭源库，Hendroid 已停止开发。

  </details>

### 游戏

#### 模拟器

- [Lemuroid](https://github.com/Swordfish90/Lemuroid)
  [[F-Droid](https://f-droid.org/packages/com.swordfish.lemuroid/)]

  <details>

  <summary>很强大的游戏机模拟器，支持任天堂、索尼等 20 多款经典游戏机的模拟。</summary><br/>

  Nintendo、GBA、PSP 都没问题。你只要下载一个游戏 ROM，扔到指定文件夹，就可以玩了，简直良心神器！

  一个软件给手机游戏带来无限可能，可以找回童年，或者把丢掉的童年找回来！

  </details>

#### 休闲益智

- [Antimine](https://github.com/lucasnlm/antimine-android)
  [[F-Droid](https://f-droid.org/packages/dev.lucanlm.antimine/)]

  很棒的扫雷游戏，界面漂亮，操作直观。

- [TriPeaks](https://github.com/mimoguz/tripeaks-gdx)
  [[F-Droid](https://f-droid.org/packages/ogz.tripeaks/)]

  像素风格的纸牌游戏，很简单，只有这一种游戏，加进来是因为界面很精致。

- [Apple Flinger](https://gitlab.com/ar-/apple-flinger)
  [[F-Droid](https://f-droid.org/packages/com.gitlab.ardash.appleflinger.android/)]

  类似愤怒的小鸟，画面很精致。但是关卡太少了，不过瘾，也不更新了。

- [Sudoku](https://github.com/SecUSo/privacy-friendly-sudoku)
  [[F-Droid](https://f-droid.org/packages/org.secuso.privacyfriendlysudoku)]
  [[网站](https://secuso.aifb.kit.edu/english/Sudoku.php)]

  <details>

  <summary>数独，F-Droid 有几个数独游戏，这个用户体验是很好的。</summary><br/>

  还有[另一个](https://gitlab.com/opensudoku/opensudoku)，但是自带只有 90 个离线关卡，此外只能下载导入。

  </details>

- [2048](https://github.com/andstatus/game2048)
  [[F-Droid](https://f-droid.org/packages/org.andstatus.game2048/)]

  目前维护最积极的 2048。

- _[Blockinger](https://github.com/vocollapse/Blockinger)
  ~~[[F-Droid](https://f-droid.org/packages/org.blockinger.game/)]~~_

  <details>

  _<summary>俄罗斯方块。很久很久很久没更新了，但是还可以用。</summary>_

  **最后更新时间：20130815 / F-droid 已 404。**

  即便很老，但玩起来很顺手，反应灵敏，比较严格的经典规则，我认为高手也能玩的很舒服。也比较无奈，竟然没有较新的开源俄罗斯方块。

  小提示：可以用上面的 Lemuroid 下载 Nintendo 原版 ROM（1991 年）玩原汁原味的俄罗斯方块。不过可能有点延迟，不灵敏。

  </details>

- _[Falling Lightblocks](https://github.com/MrStahlfelge/lightblocks)
  [[网站](https://www.golfgl.de/lightblocks/)]_

  <details>

  _<summary>经推荐发现的另一款开源俄罗斯方块，更加新一些。</summary>_

  **最后更新时间：20220104。**

  操作体验上与 Blockinger 不同，支持手势操作，有过渡动画。有一些新版俄罗斯方块的操作，比如 hold。

  但这个不是完全开源，它可以连接非开源的服务器，（可选择？）上传游戏全程操作，和登录谷歌账号进行同步。

  </details>

- [Simon Tatham's Puzzles](https://github.com/chrisboyle/sgtpuzzles)
  [[F-Droid](https://f-droid.org/packages/name.boyle.chris.sgtpuzzles/)]
  [[网站](https://chris.boyle.name/projects/android-puzzles/)]

  40 款益智小游戏合集，包含扫雷等，想费一费脑细胞的可以试试。

- [Forkyz](https://gitlab.com/Hague/forkyz)
  [[F-Droid](https://f-droid.org/packages/app.crossword.yourealwaysbe.forkyz/)]

  <details>

  <summary>纵横字谜。不推荐，只是展示有这么个游戏。</summary><br/>

  全是英文的，并且提示词都是那种没在英语文化中长大就看不懂的梗。

  </details>

- [Lexica](https://github.com/lexica/lexica)
  [[F-Droid](https://f-droid.org/packages/com.serwylo.lexica/)]

  连字成词的单词拼写游戏，对词汇量要求高，否则心态容易崩。

- _[Open Golf](https://github.com/mgerdes/Open-Golf)
  [[F-Droid](https://f-droid.org/packages/me.mgerdes.open_golf/)]_

  <details>

  _<summary>一个小的高尔夫球游戏，但是关卡太少了。</summary><br/>_

  **最后更新时间：20220525。**

  用滑动控制力度方向，让球经历复杂地形进洞。

  </details>

#### 棋类

- [Lichess](https://github.com/lichess-org/lichobile)
  [[F-Droid](https://f-droid.org/packages/org.lichess.mobileapp.free/)]
  [[网站](https://lichess.org/)]

  <details>

  <summary>在线国际象棋对弈应用。</summary><br/>

  这方面真的希望国内做出一些比较开放的棋类对弈平台，给开源应用提供一些可能性。

  </details>

- [Gobandroid](https://github.com/ligi/gobandroid)
  [[F-Droid](https://f-droid.org/packages/org.ligi.gobandroid_hd/)]

- [gobandroid ai gnugo](https://github.com/ligi/gobandroid-ai-gnugo)
  [[F-Droid](https://f-droid.org/packages/org.ligi.gobandroidhd.ai.gnugo/)]

  <details>

  <summary>第一个是围棋棋盘应用，第二个提供了围棋引擎gnugo，可以让你与电脑对弈。</summary><br/>

  Gnugo 棋力貌似可以达到 3k，初学者是完全够用的（但手机处理器肯定会拉低很多）。

  </details>

#### 塔防

- [Mindustry](https://github.com/Anuken/Mindustry)
  [[F-Droid](https://f-droid.org/packages/io.anuke.mindustry/)]
  [[网站](https://anuke.itch.io/mindustry)]

  <details>

  <summary>非常精良的塔防游戏。</summary><br/>

  Mindustry 比一般的塔防要复杂，比如要采各种矿、建立资源运输管道供给防御工事、开发科技树，敌人自由走动。有点像即时策略 RTS 了（好像就是），可玩性 max。

  没事了，已经更新了~~注：目前由于 F-Droid 服务器编译环境不兼容，软件版本卡在了主版本 5。~~

  </details>

- [Anuto TD](https://github.com/reloZid/android-anuto)
  [[F-Droid](https://f-droid.org/packages/ch.logixisland.anuto/)]

  <details>

  <summary>塔防游戏，界面元素都是作者手画的。</summary><br/>

  作者自认为很丑，因而得名（ANother Ugly TOwer defense）。游戏并不是很优秀，单位比较少，画面粗糙，敌人多了再开加速会很卡。但是我一度很上瘾。

  </details>

#### 探险

- [Shattered Pixel Dungeon](https://github.com/00-Evan/shattered-pixel-dungeon)
  [[F-Droid](https://f-droid.org/packages/com.shatteredpixel.shatteredpixeldungeon/)]
  [[网站](https://shatteredpixel.com/)]

  <details>

  <summary>Roguelike 类地牢探险游戏，画面是像素风格的，很精致。</summary><br/>

  一旦死就要重来，每次游戏都会随机生成场景，自己玩过感觉有难度。现在更新非常频繁，发布了 1.0 版本，质量有保证。

  </details>

- [Andor's Trail](https://github.com/AndorsTrailRelease/andors-trail)
  [[F-Droid](https://f-droid.org/packages/com.gpl.rpg.AndorsTrail/)]
  [[网站](https://andorstrail.com/)]

  <details>

  <summary>任务驱动的 RPG 游戏，就是那种升级加技能点买装备打怪兽的游戏。</summary><br/>

  游戏其实还在持续完善，地图还没做完，所以有一部分故事线和任务都是断的。不过目前的部分已经可以玩几个星期了。还有问题是大部分对话是英文，中文翻译的很少。

  时隔好久，又看了一眼 git 仓库。你猜怎么着，它一小时前更新版本（v0.7.14）了，巧不巧！这个版本有很多人（包括我）更新的翻译，但是依然剩下 59% 的内容没有翻译。游戏里这些人话可真多。
  （2023 年或者更早的时候，有好多人把所有游戏内容都翻译了……上万的字符串啊，你们太牛了，给你们点赞）

  </details>

- [Xeonjia(寒冰之旅)](https://gitlab.com/DeepDaikon/Xeonjia)
  [[F-Droid](https://f-droid.org/packages/xyz.deepdaikon.xeonjia/)]

  <details>

  <summary>一个“滑冰”的探险游戏。</summary><br/>

  即在冰上行走不会停，这很大程度影响了角色的行走策略。没错，这又是像素风格的界面。

  </details>

#### 沙盒

- [Luanti](https://github.com/luanti-org/luanti)
  [[F-Droid](https://f-droid.org/packages/net.minetest.minetest/)]
  [[网站](https://www.luanti.org/)]

  <details>

  <summary>类似 Minecraft 的开源沙盘游戏，可玩性很高。</summary><br/>

  原名 Minetest。我没怎么玩过，应该添加一些模块，默认好像真的只有沙盘。

  </details>

#### 赛车

- [SuperTuxKart](https://github.com/supertuxkart/stk-code)
  [[F-Droid](https://f-droid.org/packages/org.supertuxkart.stk/)]
  [[网站](https://supertuxkart.net/Main_Page)]

  <details>

  <summary>大名鼎鼎的开源赛车游戏。</summary><br/>

  游戏画面是卡通风格，有很多的跑道、赛车和道具，多种游戏模式。是开源游戏里体量很大的了。适合休闲时玩一玩。

  </details>

- [Pixel Wheels](https://github.com/agateau/pixelwheels)
  [[F-Droid](https://f-droid.org/packages/com.agateau.tinywheels.android/)]
  [[网站](https://agateau.com/projects/pixelwheels/)]

  <details>

  <summary>顶部视角的赛车游戏，像素风格，游戏节奏快。</summary><br/>

  因为不是第一视角，感觉操作有点违反直觉，转弯程度不容易控制，但熟悉了之后还蛮好玩的。

  我[建议开发者](https://github.com/agateau/pixelwheels/pull/143)使用了文件很小的子集字体，并贡献了中文翻译，不用谢。

  </details>

#### 策略

- [UnCiv](https://github.com/yairm210/UnCiv)
  [[F-Droid](https://f-droid.org/packages/com.unciv.app/)]

  <details>

  <summary>简化的文明 5，有各种国家、职业、建筑，丰富的科技树。</summary><br/>

  作者是试图还原文明5的游戏功能的，界面则抽象化了，这也使得游戏体积很小。没玩过文明 5 的我表示入手很痛苦😅。

  </details>

#### 魔方

- [DCTimer](https://github.com/MeigenChou/DCTimer-Android)

  <details>

  <summary>这不是游戏，是魔方速拧计时软件。</summary><br/>

  功能相当丰富，生成打乱几乎支持所有比赛类别，还有数据分析等。网页端还有个 csTimer，都是开源的。

  </details>

### Lineage OS自带

- [Eleven](https://github.com/LineageOS/android_packages_apps_Eleven)

  Lineage OS 自带的音乐软件，基本功能都到位了，我就没有再用第三方音乐软件

- [DocumentsUI](https://github.com/LineageOS/android_packages_apps_DocumentsUI)

  <details>

  <summary>Lineage OS 自带文件管理器。界面非常质感设计，很好看。</summary><br/>

  功能少而精：整理不同类型的文件，比如会将所有含图片的子文件夹并排，将音乐按歌手-唱片分类（不需要手动建立文件夹），筛选大文件，等等。

  </details>

<details>

<summary>过时的内容</summary>

- _~~[Terminal](https://github.com/LineageOS/android_packages_apps_Terminal)~~_

  <details>

  _<summary>安卓自带终端，需在开发者选项中开启。已在 18.1 后被废弃。</summary>_

  这个终端很简单，几乎没有选项，就是单纯地执行命令。这不就是终端的功能吗？

  </details>

</details>

## 相似集合

以下一些集合也列举了很多安卓开源软件

- [推薦的好用開源 Android APP 中文列表](https://github.com/ivon852/awesome-foss-android-apps)

- [Android FOSS](https://github.com/offa/android-foss)

- [Cool FOSS Android Apps](https://github.com/albertomosconi/foss-apps)

- [Awesome Android Apps](https://github.com/Psyhackological/AAA) 

- _~~[Awesome Android Apps](https://github.com/LinuxCafeFederation/awesome-android)~~（已 404）_

## 版权

版权声明：本文为 [Lu Xu](https://github.com/xlucn) 原创，依据 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 许可证进行授权，转载请附上出处链接及本声明。

原文链接：https://github.com/xlucn/oh-my-foss-android

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=xlucn/oh-my-foss-android&type=Timeline)](https://star-history.com/#xlucn/oh-my-foss-android&Timeline)
