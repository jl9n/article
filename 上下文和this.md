# 上下文和this指针

> A this value is a special object which is related with the execution context. Therefore, it may be named as a context object (i.e. an object in which context the execution context is activated).

> this适合执行的上下文环境息息相关的一个特殊对象。因此，它也可以称为上下文对象\[context object\](激活执行上下文的上下文)。

this与变量不同，其实是对一个区域上下文环境的记录，他与变量不同的是

* 他不会有一个向上搜寻的过程
* 不能给this赋值