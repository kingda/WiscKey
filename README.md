# 体系结构作业
## 说明
levelDB目录为最新的levelDB
wiscKey目录为改造后的论文实现。
## 操作方法：
`cmake -DCMAKE_BUILD_TYPE=Release .. && cmake --build .` 

`./db_bench --benchmarks="fillseq,fillsync,fillrandom,overwrite,fill100K,crc32c,compact,readrandom,readseq,readreverse"`