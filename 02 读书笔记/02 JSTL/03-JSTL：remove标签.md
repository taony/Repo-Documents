<c:remove>标签删除变量，无论是从指定的范围内或范围内的变量（如果没有指定范围）。这个动作通常是不特别有帮助，但它可以帮助确保一个JSP范围内的资源，它负责清理。


```
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<html>
<head>
<title><c:remove> Tag Example - www.yiibai.com</title>
</head>
<body>
<c:set var="salary" scope="session" value="${2000*2}"/>
<p>Before Remove Value: <c:out value="${salary}"/></p>
<c:remove var="salary"/>
<p>After Remove Value: <c:out value="${salary}"/></p>
</body>
</html>
```
