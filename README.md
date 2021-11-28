# XSS-ATTACK-LAB
Cross Site Script.

攻击者可以利用这种漏洞在网站上注入恶意的客户端代码。

存储型（持久型）、反射型（非持久型）、DOM 型。

## 存储型 Stored XSS Attacks
注入型脚本永久存储在目标服务器上。当浏览器请求数据时，脚本从服务器传回并执行。

## 反射型 Reflected XSS Attacks
当用户点击一个恶意链接，或者提交一个表单，或者进入一个恶意网站时，注入脚本进入被攻击者的网站。




## DOM型 DOM-based XSS Attacks
通过修改原始的客户端代码，受害者浏览器的 DOM 环境改变，导致有效载荷的执行。


## 防御措施

### HttpOnly防止窃取Cookie
浏览器禁止页面的javascript访问带有httpOnly属性的Cookie.

### 输入检查
对用户输入进行检查、过滤和转义。


### 输出检查
对服务端的返回进行检查、过滤、转义。

