# jd_auto_sign

访问 [https://www.jd.com/](https://www.jd.com/)

按 `F12`

点击 `网络`

按 `F5`

找到第一条 文件是 `/` ，点击它，弹出的列表里找 `请求头` 中的 `Cookie`

复制冒号以后的内容到仓库的 setting 中的 Secrets ，新建一个 `JD_COOKIE`，内容是复制内容。

仓库的 Action 中开启 Action