### C-FFI

git: `git@github.com:zhaojh329/lua-ffi.git`

https: `https://github.com/zhaojh329/lua-ffi.git`

> lightweight C FFI for Lua, based on libffi and aiming to be mostly compatible with LuaJIT FFI


### luaffifb (thenumbernine fork)

git: `git@github.com:thenumbernine/luaffifb.git`

https: `https://github.com/thenumbernine/luaffifb.git`

> bitflags + dynasm jit calls.
> This is a really impressive project, which - does not have (quite) have full equivalence with luajit ffi, but otherwise serves as an ffi binding module.

> It's good as is, with that+compiled/optimized luac? I almost don't see a reason for luajit other than the api drift that's happened.

> One (maybe exceptionally) optimistic idea is that of ffi/jit being a module, importable for any lua version that programmatically generates assembly for it's own execution/runtime, and has an ffi.* interface for binding C libraries.
