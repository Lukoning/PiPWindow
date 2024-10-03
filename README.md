# PiPWindow

一个纯JavaScript实现的歌曲信息小窗

灵感来源：网易云Web端的歌词小窗。使用了与其相似的方法实现

![preview.png](https://github.com/Lukoning/PiPWindow/blob/dist/preview.png)

### <a href="https://github.com/Lukoning/PiPWindow/releases">更新日志在RELEASES, HERE PLEASE -></a>

<p>❤️点击歌曲红心旁按钮或⚙️设置页按钮打开小窗</p>
<p>↔ 可拖动，可调整大小</p>
<p>🐀鼠标上移显示关闭和返回按钮</p>
<p>↗点击返回按钮会关闭小窗，并回到主窗口</p>
<p>x 点击关闭按钮也会关闭小窗，但不会回到主窗口</p>
<p>M 配合Material You主题食用，效果更佳</p>
<br />
<p>请注意：</p>
<p>目前本插件多行歌词功能依赖</p>
<p>RefinedNowPlaying 和 LyricBar</p>
<p>如要显示多行歌词</p>
<p>请先打开 RefinedNowPlaying 的播放界面</p>
<p>或安装 LyricBar （二选一）</p>
<br />
<p>也可以选择不安装上述插件、不打开播放界面</p>
<p>词源将改为网易云自带的软件内词栏（只有一行）</p>
<br />
<p>如不喜欢 LyricBar，可以：</p>
<p>1.下载 LyricBarBlur</p>
<p>2.在 LyricBarBlur 内找到如下设置：</p>
<p> - 背景模糊半径 背景不透明度 文本不透明度 边框宽度 阴影不透明度</p>
<p>3.将以上设置全部设为0，LyricBar 看起来应该完全消失了</p>
<br />
<p>如需使用 类苹果歌词(与 RefinedNowPlaying "冲突")，可以：</p>
<p>1.下载 类苹果歌词</p>
<p>2.点击上方 打开插件文件夹 按钮</p>
<p>3.双击 plugins 文件夹，然后找到 Apple-Musiclike 开头的文件</p>
<p>4.长按这个文件，将其拖到上方的 betterncm 处</p>
<p>5.回到网易云，点击 重启并重载插件</p>
<p>6.在插件市场下载 LyricBar</p>
<p>7.先别着急重载，再次点击上方 打开插件文件夹 按钮</p>
<p>8.找到刚拖过的 Apple-Musiclike 开头的文件</p>
<p>9.将其拖到 plugins 文件夹上</p>
<p>10.回到网易云，再次点击 重启并重载插件</p>
<br />
<p>？ 类苹果歌词和 RefinedNowPlaying 不是互相冲突的吗，为什么可以这样做</p>
<p>->实践证明，因为两者实现方式有别，并不会造成实际冲突。安装了类苹果歌词后，可以在打开播放界面的同时，按住Shift键，来打开 RefinedNowPlaying 的播放界面；安装 ←→0123456789JL+-,.↑↓FO 插件后，也可以通过按 F 来打开。</p>
<br />
<p>已知问题：</p>
<p>1.没法在这个窗口上暂停、切换上下曲、调音量</p>
<p>2.没法修改歌词左中右对齐</p>
<p>3.可以调整窗口大小，但没法调整窗口比例</p>
<p>4.文本超出窗口后不会自动滚动</p>
<p>5.没有逐字歌词</p>
