Diese App basiert auf dem PasswordManager Version 1.03 mit Unterstützung des biometrischen LogIns.

build.gradle:
```plaintext
compileSdk 30
minSdk 26
targetSdk 30

stay on implementation 'androidx.appcompat:appcompat:1.3.1'
do not update to 1.4.0 if you are on SDK30
implementation 'androidx.appcompat:appcompat:1.3.1'
implementation 'androidx.biometric:biometric:1.1.0'


```