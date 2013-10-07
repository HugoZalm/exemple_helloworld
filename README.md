exemple_helloworld
==================

This is a helloworld project for a multiplatform webapp in PhoneGap (using jQuery).
Tested working in Eclipse and AIDE on android.

Copy this repository (Github shell commands):
* git clone --bare https://github.com/HugoZalm/exemple_helloworld.git
* cd exemple_helloworld.git
* git push --mirror https://github.com/HugoZalm/new-repository.git
* cd ..
* rm -rf exemple_helloworld.git

Change code afther copying:
* src/nl/hugozalm/helloworld -> new_packagename
* src/nl/hugozalm/new_packagename/helloworld.java -> new_projectname.java
* src/nl/hugozalm/new_packagename/new_projectname.java -> "public class helloworld" vervangen door "public class sos" (regel 24)
* res/values/strings.xml -> "<string name="app_name">helloworld" vervangen door "<string name="app_name">sos" (regel 3)
* AndroidManifest.xml -> "package="nl.hugozalm.helloworld"" vervangen door "package="nl.hugozalm.sos"" (regel 21)
* AndroidManifest.xml -> "<activity android:name="helloworld"" vervangen door "<activity android:name="sos"" (regel 52)
