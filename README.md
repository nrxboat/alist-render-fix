# alist-render-fix
修复了alist在render上无法部署的问题

### How to use
fork本项目后先修改自己fork项目的config.json，将自己的数据库信息填进去,然后在render中创建web service，选择自己fork的项目

### database
You may need to use another remote MySQL database as instance restarts will lose data.
Recommended Free MySQL Databases:
- https://db4free.net/
- https://remotemysql.com/
- https://www.freesqldatabase.com/

### password
The initial password is randomly generated, and you can get it by checking the `logs`.
初始密码请在logs中查看
