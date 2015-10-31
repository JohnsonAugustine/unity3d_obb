# unity3d_obb
UnityOBBDownloader

This package is an adaption of the Google Play market_downloader library, for use with Unity Android (as a plugin).

This plugin does NOT solve splitting up a >50MB .apk into .obb (through asset bundles or similar techiniques). It merely handles the downloading of .obb files attached to a published .apk, on devices that don't support automatic downloading.

This software is free and published as is, with no warranty and responsibilities - use it at your own risk.
To try it out

This plugin is published as an Android Library project, and is compatible with Unity 4.5 and Unity 5.

    Open Unity, create a new project.
    Add this package
    Attach the DownloadObbExample.cs to the Main Camera
    Open GooglePlayDownloader.cs and replace the PUBLIC_KEY with your value
    Change the Bundle Identifier / Version Code so it matches an application already available on Google Play (that has .obb files attached).
    Build and Run on your android device.

To rebuild the code

    Make sure you have the JDK and Ant installed
    Open a Terminal.app / cmd.exe window

    Change directory to the plugin root

    $> cd {your new project}/Assets/Plugins/Android/UnityOBBDownloader

    Update the ant project with the local SDK path

    $> android update project -p .

    Build the plugin (use 'help' to see a complete list of commands)

    $> ant build
    
    contact johnsonaugustine@live.com for any development
    

