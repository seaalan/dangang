# dangang
运动活力健康，单杠(dangang)拉起来

# 无后端设计
数据服务采用[野狗](https://www.wilddog.com)提供的BaaS服务

# 主要功能
* 记录每天的拉单杠记录

# 页面模块设计
* 新增用户
* 添加记录
  * 下拉框选择用户
  * 填写数据记录

# 数据结构

参与的用户

```
member: {
    id: 'M1010101010',
    name: 'tom',
    birthYear: '1985',
    birthMonth: 'xx',
    gender: 'man'
}
```

运动数据记录

```
record: 
{
    memberID: 'M1010101010',
    date: '20160215',
    score: '8'
}
```
