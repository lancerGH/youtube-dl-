# youtube-dl新手使用手册
youtube-dl插件的使用教程，上手就能用这种，详细的文档必须还看官方文档。

## 1、安装
下载安装包，然后放入某个位置，在环境变量中添加此位置，ok。
## 2、使用
运行cmd，在命令行中输入相关指令。
## 3、运行指令
```youtube-dl https://www.youtube.com/watch?v=6DcwjCCRnT4```    
直接从网址上下载视频，在youtube上，视频和音频一般是分开的，需要单独下载。    
![youtube-dl run in command line](/image/youtube-dl%20001.PNG)    

```
youtube-dl --list-formats https://www.youtube.com/watch?v=RtU8nBnpFVE
youtube-dl -F https://www.youtube.com/watch?v=RtU8nBnpFVE
```    
列出网址上对应的所有可以下载的视频格式    
<img src="/image/youtube-dl--list-formats.PNG" height="80%" width = "80%" />
