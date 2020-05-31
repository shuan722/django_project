1. http传输是无状态的,在项目开发中多采用token的方式进行记录.
    其中MyJWT.py文件主要记录基于JWT规范生成token,解析验证token,
    以及优化token

2. CORS(跨域资源共享),允许浏览器向跨源服务器发送请求,从而克服ajax
    只能同源使用的限制
    Django配置注意事项:
        首先,安装django-cors-headers时注意采用离线安装,在线pip安装
        可能导致django自动升级
        其次,安装完django-cors-heaers验证是否安装完成,特别强调同时
        也要查看django版本问题.防止因版本冲突产生不可控错误或风险.
