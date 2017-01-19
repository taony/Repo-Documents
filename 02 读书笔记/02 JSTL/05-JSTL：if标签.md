<c:if>标签计算表达式，只有当表达式的值为true，则显示其主体内容。



|属性|	描述|	必需|	默认|
|-------------|:-------------:|:-------------:|-----:|
|test	|条件计算|	Yes	None|
|var|	变量名称的存储条件的结果|	No|	None|
|scope	|变量的范围的存储条件的结果	|No	page|



```
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
<html>
<head>
<title><c:if> Tag Example - www.yiibai.com</title>
</head>
<body>
<c:set var="salary" scope="session" value="${2000*2}"/>
<c:if test="${salary > 2000}">
   <p>My salary is: <c:out value="${salary}"/><p>
</c:if>
</body>
</html>
```


```
My salary is: 4000
```


