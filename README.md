Rust bindings for BLIS.

https://github.com/flame/blis

# Features
- `static` (enabled by default): Link BLIS statically.
- `parallel-pthreads`: Enables multithreading with `pthreads`.
- `parallel-openmp`: Enables multithreading with `openmp`.
- `runtime-dispatch`: Enables runtime dispatch on `x86_64`.

`parallel-pthreads` and `parallel-openmp` are mutually exclusive.
