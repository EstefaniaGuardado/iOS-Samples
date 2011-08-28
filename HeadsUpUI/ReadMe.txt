HeadsUpUI


Build Requirements
Mac OS X 10.5.3, Xcode 3.1, iPhone OS 2.0.


Runtime Requirements
Mac OS X 10.5.3, iPhone OS 2.0.


Using the Sample
Launch the HeadsUpUI project using Xcode 3.1.

To run in the simulator, set the Active SDK to Simulator. To run on a device, set the Active SDK to the appropriate Device setting.  When launched tap anywhere on the screen.  The hover user interface will appear with a fade-in effect at your touch point.  You can then tap the forward or backward buttons.  If you do not tap them, the interface will automatically fade away after 5 seconds.


Packaging List
main.m - Main source file for this sample.
AppDelegate.h/.m - The application's delegate to setup its window and content.
MyViewController.h/.m - The main UIViewController the parent view for the HoverView.
HoverView.h/.m - The view hosting the translucent button tools: play/pause.
MainView.h/.m - The background picture view for this application (embeds HoverView).


Changes from Previous Versions
1.0 - First release.


Copyright (C) 2008 Apple Inc. All rights reserved.