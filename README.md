# vscode-transparent-glow
transparent vscode css

> Original link [https://jinkey.ai/post/tech/ru-he-pei-zhi-tou-ming-fa-guang-de-sao-qi-vscode](https://jinkey.ai/post /tech/ru-he-pei-zhi-tou-ming-fa-guang-de-sao-qi-vscode)
Please indicate the source

> Exchange QQ group 706964206

Latest support for vscode 1.36 version

# 1 Install custom JS and CSS plugins
![Plugin screenshot](https://upload-images.jianshu.io/upload_images/854231-b2e5e95d9c7571a2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 2 Install glow theme
![Plugin screenshot](https://upload-images.jianshu.io/upload_images/854231-01920da488773df2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


# 3 Add style configuration file
In the VSCode installation directory (you can choose a folder at will), put the following files.
For the convenience of downloading, the files are organized into [Github-Jinkeycode](https://github.com/Jinkeycode)/[vscode-transparent-glow](https://github.com/Jinkeycode/vscode-transparent-glow), welcome star.


`enable-electron-vibrancy.js`
Open electron transparent support
![](https://upload-images.jianshu.io/upload_images/854231-bd77f033703fcede.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`vscode-vibrancy-style.css`
Here use the style provided by [@孤狼](https://blog.evolify.cn/)
![](https://upload-images.jianshu.io/upload_images/854231-fcefef968258caf0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`synthwave84.css`
Text glow style, please get the style on Github. If you want to not shine, you can use `synthwave84-noglow.css`. You can watch [https://github.com/robb0wen/synthwave-vscode](https://github.com/robb0wen/synthwave-vscode) to keep updated notifications.

`toolbar.css`
After introducing the above style configuration of the Great God, some of the titles in the left navigation bar are still not transparent. I modified the configuration myself and can import it.
![](https://upload-images.jianshu.io/upload_images/854231-448a8c07397595fd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`terminal.css`
Make the built-in terminal of vscode transparent
![](http://upload-images.jianshu.io/upload_images/854231-4e961151a1a22352?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

Modify the color of the terminal cursor, provided by [@manonloki](www.manonloki.com)
```
.panel.integrated-terminal .xterm-cursor,
.xterm-cursor-block {
  background: rgb(210, 0, 252) !important;
}
```

# 4 Modify VSCode configuration file
![](https://upload-images.jianshu.io/upload_images/854231-fbd4da9e499e6c4b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
Click on the figure above `Edit in setting.json`, open it and add the configuration (**No braces**, just add the key-value to the original json):
![setting.json](http://upload-images.jianshu.io/upload_images/854231-50272ef5974e1d00?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 5 reload
Press Ctrl + Shift + P, run "Reload Custom CSS and JS", and restart vscode. If it says `VSCode is damaged`, just select the gear "Don't prompt again" in the upper right corner.

#6 summary
The effect of the finished product is shown in the figure. If you don’t understand, you can add a small assistant WeChat udujjb to pull you into the group and ask
![](https://upload-images.jianshu.io/upload_images/854231-203ae82f1544bf0f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

The above tutorial is based on MacOS. For Linux users, please refer to how to turn on transparency; Windows electron does not support vibrancy mode, you can use the plug-in [GlassIt-VSC](https://marketplace.visualstudio.com/items?itemName=s-nlf -fh.glassit) Set transparency.

[Custom CSS and JS Loader configuration](https://github.com/be5invis/vscode-custom-css#getting-started)

[Linux Transparent Window](https://github.com/sergei-dyshel/vscode/blob/master/README.fork.md)
