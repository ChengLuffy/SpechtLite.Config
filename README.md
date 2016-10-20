# Rule template for [SpechtLite](https://github.com/zhuhaow/SpechtLite)
## Copy from **[逗bi极客](http://www.yeshigeek.com/forum.php)**

## fork from [DomYY/SpechtLite.Config](https://github.com/DomYY/SpechtLite.Config)

## 各规则根据本人喜好进行调整。


这里在谈下 `SpechtLite` 的一个实用功能： <kbd>Allow Clients From Lan</kbd>

应用场景：同处与一个局域网下的其他设备，不需要安装软件，通过您的 `SpechtLite` 进行科学上网。
使用方法：
1. 在 `SpechtLite` 勾选 <kbd>Allow Clients From Lan</kbd>；
2. 需要科学上网的同一局域网下设备，设置 `HTTP 代理`：
  - `iPhone` 点击所链接网络详情，在下面的 `HTTP 代理` 选择手动。
  - `windows` 在 `Internet 选项` 选择 `局域网设置`，勾选 `代理服务器`。
  - `Andriod` 没研究过。。。
3. 地址／服务器 写 `SpechtLite` 所在的 `Mac` 的 **局域网地址**，端口 写 `yaml` 配置文件第一行 `port:` 后所跟的参数，默认是 `9090`。
