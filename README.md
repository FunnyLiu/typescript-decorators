# TypeScript decorator #


# 源码分析

基于reflect-metadata模块兼容Reflect相关API实现各种不同类型的装饰器

## 文件路径

``` bash
├── src
|  ├── class-decorator.ts - 类装饰器
|  ├── decorators.ts - 针对不同参数个数选不同的装饰器
|  ├── index.ts - 引用示例
|  ├── method-decorator.ts - 方法装饰器
|  ├── parameter-decorator.ts - 函数参数装饰器
|  └── property-decorator.ts - 属性装饰器
```

## 外部模块依赖

reflect-metadata，用于兼容Reflect相关API。



 This project helps to understand decorators and different kinds of decorators and its samples.

 To run this project
 1. Clone this git repository
 2. run npm start
 3. host the root directory via ```http-server``` [if you dont have http-server. Run this command ```npm i http-server --g```]