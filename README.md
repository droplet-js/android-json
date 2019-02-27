# android-json

[![Build Status](https://cloud.drone.io/api/badges/v7lin/android-json/status.svg)](https://cloud.drone.io/v7lin/android-json)
[![GitHub tag](https://img.shields.io/github/tag/v7lin/android-json.svg)](https://github.com/v7lin/android-json/releases)
[![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=14)

### json

````
源码摘自 'org.json:json:20180813'
````

### snapshot

````
ext {
    latestVersion = '1.0.0-SNAPSHOT'
}

allprojects {
    repositories {
        ...
        maven {
            url 'https://oss.jfrog.org/artifactory/oss-snapshot-local'
        }
        ...
    }
}
````

### release

````
ext {
    latestVersion = '1.0.0'
}

allprojects {
    repositories {
        ...
        jcenter()
        ...
    }
}
````

### usage

java
````
...
dependencies {
    ...
    implementation "io.github.v7lin:json:${latestVersion}"
    ...
}
...
````

android
````
...
dependencies {
    ...
    implementation "io.github.v7lin:json:${latestVersion}"
    ...
}
...
````
