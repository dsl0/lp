# A3 - Dynamic Link Library (JNI)

## Compile and Run

```bash
cd "A3_Dynamic Link Library"

javac JNI.java

javac -h . JNI.java

gcc -shared -I"%JAVA_HOME%\include" -I"%JAVA_HOME%\include\win32" JNI.c -o libJNI.dll

java JNI
 