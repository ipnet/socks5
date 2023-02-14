# netty socks5

## how to build

> prepare jre

on windows

```bat
gradlew.bat clean build
```

on linux

```shell
./gradlew clean build
```

## how to run

find `socks5.jar` from directory `build/libs/`

start on default port `1080`

```shell
java -jar socks5.jar
```

or start on port which you want

```shell
java -jar -Dport=1088 sock
```
