#Simple Proxy


##How to use

- 0) Simple Proxy will not override proxy settings of Firefox 
- 1) Supports file extension with alphabet only
  - 1.1) Full compatibility with Auto-proxy Rulelist (branch 1.x)
- 2) Server must match the form of server protocol::server adress::server port
  - 2.1) For example, <font color="blue">socks::127.0.0.1::1080</font>
  - 2.2) Supported protocol: http, socks, socks4
    - 2.2.1) http support both HTTP and HTTPS protocol
    - 2.2.2) socks support SOCKS V5 protocol
    - 2.2.3) socks4 support SOCKS V4 protocol
- 3) Use remote address http:// or https:// to subscribe proxy list, compatible with base64 encoding
  - 3.1) For example, <font color=blue>https://github.com/gfwlist/gfwlist/raw/master/gfwlist.txt</font>
  - 3.2) Subscription(s) will be updated in 4 days
- 4) You can address absolute path using "Browse..." button in about:addons
- 5) You can address relative path using <font color=blue>file.txt@profile</font> to access the rulelist in Profile\SimpleProxy\file.txt
  - 5.1) profile stands for Profile\SimpleProxy\
  - 5.2) firefox stands for Mozilla Firefox\browser\SimpleProxy\
  - 5.3) winuser stands for %UserProfile%\SimpleProxy\
- 6) You can modify your rules by click "Edit Rulelist **"
  - 6.1) You need to click "save" before you close the "editor" if any modification has been done
  - 6.2) Subscriptions can not be modified
- 7) You can clear the profile which is no longer in use by press "Clear Profile **"

==

## 使用说明

- 0） Simple Proxy 不会覆盖 Firefox 本身的代理设置
- 1） 仅支持以字母作为文件后缀
  - 1.1） 完全兼容 Auto-proxy 规则列表 （仅限 1.x 分支）
- 2) 服务器必须满足 类型::地址::端口 的格式
  - 2.1) 例如 socks::127.0.0.1::1080
  - 2.2) 支持的协议类型 http, socks, socks4
    - 2.2.1) http 支持 HTTP 及 HTTPS 协议
    - 2.2.2) socks 支持 SOCKS V5 协议
    - 2.2.3) socks4 支持 SOCKS V4 协议
- 3） 可以通过添加 http:// 或 https:// 远程连接来订阅远程规则，支持base64编码的文件
  - 3.1） 例如 https://github.com/gfwlist/gfwlist/raw/master/gfwlist.txt
  - 3.2） 订阅规则每4天自动更新一次
- 4） 可以通过 about:addons 设置界面的 “浏览...” 按钮来指定绝对路径中的文件
- 5） 可以通过 file.txt@profile 这样的格式来访问相对路径 Profile\SimpleProxy\file.txt 中的规则
  - 5.1) profile 代表 Profile\SimpleProxy\
  - 5.2) firefox 代表 Mozilla Firefox\browser\SimpleProxy\
  - 5.3) winuser 代表 %UserProfile%\SimpleProxy\
- 6) 可以通过点击 编辑规则** 来修改你的规则
  - 6.1) 如果你有修改规则，你需要先点击 保存 按钮，然后再关闭 编辑器 窗口
  - 6.2) 订阅规则无法被修改
- 7） 你可以通过点击 清除档案** 来清理掉不再使用的档案
