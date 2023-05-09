# cookie-law-plugin
声明:本插件来源https://github.com/ToX82/cookie-bar
更新:增加中文版cn
cookieBAR 是针对欧盟 cookie 法的免费且简单的解决方案。

为什么要使用 cookieBAR？
围绕新的欧盟 cookie 立法存在很多谜团和大惊小怪，但它本质上非常简单。Cookie 是用于跟踪网站活动的文件，大多数网站都使用它们。网站所有者需要让访问者清楚地看到 cookie 的使用。

Cookie 栏让访问者简单清楚地知道正在使用 cookie，并告诉他们如何在担心时调整浏览器设置。

长话短说
进入此页面，根据您的需要配置 cookiebar，并将生成的代码放在网页中的某个位置：

https://28apk.com/cookie-bar/#configuration

怎么运行的？
cookieBAR 是一个即插即用的纯 vanilla javascript 插件，不需要 jQuery 或任何其他依赖项。它在需要时显示，不需要时保持沉默：如果网站有 cookie 或某些本地存储数据集，则会显示该栏，否则什么也不会发生。

一旦用户单击Allow CookiescookieBAR 将为该域设置一个 cookie，其名称cookiebar将在 30 天后过期。这意味着该插件每月只会出现一次（此持续时间是可配置的）。

如果用户决定单击Disallow Cookies，cookieBAR 将简单地删除所有 cookie 和 localStorage 数据（并且将在第一次检测到 cookie 时再次显示）。

有了cookiebarcookie，开发人员可以在激活外部脚本（例如 Google Analytics 或其他任何东西）之前轻松检查用户的决定。有关详细信息，请参阅https://28apk.com/cookie-bar/ 。
