Unity3D LogCat extension
========================

Logcat (android logging) extension for unity3D. Forget about using android studio or worthless terminal window. 
Log and filter your android messages directly from Unity3D!

Works both on **windows** & **mac OS** and **Unity Free** & **Pro** versions!

Functions
---------------------
- Start / stop logging
- Clear logs
- "Only Unity" pre-filter
- Filter by log type (error, warning, debug, info, verbose)
- Filter by text (case-insensitive)
- List of devices
- Update devices list

How to use with Package Manager
---------------------

Add package to `manifest.json`
```
{
  "dependencies": {
    "com.github.dzonatan.unity3d-logcat-extension": "https://github.com/shiena/Unity3D-LogCat-extension.git#upm"
  }
}
```

How to use without Package Manager
---------------------
1. Clone `Editor/LogCatWindow.cs` from this repository into a folder named `Editor` within your `Assets` folder
2. Plug in the android device to the usb
3. Click Window -> LogCat - Android Logger
4. Start logging by clicking "Start logging" button!

Screenshots
---------------------

### Initial window
![Initial window](/screenshots~/InitialWindow.png)

### Filter by log type(s)
![Filter by string](/screenshots~/FilterByErrorTypes.png)

### Filter by log type(s) & text
![Filter by log type & string](/screenshots~/FilterByErrorTypesAndString.png)

Contribution
---------------------
Feel free to contribute!
