## PanLi Host - Chrome Extension

>通过该 Chrome 扩展，快捷方便的切换、设置 host 代理规则，而不用修改系统 hosts 文件，方便web开发人员在 各种/测试/开发/线上 环境快速切换

可以尝试使用 百度浏览器或者360之类的支持 Chrome 扩展的浏览器：
360 浏览器/百度浏览器等其他支持 Chrome 扩展的浏览器，[下载 crx 文件](./down/PLS-host.crx)，转至浏览器扩展程序管理界面，
将下载的 crx 文件拖拽至该页面中释放，即可根据提示安装使用。

批量添加规则（IP:端口、域名、tag、备注分别用空格隔开；多个 tag 用英文逗号隔开）：

```
#IP:端口 域名 tag 备注
127.0.0.1:8888 www.nnn.com prod Fiddler
127.0.0.1 *.zanjs.com
192.168.1.2 www.zanjs.com
```



## 起缘

>在程序开发过程中，难免开发、测试、生产环境各种切换，一般我们直接修改系统的 hosts 文件。

好了，能否有一个工具管理方便，又快捷简单呢？


由于最近忙，没有详细测试完善，任何疑问，建议，欢迎[提交 Issues](https://github.com/Riant/host-switch-plus/issues).




