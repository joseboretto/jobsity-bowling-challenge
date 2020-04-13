# jobsity-bowling-challenge

https://jobsity.com/

Note: pdf uploaded was converted to an image to avoid indexation and keep it as private as possible.

# Solution 
## Run
```
cat bowling-game.txt
docker-compose run bowling < bowling-game.txt
```
## Re Build
```
docker-compose up --build bowling
```

## Development
In order to develop this project you will need:
- JDK 8
- Maven 3

```
mvn package
java -jar ./target/bowling.jar < bowling-game.txt
```

## Code Design Choices

- **Language**: I chose Java because it is a language that I use in the company I am working on. It is stable and has great performance along with extensive documentation.
- **Build**: Maven.
- **Tests**: I choose Junit + Mockito because they are well known.
- **Patterns**: I followed the SOLID patterns , program to an interface instead of an implementation, and dependency injection.


## complete solution (private)

https://gitlab.com/joseboretto/jobsity-bowling-challenge



