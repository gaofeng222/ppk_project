# 同源策略

> www.quirksmode.org 和  search.quirksmode.org 是两个不同的子域名

> www.quirksmode.org 打开  search.quirksmode.org 一个页面，同源策略限制，是打不开的

> 解决方法 : 给这两个窗口设置 window.domain = "quirksmode.org";

> 这样这两个页面都会认为自己是来自quirksmode.org的页面，因此www 和search能通信了