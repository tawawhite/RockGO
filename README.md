# RockGO
本仓库是xingo的一个分支,基于xingo的定制版本.

开发便签：
    sync.pool 优化

任务列表：
    待测试 rpc 心跳检测
    rpc 断线重连
    待测试 rpc 调用超时机制，未在超时时取消pending的记录，是否会有错误累计？
    待测试 rpc 支持无返回值单向调用（无法确定是否调用成功，用于对可靠性要求低的广播）