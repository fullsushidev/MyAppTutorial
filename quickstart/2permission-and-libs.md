#### Granting Permissions
Parse is a [backend as a service (BaaS)](https://en.wikipedia.org/wiki/Mobile_backend_as_a_service), that provides you with an application development platform in the cloud.
Therefore, **it requires you to grant internet permission to work.**

Add the following code to your `AndroidManifest.xml` file to grant this permission to your Android App:

{% label %}AndroidManifest.xml{% endlabel %}
```xml
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
<uses-permission android:name="android.permission.INTERNET"/>
```
<!--You should have something like these:
<br>[JPG HERE]-->

<BR>
#### Adding Libs
To call all Parse provided functions you will need to import libs to your code.

Choose the activity which will implement parse function and import the following libs:
{% label %}.java{% endlabel %}
```java
import com.parse.Parse;
import com.parse.ParseObject;
import com.parse.ParseUser;
```
<!--YYou should have something like these:
<br>[JPG HERE]-->


