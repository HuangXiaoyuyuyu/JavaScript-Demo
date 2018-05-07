JavaScript的7基本数据类型：
Number  字符串  布尔  数组  Object   Null  Undefined
其中：Undefined其实是由Null衍生出来的
所以： //null和undefined比较
        var str1 = null;
        var str2 = undefined;
        console.log(str1 == str2);    1
        console.log(str1 === str2);  2
1的结果是true  而在JavaScript中“===”是代表数值相等 类型相等  所以2是false。