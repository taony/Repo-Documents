JavaServer Pages标准标记库（JSTL）是一个有用的JSP标签的集合，它封装了许多JSP应用程序通用的核心功能。

JSTL支持常见的，结构性任务，如迭代和条件，标签为操纵XML文件，国际化标签和SQL标签。它还提供了一个框架，将现有的自定义标签和JSTL标签。

JSTL标签进行分类，根据其功能分为以下，可用于创建一个JSP页面时，JSTL标签库组：

- 核心标签(Core Tags)
- 格式化标签(Formatting tags)
- SQL标签(SQL tags)
- XML标签(XML tags)
- JSTL函数（JSTL Functions）

安装JSTL库:

如果您使用的是Apache Tomcat容器，那么按照下面两个简单的步骤：

下载的二进制发行版，从Apache标准标记库和解压的压缩文件。

使用标准的标签库从Jakarta Taglibs分布，复制发行版'lib'目录到应用程序的JAR文件 webapps\ROOT\WEB-INF\lib 目录中。

要使用JSTL库，要在每一个JSP的顶部，使用该库必须包括一个<taglib>指令。
核心标签:

核心组的标签是最常用的JSTL标签。以下是在您的JSP的语法包括JSTL核心库：

```
<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
```
格式化标签：

使用JSTL格式标签来格式化和显示文本，日期，时间和数字的，国际化的网站。以下是在您的JSP的语法，包括格式化库：

```
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>
```
SQL标签:

JSTL的SQL标签库标签可以交互关系型数据库（如Oracle，MySQL或Microsoft SQL Server的关系数据库管理系统）。

以下是在您的JSP语法包括JSTL SQL库：

```
<%@ taglib prefix="sql" uri="http://java.sun.com/jsp/jstl/sql" %>
```
XML 标签:

JSTL XML标记提供了一种创建和操作XML文档的JSP为中心的方式。以下是在您的JSP的语法包括JSTL XML库。

JSTL XML标记库具有自定义标签与XML数据交互。这包括XML解析，转换XML数据，流控制，基于XPath表达式。


```
<%@ taglib prefix="x" uri="http://java.sun.com/jsp/jstl/xml" %>
```
JSTL 函数:

JSTL包括一些标准功能，其中大部分是常见的字符串操作函数。以下是在JSP的语法包函JSTL函数库：


```
<%@ taglib prefix="fn" uri="http://java.sun.com/jsp/jstl/functions" %>
```
