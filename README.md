# ACL rule lists

Personal split-routing rule lists. Referenced via jsDelivr:

```
https://cdn.jsdelivr.net/gh/buzzbuzzcock/acl-lists@main/<file>.list
```

| File | Policy | Position |
|---|---|---|
| `00-allow-before-reject.list` | DIRECT | first, before any REJECT list |
| `01-foreign-sdk-proxy.list` | PROXY | first, before any REJECT list |
| `10-cn-gap.list` | DIRECT | before the China list |
| `11-overseas-iot-proxy.list` | PROXY | before the China list |

Snapshot of upstream vendor lists inlined in `10-cn-gap.list`: 2026-10-14.
