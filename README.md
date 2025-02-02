# danmuG
[![Pages](https://github.com/Dark-Sword-22/danmuG/actions/workflows/python-pages.yml/badge.svg)](https://github.com/Dark-Sword-22/danmuG/actions/workflows/python-pages.yml)
![Visits](https://visitor-badge.glitch.me/badge?page_id=darksword22.danmuG&left_color=red&right_color=green&left_text=Dark%20Sword)

秦川弹幕机器人 

[https://dark-sword-22.github.io](https://dark-sword-22.github.io)

## 功能说明
大概是被设计为运行在一个服务器上，持续监视直播间，发现直播立马记录弹幕，的这么一个东西。如果你是开发人员，请查看[这里](https://github.com/Dark-Sword-22/danmuG/blob/main/misc/%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3.md)。

### 我们做了什么

- 目前直播间已经被监视，所有偷偷开播都会在最慢5秒内被发现，并开始记录弹幕。
- 下播后会自动上传当日高能时刻分析，希望有帮助到切片好哥哥。
- 作为副产物，我们也许可以将弹幕重投至录播以提高其观看体验，目前缺人。
- 另外作为对轴工具的副产物，你可以使用[这里](https://github.com/Dark-Sword-22/danmuG/tree/main/mkm)的工具下载直播流。

### 目前的困难
1. ~~截取弹幕需要好哥哥。为了获取完整弹幕，理想状态是运行一台7\*24小时运行的服务器持续监视直播间。但是试着在VPS上跑了一下，发现cc网页版对于VPS来说还是太吃性能了，已经爆炸。
目前看来还是只能在普通的个人电脑（台式/笔记本）上运行监视程序，需要有闲老哥贡献算力和带宽。~~ 经由好哥哥指路，目前弹幕获取已经可以在服务器上全自动托管。
2. 重投弹幕需要好哥哥。为避免触发B站拦截墙，弹幕投稿速度设置的很慢。根据小学数学计算，以目前速度大约每24小时可以投完1P的弹幕，如果敬业先锋天天播，那么每天的视频只有1P在+24h后有弹幕。如果要实现视频投稿8小时内弹幕全覆盖的话，需要好哥哥15人。

### 如何贡献？
遵循以下步骤

1. 作为投弹工具人，需要有B站账号，以及一台电脑，或一台服务器，手机不行。
2. 到[这个链接](https://github.com/Dark-Sword-22/danmuG/releases/latest)下载工具，并按照[操作说明](https://github.com/Dark-Sword-22/danmuG/tree/main/thunder)即可成为好哥哥。
3. 目前工具已经打包，不需要投稿者自己提供任何运行环境。

*- 另外招募一位协同管理，主要工作是更新新视频的对轴。并不花时间，但是需要关注秦川视频投稿动态，有意请发ISSUE -*

### Upd

- 21.12.04 更新重投协调服务器。
- 21.12.01 更新弹幕获取的模拟登陆版本。
- 21.11.30 更新了自然语言处理的算法，现在tag应该能更合理地表示该时刻发生的事件。
                
                                      
     