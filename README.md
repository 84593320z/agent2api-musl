把 aimod-cc/Agent2API 的上游 tag 交叉编译成 musl 静态包。

- 本仓库不存上游源码，每次构建按 tag 现拉
- 产物：agent2api-server-linux-{arm64,amd64}-musl.tar.gz(+.sha256)
- 触发：每日 04:00 UTC 自动查新 tag；也可手动 dispatch
