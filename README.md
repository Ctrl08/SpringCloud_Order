# 基于Spring Cloud的外卖订餐系统

#### 项目需求

客户端：针对普通⽤户，⽤户登录、⽤户退出、菜品订购、我的订单。 

后台管理系统：针对管理员，管理员登录、管理员退出、添加菜品、查询菜品、修改菜品、删除菜品、 订单处理、添加⽤户、查询⽤户、删除⽤户。

#### 微服务划分

- account 提供账户服务：⽤户和管理的登录退出。 
- menu 提供菜品服务：添加菜品、删除菜品、修改菜品、查询菜品。
- order 提供订单服务：添加订单、查询订单、删除订单、处理订单。
- user 提供⽤户服务：添加⽤户、查询⽤户、删除⽤户。

