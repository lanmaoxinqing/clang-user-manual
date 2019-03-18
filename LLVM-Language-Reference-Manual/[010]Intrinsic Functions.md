# Intrinsic Functions
## Variable Argument Handling Intrinsics
### llvm.va_start
### llvm.va_end
### llvm.va_copy
## Accurate Garbage Collection Intrinsics
### llvm.gcroot
### llvm.gcread
### llvm.gcwrite
## Code Generator Intrinsics
### llvm.returnaddress
### llvm.frameaddress
### llvm.read_register and llvm.write_register
### llvm.stackrestore
### llvm.prefetch
### llvm.pcmarker
### llvm.readcyclecounter
### llvm.clear_cache
## Standard C Library Intrinsics
### llvm.memcpy
### llvm.memmove
### llvm.memset
### llvm.sqrt.*
### llvm.powi.*
### llvm.sin.*
### llvm.cos.*
### llvm.pow.*
### llvm.exp.*
### llvm.exp2.*
### llvm.log.*
### llvm.log10.*
### llvm.log2.*
### llvm.fma.*
### llvm.fabs.*
### llvm.minnum.*
### llvm.maxnum.*
### llvm.copysign.*
### llvm.floor.*
### llvm.ceil.*
### llvm.trunc.*
### llvm.rint.*
### llvm.nearbyint.*
### llvm.round.*
## Bit Manipulation Intrinsics
### llvm.bswap.*
### llvm.ctpop.*
### llvm.ctlz.*
### llvm.cttz.*
## Arithmetic with Overflow Intrinsics
### llvm.sadd.with.overflow.*
### llvm.uadd.with.overflow.*
### llvm.ssub.with.overflow.*
### llvm.usub.with.overflow.*
### llvm.smul.with.overflow.*
### llvm.umul.with.overflow.*
## Specialised Arithmetic Intrinsics
### llvm.fmuladd
## Half Precision Floating Point Intrinsics
### llvm.convert.to.fp16
### llvm.convert.from.fp16
## Debugger Intrinsics
## Exception Handling Intrinsics
## Trampoline Intrinsics
### llvm.init.trampoline
### llvm.adjust.trampoline
## 内存使用标识(Memory Use Marker)
### llvm.lifetime.start
### llvm.lifetime.end
### llvm.invariant.start
### llvm.invariant.end
## General Intrinsics
### llvm.var.annotation
### llvm.ptr.annotation.*
### llvm.annotation.*
### llvm.trap
### llvm.debugtrap
### llvm.stackprotector
### llvm.stackprotectorcheck
### llvm.objectsize
### llvm.expect
### llvm.assume
### llvm.donothing
## Stack Map Intrinsics
