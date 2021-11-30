# danmuG
[![Pages](https://github.com/Dark-Sword-22/danmuG/actions/workflows/python-pages.yml/badge.svg)](https://github.com/Dark-Sword-22/danmuG/actions/workflows/python-pages.yml)

秦川弹幕机器人

## 功能说明
大概是被设计为运行在一个服务器上，持续监视直播间，发现直播立马记录弹幕。而后将弹幕上传至录播，希望录播也能有直播间的欢乐。同时希望以原生弹幕解决直播录屏降低画质的问题。

### 目前的困难
1. 截取弹幕需要好哥哥。为了获取完整弹幕，理想状态是运行一台7\*24小时运行的服务器持续监视直播间。
但是试着在VPS上跑了一下，发现cc网页版对于VPS来说还是太吃性能了，已经爆炸。
目前看来还是只能在普通的个人电脑（台式/笔记本）上运行监视程序。
脚本是启动后完全无人值守的，需要有闲老哥贡献算力和带宽，因为作者本人电脑上经常要跑各种奇怪的计算和渲染任务，无法持续稳定地运行某一单一脚本。
2. 重投弹幕需要好哥哥。为避免触发B站拦截墙，弹幕投稿速度设置的很慢。目前速度大约每24小时可以投完1P的弹幕，需要人手。

### 如何贡献？
遵循以下步骤

1. 发送ISSUE申请本仓库权限
2. 安装Python并遵循requirements.txt安装依赖
3. 确保git已经安装且可以正常使用
4. 确保你使用Chrome浏览器并下载了对应版本的chromedriver
5. 在本地执行`python danmu.py`即可
6. 如果你想帮忙投稿弹幕的话请直接发ISSUE
