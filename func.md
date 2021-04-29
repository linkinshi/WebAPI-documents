# Func
最后修改：2021.4.29

路由 | 方式 | 参数 | 返回值 |描述
-----|------|-----|-------|----
`/func/detect_rules` | GET | N/A | rules | 获取当前的审计规则

路由 | 方式 | 参数 | 返回值 |描述
-----|------|-----|-------|----
`/func/block_ip` | GET | N/A | block_ips | 获取当前的block_ips

路由 | 方式 | 参数 | 返回值 |描述
-----|------|-----|-------|----
`/func/unblock_ip` | GET | N/A | unblock_ips | 获取当前的unblock_ips

路由 | 方式 | 参数 | 返回值 |描述
-----|------|-----|-------|----
`/func/ping` | GET | N/A | N/A | Ping? Pong!

---
路由 | 方式 | 参数 | 描述
-----|------|-----|-------
`/func/block_ip` | POST | node_id, ip | 上报block_ip

---
路由 | 方式 | 参数 | 描述
-----|------|-----|-------
`/func/speedtest` | POST | node_id, telecomping, telecomeupload, telecomedownload, unicomping, unicomupload, unicomdownload, cmccping, cmccupload, cmccdownload | 上报三网 speedtest 结果