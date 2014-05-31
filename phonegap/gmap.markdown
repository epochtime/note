


```ruby
#create key
keytool -genkey -alias myKey -keystore debug.keystore
keytool -selfcert -alias myKey -keystore debug.keystore
```

display keystore


```
C:\test\HelloMap\platforms\android> keytool -list -v -keystore "%USERPROFILE%\.android\debug.keystore" 
-alias androiddebugkey -storepass android -keypass android
```

https://github.com/wf9a5m75/phonegap-googlemaps-plugin
