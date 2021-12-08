# Projeto04Socket

Executando o código no terminal:

	java [package path] [url] [endpoint]

no meu caso foi:

	C:\Users\wtl25\Documents\Java>"C:\Program Files\Java\jdk-11.0.4\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2019.2\lib\idea_rt.jar=61108:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2019.2\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\wtl25\Documents\Java\out\production\Java
 com.company.SimpleSocketClientExample localhost /


Para localhost foi utilizado o NGINX, especificando a porta do NGINX no código.

Retornando:

	Loading contents of URL: localhost
	HTTP/1.1 200 OK
	Server: nginx/1.17.6
	Date: Wed, 08 Dec 2021 02:41:37 GMT
	Content-Type: text/html
	Content-Length: 238
	Connection: close
	Last-Modified: Wed, 24 Nov 2021 05:38:08 GMT
	ETag: "619dcfc0-ee"
	Accept-Ranges: bytes

	<!DOCTYPE html>
	<html>
	<head>
	<title>Node 1</title>
	<style>
    	body {
        	width: 35em;
        	margin: 0 auto;
        	font-family: Tahoma, Verdana, Arial, sans-serif;
    	}
	</style>
	</head>
	<body>
        	<p>NODE 1 YAS</p>
	</body>
	</html>

