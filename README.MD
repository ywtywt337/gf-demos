#这是一个测试

# GoFrame Demos

This repo implements some demos using GoFrame.
1. A simple websocket chat service.
1. Basic API example for user SignUp/SignIn.
1. Universal CURD service.

## Installation

### 1. You should have a go development environment before everything takes off.
### 2. Use `git clone` cloing the repo to your local folder. 
`git clone https://github.com/gogf/gf-demos`

### 3. Run command `go run main.go`, and you'll see something as follows if success:
```
  SERVER  | DOMAIN  | ADDRESS | METHOD |        ROUTE        |                              HANDLER                              |           MIDDLEWARE             
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /chat               | github.com/gogf/gf-demos/app/api/chat.(*Controller).Index         | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /chat/index         | github.com/gogf/gf-demos/app/api/chat.(*Controller).Index         | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /chat/setname       | github.com/gogf/gf-demos/app/api/chat.(*Controller).SetName       | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /chat/websocket     | github.com/gogf/gf-demos/app/api/chat.(*Controller).WebSocket     | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /curd/:table/all    | github.com/gogf/gf-demos/app/api/curd.(*Controller).All           | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /curd/:table/delete | github.com/gogf/gf-demos/app/api/curd.(*Controller).Delete        | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /curd/:table/one    | github.com/gogf/gf-demos/app/api/curd.(*Controller).One           | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /curd/:table/save   | github.com/gogf/gf-demos/app/api/curd.(*Controller).Save          | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /curd/:table/update | github.com/gogf/gf-demos/app/api/curd.(*Controller).Update        | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /user/checknickname | github.com/gogf/gf-demos/app/api/user.(*Controller).CheckNickName | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /user/checkpassport | github.com/gogf/gf-demos/app/api/user.(*Controller).CheckPassport | middleware.CORS                  
|---------|---------|---------|--------|---------------------|-------------------------------------------------------------------|---------------------------------|
  default | default | :8199   | ALL    | /user/issignedin    | github.com/gogf/gf-demos/app/api/
