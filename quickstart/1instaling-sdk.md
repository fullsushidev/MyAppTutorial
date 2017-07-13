> Follow this tutorial if you haven’t installed our SDK yet.

In your Android Studio project, go to the `app/build.gradle` file:
<sub>Be careful, there's two files with `build.gradle` name:</sub>

![](/assets/opengradle.gif)

<BR>
Add Maven repository before `dependencies {}`:
{% label %}build.gradle{% endlabel %}
```java
repositories{
    mavenCentral()
}
```
![](/assets/addmaven.gif)

<BR>
Now you can add SDKs that we will use by copying and pasting the following lines inside `dependencies {}`:
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

<BR>
Sync your `build.gradle` and we are ready to go.

![gif](/assets/syncgradle.gif)
