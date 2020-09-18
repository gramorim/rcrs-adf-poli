# `rcrs-adf-poli` RCRS Agent Development Framework (Poli)

(Linux) Instructions to download, build and run the Poli implementation using the Agent Development Framework (ADF)

## 1. Software Pre-Requisites

- Git
- Gradle
- OpenJDK Java 11+

## 2. Download

```bash

$ git clone https://github.com/gnardin/rcrs-adf-poli.git
```

## 3. Compile

```bash

$ ./gradlew clean

$ ./gradlew build
```

## 4. Execute

The `rcrs-adf-sample` is a sample team implementation for the RCRS (`rcrs-server`) using the ADF core (`rcrs-adf-core`).

To run the `rcrs-adf-poli`, first the `rcrs-server` must be running (Instructions of how to download, compile and run the `rcrs-server` are available at <https://github.com/roborescue/rcrs-server>).

After start the `rcrs-server`, open a new terminal window and execute

```bash

$ cd rcrs-adf-poli

$ ./launch-poli.sh
```
