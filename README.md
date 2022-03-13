# faf-syscall

syscall macro
* Fast
* Minimalist
* Dependency-free
* Linux
* `#![no_std]`
* Stable (not nightly)

This was originally developed for the [faf web server](https://github.com/errantmind/faf)

__Usage__

let errno = `sys_call!(SYS_NUM, arg1, arg2, ...)`

Returns result as a positive isize or errno as a negative isize.