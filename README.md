
# JMicros - PokeApi Client
 
Repository with an example of automated smoke test using Java.

## Build Prerequisites
1. jdk 1.8
2. gradle 3.4.1
3. amazoncorretto 8


## Build
```
gradle clean assemble fatjar && docker build -t jmicros .
```

## Execute
```
docker-compose up jmicros
```