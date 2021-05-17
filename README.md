# Spring Boot MVC with thymeleaf hello world!

### java8, spring5, thymeleaf, gradle

### directory
![image](https://user-images.githubusercontent.com/7710893/118436323-9a8f1380-b71b-11eb-82ce-0e880a141c32.png)


### gradle

~~~
plugins {
	id 'org.springframework.boot' version '2.4.5'
	id 'io.spring.dependency-management' version '1.0.11.RELEASE'
	id 'java'
}

group = 'com.example'
version = '0.0.1-SNAPSHOT'
sourceCompatibility = '1.8'

repositories {
	mavenCentral()
}

dependencies {
	implementation 'org.springframework.boot:spring-boot-starter-web'
	implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
	implementation 'org.springframework.boot:spring-boot-devtools'
	implementation 'org.webjars:bootstrap'
	
	testImplementation 'org.springframework.boot:spring-boot-starter-test'
}

test {
	useJUnitPlatform()
}
~~~



