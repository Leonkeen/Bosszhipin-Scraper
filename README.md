# Boss直聘爬虫，可爬取聊天界面下的Boss直聘公司信息。
Boss直聘手机上聊天,所以想着在电脑上爬取下公司的详细信息和地址等.
可以随意修改不合适的地方, 目前是v1的稳定性比较好, 就是爬取的比较少, 大概就是爬取前20个左右, 就歇菜了. v2的版本可以爬取到20多个, 但是我自己爬取的时候会出现一些奇奇怪怪的问题,比如, 弹出验证码, 或者是握手包之类的问题, :ssl_client_socket_impl.cc(978)] handshake failed; returned -1, SSL error code 1, net_error -100, 不过问题不大, 就是抓取的数据有点少, 有点难受.
算是有点苦手吧, 但是磕磕碰碰的算是下载好了.
![爬取结果preview](https://github.com/Leonkeen/Boss-/assets/51162998/14574e3f-d812-456c-aaa2-40896e1eff83)
右边是..敏感的信息岗位薪资等,我就没截图了.
需要的插件 requirement
selenium
pandas
csv
需要特别注意版本号,chromedriver是真的有点小坑.
像我用的就得是 pip install selenium==4.1
然后chromedriver我用的是配合chrome版本114的.
