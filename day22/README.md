## number方法操作

+ 数值转换
    - Number()

    - parseInt()
    - parseFloat()
+ 正则表达式
+ if语句
+ for语句

## string方法操作
> String类型是字符串的对象包装类型，可以向下面这样使用String构造函数来创造。
    var strObj = new String("hello world");
+ 属性
    - length:返回字符串数量。
+ 方法
    1. 字符方法
        + charAt(),返回以但字符字符串的形式返回给定位置的那个字符。
            strObj.charAt(1); //'e'
        + charCodeAt(),返回给定位置的字符编码。
            strObj.charAt(1); //'101'
        + 使用方括号也可以访问，但是IE7以下不支持
            strObj[1];  //'e' 
    2. 字符串操作方法
        + concat(),用于将一个或多个字符串拼接起来，可以接受任意多个参数。但是实践中用的更多的是+操作符。
            var result = strObj.concat('world','!'); //'hello worldworld!';
            strObj //'hello world';  
        + slice(),返回被操作字符串的一个子字符串，接受一或两个参数。第一个参数指定子字符串的开始位置，第二个参数表示子字符串到哪里结束。第二个参数指定的是子字符串最后一个字符后面的位置。
        + substr(),第二个参数指定的则是返回的字符个数。
        + substring(),同slice()
    3. 字符串操作方法
        + indexOf()
        + lastIndexOf()
    4. trim()方法
    5. 字符串大小写转换方法
        + toLowerCase()
        + toLocaleLowerCase()
        + toUpperCase()
        + toLocaleUpperCase()
    6. 字符串的模式匹配方法
        + match()
        + search()
        + replace() 
        + split()
+ 不会修改字符串原先值的方法
    - charAt()
    - charCodeAt()
    - concat()
    - slice()
    - substr()
    - substring()


## 数组
+ 栈(先进后出)
    - push(后添加) pop(后移除)
+ 队列(先进先出，后进后出)
    - push(后添加) shift(前移除)
    - unshift(前添加) pop(后移除) 因为越后面的元素越先进来，越前面的元素越后进来

## 对象