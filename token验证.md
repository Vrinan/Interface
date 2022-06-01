## WebService接口文档
​    
​    
### 1 接口名称  

ESS token验证接口

### 2 接口描述    

- ESS单点登录，传入token，返回用户名

### 3 请求地址  

`{apiAddress}/WebService/PMSService.asmx?op=Auth`  

### 4 请求方式  

**Post**  

### 5 请求参数  

#### 5.1 参数 
| 参数名    | 必选 | 类型   | 限制条件        | 说明     |
| --------- | ---- | ------ | --------------- | -------- |
| token  | 是   | string |  | token   |


### 6 返回示例
* 成功
```json
{"status":"2000","username":"ganwei","errmsg":""}
```
* 失败
```json
{"status":"500","username":"","errmsg":"过期"}
```

### 7 备注  


