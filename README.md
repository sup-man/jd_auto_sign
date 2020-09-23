# jd_auto_sign

每天 00:30 + 8 * n 自动签到

fork 仓库

浏览器登录 https://bean.m.jd.com 点击签到并且出现签到日历后,

(登录滑动验证码不好滑可以装一个 [京价保](https://jjb.im/) 的浏览器插件，登录之后卸载它)

按 `F12` 呼出开发人员工具

点击 `网络` 查看网络请求

按 `F5` 重新加载页面

找到第一条文件是 `signIndex.action` ，点击它，弹出的列表里找 `请求头` 中的 `Cookie`

复制冒号以后的内容到仓库的 setting 中的 Secrets ，新建一个 `JD_COOKIE`，内容是复制内容。

仓库的 Action 中开启 Action

触发签到的方法是 star 一下仓库，或者 commit 一次 master
