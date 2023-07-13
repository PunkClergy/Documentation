
|序号| 名称 |
|----| -|
| 1  | [NPM发包流程](#npm发包流程)|


## npm发包流程

1. 创建空文件夹(test)
2. 再git Bash中打开
3. 登录npm
```
npm login
```
4. 依次输入详细信息 [账号密码](https://github.com/PunkClergy/PrivateAccountPassword#npm%E8%B4%A6%E5%8F%B7)
```
Username ~ 用户名
Password ~ 密码
Email ~ 邮箱
one-time password ~ 邮箱验证码
...
```
5. 初始化代码库~首次发包需要执行
```
npm init
```
6. 依次输入包详细信息
```
pack name ~ 发布包名称
version ~ 版本号
description ~ 描述
entry point ~ 入口文件
...
```
7. 书写插件代码
8. 发布npm
```
npm publish
```
9. 错误代码
```
注: 400当前版本存在  
    401未登录  
    403当前包名称已经被占用
    409已经存在指向（重新执行npm config set registry=http://registry.npmjs.org）
```

