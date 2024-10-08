# 内存条

![你可曾记得，九月的热舞～](oredict:oc:ram1)

内存条和[CPU](cpu1.md)一样都是所有种类[电脑](../general/computer.md)的必备配件。根据[CPU](cpu1.md)的架构不同，内存很大程度上影响了[电脑](../general/computer.md)的工作能力。例如，对标准Lua架构而言，内存大小控制了Lua脚本能使用的实际内存量。意味着如果要运行越大，越内存密集型的程序，就需要越多内存。

内存条有多种等级，默认情况容量大小如下：
- T1: 192KB
- T1.5: 256KB
- T2: 384KB
- T2.5: 512KB
- T3: 768KB
- T3.5: 1024KB

注意，这些值仅对Lua架构有效。其他架构下各等级内存条可能会提供不同大小。还请注意T1和1.5级内存都算作T1组件，T2 T3同理。

若需要，容量值可在配置文件中修改。
