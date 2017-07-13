#### Initialize your parse
To connect your App and Back4App we will use `Parse.Initialize` function to build a **bridge**.

Inside your activity `onCreate` add below code.
{% label %}.java{% endlabel %}
```java
Parse.initialize(new Parse.Configuration.Builder(this)
                .applicationId("PASTE HERE YOUR Back4App APPLICATION ID")
                .clientKey("PASTE HERE YOUR CLIENT KEY")
                .server("https://parseapi.back4app.com/").build()
);
```
Now go to your App Dashboard at Back4App website to find your Application ID and your Client Key
Click on Features -> Core Settings -> Server

Go back to your `Parse.Initialize` function and paste your applicationId and your clientKey.

You should have something like these:
<br>[JPG HERE]
> #### warning::Note
> You need to point the server url to Back4App. If you just simply use Parse.initialize(this,aped,client key), it will not point to your back4app Application.
