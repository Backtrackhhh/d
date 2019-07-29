# Psychological Assistance After Disaster using IBM Cloud Services and Unity
***
## Introduction
***
In the face of growing natural disasters, the project is dedicated to addressing the psychological reconstruction of children after disasters. We use the services provided on IBM cloud to achieve dialogue with children, with unity to build avatars, we hope that this avatar chat bot can help us better solve the psychological problems of children after the disaster, and through chat data to make a psychological assessment of children in the region.
## Included Components 
***
- [IBM Cloud Watson Assistant](https://cloud.ibm.com/catalog?search=label:%E8%BD%BB%E9%87%8F&category=ai)
- [IBM Cloud Speech to Text](https://cloud.ibm.com/catalog?search=label:%E8%BD%BB%E9%87%8F&category=ai)
- [IBM Cloud Text to Speech](https://cloud.ibm.com/catalog?search=label:%E8%BD%BB%E9%87%8F&category=ai)
- [IBM Cloud Tone Analyzer](https://cloud.ibm.com/catalog?search=label:%E8%BD%BB%E9%87%8F&category=ai)
- [Unity](https://unity.cn/)

## Setup
***
### Dependency

- unity v2018.1.3+
- node v7.0+  

**Go** to [download unity](https://unity.cn/)

!["download"](img/p1.PNG)

**Use**
```bash
npm install  
npm start
```
to get node installed at your computer

**OR**

go to [NODEJS](https://nodejs.org/en/) to get the archive

## Code structure
C:.
│  list.txt

│  New Unity Project (21).exe

│  UnityCrashHandler64.exe

│  UnityPlayer.dll  
│  WinPixEventRuntime.dll  
│  
├─MonoBleedingEdge
│  ├─EmbedRuntime
│  │      mono-2.0-bdwgc.dll
│  │      MonoPosixHelper.dll
│  │      
│  └─etc
│      └─mono
│          │  browscap.ini
│          │  config
│          │  
│          ├─2.0
│          │  │  DefaultWsdlHelpGenerator.aspx
│          │  │  machine.config
│          │  │  settings.map
│          │  │  web.config
│          │  │  
│          │  └─Browsers
│          │          Compat.browser
│          │          
│          ├─4.0
│          │  │  DefaultWsdlHelpGenerator.aspx
│          │  │  machine.config
│          │  │  settings.map
│          │  │  web.config
│          │  │  
│          │  └─Browsers
│          │          Compat.browser
│          │          
│          ├─4.5
│          │  │  DefaultWsdlHelpGenerator.aspx
│          │  │  machine.config
│          │  │  settings.map
│          │  │  web.config
│          │  │  
│          │  └─Browsers
│          │          Compat.browser
│          │          
│          └─mconfig
│                  config.xml
│                  
└─New Unity Project (21)_Data
    │  app.info
    │  boot.config
    │  globalgamemanagers
    │  globalgamemanagers.assets
    │  level0
    │  resources.assets
    │  resources.assets.resS
    │  resources.resource
    │  RTVoiceTTSWrapper.exe
    │  sharedassets0.assets
    │  sharedassets0.assets.resS
    │  sharedassets0.resource
    │  
    ├─Managed
    │      Assembly-CSharp-firstpass.dll
    │      Assembly-CSharp-firstpass.pdb
    │      Assembly-CSharp.dll
    │      Assembly-CSharp.pdb
    │      CTNAudio.dll
    │      CustomMarshalers.dll
    │      IBM.Cloud.SDK.dll
    │      IBM.Cloud.SDK.pdb
    │      Interop.SpeechLib.dll
    │      Microsoft.CSharp.dll
    │      Mono.Posix.dll
    │      Mono.Security.dll
    │      mscorlib.dll
    │      Newtonsoft.Json.dll
    │      RTVoiceUWPBridge.dll
    │      SALSA.dll
    │      System.Configuration.dll
    │      System.Core.dll
    │      System.dll
    │      System.Runtime.Serialization.dll
    │      System.Security.dll
    │      System.ServiceModel.Internals.dll
    │      System.Xml.dll
    │      System.Xml.Linq.dll
    │      Unity.Analytics.DataPrivacy.dll
    │      Unity.Analytics.DataPrivacy.pdb
    │      Unity.Analytics.StandardEvents.dll
    │      Unity.Analytics.StandardEvents.dll.mdb
    │      Unity.Analytics.Tracker.dll
    │      Unity.Analytics.Tracker.dll.mdb
    │      Unity.TextMeshPro.dll
    │      Unity.TextMeshPro.pdb
    │      UnityEngine.AccessibilityModule.dll
    │      UnityEngine.AccessibilityModule.xml
    │      UnityEngine.Advertisements.dll
    │      UnityEngine.AIModule.dll
   ......
    │      UnityEngine.WindModule.xml
    │      UnityEngine.xml
    │      UnityEngine.XRModule.dll
    │      UnityEngine.XRModule.xml
    │      WatsonUnitySDK.dll
    │      WatsonUnitySDK.pdb
    │      websocket-sharp.dll
    │      
    ├─Plugins
    │      libflac-8.dll
    │      libgcc_s_sjlj-1.dll
    │      libgomp-1.dll
    │      libid3tag-0.dll
    │      libogg-0.dll
    │      libpng16-16.dll
    │      libsox-3.dll
    │      libssp-0.dll
    │      libvorbis-0.dll
    │      libvorbisenc-2.dll
    │      libvorbisfile-3.dll
    │      libwavpack-1.dll
    │      libwinpthread-1.dll
    │      zlib1.dll
    │      
    └─Resources
            unity default resources
            unity_builtin_extra
            


# License

This code pattern is licensed under the Apache Software License, Version 2.  Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
# Links

* [IBM Cloud Docs](https://cloud.ibm.com/docs/)
* [Code Pattern](https://developer.ibm.com/cn/patterns/)


