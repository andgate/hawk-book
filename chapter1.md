```
Hello World
```

This is what the traditional hello world looks like in Hawk.

```
// This is a comment, which the compiler will ignore.

// This is the main function.
fun main:
  // The statements here will be execute when the compiled binary is called.
  
  // Print text to the console
  println "Hello World!"
```

A binary can be made with the hawk compiler: `hkc`.

```
$ hkc hello.hk
```

`hkc` will produce a hello binary that can be executed.

```
$ ./hello
Hello World!
```



