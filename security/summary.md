##总结
总体来看，Docker容器还是十分安全的，特别是在容器内不使用root权限来运行进程的话。

另外，用户可以使用现有工具，比如Apparmor, SELinux, GRSEC来增强安全性；甚至自己在内核中实现更复杂的安全机制。
