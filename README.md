# getfit
Problem: There's a "audioplayers" named package in pubspec.yaml file that is further implemented in easy_workout.dart file for the audio process in the emulator.

The error that's occuring in terminal when trying to build the project:
'attrib' is not recognized as an internal or external command, operable program or batch file.

1: Task failed with an exception.
-----------
* What went wrong:
Execution failed for task ':audioplayers:verifyReleaseResources'.
> A failure occurred while executing com.android.build.gradle.tasks.VerifyLibraryResourcesTask$Action
   > Android resource linking failed
     ERROR:C:\Users\Dell\Documents\getfit2\build\audioplayers\intermediates\merged_res\release\values\values.xml:141: AAPT: error: resource android:attr/lStar not found.

Solutions I have tried but did not work:
1) Upgrading the audioplayers package
2) Cleaning and Rebuilding the project

These were the only solutions i could find.
The error above is clearly trying to mention that it's verify the release resource of audioplayer's package with the current xml file that should be located in the desired location "C:\Users\Dell\Documents\getfit2\build\audioplayers\intermediates\merged_res\release\values\values.xml:141" but its not able to find that resource file.
