[![Maven Central](https://img.shields.io/maven-central/v/net.sourceforge.streamsupport/android-retrofuture.svg)](http://mvnrepository.com/artifact/net.sourceforge.streamsupport/android-retrofuture)
[![javadoc.io](https://javadocio-badges.herokuapp.com/net.sourceforge.streamsupport/android-retrofuture/badge.svg)](http://www.javadoc.io/doc/net.sourceforge.streamsupport/android-retrofuture/)
[![Download](https://api.bintray.com/packages/stefan-zobel/android-retrofuture/android-retrofuture/images/download.svg) ](https://bintray.com/stefan-zobel/android-retrofuture/android-retrofuture/_latestVersion)

# android-retrofuture

![](art/streamsupport-sf.png)

android-retrofuture is a backport of the Java 8 CompletableFuture API upgraded to the current Java 9 (JEP 266) enhancements for Android developers wanting to use the Android Studio 3.0 desugar toolchain.

There is nothing specific to Android or the desugar toolchain in this code (it could even be compiled to Java 6 bytecode) but
it has a dependency on [android-retrostreams](https://github.com/retrostreams/android-retrostreams) which is why this exists as a separate component (the corresponding
[streamsupport-cfuture](https://github.com/stefan-zobel/streamsupport/tree/master/src/cfuture) component can't be used with android-retrostreams
and [android-retrostreams](https://github.com/retrostreams/android-retrostreams) itself can *only* be used with desugar or Java 8 and higher).

Other than having a different package name this code has no further changes compared with [streamsupport-cfuture](https://github.com/stefan-zobel/streamsupport/tree/master/src/cfuture)

The new Java 12 exception handling methods for CompletableFuture [JDK-8211010](https://bugs.openjdk.java.net/browse/JDK-8211010) have been integrated in release 1.7.0

Online Javadoc is available at [docs](https://retrostreams.github.io/android-retrofuture/apidocs/index.html)

Please give feedback [here](https://github.com/retrostreams/android-retrofuture/issues) if you experience any problems.


### build.gradle:

```gradle
dependencies {
    compile 'net.sourceforge.streamsupport:android-retrofuture:1.7.0'
}
```

## LICENSE

GNU General Public License, version 2, [with the Classpath Exception](https://github.com/retrostreams/android-retrofuture/blob/master/GPL_ClasspathException)

