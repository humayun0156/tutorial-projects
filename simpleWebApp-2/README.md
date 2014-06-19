simpleWebApp-2
======

This module is to show how to use `<context-param>` in a web application.<br>
Basically `<context-param>` is used to pass parameters to the whole web application.

If you run this module with the following command :

```mvn jetty:run```

and hit the following URL :

```http://localhost:8081/simpleWebApp-2/```

then in the console you will see the output

```
YourName
simpleWebApp-2@email.com
```

which was set in the web.xml file `<context-param>` element
