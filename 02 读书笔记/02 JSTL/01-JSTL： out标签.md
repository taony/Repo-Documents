# 一、 <c:out>标签 #
标记<c:out>显示表达式的结果，类似的方式<%=%>效果，与其不同的是标记<c:out>，可以使用简单的“.”符号来访问属性。例如，要访问customer.address.street，使用的标签是<c:out value="customer.address.street"/>.
标记<c:out>可自动转义XML标签，以便他们都不会计算为实际的标签。
## 属性: ##
标记<c:out>具有以下属性：


|属性       | 描述            | 必需	| 默认值 |
|-------------|:-------------:|:-------------:|-----:|
| value	    | 输出的信息      | 	Yes	      | None     | 
| default	| 反馈输出的信息  | 	No        | 	body| 
| escapeXml	| True，如果标签转义特殊XML字符	  | No| 	true| 

```
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<html>
<head>
<title><c:out></title>
</head>
<body>
<c:out value="${'<tag> , &'}"/>
</body>
</html>
```
这将产生以下结果：

```
<tag> , &
```
