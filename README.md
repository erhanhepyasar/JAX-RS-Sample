JAX-RS Sample Application
-----------------------------------
Library: Jersey

Step by Step
-----------------------------------
- Eclipse > New Dynamic Web Project > Assign Tomcat
- Project > Properties > Tergeted Run Time: Tomcat (Error on the jsp file dissappears)
- https://jersey.java.net > Download Jersey-JAX-RS 2.0 RI bundle > Add all jars to WebContent/WEB-INF/lib
- Create class MyRestApp extends Application (import javax.ws.rs.core) with @ApplicationPath annotation
- Create controller class with @Path annotation
- Define methods with @GET, @Produces("text/plain") annotations
- Run as > Run on Server
- Browse http://localhost:8080/JAX-RS-Starter/app/hello
