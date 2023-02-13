# netty socks5

## how to build

> prepare jre

on windows

```bat
gradlew.bat clean shadowJar
```

on linux

```shell
./gradlew clean shadowJar
```

## how to run

find `socks5.jar` from directory `build/lib/`

start on default port `1080`

```shell
java -jar socks5.jar
```

or start on port which you want

```shell
java -jar -Dport=1088 sock
```
