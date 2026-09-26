# LibreTV 可用订阅（本仓库与LibreTV项目无直接关联）

[LibreTV](https://github.com/bestZwei/LibreTV-Next) 的数据源订阅列表（LibreTV-SourceList JSON 格式），在「设置 → 源管理 → 数据源订阅」中填入下方任意地址即可订阅。

| 文件 | 订阅地址 | 内容 |
| --- | --- | --- |
| 优质合集 | `https://raw.githubusercontent.com/bestzwei/libretv-subscriptions/main/premium.json` | 优质内容 |
| 可用合集 | `https://raw.githubusercontent.com/bestzwei/libretv-subscriptions/main/usable.json` | 覆盖面广 |

优质合集与可用合集的差异：优质只保留经过验证稳定、内容质量高的源；可用在优质基础上扩充更多备选，适合搭配 LibreTV 的健康度自动停用使用——坏源会被自动停用，不影响好源。

## 更新方式

直接编辑对应的 JSON 文件提交即可，订阅端在「源管理 → 数据源订阅」点 **⟳** 手动同步；通过 `DEFAULT_SUBSCRIPTIONS` 预置的订阅每 24 小时自动刷新。

字段格式见 [LibreTV README · 订阅格式](https://github.com/librespark/LibreTV#订阅格式libretv-sourcelist-json)。

# 其他参考

+ https://github.com/mylazily/ziyuanzhan