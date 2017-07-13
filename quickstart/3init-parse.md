Initialize your parse



To connect your app and back4app. We can use Parse.Initialize function build a Bridge.

Inside your activity onCreate add below code.

Note that you need to point the server url to back4app. If you just simply use Parse.initialize(this,aped,client key), It will not point to your back4app Application.

Parse.initialize(new Parse.Configuration.Builder(this)
                .applicationId("Your Back4app application ID")
                .clientKey("You can find it on Features -> Core Settings -> Server")
                .server("https://parseapi.back4app.com/").build()
);

To this step, the basic setup should be done.
