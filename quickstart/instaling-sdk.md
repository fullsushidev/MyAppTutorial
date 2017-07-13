<!-- Since parse.com won’t update their SDK, we need to download the latest Android SDK from Github. -->

In your Android Studio project, go to the `app/build.gradle` file:

![](/assets/opengradle.gif)

Add the Maven repository before `dependencies {}`:
{% label %}build.gradle{% endlabel %}
```java
repositories{
    mavenCentral()
}
```
![](/assets/addmaven.gif)

Now you can add SDKs that we would use by copying and pasting the following lines inside `dependencies {}`:
  {% label %}build.gradle{% endlabel %}
  ```java
  compile 'com.parse:parse-android:1.15.8'
  compile 'com.parse.bolts:bolts-tasks:1.4.0'
  ```
 Make sure that you also have these lines inside `dependencies {}`:
  {% label %}build.gradle{% endlabel %}
  ```java
  compile fileTree(dir: 'libs', include: ['*.jar'])
  compile 'com.android.support:appcompat-v7:25.3.1'
  testCompile 'junit:junit:4.12'
  ```
And at the end your code will look something like this:
![](/assets/addSDK.gif)

Sync your `build.gradle` and we are ready to go.

[GIF HERE]
