clp-ffi-java is a library to encode log messages with 
[CLP](https://github.com/y-scope/clp), and work with the encoded messages using
a foreign function interface (FFI).

# Requirements

* A C++ compiler that supports C++-17
* CMake 3.5.1 or higher

# Common build commands

* Build and test
  ```shell
  mvn package
  ```
* Build without any extras
  ```shell
  mvn package -DskipTests -Dmaven.javadoc.skip=true -Dmaven.source.skip
  ```
* Generate the JNI headers
  ```shell
  mvn generate-sources
  ```
* Build the native library
  ```shell
  mvn generate-resources
  ```

# Testing

```shell
mvn test
```
