# Rule template for [SpechtLite](https://github.com/zhuhaow/SpechtLite)

## fork from [DomYY/SpechtLite.Config](https://github.com/DomYY/SpechtLite.Config)

## 各规则根据本人喜好进行调整。
注：由于 `mail.app` 🔗 `outlook` 邮箱的请求的 **URL** 直连很不稳定，有时直接断流，而使用 **speed** 规则会导致登陆 **IP** 多变，触发异常报告，所以我在 `yaml` 文件 `proxy` 规则之前 添加：
```
- type: list
  file: ~/.SpechtLite/one
  adapter: adapter1
```
同时在 `~/.SpechtLite/` 下创建名为  `one` 的文件，在其中加入需要进行代理处理，却需要稳定节点 **IP** 的网络请求 **URL**。

---
这里在谈下 `SpechtLite` 的一个实用功能： <kbd>Allow Clients From Lan</kbd>

应用场景：同处与一个局域网下的其他设备，不需要安装软件，通过您的 `SpechtLite` 进行科学上网。
使用方法：

1. 在 `SpechtLite` 勾选 <kbd>Allow Clients From Lan</kbd>；
2. 需要科学上网的同一局域网下设备，设置 `HTTP 代理`：
  - `iPhone` 点击所链接网络详情，在下面的 `HTTP 代理` 选择手动。
  - `windows` 在 `Internet 选项` 选择 `局域网设置`，勾选 `代理服务器`。
  - `Andriod` 没研究过。。。
3. 地址／服务器 写 `SpechtLite` 所在的 `Mac` 的 **局域网地址**，端口 写 `yaml` 配置文件第一行 `port:` 后所跟的参数，默认是 `9090`。


---


关于如何配置 `SpechtLite` 请参考：[SpechtLite简单使用说明](http://chengluffy.tech/2016/11/29/SpechtLite简单使用说明/)
