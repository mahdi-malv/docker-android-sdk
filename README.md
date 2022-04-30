> **DEPRECATED**: Consider using other updated images (such as [Circle CI's](https://hub.docker.com/r/circleci/android/tags) or [Tapsell's](https://hub.docker.com/r/tapsellorg/android-sdk/tags)) which are currently well maintained

# Android SDK docker image
> View on [DockerHub](https://hub.docker.com/r/mahdimalv/android-sdk)

Made this image to be able to run CI testing with **Android studio Arctic Fox**.  
This version of Android studio requires **Java 11** that does not exists in many docker images I've found

## Contains
- Android API 30
- Java JDK 11

## Usage

```
docker pull mahdimalv/android-sdk:api30-jdk11
```


