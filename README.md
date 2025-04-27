# SpringBoot-Starter

Set the logs in the property file.


application.properties :

logging.level.org.springframework = debug



How are our requests handled?

	DispatcherServlet - Front Controller Pattern
	
	* Mapping Servlets : dispatcherServler urls = [ / ]
	

	


Who is configuring error mapping?

AutoConfiguration (ErrorMvcAutoConfiguration)

Note :

	if you are giving wrong path (url) getting 404.
	
	ErrorMvcAutoConfiguration  giving -> error page automatically . ie. Whitelabel Error Page


How are all jars available (Spring, Spring MVC , Jackson and Tomcat) ?

	Starter Projects. [ spring boot starter web ]
