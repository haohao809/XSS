## Web安全之模拟XSS攻击
**理解XSS的攻击方式**
- 反射型
> 发出请求是,XSS代码出现在URL中,作为输入提交到服务器端,服务器端解析后响应,XSS代码随着响应内容一起传回浏览器,最后浏览器解析执行XSS代码。这个过程像一次反射,故叫做反射型XSS。
- 存储型
> 存储型XSS和反射型XSS的差别在于,提交的代码会存储在服务器中(例如数据库,内存,文件系统等),下次请求页面是不用再提交XSS代码。

window平台 项目构建
1.安装express
npm install -g express-generator@4
2.执行express 模板ejs
express -e ./
3.安装
npm install
