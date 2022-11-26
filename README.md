# Dockerized template for SpringBoot3 project with Java17 and Gradle
This is a template for setting up a new project with SpringBoot3 in docker.

## Usage
```
cd docker_template_springboot3_java17_gradle
docker compose run
```

## Notes
To prevent the 'xargs is not available' error, add the line 'eval "microdnf install findutils"' to gradlew and rename the file gradle_fixed.