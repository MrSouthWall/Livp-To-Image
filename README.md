
## 预览

<p align="left">
  <img height="400" src="https://raw.githubusercontent.com/MrSouthWall/LivpToImage/refs/heads/main/README-Assets/PreviewImage.png">
</p>

## 简介
.livp 文件是苹果 iPhone 拍摄的 live 图格式，当我们解压缩 .livp，可以发现 .livp 文件实际上是由一个 jpeg / heic 和 mov 组成的，本工具就是帮您简单快捷地将 .livp 文件中的 jpeg / heic 提取出来。

## 故事
制作这个工具的起因，是女友在工作中有这方面的需求，需要批量从 .livp 文件中提取 jpeg。这是一个很小众的需求，在互联网上并没有找到合适的解决方案，在 GitHub 上也只有通过命令行执行的方案，这对于一个不擅长代码的女孩子略显得有些复杂了。

同时我是一名苹果开发者，而她在工作中使用 PC，我对于 PC 端的软件开发并不了解。于是，在考虑了多种方式后，我想到可以利用 HTML 技术来实现这一需求。

我对 HTML 的了解也知之甚少，于是求助于 ChatGPT，在与 ChatGPT 历经几轮「赛博对线」后，这个简单的小工具就诞生了。

> [!NOTE]
> **本工具 99% 的代码都由 ChatGPT 编写。**

## 使用方法
- 前往 [LivpToJpeg 工具](https://mrsouthwall.github.io/LivpToImage/ "点击前往 LivpToImage 工具") 网页即可使用；
- 下载本仓库的文件到本地，使用任意浏览器打开 `index.html` 文件即可；

拖拽 .livp 文件到方框内，网页会自动进行提取，稍等片刻，就会显示缩略图。您可以通过「点击缩略图」进行单个图片的下载，也可点击「下载全部图片」按钮进行批量下载。

## 注意
由于代码是本地运行的，所以通过以上两种不同的方式打开网页，「拖拽文件至网页」和「下载文件至本地」的操作都**不会消耗流量**，也**不会上传**您的图片至云端服务器，确保**不会侵犯您的隐私**，如您仍感到不放心，可以断网使用本工具，或检查源码确认安全。
