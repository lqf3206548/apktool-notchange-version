# apktool-nochange-compileSdkVersion、compileSdkVersionCodename...
现在已有的版本,Existing version    
获取请看分支,get see branch  
>compile-29  
>compile-28  
  
由于apktool的限制,在回编译会覆盖被处理apk的compileSdkVersion属性为23，compileSdkVersionCodename属性为6.0-2438415  
我通过修改apktool.jar的文件,使apk编译出来为以下版本  
详细请看我的[csdn-blog](https://blog.csdn.net/weixin_44681497/article/details/124174463)   
```
<manifest
android:compileSdkVersion="29" 
android:compileSdkVersionCodename="10" 
platformBuildVersionCode="30" 
platformBuildVersionName="11">
    <uses-sdk android:minSdkVersion="20" android:targetSdkVersion="30"/>
    </manifest>
```  
apk和jar已经上传，请自取  

### 如果对您有帮助，请给我一颗星星感谢.
---
english for machine translation:  
solve apktool Back compilation apk will change androidmainfest.xml  
Due to the limitation of apktool, the compilesdkversion attribute of the processed APK is 23 and the compilesdkversioncodename attribute is 6.0-2438415 during back compilation  
I modified apktool Jar file to compile APK into the following version  
Details see my [CSDN blog](https://blog.csdn.net/weixin_44681497/article/details/124174463)  all was chinese  
```
<manifest
android:compileSdkVersion="29" 
android:compileSdkVersionCodename="10" 
platformBuildVersionCode="30" 
platformBuildVersionName="11">
<uses-sdk android:minSdkVersion="20" android:targetSdkVersion="30"/>
</manifest>
```
Apk and jar have been uploaded. Please take them yourself  

### If it helps you, please give me a star , thank you
