# 调试

## 追踪

strace -ff -o ./draft/out ./src/redis-server

dtruss -ff -o ./draft/out ./src/redis-server