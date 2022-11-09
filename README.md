Sample project to demonstrate maven-compiler issue with `proc:only`.

Run 
```
clean compile -X -f pom.xml
```

and check unexpected output during first compile goal:

```
[INFO] Compiling 2 source files to [...]
```