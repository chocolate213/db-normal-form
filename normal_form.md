# 数据库范式（Normal Form）
## 第一范式(First Normal Form)
 设定一个关系为R(U)，若U中的每一个属都是不可再分的，或者说都是不被其他属性所包含的独立属性，则称关系R(U)是符合第一范式的（first normal form），第二范式又称1NF。
## 第二范式(Second Normal Form)
  设定一个关系为R(U)，它是满足第一范式的，若R不存在非主属性对候选码的部分函数依赖，则称该关系是符合第二范式（second normal form）的，第二范式又称2NF。
## 第三范式(Third Normal Form)
  设定一个关系为R(U)，它是满足第一范式的，若R中不存在非主属性对候选码的传递函数依赖，则称该关系是符合第三范式（third normal form）的，第三范式又称3NF。
## BC范式(Boyce-Codd Normal form)
  设定一个关系为R(U)，它是满足第一范式的，若R中不存在任何属性对候选码的传递函数依赖，则称R是符合BC范式的。
