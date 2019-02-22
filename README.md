# android-json

[![Build Status](https://cloud.drone.io/api/badges/v7lin/android-json/status.svg)](https://cloud.drone.io/v7lin/android-json)
[ ![Download](https://api.bintray.com/packages/v7lin/maven/json/images/download.svg) ](https://bintray.com/v7lin/maven/json/_latestVersion)

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
