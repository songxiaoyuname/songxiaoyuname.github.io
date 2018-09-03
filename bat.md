#### 使用npm启动
```
@echo off 
d:
cd demo\xy-cloth\xy-front

call npm run local
cmd /k      使得cmd窗口不关闭，停留在当前路径
```
> call执行完，窗口就关闭了


#### 使用gulp启动
```
@echo off 
d:
cd webApp\5.0

start cmd /k "gulp"
```
