<c:set>标记是JSTL的setProperty动作的友好版本。标签是有用的，因为它的表达式求值，并使用结果的JavaBean或java.util.Map对象设置一个值。


属性:
<c:set>标记具有以下属性：

属性
描述	必需	默认值
value	保存信息	No	body
target	变量的名称，其属性应该修改	No	None
property	要修改的属性	No	None
var	变量的名称存储信息	No	None
scope	变量来存储信息的范围	No	Page
如果指定目标，属性也必须指定。



```
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<html>
<head>
<title><c:set></title>
</head>
<body>
<c:set var="salary" scope="session" value="${2000*2}"/>
<c:out value="${salary}"/>
</body>
</html>
```
这将产生以下结果：

```
4000
```
