## About
This is an example project for working with Spring Security & Kotlin DSL.  
There are a bunch of pitfall to properly work with the latest version of Spring Boot and Spring Security.

I created it to init Spring Security for the minimum effort to go through with.
Please enjoy:)

## Tech Stack
see ./build.gradle.kts for detail.

Build Tools: Gradle(v7.0)
Language: Kotlin(jvm1.4.32)
Framework: Spring Boot(v2.4.5)
DB: MySQL(see docker-compose.yml)

## Init Project
### 1: init database 
```bash
docker-compose up mysql 
```
### 2: build and start project
```bash
gradle bootRun
#or
./gradlew bootRun
```

### 3: go and see how it works
just go localhost:8080