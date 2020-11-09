SpringBootFX
Simple example for Spring Boot and JavaFX application
Simple example for Spring Boot and JavaFX application
Contains profiles: default, nmi and aper

Active profile nmi sets in application.yml

spring:
  main:
    web-application-type: none
    banner-mode: off
  profiles:
    active: nmi
logging:
  level:
    org:
      springframework: info
  
  You can switch active profile to **aper** at a startup using 
'''

  -Dspring.profiles.active=aper
''' 
  Output zip with single JAR appears after Gradle build task:
  build/distributions/SpringBootFX-boot

https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#boot-documentation

https://spring-projects.ru/guides/lessons/lesson-2/
