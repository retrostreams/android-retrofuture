# android-retrofuture

![](art/streamsupport-sf.png)

android-retrofuture is a backport of the Java 8 CompletableFuture API upgraded to the current Java 9 (JEP 266) enhancements for Android developers wanting to use the Android Studio 3.0 desugar toolchain.

There is nothing specific to Android or the desugar toolchain in this code (it could even be compiled to Java 6 bytecode) but
it has a dependency on [android-retrostreams](https://github.com/retrostreams/android-retrostreams) which is why this exists as a separate component (the corresponding
[streamsupport-cfuture](https://sourceforge.net/p/streamsupport/code/ci/default/tree/src/cfuture/) component can't be used with android-retrostreams).

Other than having a different package name this code has no changes compared with [streamsupport-cfuture](https://sourceforge.net/p/streamsupport/code/ci/default/tree/src/cfuture/)

Please give feedback [here](https://github.com/retrostreams/android-retrofuture/issues) if you experience any problems.


## LICENSE

GNU General Public License, version 2, with the Classpath Exception

