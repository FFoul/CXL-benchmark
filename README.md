# CXL Benchmark Applications

This repository vendors source code for benchmark applications used in CXL experiments. The applications are copied into `apps/` as regular source trees, not Git submodules.

## Included Applications

| Application | Local path | Upstream | Version / ref | Commit |
| --- | --- | --- | --- | --- |
| Phoenix-2.0 | `apps/phoenix-2.0` | <https://github.com/kozyraki/phoenix> | `master`, `phoenix-2.0` subdirectory | `1276c8d8f3b82050071d0a7a4b8a352a05d1faab` |
| DBx1000 | `apps/dbx1000` | <https://github.com/yxymit/DBx1000> | `master` | `5f172a99bd57bed29745df81f72e93f91292bb31` |
| GeminiGraph | `apps/geminigraph` | <https://github.com/thu-pacman/GeminiGraph> | `master` | `170e7d36794fdcaca077f23bd0cd76e8ccab9e74` |
| CNN Benchmarks | `apps/cnn-benchmarks` | <https://github.com/jcjohnson/cnn-benchmarks> | `master` | `83d441f852134f4a98aa3e665499d9369b6141c9` |
| Redis | `apps/redis` | <https://github.com/redis/redis> | `8.8.0` | `5a693aaed0842c4eef21c706b79fa49938ca9f6c` |
| Memcached | `apps/memcached` | <https://github.com/memcached/memcached> | `1.6.42` | `f1674f0231e5d291db474c4ad297f5f069d32521` |
| LevelDB | `apps/leveldb` | <https://github.com/google/leveldb> | `1.23` | `99b3c03b3284f5886f9ef9a4ef703d57373e61be` |
| TensorFlow Benchmarks | `apps/tensorflow-benchmarks` | <https://github.com/tensorflow/benchmarks> | `master` | `8fb79079265933ad39bea628b777af662f5bf15d` |
| PARSEC Benchmark | `apps/parsec-benchmark` | <https://github.com/cirosantilli/parsec-benchmark> | `3.0` | `b758a0ed159c1b5f854147c8915f360fac195820` |

Imported on 2026-06-29.

## Notes

- The upstream `.git` directories were not copied.
- No Git submodules are used by this repository.
- Each application directory includes a `SOURCE_VERSION` file with the upstream repository, selected version/ref, commit, and import date.
- Upstream licenses remain with their respective source trees.
