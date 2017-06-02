tomcat-version:8

Http11NioProtocol

```xml
<Executor 
	name="tomcatThreadPool"
	namePrefix="catalina-exec-"
	maxThreads="150"
	minSpareThreads="4"
/>
		
<Connector 
	port="80"
	protocol="org.apache.coyote.http11.Http11NioProtocol"
	connectionTimeout="20000"
	enableLookups="false" 
	redirectPort="8443"
	URIEncoding="utf-8"
/>		

```