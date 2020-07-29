# java-jni-platform-headers
Java jni platform headers for cross-building.

Most JDK distributions just inclue the jni_md.h for their native platform.
For cross-building JNI libraries I needed one place to store the platform-specific headers in one place
without dowloading binaries for all platforms.

These headers are copied from OpenJDK distributions.

This is just for a CI of another project.
