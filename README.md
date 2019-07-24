# 前端知识点汇总

### ES6

> 列举常用es6特性：
- ①　申明变量let和const
- ②　可在传递参数除指定默认值
- ③　箭头函数写法更加简洁，省略了function关键字申明，省略return
- ④　模板字符串
- ⑤　Promise链式调用
- ⑥　增加了class关键字来定义声明一个类，还多了extends继承关键字
- ⑦　export导出模块、import导入模块
- ⑧　解构赋值 [react-redux]() 状态管理库;用redux-logger打印日志，方便调试;用redux-thunk实现异步操作
> let, const, var 的区别
- ①　var声明的变量会挂载在window上，而let和const声明的变量不会
- ②　var声明变量存在变量提升，let和const不存在变量提升
- ③　let和const声明形成块作用域
- ④　同一作用域下let和const不能声明同名变量，而var可以
>es6箭头函数的this
- 箭头函数的this是在定义函数时绑定的，不是在执行过程中绑定的。简单的说，函数在定义时，this就继承了定义函数的对象

### 路由

