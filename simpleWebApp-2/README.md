simpleWebApp-2
======

This project is to show how to use `<context-param>` in a web application.
Basically `<context-param>` is used to parameters to the whole web application.

If you run this module with the following commnad : 

```mvn jetty:run```

and hit the following URL<br/>
`http://localhost:8081/simpleWebApp-2/` <br/>
then in the console you will see the output

```
YourName
simpleWebApp-2@email.com
```

which was set in the web.xml file `<context-param>` element
