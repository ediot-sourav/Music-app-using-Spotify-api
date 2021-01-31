# Music-app-using-Spotify
This is a simple app where you will fetch audio tracks from Spotify.

Things that you require to Run this application Successfully
------------------------------------------------------------

1. A Spotify developer account. If you don't have a Spotify developer account you can make this here https://developer.spotify.com/

2. Spotify app should be installed on your device and also you should be logged in. Otherwise it could give error displaying no app installed...

3. Create an app or register an app in the Spotify dashboard.

4. By creating an app in dashboard you will be given a id. Store that id and in Mainactivity use you id instead of my id.

5. And while registering you need to give you package name and also you SHA1 of your android project.

6. You need to Download the Spotify Android SDK from https://github.com/spotify/android-sdk/releases extract it and paste it into you projects libs folder.

7. Add the library to your project by importing it as a module. In the “Project” side bar in Android Studio (View –> Tool Windows –> Project), right click your project’s root folder and navigate to “New” –> “Module”.In the “New Module” window, choose the option “Import .JAR/AAR Package”. Click “Next”.

8. And locate the spotify-app-remote-release-version.aar under the “app-remote-lib” folder in the unzipped bundle. Click “Open” and choose a suitable subproject name. I have used "spotify-app-remote" in this project.

9. And finally... add these dependencies
dependencies {
    // your app dependencies
    implementation project(':spotify-app-remote')
    implementation "com.google.code.gson:gson:2.8.5"

10. And Done now you can use your application.

These are the requirements that you need to run the app.
