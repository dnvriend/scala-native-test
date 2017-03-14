# scala-native-test
A small study project on [scala-native](http://www.scala-native.org/en/latest/index.html).

## How to use
You build the project using:

```bash
sbt nativeLink
```

The artifact should be in `scala-native-test/target/scala-2.11` and should be called `scala-native-test-out

You can run the executable with:

```bash
$ ./scala-native-test-out Dennis 44
Hello Dennis, you are 44 years old.
```

Have fun!