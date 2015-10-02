

Make sure to download jdk1.6.0_30 and then set ANT_HOME and JAVA_HOME in build.cmd !!

This code is not compatible with newer JDKs, downloading jdk1.6.0_30 is necessary

--


log4jdbc is built with Ant 1.8.x, JDK 1.4.x and JDK 1.6.x

The build.cmd file is useful for building both the jdbc 3 version (JDK 1.4) and 
the jdbc 4 version (under JDK 1.6) under windows.  The javadoc.cmd file is 
useful for building javadoc (requires the 3rd party ydoc tool)
