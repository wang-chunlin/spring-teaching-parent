# 基础
实现HandlerInterceptor
接口3个方法的含义理解
注册拦截器:mvc:interceptors

## 静态资源排除设置

# Filter与Interceptor
 相同点:
 1.执行原理类似,都是环绕的执行方式
 2.都是用来进行全局的一些处理,不用把代码写到
 每一个处理者里面
 3.都可以认为是一个切面类
 
 不同点:
 1.拦截器是被spring管理的,所以可以注入一些东西
 2.拦截器可以设置排除一些路径,而且支持ant格式的模式地址
 
 
