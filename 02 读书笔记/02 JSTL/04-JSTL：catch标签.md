<c:catch>标签捕获任何Throwable，发生在它的身上，有选择地公开。简单地用于错误处理，更优雅地处理这个问题。
属性:
<c:catch>标签具有以下属性：


属性	描述	必选	默认
var	变量的名称保存在java.lang。如果抛出的Throwable在body元素内。	No	None

```
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<html>
<head>
<title><c:catch> Tag Example - www.yiibai.com</title>
</head>
<body>

<c:catch var ="catchException">
   <% int x = 5/0;%>
</c:catch>

<c:if test = "${catchException != null}">
   <p>The exception is : ${catchException} <br />
   There is an exception: ${catchException.message}</p>
</c:if>

</body>
</html>
```

这将产生以下结果：

```
The exception is : java.lang.ArithmaticException: / by zero
There is an exception: / by zero
```
