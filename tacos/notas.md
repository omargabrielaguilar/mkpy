mvnw -> maven wapper scripts
pom.xml -> maven build specification
TacosApp -> spring boot main class
application.propeties -> specify conf properties
static -> where any static content(image, stylesheets, js, etc)
templates -> thymeleaf...
TacosAppTest -> simple test class

------
@SpringBootApplication is a composite annotation that combines the following
three annotations:
     @SpringBootConfiguration—Designates this class as a configuration class.
    Although there’s not much configuration in the class yet, you can add Java-
    based Spring Framework configuration to this class if you need to. This annota-
    tion is, in fact, a specialized form of the @Configuration annotation.
     @EnableAutoConfiguration—Enables Spring Boot automatic configuration.
    We’ll talk more about autoconfiguration later. For now, know that this annota-
    tion tells Spring Boot to automatically configure any components that it thinks
    you’ll need.
    @ComponentScan—Enables component scanning. This lets you declare other
    classes with annotations like @Component, @Controller, and @Service to have
    Spring automatically discover and register them as components in the Spring
    application context.

---------------------
SPring mvc -> controllers a class that handles request and responds with some information
