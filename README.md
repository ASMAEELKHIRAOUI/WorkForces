# WorkForces
## Global view on spring

- **IOC (Inversion Of Control):** Spring’s IOC container manages the lifecycle of java objects.
- **DI (Dependency Injection):** Spring supports dependency injection, allowing to inject object dependencies into classes.
- **Beans:** are the objects that are managed by the Spring container, they can be of various scopes, such as:
    - **Singleton:** one instance is created for the entire app context.
    - **Prototype:** a new instance is created every time it is requested.
    - **Request:** a new instance is created for each HTTP request.
    - **Session:** a new instance is created for each user session.
    - **Global Session:** a new instance is created for each global session.
  IoC has a component called IoC container, it is responsible for managing the lifecycles of beans and their dependencies. Spring is an example of such a container.
Bean Definition: A bean is essentially an object or an instance of a class, but in the context of Spring, it is defined and managed by the Spring IoC container. Bean definitions are typically specified in XML configuration files, Java code, or using annotations.
