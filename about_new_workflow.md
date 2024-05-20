The jpf.yml creates a config file such as this one
```
target=chapter_array_and_linkedlist.array
classpath=projects/hello-algo/codes/java/build
sourcepath=projects/hello-algo/codes/java
vm.por=true
vm.version=11
jvm.insn_factory.class=gov.nasa.jpf.jvm.bytecode.InstructionFactory
jpf.basedir=/tmp/jpf-core
```

And then it run the jpf tool