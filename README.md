###重复使用
###防止工具重复
###快速搜索
### 以TODO注释规范为基础
1. 对包的作用的描述形如：//标识：<packageUse>:描述内容，一个包只有一个
2. 针对不同的对象，如类，对象，方法，属性的注释可以表述形如：//标识 :<对象关键字>:<result>number|<param>number:描述内容
    - **标识**：TODO,FIXME,HACK,OPTIMIZE,NOTE
    - **<对象关键字>**:如<class>,<object>,<enum>,<fun>等，表示的注释对象是什么，便于以后过滤，
    - **<result>number|<param>number**:result表示要使用的，parma表示需要调节的，number为了对应的数字编号，必须全局记录，。

3. number[1,]
