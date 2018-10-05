

# Android 7 (SDK 25.X)
### based on [rahulcv/java](https://github.com/rahulcv/docker-java)
- Ant 1.9.6
- Maven 3.3.9
- Java 1.8.0_111
- Gradle 2.10 (Groovy 2.4.5)
- Android SDK 24.4.1
    + APIs: android-10,android-15,android-16,android-17,android-18,android-19,android-20,android-21,android-22,android-23,android-24,android-25
    + Build-Tools: 25.0.2

----
## Tagging scheme
- `v${TOOLS_VERSION}-${BUILD_TOOLS_VERSION}-${HIGHEST_ANDROID_SDK_VERSION}`
- e.g. `v25.2.5-27.0.0-26`
----
### Pull from Docker Hub
```
docker pull rahulcv/android:latest
```

### Build from GitHub
```
docker build -t rahulcv/android github.com/rahulcv/docker-android
```

### Run image
```
docker run -it rahulcv/android bash
```

### Use as base image
```Dockerfile
FROM rahulcv/android:latest
```

----

