使用npm install -g json-serve安装服务器

使用npm run json:server:remote启动服务器

//获取所有用户信息
http://localhost:3000/users

//获取所有用户id为1的信息
http://localhost:3000/users/1
http://localhost:3000/users/?id=1

//获取用户信息id按顺序排列 asc升序 desc降序
http://localhost:3000/users?_sort=id&_order=desc

//获取用户id大于1的前两条数据
http://localhost:3000/users/?id>1&_limit=2
