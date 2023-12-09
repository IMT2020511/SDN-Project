 **Steps to install Android Studio on Windows**

1. Download Android Studio:<br>
• Go to the official Android Studio website: https://developer.android.com/studio.<br>
• Click on the ”Download” button.<br>
• Download the version for Windows.<br>
2. Run the installer:<br>
• Locate the downloaded installer file (usually a .exe file).<br>
• Double-click on the installer to run it.<br>
3. Choose components:<br>
• Select “Custom” installation to customize the components or choose “Standard” for the
default components.<br>
• Ensure that “Android Virtual Device (AVD)” and “Performance (Intel ® HAXM)” are
selected.<br>
4. Choose install location:<br>
• Select the destination folder where you want to install Android Studio.<br>
• Click “Next”.<br>
5. Install type:<br>
• Choose the type of setup you want (Standard or custom).<br>
• Click “Next”.<br>
6. Complete Installation:<br>
• Click “Install” to start the installation process.<br>
7. Complete setup:<br>
• Once the installation is complete, click “Next” and then “Finish”.<br>
8. Run Android Studio:<br>
• Launch Android Studio by finding it in your Start Menu or desktop shortcuts.<br>
• The first time you run Android Studio, it will download and install the Android SDK
components.<br>
9. Configure SDK:<br>
• Follow the setup wizard to configure the Android SDK with the necessary packages.<br>
• Download the SDK components required for your development.<br>
10. Finish Setup:<br>
• Once the SDK components are downloaded and installed, you should be ready to start
Android development.<br>
11. Configure Android Virtual Device (AVD):<br>
• Create an Android Virtual Device to test your applications.<br>
• Go to “Tools” > “AVD Manager” and create a new virtual device<br>


**Creating a basic UI in Android Studio**

1. Create a new project:<br>
• Open Android Studio.<br>
• Click on “Start a new Android Studio project.”<br>
• Choose an appropriate template. For a basic UI, you can start with an “Empty Activity”
or “Basic Activity.”<br>
2. Configure your project:<br>
• Enter the name of your application in the “Name” field.<br>
• Set the “Save location” for your project.<br>
• Choose the language (Java or Kotlin).<br>
• Set the minimum API level. For a basic project, you can use a relatively low API level.<br>
3. Design the UI:<br>
• Open the ‘res’ folder in the ‘app/src/main directory’.<br>
• Navigate to the ‘res/layout folder’.<br>
• Open the ‘activity main.xml file’. This file defines the layout of your main activity.<br>
• You can use the visual editor or switch to the XML view to define your UI components.<br>
4. Add UI components:<br>
• Drag and drop UI components from the Palette (located on the left side) to the layout.<br>
• Common UI components include ‘TextView’ (for displaying text), ‘Button’ (for user
interaction), ‘EditText’ (for user input), etc.<br>
5. Adjust properties:<br>
• Customize the properties of each component using the Attributes panel. You can set
properties such as text, color, size, etc.<br>
6. Connect UI elements with code:<br>
• Open the corresponding Java or Kotlin file for your main activity (‘MainActivity.java’
or ‘MainActivity.kt’).<br>
• Define variables for the UI components by using ‘findViewById’.<br>
• Perform any necessary actions or logic in response to user interactions.<br>
7. Run your app:<br>
• Connect a physical Android device or use an emulator.<br>
• Click on the ”Run” button (green triangle) in the toolbar to build and run your app.<br>
8. Test your app:<br>
• Interact with your app on the emulator or device to ensure that the UI behaves as
expected.<br>


**Adding firebase to the android project**
1. Create a Firebase project<br>
2. Register your app with Firebase<br>
• Go to the Firebase console.<br>
• In the center of the project overview page, click the Android icon or Add app to launch
the setup workflow.<br>
• Enter your app’s package name in the Android package name field.<br>
• (Optional) Enter other app information: App nickname and Debug signing certificate
SHA-1.<br>
• Click Register app.<br>
3. Add a Firebase configuration file<br>
• Download and then add the Firebase Android configuration file (google-services.json) to
your app:<br>
(a) Click Download google-services.json to obtain your Firebase Android config file.<br>
(b) Move your config file into the module (app-level) root directory of your app<br>
• To make the values in your google-services.json config file accessible to Firebase SDKs,
you need the Google services Gradle plugin (google-services).<br>
(a) In your root-level (project-level) Gradle file (<project>/build.gradle.kts or
<project>/build.gradle), add the Google services plugin as a dependency<br>
(b) In your module (app-level) Gradle file (usually <project>/<app-module>
/build.gradle.kts or <project>/<app-module>/build.gradle), add the Google
services plugin.<br>
4. Add Firebase SDK’s to your app<br>
• In your module (app-level) Gradle file (usually <project>/<app-module>/build.gradle.kts
or <project>/<app-module>/build.gradle), add the dependencies for the Firebase
products that you want to use in your app.<br>
• After adding the dependencies for the products you want to use, sync your Android
project with Gradle files.<br>






