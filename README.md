# Messaging library
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=kryonitelabs_messaging&metric=alert_status)](https://sonarcloud.io/dashboard?id=kryonitelabs_messaging)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=kryonitelabs_messaging&metric=coverage)](https://sonarcloud.io/dashboard?id=kryonitelabs_messaging)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=kryonitelabs_messaging&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=kryonitelabs_messaging)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=kryonitelabs_messaging&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=kryonitelabs_messaging)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=kryonitelabs_messaging&metric=security_rating)](https://sonarcloud.io/dashboard?id=kryonitelabs_messaging)

This library contains a simple `MessagingService` which simplifies the setup and work
with RabbitMQ and the AMQP protocol.

## Usage
### Gradle
```java
repositories {
    maven(url = "https://jitpack.io")
}

dependencies {
    implementation("com.github.kryonitelabs:messaging:1.2.1")
}
```

### Maven
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>

<dependency>
  <groupId>com.github.kryonitelabs</groupId>
  <artifactId>messaging</artifactId>
  <version>1.2.1</version>
</dependency>
```
## Examples
Examples can be found in the tests [here](src/test/java/org/kryonite/service/DefaultMessagingServiceTest.java) and the latest
javadoc is published to:
https://kryonitelabs.github.io/messaging/latest/
