# ReplaceJavaCoreAPIs
Let the JVM load your DIY class before the jars in JRE.

Using the Command '-Xbootclasspath/p:xxx.jar', we can let JVM load our DIY class(in jar) before bootstrap classloader loading JavaCoreAPI.
