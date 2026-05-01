# Earth tower defense

This is a semestral project for FIIT OOP_B (object oriented programming) course, written in 2024-25 years. The idea of this project was to implement a small desktop game basing on fundamental OOP principles, and to practice techniques, studied during the course.

## Tech stack

- Java 21
- LibGDX 1.13.1
- JUnit
- Mockito

## How to start

```bash
./gradlew.bat lwjgl3:run 
```

## Known issues

- Bad testability due to the bad structure of entities - monolyth structure of player and other entities instead of component structure and insufficient usage of abstractions;
- Incomplete mechanism of serialization and storing the progress;
- Buggy colliders.