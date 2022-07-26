# conviva-android-imasdk

## Conviva ima module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-ima-sdk:4.0.4'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])
    
    
## Note:  

* Refer (https://pulse.conviva.com/learning-center/content/sensor_developer_center/sensor_integration/android/android_stream_sensor.htm#IntegrateAdManagers) for integration guidelines.
