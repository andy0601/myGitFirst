## 迭代五接口说明文档



### 1.数据库检查接口

##### 1）查询接口

接口地址：/dbc?group_id=0 &_page=1&_limit=20

请求方法：GET

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
null
```

成功返回：

```json
{
    "data":
    {"page": 1,
     "tb_data": [
     {
     "dbc_id": "ID", 
     "adddate": "2018-09-25 16:40:02", 
     "dbc_desc": "描述", 
     "dbc_type": "执行类型", 
     "dbc_sql": "执行SQL",
      "group_id": "999", 
      "dbc_status": "状态"
       },
       {
     "dbc_id": "ID", 
     "adddate": "2018-09-25 16:40:02", 
     "dbc_desc": "描述", 
     "dbc_type": "执行类型", 
     "dbc_sql": "执行SQL",
      "group_id": "999", 
      "dbc_status": "状态"
       }
      ],
      "total": 2, 
      "group_id": 0, 
      "pages": 1}, 
      "code": 200, 
      "message": "操作成功!"
      }


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```
##### 2）明细接口

接口地址：/dbc/DBC_00001(dbcID)

请求方法：GET

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
null
```

成功返回：

```json
{
    "data":   
     {
     "dbc_id": "ID", 
     "adddate": "2018-09-25 16:40:02", 
     "dbc_desc": "描述", 
     "dbc_type": "执行类型", 
     "dbc_sql": "执行SQL",
      "group_id": "999", 
      "dbc_status": "状态"
       },
      "code": 200, 
      "message": "操作成功!"
      }


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```

##### 3）新增

接口地址：/dbc

请求方法：POST

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
  {
     "dbc_desc": "描述", 
     "dbc_type": "执行类型", 
     "dbc_sql": "执行SQL",
      "group_id": "", 
      "dbc_status": "状态"
       }
```

成功返回：

```json
{
    "code":200,
    "data":"",
    "message":"新增成功"
}


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```

##### 4）删除

接口地址：/dbc/DBC_00001(dbcID)

请求方法：POST

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
null
```

成功返回：

```json
{
    "code":200,
    "data":"",
    "message":"删除成功"
}


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```
##### 4）修改

接口地址：/dbc

请求方法：PATCH

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
 {
     "dbc_desc": "描述", 
     "dbc_type": "执行类型", 
     "dbc_sql": "执行SQL",
      "dbc_status": "状态",
      "group_id":""
       }
```

成功返回：

```json
{
    "code":200,
    "data":"",
    "message":"删除成功"
}


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```
##### 5）执行

接口地址：/dbc/exe

请求方法：POST

请求头：

```json
{
"Token":"密钥YYYY"
}
```

请求参数：

```json
 {

     "dbc_sql": "执行SQL",
     "dbc_env_id":"数据库环境ID"

       }
```

成功返回：

```json
{
    "code":200,
    "data":[
    {
    "数据库数据":"数据库数据"
    }
    ],
    "message":""
}


```

异常返回：

```json
{
    "code":"401-异常",
    "data":"",
    "message":"异常信息！～"
}
```