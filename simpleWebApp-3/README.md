simpleWebApp-3
======

This module is to show how to pass initial value in a servlet.

If you run this module with the following command :

```mvn jetty:run```

and hit the following URL :

```
http://localhost:8081/simpleWebApp-3/test
```

then in the console you will see the output

```
YourName
```

the `/test` is needed because we use int the `<servlet-mapping>` element as follows :

```xml
<servlet-mapping>
    <servlet-name>myServlet</servlet-name>
    <url-pattern>/test</url-pattern>
</servlet-mapping>
```
