# publicdata

PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app> flutter run --verbose
[ +115 ms] executing: [C:\Users\Administrator\Documents\flutter/] git -c log.showSignature=false log -n 1 --pretty=format:%H
[ +552 ms] Exit code 0 from: git -c log.showSignature=false log -n 1 --pretty=format:%H
[   +1 ms] f4abaa0735eba4dfd8f33f73363911d63931fe03
[   +1 ms] executing: [C:\Users\Administrator\Documents\flutter/] git tag --points-at f4abaa0735eba4dfd8f33f73363911d63931fe03
[  +64 ms] Exit code 0 from: git tag --points-at f4abaa0735eba4dfd8f33f73363911d63931fe03
[        ] 2.2.3
[   +7 ms] executing: [C:\Users\Administrator\Documents\flutter/] git rev-parse --abbrev-ref --symbolic @{u}
[  +48 ms] Exit code 0 from: git rev-parse --abbrev-ref --symbolic @{u}
[        ] origin/stable
[        ] executing: [C:\Users\Administrator\Documents\flutter/] git ls-remote --get-url origin
[  +55 ms] Exit code 0 from: git ls-remote --get-url origin
[        ] https://github.com/flutter/flutter.git
[ +173 ms] executing: [C:\Users\Administrator\Documents\flutter/] git rev-parse --abbrev-ref HEAD
[  +51 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
[        ] stable
[ +136 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping update.
[   +8 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[   +1 ms] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[ +103 ms] executing: C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe devices -l
[  +68 ms] List of devices attached
           RZ8N9265VDK            device product:f41dd model:SM_F415F device:f41 transport_id:2
[  +11 ms] C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe -s RZ8N9265VDK shell getprop
[ +129 ms] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[   +1 ms] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
[   +4 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[   +1 ms] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[  +75 ms] "flutter run" took 458ms.
[  +31 ms] Error: No pubspec.yaml file found.
           This command should be run from the root of your Flutter project.
[   +4 ms] 
           #0      FlutterCommand.validateCommand (package:flutter_tools/src/runner/flutter_command.dart:1309:11)
           #1      RunCommand.validateCommand (package:flutter_tools/src/commands/run.dart:448:19)
           #2      FlutterCommand.verifyThenRunCommand (package:flutter_tools/src/runner/flutter_command.dart:1148:11)
           <asynchronous suspension>
           #3      FlutterCommand.run.<anonymous closure> (package:flutter_tools/src/runner/flutter_command.dart:1043:27)      
           <asynchronous suspension>
           #4      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #5      CommandRunner.runCommand (package:args/command_runner.dart:196:13)
           <asynchronous suspension>
           #6      FlutterCommandRunner.runCommand.<anonymous closure>
           (package:flutter_tools/src/runner/flutter_command_runner.dart:284:9)
           <asynchronous suspension>
           #7      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #8      FlutterCommandRunner.runCommand (package:flutter_tools/src/runner/flutter_command_runner.dart:232:5)        
           <asynchronous suspension>
           #10     AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #11     main (package:flutter_tools/executable.dart:91:3)
           <asynchronous suspension>


[ +273 ms] ensureAnalyticsSent: 261ms
[   +5 ms] Running shutdown hooks
[   +1 ms] Shutdown hooks complete
[   +2 ms] exiting with code 1
PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app> cd .
PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app> cd ..
PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2> flutter create my_app
Recreating project my_app...
  my_app\.gitignore (created)
  my_app\.idea\libraries\Dart_SDK.xml (created)
  my_app\.idea\libraries\KotlinJavaRuntime.xml (created)
  my_app\.idea\modules.xml (created)
  my_app\.idea\runConfigurations\main_dart.xml (created)
  my_app\.idea\workspace.xml (created)
  my_app\.metadata (created)
  my_app\android\app\build.gradle (created)
  my_app\android\app\src\main\kotlin\com\example\my_app\MainActivity.kt (created)
  my_app\android\build.gradle (created)
  my_app\android\my_app_android.iml (created)
  my_app\android\.gitignore (created)
  my_app\android\app\src\debug\AndroidManifest.xml (created)
  my_app\android\app\src\main\AndroidManifest.xml (created)
  my_app\android\app\src\main\res\drawable\launch_background.xml (created)
  my_app\android\app\src\main\res\drawable-v21\launch_background.xml (created)
  my_app\android\app\src\main\res\mipmap-hdpi\ic_launcher.png (created)
  my_app\android\app\src\main\res\mipmap-mdpi\ic_launcher.png (created)
  my_app\android\app\src\main\res\mipmap-xhdpi\ic_launcher.png (created)
  my_app\android\app\src\main\res\mipmap-xxhdpi\ic_launcher.png (created)
  my_app\android\app\src\main\res\mipmap-xxxhdpi\ic_launcher.png (created)
  my_app\android\app\src\main\res\values\styles.xml (created)
  my_app\android\app\src\main\res\values-night\styles.xml (created)
  my_app\android\app\src\profile\AndroidManifest.xml (created)
  my_app\android\gradle\wrapper\gradle-wrapper.properties (created)
  my_app\android\gradle.properties (created)
  my_app\android\settings.gradle (created)
  my_app\ios\Runner\AppDelegate.swift (created)
  my_app\ios\Runner\Runner-Bridging-Header.h (created)
  my_app\ios\Runner.xcodeproj\project.pbxproj (created)
  my_app\ios\Runner.xcodeproj\xcshareddata\xcschemes\Runner.xcscheme (created)
  my_app\ios\.gitignore (created)
  my_app\ios\Flutter\AppFrameworkInfo.plist (created)
  my_app\ios\Flutter\Debug.xcconfig (created)
  my_app\ios\Flutter\Release.xcconfig (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Contents.json (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-1024x1024@1x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@1x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-20x20@3x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@1x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-29x29@3x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@1x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-40x40@3x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-60x60@3x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@1x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-76x76@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\Icon-App-83.5x83.5@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\Contents.json (created)
  my_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage.png (created)
  my_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@2x.png (created)
  my_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\LaunchImage@3x.png (created)
  my_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\README.md (created)
  my_app\ios\Runner\Base.lproj\LaunchScreen.storyboard (created)
  my_app\ios\Runner\Base.lproj\Main.storyboard (created)
  my_app\ios\Runner\Info.plist (created)
  my_app\ios\Runner.xcodeproj\project.xcworkspace\contents.xcworkspacedata (created)
  my_app\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  my_app\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  my_app\ios\Runner.xcworkspace\contents.xcworkspacedata (created)
  my_app\ios\Runner.xcworkspace\xcshareddata\IDEWorkspaceChecks.plist (created)
  my_app\ios\Runner.xcworkspace\xcshareddata\WorkspaceSettings.xcsettings (created)
  my_app\lib\main.dart (created)
  my_app\my_app.iml (created)
  my_app\pubspec.yaml (created)
  my_app\README.md (created)
  my_app\test\widget_test.dart (created)
  my_app\web\favicon.png (created)
  my_app\web\icons\Icon-192.png (created)
  my_app\web\icons\Icon-512.png (created)
PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app> flutter run --verbose
[ +117 ms] executing: [C:\Users\Administrator\Documents\flutter/] git -c log.showSignature=false log -n 1 --pretty=format:%H
[ +540 ms] Exit code 0 from: git -c log.showSignature=false log -n 1 --pretty=format:%H
[   +1 ms] f4abaa0735eba4dfd8f33f73363911d63931fe03
[   +2 ms] executing: [C:\Users\Administrator\Documents\flutter/] git tag --points-at f4abaa0735eba4dfd8f33f73363911d63931fe03
[  +59 ms] Exit code 0 from: git tag --points-at f4abaa0735eba4dfd8f33f73363911d63931fe03
[        ] 2.2.3
[   +9 ms] executing: [C:\Users\Administrator\Documents\flutter/] git rev-parse --abbrev-ref --symbolic @{u}
[  +45 ms] Exit code 0 from: git rev-parse --abbrev-ref --symbolic @{u}
[        ] origin/stable
[        ] executing: [C:\Users\Administrator\Documents\flutter/] git ls-remote --get-url origin
[  +39 ms] Exit code 0 from: git ls-remote --get-url origin
[        ] https://github.com/flutter/flutter.git
[ +177 ms] executing: [C:\Users\Administrator\Documents\flutter/] git rev-parse --abbrev-ref HEAD
[  +55 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
[        ] stable
[ +150 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping update.
[   +7 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[   +2 ms] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[   +1 ms] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[   +2 ms] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[ +108 ms] executing: C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe devices -l
[  +70 ms] List of devices attached
           RZ8N9265VDK            device product:f41dd model:SM_F415F device:f41 transport_id:2
[  +11 ms] C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe -s RZ8N9265VDK shell getprop
[ +130 ms] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
[   +1 ms] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
[   +4 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
[ +128 ms] Skipping pub get: version match.
[ +170 ms] Generating
C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\android\app\src\main\java\io\flutter\plugins\GeneratedPluginRegistrant.java
[  +86 ms] ro.hardware = exynos9611
[        ] ro.build.characteristics = phone
[  +71 ms] Initializing file store
[  +14 ms] Skipping target: gen_localizations
[  +19 ms] complete
[   +9 ms] Launching lib\main.dart on SM F415F in debug mode...
[  +10 ms] C:\Users\Administrator\Documents\flutter\bin\cache\dart-sdk\bin\dart.exe --disable-dart-dev
C:\Users\Administrator\Documents\flutter\bin\cache\artifacts\engine\windows-x64\frontend_server.dart.snapshot --sdk-root       
C:\Users\Administrator\Documents\flutter\bin\cache\artifacts\engine\common\flutter_patched_sdk/ --incremental --target=flutter 
--debugger-module-names --experimental-emit-debug-metadata -DFLUTTER_WEB_AUTO_DETECT=true --output-dill
C:\Users\ADMINI~1\AppData\Local\Temp\flutter_tools.d54ea3b8\flutter_tool.e4f770b6\app.dill --packages
C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\.dart_tool\package_config.json -Ddart.vm.profile=false
-Ddart.vm.product=false --enable-asserts --track-widget-creation --filesystem-scheme org-dartlang-root --initialize-from-dill  
build\3c113a45063dc6628e68a4111abcacad.cache.dill.track.dill --enable-experiment=alternative-invalidation-strategy
[  +33 ms] executing: C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe -s RZ8N9265VDK shell -x logcat -vtime -t 1
[  +26 ms] <- compile package:my_app/main.dart
[ +811 ms] --------- beginning of system
                    07-15 20:50:31.929 I/io_stats( 4313): !@   8,0 r 8443879 213432864 w 1475548 27571200 d 964982 37607264 f  
                    920684 1135162 iot 3534908 2951124 th 102400 0 0 pt 0 inp 0 0 96225.001
[  +23 ms] executing: C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe version
[  +73 ms] Android Debug Bridge version 1.0.41
           Version 31.0.2-7242960
           Installed as C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe
[  +15 ms] executing: C:\Users\Administrator\AppData\Local\Android\sdk\platform-tools\adb.exe start-server
[  +53 ms] Building APK
[  +64 ms] Running Gradle task 'assembleDebug'...
[  +35 ms] Using gradle from C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\android\gradlew.bat.
[  +32 ms] executing: C:\Program Files\Android\Android Studio\jre\bin\java -version
[ +257 ms] Exit code 0 from: C:\Program Files\Android\Android Studio\jre\bin\java -version
[  +28 ms] openjdk version "11.0.8" 2020-07-14
           OpenJDK Runtime Environment (build 11.0.8+10-b944.6842174)
           OpenJDK 64-Bit Server VM (build 11.0.8+10-b944.6842174, mixed mode)
[  +11 ms] executing: [C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\android/]
C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\android\gradlew.bat -Pverbose=true -Ptarget-platform=android-arm64  
-Ptarget=C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\lib\main.dart
-Pdart-defines=RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ== -Pdart-obfuscation=false -Ptrack-widget-creation=true
-Ptree-shake-icons=false -Pfilesystem-scheme=org-dartlang-root assembleDebug
[+1631 ms] Welcome to Gradle 6.7!
[   +2 ms] Here are the highlights of this release:
[  +43 ms]  - File system watching is ready for production use
[   +2 ms]  - Declare the version of Java your build requires
[  +29 ms]  - Java 15 support
[  +86 ms] For more details see https://docs.gradle.org/6.7/release-notes.html
[+2292 ms] FAILURE: Build failed with an exception.
[  +16 ms] * Where:
[  +13 ms] Build file 'C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app\android\app\build.gradle' line: 24
[  +16 ms] * What went wrong:
[ +112 ms] A problem occurred evaluating project ':app'.
[   +4 ms] > com/google/gson/JsonParseException
[   +2 ms] * Try:
[   +2 ms] Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run  
with --scan to get full insights.
[   +8 ms] * Get more help at https://help.gradle.org
[   +2 ms] BUILD FAILED in 3s
[ +595 ms] Running Gradle task 'assembleDebug'... (completed in 5.2s)
[+8532 ms] Exception: Gradle task assembleDebug failed with exit code 1
[   +4 ms] "flutter run" took 15,785ms.
[  +11 ms] 
           #0      throwToolExit (package:flutter_tools/src/base/common.dart:10:3)
           #1      RunCommand.runCommand (package:flutter_tools/src/commands/run.dart:663:9)
           <asynchronous suspension>
           #2      FlutterCommand.run.<anonymous closure> (package:flutter_tools/src/runner/flutter_command.dart:1043:27)      
           <asynchronous suspension>
           #3      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #4      CommandRunner.runCommand (package:args/command_runner.dart:196:13)
           <asynchronous suspension>
           #5      FlutterCommandRunner.runCommand.<anonymous closure>
           (package:flutter_tools/src/runner/flutter_command_runner.dart:284:9)
           <asynchronous suspension>
           #6      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #7      FlutterCommandRunner.runCommand (package:flutter_tools/src/runner/flutter_command_runner.dart:232:5)        
           <asynchronous suspension>
           #8      run.<anonymous closure>.<anonymous closure> (package:flutter_tools/runner.dart:62:9)
           <asynchronous suspension>
           #9      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #10     main (package:flutter_tools/executable.dart:91:3)
           <asynchronous suspension>


[ +105 ms] ensureAnalyticsSent: 92ms
[   +3 ms] Running shutdown hooks
[        ] Shutdown hooks complete
[   +1 ms] exiting with code 1
PS C:\Users\Administrator\Desktop\mpbapp\FlutterPOC_v2\my_app> 
             
             
