# Spring-Framwork--1
Pluralsight Spring Path

# Big Picture 

Spring Framework = web, data, AOP, Core
    
    Auto-configuration - 自动配置 (based on dependencies)
    Standalone: .jar = Just Run. Package appliction & Run the application
    Opinionated: opinions make getting started fast
   
Spring Boot = quick & easy != less

Software Framework: 是一个通用的、可重用的软件环境，它提供特定功能(web, data function)作为更大软件平台应用(Spring Framework -> Java)的一部分,促进软件`产品和解决方案开发

Spring Framework: 6 Key Areas

    1) Core = Dependency Injection (data binding, type conversion, validation)
    2) Web = 
    3) AOP, Data Access, Integration, Testing

Dependency: nothing but a library that provides specific support to the application to run and implement.

WEB
    Spring Web MVC
        Servlet: is an object that receives a request and generates a response based on that request.
        MVC: Model–view–controller is a software architectural pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements.
        Request -> MVC -> Response
        
    Spring Web Webflux: reactive programming
        REACT quickly: don't wait for another process to go through

    AOP: Aspect-Oriented Programming = a programming paradigm that aims to increase modularity by allowing the separation of cross-cutting concerns

    Data Access: Easy via query
        stmnt.executeQuery(SELECT COUNT(*) FROM foo"); rs.getInt(1);
        Transaction happen the same time or don't happen the same time. Avoid the inbalence.
        
    < Exception >: an event within a program that disrupt execution.
        MySQL error:630
        Oracle error: 1400
        Other similar errors
    
    Integration: 









