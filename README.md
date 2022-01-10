#Switch-Config

https://www.cnblogs.com/hup666/p/13899788.html

```java
public class CommonTypeSwitch {

    @AppSwitch(des = "String 类型开关", level = Level.p2)
    public static String stringSwitch = "string";

    @AppSwitch(des = "Integer 类型开关", level = Level.p1)
    public static Integer integerSwitch = 2;

    @AppSwitch(des = "Boolean 类型开关", level = Level.p4)
    public static Boolean booleanSwitch = true;

    @AppSwitch(des = "AtomicInteger 类型开关", level = Level.p1)
    public static AtomicInteger atomicIntegerSwitch = new AtomicInteger(21);

    @AppSwitch(des = "AtomicBoolean 类型开关", level = Level.p1)
    public static AtomicBoolean atomicBooleanSwitch = new AtomicBoolean(true);
}
```
