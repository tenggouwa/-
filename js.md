## Javascript规范、
*****

1. **命名规范(驼峰命名)**
 + ***变量***.前缀是名词， 尽量体现属性。
 + ***函数***.前缀是动词，can/has/is/get/set/set/load。
 + ***常量***.名称全部大写，`MAX_COUNT`。
 + ***构造函数***.大驼峰命名。

2. **注释规范**
 + ***单行注释***. 单行注释以两个斜线开始，以行尾结束。 
 + ***多行注释***.  
 ```
/*
* 代码执行到这里后会调用setTitle()函数
* setTitle()：设置title的值
*/
  setTitle();
```
 + ***函数注释***
```
@param name {String} // 参数
@return {Boolean} // 返回值
@autorn {name} 2019/03/22
@version 1.0.23
@example 
```
