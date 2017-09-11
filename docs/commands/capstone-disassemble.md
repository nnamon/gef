## Command capstone-disassemble ##

If you have installed the [`capstone`](http://capstone-engine.org) library and
its Python bindings, you can use it to disassemble any memory in your debugging
session. This plugin was created to offer an alternative to `GDB` disassemble
function which sometimes gets things mixed up.

You can use its alias `cs-disassemble` or just `cs` and the location to
disassemble (if not specified, it will use `$pc`).

```
gef➤ cs main
```

![cs-disassemble](https://i.imgur.com/wypt7Fo.png)
