# Installation

### SDKMan \(preferred\)

```
Install via script
$ curl -s "https://get.sdkman.io" | bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"

Verify Installation
$ sdk version

Install Java
$ sdk install java

List versions available by candidate
$ sdk list java

Install desired Java version from the list
$ sdk install java x.y.z-open
$ sdk install java 11.0.2-open
```

### OpenJDK

Very straightforward installation

```
Download from http://jdk.java.net/11/

Unzip the downloaded file
$ tar xf openjdk-11.0.2_osx-x64_bin.tar.gz

Move the extracted folder to where MacOS searches for Java JDK
$ sudo mv jdk-11.0.2.jdk /Library/Java/JavaVirtualMachines/

That's it!! Now test:
$ java -version
$ javac -version
```



