<%@ page language="java" contentType="text/html; charset=UTF-8"%>
<%@taglib prefix="s" uri="/struts-tags"%>
<html>
<head>
<title><s:text name="loginPage"/></title>
</head>
<body>
//用户测试的用户名和密码分别为：admin,123456
<br>
<s:fielderror></s:fielderror>
<s:form action="login">
            <s:textfield name="username" key="user"/>
            <s:password name="password" key="pass"/>
            <s:submit key="login"/>
</s:form>
</body>
</html>
