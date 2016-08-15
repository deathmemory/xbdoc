# 接口说明
api 基地址：http://www.xbjsq.com

###返回内容获取JQuery
selector: body > table > tbody > tr:nth-child(2) > td > div > b

###手机验证码接口（注册）
| key        |  default value |  Description |
| ------------- |-------------|-------------|
| enews | Rzsj | 认证手机 |
| phone | 185xxxx1953 | 手机号 |

###手机验证码接口（取回密码）
| key        |  default value |  Description |
| ------------- |-------------|-------------|
| enews | Rzsjq | 认证手机取回 |
| phone | 185xxxx1953 | 手机号 |

###注册接口
| 说明        |  value | 
| ------------- |-------------|
| Method     |  POST  |
| URL     |  /e/member/doaction.php  |
| 验证码获取地址 | /e/ShowKey/?v=reg |

请求参数

| key        | default value           | Description  |
| ------------- |:-------------:| -----:|
| username     |  - | 用户名 |
| password      |  - | 密码 |
| repassword     | -  | 确认密码 |
| email      | - | email |
| key     | - | 验证码 |
| enews      | register | 固定值 |
| groupid      | 5 | 固定值 |
| tobind      | 0 | 固定值 |

###登录接口
| 说明        |  value | 
| ------------- |-------------|
| Method     |  POST  |
| URL     |  /e/member/doaction.php  |
| 验证码获取地址 | e/ShowKey/?v=login&t=`<random>` |

请求参数

| key        | default value           | Description  |
| ------------- |:-------------:| -----:|
| username     |  - | 用户名 |
| password      |  - | 密码 |
| key     | - | 验证码 |
| lifetime      | 0 | cookie 保存时效 |
| enews      | login | 固定值 |
| tobind      | 0 | 固定值 |

###退出接口
默认带 Cookie 请求

| 说明        |  value | 
| ------------- |-------------|
| Method     |  GET  |
| URL     |  /e/member/doaction.php?enews=exit  |
