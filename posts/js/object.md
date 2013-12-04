# JavaScrip对象和原型继承解析

## 1.为什么对象的prototype属性为undefind?
>Example: the definition of console.log

    console.log = function(d) {
      process.stdout.write(d + '\n');
    };

>process.stdin
A Readable Stream for stdin. The stdin stream is paused by default, so one must call process.stdin.resume() to read from it.